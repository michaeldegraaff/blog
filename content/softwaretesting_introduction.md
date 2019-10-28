+++
title = "Software testing methods: How we integrated them in our development cycle"
date = "2019-01-14"
tags = ["test", "methods"]
+++

The key question when building websites, web shops, intranets, mine environments and customized software is: Does it all work as we have agreed upon? The best way to find out is to cover the acceptance criteria. In this article you can read how we have seamlessly integrated testing into our development process.
<!--more--> 

# Testing: A specialization area of its own
We have various in-house testers that validate the functionality and performance of our software. Because just as a writer has a difficulty editing his own work, a developer can have a blind spot for his own code. Next to that, a developer cannot always oversee what happens when different separately built functionalities of the software come together. 

# Before starting the project: Define acceptance criteria
Testers actually start before development starts, namely when drawing up the acceptance criteria. They should because these criteria also contain the various test components and the conditions that the software must meet. The tester helps specify these criteria and decides on whether these are valid.

By doing this, it will prevents surprises during the acceptance test at the end of the process. During the acceptance test, the client runs through the application, website or web shop. If errors still come to light, you have to go all the way back in to the development process. 

# Technical tests
The requirements are specified in the Definition Of Done (DoD). This document describes what the software must meet and therefore what and how it will be tested. Every time a piece of software is ready, the development team performs two technical tests:

**Unit test (explanation below)**

> We test the smallest testable unit, for example a separate software module, a menu choice that calls on various other modules, or another part of the software.

**System test**

> We test all testable units, but in conjunction with each other. Because multiple parts that work perfectly independently of each other can result in an error when combined. 

In addition to these two standard technical tests, there are three more performance tests. These tests guarantee that the entire system, i.e. all the different parts together, performs properly and that the various functions are performed quickly enough. These are:

**Load test**

> The tester examines whether the system can handle a real user load, both with normal and peak use. If not, the developer, tester, system administrator and designers will find the cause of this. Together with the system administrator, we also look at the technical infrastructure to see which improvements are possible here.

**Stress test**

> During a stress test we put pressure on the system for a long time with a lot of input, many users and many processing operations. This way we find out how many user actions the system can handle.

**Duration test**

> Where the stress test simulates a long-term peak load, the purpose of the duration test is to simulate a real load over a long period. This allows you to check whether the hardware does not collapse under prolonged load. You can also track memory leaks, whereby the system uses an unnecessary amount of computer memory.

It is advisable to let the three performance tests take place periodically after delivery or go live. This way you know for sure that your application, website or web shop will continue to work properly. 

# Functional tests
Thanks to the technical tests, we know that the software works technically: there are no error messages, the software does not stop suddenly, and the speed (performance) is sufficient. But software must not only work technically, you must be able to work with it. That is why we perform three different functional tests:

**Regression test** 

Every time a new part of the software is ready, we develop a special test script that automatically checks whether the software does what it should do. This is the so-called regression test. As the software is further expanded, the set of test scripts is also being expanded further and further. In this way, we continue to monitor during the development process


**Functional acceptance test (FAT)**

> Both the tester and the end user get to work with the software and see if everything actually works as agreed upon.

**User acceptance test (GAT)** 

> This test also takes place with a user panel. They then test whether the software offers sufficient support for what they attend to do with it when it's finished.

# Decide on when to start testing
As soon as part of the software is ready, we perform a unit, system and regression test. When bugs are found, we immediately pick it up in the next step of the development process. The functional and user acceptance tests take place at the end of the process. 