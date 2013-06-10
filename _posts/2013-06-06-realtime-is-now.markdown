---
layout: post
title: Realtime Is Now!
author: Jason Lengstorf
twitter: @jlengstorf
gplus: 101737362787862429754
categories: [realtime, general]
excerpt: It's easy to get started with realtime. Don't get left behind on the 
         next big trend in web design!
---

Realtime is fast becoming a non-optional part of web development. Get on board 
or be left behind!

Here's how easy it is to start:

{% highlight php linenos %}
<?php

require('Pusher.php');

$pusher = new Pusher($key, $secret, $app_id);
$pusher->trigger('my-channel', 'my-event', array('message' => 'hello world') );

{% endhighlight %}

Go [get your copy of *Realtime Web Apps*][1], set up a [Pusher account][2], and 
step into the future!

[1]: http://amzn.to/15RKxF3
[2]: http://pusher.com/

