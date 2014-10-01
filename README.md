# What are you looking for?
[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/Rajivhost/ReactiveTrader?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

 - [A quick overview](#overview)
 - [Video & Podcast](#video-and-podcast)
 - [Documentation](https://github.com/AdaptiveConsulting/ReactiveTrader/wiki)
 - [Blogs](#blogs)
 - [Training](#training)
 - [Future Announcements](#future-annoucements)

# Overview

Reactive Trader is a client-server application demonstrating some of the problems needing to be dealt with when building reactive, or event driven, user interfaces. It was initially built as a demonstration application for a presentation we gave at [ReactConf 2014](http://reactconf.com/). We have decided to open source it so the community can benefit from our contribution.

Reactive Trader was written by the team at [Adaptive](http://weareadaptive.com), a consultancy that specialises in building real time trading systems. We have many years of experience in building trading systems for clients with highly demanding latency and reliability requirements. Over the years we have learnt quite a few lessons, and wanted to talk about and point to examples of how we solve technical problems related to real time delivery of messages.

![image](https://f.cloud.github.com/assets/1256913/2470980/8e95e5c6-b01c-11e3-9311-cc17a7c1b191.png)

... talking via Web Socket with ...

![image](https://f.cloud.github.com/assets/1256913/2470993/d7f153ea-b01c-11e3-9c0c-ac8c8261299a.png)

Reactive Trader comes in different flavours (click on the link for a demo)
 
 - [WPF (ClickOnce)](https://reactivetrader.blob.core.windows.net/client/Adaptive.ReactiveTrader.application)
 - [HTML5](https://reactivetrader.azurewebsites.net/)
 - [Windows Store App](http://apps.microsoft.com/windows/app/reactive-trader/a2c622c5-ef66-4653-911f-688fe79ac999)
 - [iOS native app](https://itunes.apple.com/gb/app/reactivetrader/id892239109?mt=8)

# Talk

Click on the image below to watch the video on YouTube.  It was recorded during our talk at [ReactConf 2014](http://reactconf.com/)
[![Our video from ReactConf 2012](http://img.youtube.com/vi/Tp5mRlHwZ7M/0.jpg)](http://www.youtube.com/watch?v=Tp5mRlHwZ7M)

# Podcast

![Hanselminutes](http://www.hanselman.com/images/blog-hanselminutes.png)

We had the pleasure of chatting with [Scott Hanselman](http://www.hanselman.com/) on his regular podcast Hanselminutes about Reactive Trader, Rx, trading systems, open source, etc.
[Podcast](http://www.hanselminutes.com/428/creating-reactive-user-interfaces-with-adaptive-consultings-reactive-trader)

# Blogs

We have written a number of blog posts in which we dive deeper into certain aspects of Reactive Trader.

- [Asynchrony and concurrency](http://weareadaptive.com/blog/2014/04/18/asynchrony-concurrency/), in which we discuss embracing asynchrony and concurrency at all levels of your application.
- [Everything is a stream](http://weareadaptive.com/blog/2014/05/05/everything-is-a-stream/), in which we point out that all service calls from Reactive Trader result in streams of responses, not just a single response - and why this is so powerful.
- [System health & failures](http://weareadaptive.com/blog/2014/06/16/system-health-failures/), in which we dig more into models of system health so you can easily respond to failures in your application, and how to use heart beating to detect component failure.

# Training

We have been using Reactive Extensions since 2010. Lee Campbell, author of [Intro To Rx](http://www.introtorx.com/), runs our Rx training course, [Practical Rx](http://weareadaptive.com/training). We still have places available at our next scheduled course in London, UK, on July 7th and 8th. Tickets are [available here](https://ti.to/adaptive/rxtraining), and you can also [read more about the course](http://weareadaptive.com/training). Reactive Trader makes extensive use of Reactive Extensions, and this course is a great opportunity to learn to think in Rx.

# Future Announcements

We announce all new features and [blog posts](http://weareadaptive.com/blog/) on Twitter: [@AdaptiveLimited](https://twitter.com/AdaptiveLimited)
