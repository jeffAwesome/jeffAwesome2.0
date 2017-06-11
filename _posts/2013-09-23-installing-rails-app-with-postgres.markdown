---
layout: post
title:  "Installing rails app with postgresql"
date:   2013-09-23 210:54:44 -0500
categories: blog
tags: [code]
---

<p>I&#8217;ve been working on the backend side of rails apps the past few months. One thing I&#8217;ve realized
is that you can go through a million tutorials but until you put those concepts to work you&#8217;ll have
a harder time grasping them.</p>

<p>Today I want to go over a very simple concept. This is applicable in many ways, especially when learning
to use different databases in a rails app. Today we&#8217;ll be covering installing a brand new rails app with
the postgreSQL database. Normally you&#8217;d have the SQLite db set up by default. There are numerous advantages
to this.. one being that heroku uses this&#8230; and if you&#8217;re installing your apps on heroku its nice to be
using the same database as heroku to avoid any potential issues that could come up relating to database configuration.</p>

<h1>Okay on to business&#8230;</h1>

{% highlight ruby %}
rails new yourApp --database=postgresql
{% endhighlight %}

<p>That&#8217;s it. If you already have a rails app created and want to switch its still very straightforward.</p>

<ol>
<li>Remove the sqlite gem from your gemfile</li>
<li>Add in the gem &#8216;pg&#8217; into your gemfile</li>
<li>run bundle</li>
<li>Then make sure your database.yml files are using the correct adapters. Here is an example</li>
</ol>

{% highlight ruby %}
development:
  adapter: postgresql
  encoding: unicode
  database: appname_development
  pool: 5
  username: your_system_username
  password:
{% endhighlight %}

<p>That&#8217;s it. You should be good to go. Of course you&#8217;ll need to make sure you have the PG installed on your system.
If you have homebrew you can do this easily</p>

{% highlight ruby %}
$ brew update
  $ brew doctor
  $ brew install postgresql
{% endhighlight %}

<p>The first two commands make sure brew is up to date and healthy&#8230; the third is the command to install postgreSQL. That&#8217;s it.
This is something I would have found useful a few months ago so I figured I would include it here.</p>

<p>Enjoy and Be Awesome</p>


