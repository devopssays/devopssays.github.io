---
layout: post
title:  "Is this thing on?"
date:   2015-11-01 19:24:03 +0100
categories: announcements
---

{% highlight ruby %}
def make_new_website(name)
  jekyll new .
  jekyll build
  octopress deploy
end
make_new_website('devopssays.com')
{% endhighlight %}

