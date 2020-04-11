---
title: "Flutter: The Future Of Mobile App Development"
date: 2019-05-20T15:58:17+05:30
author: "Eric Grandt"
featured_image: "/img/blog/flutter2.jpg"
categories: ["Flutter"]
type: "blog"
draft: false
---
<p>I dabbled a bit in Android and iOS development quite a few years back using Java and Objective-C. After spending about a month working with both of them, I decided to move on. I just couldn’t get into it.</p>	
<p>But recently, I learned about Flutter and decided to give mobile app development another shot. I instantly fell in love with it as it made developing multi-platform apps a ton of fun. Since learning about it, I’ve created an app and a library using it. Flutter seems to be a very promising step forward and I’d like to explain a few different reasons why I believe this.</p>
<h2>Powered by Dart</h2>
<p>Flutter uses the Google-developed Dart language. If you’ve used Java before, you’ll be fairly familiar with the syntax of Dart as they are quite similar. Besides the syntax, Dart is a fairly different language.</p>
<p>I’m not going to be talking about Dart in depth as it’s a bit out of scope, but I’d like to discuss one of the most helpful features in my opinion. This feature being support for asynchronous operations. Not only does Dart support it, but it makes it exceptionally easy.</p>
<p>This is something you’ll most likely be using throughout all of your Flutter applications if you’re doing IO or other time-consuming operations such as querying a database. Without asynchronous operations, any time-consuming operations will cause the program to freeze up until they complete. To prevent this, Dart provides us with the async and await keywords which allow our program to continue execution while waiting for these longer operations to complete.
</p>

<h2>Write Once, Run on Android and iOS</h2>
<p>Developing mobile apps can take a lot of time considering you need to use a different codebase for Android and iOS. That is unless you use an SDK like Flutter, where you have a single codebase that allows you to build your app for both operating systems. Not only that, but you can run them completely natively. This means things such as scrolling and navigation, to name a few, act just like they should for the OS being used.
To keep with the theme of simplicity, as long as you have a device or simulator running, Flutter makes building and running your app for testing as simple as clicking a button.</p>

<h2>UI Development</h2>
<p>UI development is one of those things that I almost never look forward to. I’m more of a backend developer, so when it comes to working on something that is heavily dependent on it, I want something simple. This is where Flutter shines in my eyes.
UI is created by combining different widgets together and modifying them to fit the look of your app. You have near full control over how these widgets display, so you’ll always end up with exactly what you’re looking for. For laying out the UI, you have widgets such as Row, Column, and Container. For content, you have widgets like Text and RaisedButton. This is only a few of the widgets Flutter offers, there are a lot more.</p>

<h2>Libraries</h2>
<p>Flutter provides a lot of great features out of the box, but there are times when you need a bit more than it offers. This is no problem at all considering the extensive number of libraries available for Dart and Flutter. Interested in putting ads in your app? There’s a library for that. Want new widgets? There are libraries for that.</p>	
<p>If you’re more of a do-it-yourselfer, make your own library and share it with the rest of the community in no time at all. Adding libraries to your project is simple and can be done by adding a single line to your pubspec.yaml file. </p>
<p>After adding it to the file, run flutter packages get and you're good to go. Libraries make developing Flutter apps a breeze and save a lot of time during development.</p>

<h2>Final Thoughts</h2>
<p>With Flutter, the possibilities are practically endless, so even super extensive apps can be created with ease. If you develop mobile apps and have yet to give Flutter a try, I highly recommend you do as I’m sure you’ll fall in love with it as well. After using Flutter for quite a few months, I think it’s safe to say that it’s the future of mobile development. If not, it’s definitely a step in the right direction.</p>