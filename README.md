# Visual Studio Live! San Diego - August 2023  

## Description  
This repository contains slides and code samples for sessions presented at Visual Studio Live! San Diego - August 7-11, 2023.  

## Sessions  

**M01 - Hands-On Lab: Asynchronous and Parallel Programming in C#**  
*Level: Intermediate*  

Asynchronous programming is a critical skill to take full advantage of today's multi-core systems. But async programming brings its own set of issues. In this workshop, we'll work through some of those issues and get comfortable using parts of the .NET Task Parallel Library (TPL).  

We'll start by calling asynchronous methods using the Task Asynchronous Pattern (TAP), including how to handle exceptions and cancellation. With this in hand, we'll look at creating our own asynchronous methods and methods that use asynchronous libraries. Along the way, we'll see how to avoid deadlocks, how to isolate our code for easier async, and why it's important to stay away from "async void".  

In addition, we'll look at some patterns for running code in parallel, including using Parallel.ForEachAsync, channels, and other techniques. We'll see pros and cons so that we can use the right pattern for a particular problem.  

Throughout the day, we'll go hands-on with lab exercises to put these skills into practice.  

Objectives:  

* Use asynchronous methods with Task and await  
* Create asynchronous methods and libraries  
* How to avoid deadlocks and other pitfalls  
* Understand different parallel programming techniques  

Pre-Requisites:  

Basic understanding of C# and object-oriented programming (classes, inheritance, methods, and properties). No prior experience with asynchronous programming is necessary; we'll take care of that as we go.  

Attendee Requirements:

* You must provide your own laptop computer (Windows or Mac) for this hands-on lab.

* You need to have the .NET 6 SDK or .NET 7 SDK installed as well as the code editor of your choice (Visual Studio 2022 Community Edition or Visual Studio Code are both good (free) choices).

* Interactive labs, web application samples, and console samples will work with Windows, macOS, and Linux (anywhere .NET 6/7 will run).

* WPF desktop samples will only work on Windows machines. There are equivalent web and console examples for these projects.

Links:

* .NET 7.0 SDK
[https://dotnet.microsoft.com/en-us/download](https://dotnet.microsoft.com/en-us/download)

* Visual Studio 2022 (Community)
[https://visualstudio.microsoft.com/downloads/](https://visualstudio.microsoft.com/downloads/)
Note: Install the "ASP.NET and web development" workload for the labs and samples. Include ".NET desktop development" for "digit-display" sample and WPF-based samples.

* Visual Studio Code
[https://code.visualstudio.com/download](https://code.visualstudio.com/download)

Resources:  
* Slides: [/M02-hol-async-and-parallel-programming/SLIDES-M02-Asynchronous-Programming-in-CSharp.pdf](./M02-hol-async-and-parallel-programming/SLIDES-M02-Asynchronous-Programming-in-CSharp.pdf)
* Sample Code: [/M02-hol-async-and-parallel-programming/](./M02-hol-async-and-parallel-programming/)  
* Labs (for easy download): [https://github.com/jeremybytes/async-workshop-labs-only-2023](https://github.com/jeremybytes/async-workshop-labs-only-2023)

---  

**T15 - Get Func-y: Delegates in C#**  
*Level: Introductory / Intermediate*  

Delegates are the gateway to functional programming. So lets understand delegates and how we can change the way we program by using functions as parameters, variables, and properties. In addition, we'll see how the built in delegate types, Func and Action, are waiting to make our lives easier. We'll see how delegates can add elegance, extensibility, and safety to our programming.  

You will learn:
* What delegates are  
* How to use functions as parameters and return values  
* Write code that can be easily extended  

Resources:  
* Slides: [/T15-delegates/SLIDES-T15-delegates-in-csharp.pdf](./T15-delegates/SLIDES-T15-delegates-in-csharp.pdf)
* Sample Code: [/T15-delegates/](./T15-delegates/)

---

**W22 - I'll Get Back to You: Task, Await, and Asynchronous Methods in C#**  
*Level: Introductory / Intermediate*  

There's a lot of confusion about async/await, Task/TPL, and asynchronous and parallel programming in general. So let's start with the basics and look at how we can call asynchronous methods using Task and then see how the "await" operator can makes things easier for us. Along the way, we'll look at continuations, ConfigureAwait, and exception handling.

You will learn:  
* How to run code after a Task is complete  
* How to handle exceptions that occur in an asynchronous method  
* When to use "ConfigureAwait"    

Resources:  
* Slides: [/W22-task-and-await/SLIDES-W22-task-and-await.pdf](./W22-task-and-await/SLIDES-W22-task-and-await.pdf)
* Sample Code: [/W22-task-and-await/](./W22-task-and-await/)

---
