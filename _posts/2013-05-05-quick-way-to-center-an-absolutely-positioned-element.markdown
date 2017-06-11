---
layout: post
title:  "Quick Way to Absolutely Position An Element"
date:   2013-05-05 21:54:44 -0500
categories: blog
tags: [code]
---
<p>I find it hard to blog about technical related issues. I feel most of the time everything I have to say has already been said but this is something i&#8217;ve found a lot of my peers especially at the current company I work at weren&#8217;t aware of&#8230; its a quick way to center an absolutely positioned element.<!-- more --></p>

<p>The only real requirement for this is you need to know the width of the element. Here is an example:</p>


{% highlight css %}
#sampleDiv {
  position: absolute;
  top: 30%;
  left: 50%;
  margin-left: 225px;
  width: 450px;
}
{% endhighlight %}

<p>That&#8217;s it&#8230; you position the element left 50 percent and then create a negative margin of 1/2 the width of the element, and it works.</p>

<p>I was surprised to know that this was something a few people I work with weren&#8217;t aware of so I thought I would share just in case anyone out there isn&#8217;t aware of this technique.</p>

Be Awesome :)
