---
layout: post
author: Jesse Parker
title: "Wait...Why Should I, A GIS Person, Learn Programming?"
---

# Why Programming?
When I started learning GIS in school, I did not understand programming...I didn't even know what programming or software development was. This was not all bad. I was able to dedicate time to really understanding spatial concepts, map making, and Error code 99999. 

Eventually you will stop wanting to do the boring tasks of a GIS Tech, as I did. This is probably why you are here reading this blog. Or maybe, you want to create new tools for coworkers, custom widgets for web apps, or even full custom web mapping applications for your customer. Fantastic! You have come to the right place for a jumping off point.

If you learn by doing, like me, this blog will should work really well for you. I do not intend to hold hands, but I will give you learning paths and resources that I have found useful in my self-taught studies.


Below are a couple areas where you can use programming to improve your GIS workflows.

## - Automate Tasks and Workflows
If you're new to programming, this is where you want to start. Think of a task you do everyday on your computer...that you find really boring...preferably a GIS task. This is your first project after you learn the basics. 

![Automate the Boring Stuff]({{ site.url }}/assets/post/images/automate_the_boring_stuff.jpg)

A good book to start learning Python that many people recommend is [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/){:target="_blank"} by [Al Sweigart](https://twitter.com/AlSweigart){:target="_blank"}. (BTW, click that link. The book is there for FREE!). This will book will not only walk you through the syntax, but also give you a good idea on how powerful Python (and programming in general) can be.

## - Process Data
If you have worked with GIS in any capacity for more than 5 minutes, you know the data frequently requires various transformations, manipulations, translations, et cetera. In programming these operations are known to many as *ETL*, or Extract-Transofrm-Load.

Some GIS software provides tools to do these tasks, but usually they only cover common workflows. An example of this would be the ArcGIS [KML to Layer](https://pro.arcgis.com/en/pro-app/latest/tool-reference/conversion/kml-to-layer.htm){:target="_blank"} conversion tool. This is a good generic tool to extract Google format data, transform it to an ArcGIS format, and load it into a geodatabase. 

> *So if we can do this in existing software, why would we need programming?*

Think about what your workflow might look like in the following examples using this tool:
- What if you had 1000 KMLs to process?
- What if you only needed a specific feature or type in each of those KMLs?
- What if you wanted the data in ArcGIS Enterprise or ArcGIS Online?

Using Python, or other programming technologies, you can reduce unnecessary steps and time in the above examples.

# I do those things already, where else can I use these skills?

Look around your organization, would your users or colleagues benefit from a mobile application for data collection or visualization?

Maybe your CEO needs a 'Go' button to do a specific analysis in one of your out-of-the-box web applications?

Maybe you need a new ribbon in ArcGIS Pro with tools and buttons that do complete common tasks for you?

What about creating a super awesome custom map that you want to post to [r/DataIsBeautiful](https://www.reddit.com/r/dataisbeautiful){:target="_blank"} or [r/GIS](https://www.reddit.com/r/gis){:target="_blank"}?

# You can do it!

Learn the syntax.

Learn some basic programming concepts.

Start with small projects that are useful for your day-to-day 

It's all about the easy wins at the beginning. 

![Programmers - Dark Mode]({{ site.url }}/assets/post/memes/dark_mode_bugs.jpg)
