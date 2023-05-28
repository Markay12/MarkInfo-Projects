---
layout: post
title: "Swift App Programming"
date: 2023-01-24
excerpt: "Swift is a modern and powerful programming language developed by Apple. It is designed to be fast, safe, and efficient, making it suitable for developing a wide range of software applications, including mobile apps, desktop software, and even server-side applications. This module showcases learning the Swift programming language and some of the projects I have created."
project: true
tags: [Mobile App Development, GitHub]
feature: 
comments: false
---

![Github Commits](https://img.shields.io/github/last-commit/Markay12/SwiftProgramming-Introduction?color=orange&label=Last%20Commit&style=plastic)
![Github Contributors](https://img.shields.io/github/contributors/Markay12/SwiftProgramming-Introduction?label=Contributors)

[Github Page](github.com/Markay12/SwiftProgramming-Introduction)


# Swift Language

Swift is an intuitive programming language created by Apple for iOS, macOS, watchOS, and tvOS app development. It's an open-source language that is designed to be not only easy to learn, but also powerful enough for professional developers. Since its introduction in 2014, Swift has quickly become one of the fastest growing languages in history.

Swift adopts safe programming patterns and adds modern features to make programming easier, more flexible, and more fun. The compiler is optimized for performance, and the language is optimized for development, without compromising on either.

Swift incorporates the latest research on programming languages, combined with decades of experience building Apple platforms. Named parameters are expressed in a clean syntax that makes APIs in Swift even more easy to read and maintain. Memory is managed automatically and there is no use of semicolons.

In addition, Swift supports inferred types to make code cleaner and less prone to mistakes, and modules eliminate headers and provide namespaces.


# GitHub Swift Structure

The structure of this GitHub page is setup with three main sections. The three main sections are as follows

1. docs
2. Projects 
3. Exploratory

## Docs

The docs directory stores all the documented information on how to write code using swift. The docs in here include quick notes on how to use Swift and its modules. This section is more for learning about Swift and how to use the language than actual projects. Syntax, namespace, and optimization techniques are included. The learning modules included up to May 26th 2023 are

1. Introduction [For Syntax]
2. Arrays
3. Dictionaries
4. Navigation View

All four of these are great to get started learning how to use the Swift language and start creating your own applications.

## Projects

The projects directory includes many projects that I have worked on and projects that you can start with yourself. They are all great starting places for anyone to get their hands on Swift. The list that I will be putting here is how I suggest starting with the projects. This is so you can begin with some easier subjects before moving onto the more difficult app programming techniques.

### Person Information Application

This is a good introductory application to learning how to use Swift and Storyboards. This application is a simple input and output based app that logs user information and based on that information, returns output.

This app takes users SSN, Name, and Age. This information is then stored using CoreData on the phone. Since the information is stored, users and patients that have already been logged into the system can be searched. Example of the front UI is shown here.


<img src="/assets/img/swift_apps/patientInfoScreenshot.png" alt="Patient Information UI Image" width="200" height="300">

### Patient Portal

The patient portal application was developed to showcase the use of multiple different modules working together. The file structure of this project showcases how to modularize the code. There is a new file for each working sheet/part of this project. 

Rather than having a button on the main view that executes a large group of code, it will call the methods and functions of the other file in the project. Therefore, this project demonstrated encapsulation and inheritance between different files and objects. 

In addition to what was added above, this project exhibits a better UI design for users. As the projects continue the UI and UX will become increasingly better as we are no longer just focused on the basics of code but also usability.


<img src="/assets/img/swift_apps/PatientPortal_AddHealth.png" alt="Patient Information UI Image" width="234" height="506.4">
<img src="/assets/img/swift_apps/PatientPortal_MainView.png" alt="Patient Information UI Image" width="234" height="506.4">

<img src="/assets/img/swift_apps/PatientPortal_CheckHealth.png" alt="Patient Information UI Image" width="234" height="506.4">

The above three images showcase the main workings of the application. The user is able to add information about their health each morning and it will be added to their log. 

As the user inputs information it will be checked to see whether or not they are in a healthy range for their body. This is where the check is made and will alert the user if their health readings are not good.


![Github Commits](https://img.shields.io/github/last-commit/Markay12/SwiftProgramming-Introduction?color=orange&label=Last%20Commit&style=plastic)
![Github Contributors](https://img.shields.io/github/contributors/Markay12/SwiftProgramming-Introduction?label=Contributors)

[Github Page](github.com/Markay12/SwiftProgramming-Introduction)
