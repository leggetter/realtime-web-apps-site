---
layout: post
title: "Realtime Is Now!"
date: 2013-06-06 08:15:24
categories: realtime, general
---

Realtime is fast becoming a non-optional part of web development. Get on board or 
be left behind!

Here's how easy it is to start:

{% highlight php %}
<?php

require('Pusher.php');

$pusher = new Pusher($key, $secret, $app_id);
$pusher->trigger('my-channel', 'my-event', array('message' => 'hello world') );

{% endhighlight %}

Go [get your copy of *Realtime Web Apps*][1], set up a [Pusher account][2], and 
step into the future!

[1]: http://amzn.to/15RKxF3
[2]: http://pusher.com/

