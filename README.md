# react-native-exploration
This project will contain documentation, links, and references to projects using React Native.

## But First, An Introduction
Hi, my name is Jorge Viramontes. I've served as an iOS developer for over 5 years as a software consultant. I've also had experience developing web applications using Angular built on top of Typescript. The purpose of this project is to document any findings as I explore how to use React Native to build iOS and Android applications. I will explore and leverage various APIs, SDKs, and other tools to quickly build valuable features. I hope you find this valuable and insightful as you progress along your own coding journey.

## Practical Adivce for the Newbie

My journey started with a simple Google search: "How to write iOS apps using React Native." Here's my advice on how to learn any new development tool.

### **Find the documentation of the tool.** 
The internet is a wide world out there. But sometimes the simplest solutions are provided to you by the people who worked on the product themselves. Many development frameworks will contain a "Getting Started" guide, "Quick Start" guide, tutorials, or extensive documentation of their API. I would highly recommend spending time with the resources they provide and explore what the existing community provides. 

### **Try everything.** 
Here's a secret that not many developers will tell you: coding is just a whole bunch of searching on Google and following tutorials, or finding a solution on StackOverflow that fits your needs. The more practice and experience you get, the more comfortable and confident you will become as you gain experience using different debugging techniques and get the results you ultimately expect. It's a giant game of **experiment, fail, learn, iterate.** 

### **Understand the foundation.** 
While it's important to try everything to get your software to work, it's a lot smarter to try everything once you understand how the underlying mechanism works. Before getting started, it is important to have a foundational understanding of data structures and algorithms and the language you are using. JavaScript is a powerfully simple language that is used in a myriad of ways by various frameworks and libraries, React Native included. 

To jump right in to development without understanding how JavaScript functions under-the-hood will leave you in a constant game of catch up, uncertain about what's going on. I _highly_ recommend checking out [this course on JavaScript](https://www.udemy.com/course/understand-javascript/). The instructor goes into details on some of the most complex parts of JavaScript such as runtime and execution time, function scope, etc., and explains it in a digestable easy-to-understand way.

Okay, okay, okay. Enough chit-chat. Let's get down to the nitty gritty.

![Code all the things](/assets/code-all-the-things.jpg)

## What You'll Need

### **Hardware** 
I work using a MacBook Pro (13-inch, 2016). This is the only piece of hardware you will need to build applications using React Native. Having an actual mobile device for testing is a nice-to-have but not necessary, as there are emulators that allow you to run your mobile app on your machine. 

### **Terminal** 
If you're not familiar with Git & the Terminal Command Line Interface (Terminal CLI), I highly recommend use learn your way around that first, as it makes your development process faster and, frankly, you just look much cooler working out of a terminal. It's like you're going into the Matrix. 

![Run, Neo, Run!](/assets/run-neo-run.jpg)

_Run Neo, Run!_

A simple Google search for "Mac terminal basic commands" yields fruitful results, such as this [tutsplus article](https://code.tutsplus.com/tutorials/command-line-basics-and-useful-tricks-with-the-terminal--cms-29356).

### **Web Development Tools**
If you're new to web development, welcome! I promise, it's not that scary of a world here. Being a web developer means downloading a shitton of libraries from the internet that other smart people have already built before you. Don't reinvent the wheel, stand on the shoulders of giants. All you have to do is finally install all those funny-sounding libraries you've heard people talking about.

To successfully get your project up and running using Expo, you'll need to download the following:
 * [Node.js.](https://nodejs.org/en/) JavaScript runtime built on Chrome's V8 JavaScript engine. 
 * [npm CLI](https://www.npmjs.com/get-npm). Your terminal's best friend for downloading trusted libraries with a single command line. This comes included with your download of Node.js. Two-for-one, sweet!

#### Using Expo
[Expo](https://expo.io/) is one of those cool tools I just discovered by doing this exploration. Expo empowers a development team to build, deploy, and quickly iterate on native Android, iOS, and web apps from the same JavaScript codebase. It provides a great level of flexibility while still maintaining quality of the end user experience. 

#### Without Using Expo
If app size is a concern*, or you wish to explore React Native with more flexibility, you can use the react-native-cli, but this will require 

> *Expo iOS apps ship at minimum size of 25MB and Android apps at 20MB. This is because it includes code for all the Expo APIs whether you choose to use them or not. 

## Time to Build
As I stated above, the best resources are often provided by the creators of the tool, so I followed along with this [environment setup](https://reactnative.dev/docs/environment-setup) to get a Hello World app on my iPhone. It was really exciting how quickly I was able to see results using these tools. I was able to go from zero to app on my phone using the [Expo Client](https://expo.io/tools#client) in about a day. 

## Check My Work
I used the above tutorials to create these projects and will continue to dive into these more and try integrating different features.

- TBD

## **Closing Thoughts - Decisions, Decisions, Decisions**
Look, if you're new to web development, it may surprise you that there are several decisions you need to make as you move forward and develop your application. The sheer amount of packages available on [npm](https://www.npmjs.com/) can be daunting, let alone all the [JavaScript libraries and frameworks.](https://en.wikipedia.org/wiki/List_of_JavaScript_libraries)
This was something that would hold me back in the past, but it becomes easier when you realize it's all about focusing on your expected outcome and how we can get there.

To align us back on our focus, we want to build an app for iOS & Android. Using the React Native framework is a great solution for this. React Native provides a development experience where one builds React components that ultimately use native iOS & Android code. This is different than other solutions such as [Adobe PhoneGap](https://phonegap.com/) or [Apache Cordova](https://cordova.apache.org/), which [run web views inside the native code](https://cordova.apache.org/docs/en/latest/guide/overview/), which leads to a subpar user experience. 

Building apps with React Native allows us to build Android and iOS apps straight from our MacBook. 

## Sources

Envato tuts+ Command Line Basics: https://code.tutsplus.com/tutorials/command-line-basics-and-useful-tricks-with-the-terminal--cms-29356
JavaScript Course: https://www.udemy.com/course/understand-javascript/
React Native Development Environment Setup: https://reactnative.dev/docs/environment-setup
Cordova Architecture Diagram: https://cordova.apache.org/docs/en/latest/guide/overview/
Blog on PhoneGap: https://reactorapps.io/blog/beginners-guide-to-phonegap/
