---
layout: post
title:  "The Business Owners Guide To Using  Google Analytics"
date:   2017-06-13 9:54:44 -0500
categories: blog
tags: ['Google Analytics', 'Business Owner']
---


A Success Story
===================

There is a story about a business owner who is able to track their incoming website visitors and use that information
to actually generate qualified leads and eventually customers.  A story about a business owner who broke free from his
competition by using content strategy and Google Analytics.  The story about a business who actually had a waiting
list of customers.


**If this sounds impossible, I want to assure you IT'S NOT…** but you’ll need to learn about using Google Analytics to better
understand how your potential customers are using your website.

Todays post is going to start you on the journey to using Google Analytics to understand how to leverage Google Analytics
in your businesses favor.

We are going to cover:
* What is a Google Analytics View
* How to setup a new View
* What a Filter is inside Google Analytics
* How to setup a new Filter for your views.


So lets get started. If you haven't already setup your Google Analytics account you can refer to a past article called
[The Business Owners Guide To Setting Up Google Analytics](http://jeffawesome.com/2017/06/10/the-business-owners-guide-to-setting-up-google-analytics.html).


What is A View:
=================

A reporting view is a view that gives you reports and other analysis tools.  By Default Google Analytics gives you an
unfiltered view. This means all data will show up when you're in this view.



Set up views:
===================

Once you’ve installed your google Analytics code on your website.  Its time to get started .
The very first thing you should do is create a custom **View**.

By default Google Analytics gives you an unfiltered view.
We want to setup an initial view where we will use a simple filter to not filter out any data from us and any employees.


Create A New View
=====================

In order to create a new view make sure to be logged in. Click the “Admin” link on the left menu.

The View tab will be the far right column.

Click on the dropdown and click “Create New View”

![Setting up a custom view](/assets/img/add-views-analytics-1.jpg)

Name the view “Default View”. Were going to use this as the base for your data.


Create A Filter For the View
===============================

Now that you’ve created a view. its time to filter that data. There are many many reasons why you’d want to filter
data on that view.  If you have a campaign that you’re basing in only New York you could filter data to only
show users visiting your site from New York.

In this instance were going to add a filter to remove any visits to the site from our ip address.

If you don’t know this don’t worry. Just go to google and search “What is my ip address?”.
The results will give you your actual ip address.  Pretty cool huh?

Just copy that ip address.

Now back in “Views” click on the “Filters” link.

![Create A Filter for the view](/assets/img/add-views-analytics-4.jpg)

You should now see the “View” page.  On this page click the red button. “+ Add Filter”.

![Create A Filter for the view](/assets/img/add-views-analytics-5.jpg)


Now its time to “Add Filter to View”

![Create A Filter for the view](/assets/img/add-views-analytics-6.jpg)


Here are details about each section on this Add Fiter to View form.

**Choose a method to apply filter to view:**

Choose the “Create new Filter”.

**Filter Name:**

We are going to choose “Predefined”.

**Filter Type:**

We will call the filter “Exclude Employees”.

Beneath that we’ll do the following rules.

“Exclude”  and  “traffic from the ip addresses” and “that are equal to”.

**Ip Address:**

And that’s it.  Click the “Save” button.

Congrats. You’ve just created your first filter. This will filter out any and all website analytics from your
employees giving you a better picture of who is coming to your site.

So that’s it for today. In our next Google Analytics post were going to cover how to setup goals and use a real
world example of testing out a custom goal for users subscribing to our newsletter.

Good luck and **Be Awesome**.
