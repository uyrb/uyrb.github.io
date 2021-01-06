---
layout: post
title: github-init
tags: [ jekyll ]
categories: [ default ]
---

 

s
ruby src テスト
{% highlight ruby %}
y = Fiber.new do |n|
  loop.with_index(0){|q,i| Fiber.yield i*n }
end
6.times { p y.resume 2 }

{% endhighlight %}
