---
title: "A Simplified Introduction to Dart"
date: 2019-03-05T15:58:35+05:30
author: "Sameeha Rahman"
featured_image: "/img/blog/dart.jpg"
categories: ["Flutter"]
type: "blog"
draft: false
---
<h2>What is Dart?</h2>
<p>Google had its first ever release of Flutter 1.0 last December, after having it in beta mode for over 18 months. Dart is the programming language used to code Flutter apps. Dart is another product by Google and released version 2.1, before Flutter, in November. As it is starting out, the Flutter community is not as extensive as ReactNative, Ionic, or Xamarin.
A while back, I discovered a liking for JavaScript. I was ecstatic to be working on a ReactNative mobile app for my internship. I enjoy coding hybrid mobile apps too, so wanted to give Flutter a try, as I had done Xamarin sometime last year.
At my first glance of Flutter (and Dart), I felt befuddled and couldn’t seem to understand anything. They even had a section on their docs for developers moving from React Native. So, I took to digging deeper on all things Dart.</p>
<p>Dart looks a bit like C and is an object-oriented programming language. So, if you prefer the C languages or Java, Dart is the one for you, and you’ll likely be proficient in it.
Dart is not only used for mobile app development but is a programming language. Approved as a standard by Ecma (ECMA-408), it’s used to build just about anything on the web, servers, desktop and of course, mobile applications (Yes, the same people who standardized our favorites ES5 and ES6.)</p>
<p>Dart, when used in web applications, is transpiled to JavaScript so it runs on all web browsers. The Dart installation comes with a VM as well to run the .dart files from a command-line interface. The Dart files used in Flutter apps are compiled and packaged into a binary file (.apk or .ipa) and uploaded to app stores.</p>

<h2>What does coding in Dart look like?</h2>
<p>1. The entry point of a Dart class is the main() method. This method acts as a starting point for Flutter apps as well.</p>
<p>2. The default value of most data types is null.</p>	
<p>3. Dart classes only support single inheritance. There can be only one superclass for a particular class but it can have many implementations of Interfaces.</p>
<p>4. The flow control of certain statements, like if conditions, loops (for, while and do-while), switch-case, break and continue statements are the same.</p>
<p>5. Abstraction works in a similar manner, allowing abstract classes and interfaces.
</p>

<h2>Unlike them (and sometimes a bit like JavaScript)</h2>
<p>1. Dart has type inference. The data type of a variable need not be explicitly declared, as Dart will “infer ”what it is. In Java, a variable needs to have its type explicitly given during declaration. For example, String something;. But in Dart, the keyword is used instead like so, var something;. The code treats the variable according to whatever it contains, be it a number, string, bool or object.</p>
<p>2. All data types are objects, including numbers. So, if left uninitialized, their default value is not a 0 but is instead null.</p>
<p>3. A return type of a method is not required in the method signature.</p>
<p>4. The type num declares any numeric element, both real and integer.</p>
<p>5. The super() method call is only at the end of a subclass’s constructor.</p>
<p>6. The keyword new used before the constructor for object creation is optional.</p>
<p>7. Method signatures can include a default value to the parameters passed. So, if one is not included in the method call, the method uses the default values instead.</p>
<p>8. It has a new inbuilt data type called Runes, that deal with UTF-32 code points in a string. For a simple example, see emojis and similar icons.</p>