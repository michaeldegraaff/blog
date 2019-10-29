+++
title = "Trends in software testing- part 1: High level overview"
date = "2019-10-28"
tags = ["test", "software", "machine learning", "devOps", "Iot", "big data"]
+++

The software development industry never stands still. To remain relevant as a software tester in this ever-changing and dynamic world, finding a connection with these new trends is extremely important. In these series we will discuss some of these current trends in software development to see if and how we as software testers will remain important now and in the future.
<!--more-->
As a starting point for these series, we will describe on a high level what the trend comprehends and how software testers are or will be affected by this. We will then go on a deepening per trend in the continuation of the series.
 
# Machine learning in testing
Within software development, machine learning is mainly about the development of algorithms. The development of these algorithms involves analyzing (often large amounts of) data. How this information is handled can be divided into three categories.

For example, "Supervised Machine" learning uses data where the input and output are determined by people. This way of machine learning can best be compared to a teacher who supervises the learning process. We know the correct answers, the algorithm where our brains repeatedly makes predictions about the course material and is corrected by the teacher. Learning stops when the algorithm has reached an acceptable performance level.

With "Unsupervised Machine learning" only input is given to data but no output is determined. The purpose of this is to model the underlying structure or distribution in the data to learn more about the data. No correct answers are given here.

Finally, there is "Reinforcement Machine" learning. This way of machine learning is nothing but learning through trial & error. A computer examines the ideal outcome based on data by simply simulating this a large number of times.

When testing software, there must be a defined and known output for each input. We enter values, make selections or navigate through an application and compare the actual result with the expected result. If they match, the test case may continue, if this is not the case, then we may have a bug.

In the above scenario, a tester would analyze the acceptance criteria of the test object and cover it in test scenarios. The biggest problem nowadays lies in the fact that we want more and more coverage of acceptance criteria with all possible marginal cases because more functionality within applications is considered critical. On the other hand, we have less time for this. The less time there is to process data, the greater the chance that testing will produce unusable results with overlooked errors in the software. Before you know it, customers will find bugs, which usually leads to frustration and the reputation of the brand.

For the purpose of regression, we then want to automate as many test cases as possible. Automating this is a lot of repeated work and takes a lot of time on maintenance. This is because traditional testing techniques still depend on people to collect and analyze data.

This is where machine learning can help. With machine learning, we can learn the system to learn and apply that knowledge in the future. This contributes to reducing errors. The time required to perform a software test and find a possible bug is shortened and the amount of data that needs to be processed can still increase without increasing the pressure on the test team.

There are already a number of interesting solutions for this on the market. Platforms where machine testing can be used to create, manage and execute automated tests, without having to program them yourself and without having to worry about maintenance.

# Increasing Adoption or DevOps
Before a piece of functionality can be delivered within software development, it first goes through all different disciplines within a company. This includes architecture, development, design and testing. All these disciplines are responsible for the end result of the software and the code. To improve the collaboration and productivity of the software development process, DevOps integrates these disciplines by: Automating the infrastructure, automating workflows and continuously measuring the performance of applications. All this is aimed at keeping the quality of the software as high as possible. This makes testing an important player within the DevOps method.

Whereas traditionally attention was only paid to testing at the end of the development process, it now concerns cooperation at every level, which means that testing has been at the table from the start of development. By guaranteeing quality throughout the development of a functionality, it is ensured that the functionality can be released/delivered at any time.

Automating tests plays a crucial role in guaranteeing quality and the speed with which functionalities can be delivered. It is important that testers integrate and work closely with the development team. Because of this close collaboration, the tester knows at all times which pieces of code/functionality will be delivered at what time and the tester can immediately start deregistering and prepare as much as possible for the automation of the test cases.

All this contributes to identifying bugs as early as possible in the development process. Because the automated test cases are part of the joint infrastructure and dashboards are set up for the results, the team can already see the effect on the quality of the whole and where the errors occur when delivering the smallest piece of functionality.
 
# Big Data Testing
"Big Data" is a collection of data that cannot be stored or processed by the traditional database.

Big Data is characterized by the large amounts of data, the pace at which it is generated and the diversity of the different types of data. Big data can be divided into two categories:

+ Structured: An example of this is purchase data from a webshop
+ Unstructured: Social media posts or online reviews of products

Testing at Big Data involves the verification of this data stream. The data from the different sources must be the same as the data that ends up in the big data system. In addition, no data may be lost. Every logbook or message generated from the source must be present in the Big Data system. In addition, it is also tested whether duplicates end up in the system.

Both performance and functional testing are used to validate these data flows.

> For example, a performance test can be used to determine how quickly the system can process the data from different data sources and how the system handles data that are waiting to be processed.

Functional testing of the big data is reasonably comparable to testing of normal software applications. Functional testing is performed by testing the front-end application based on user requirements. The front can be a web application that has an interface with a big data framework at the back. Results produced by the front-end application must be compared with the expected results to validate the application.
 
# IoT Testing
The Internet of Things is about a network of devices that are connected to the internet to collect and exchange data. The connected devices send this data to servers where it is then aggregated and analyzed. We usually have access to the results on our mobile devices or computers via apps or browsers. Testers verify all these results to ensure the reliability of the application. In addition, the availability, sending and receiving of data to the servers play an important role.

Broadly speaking, IoT test scenarios are subdivided into six types:
- Security testing: Dealing with data attack is fundamental to IoT operations and therefore companies must conduct security testing to eliminate vulnerabilities and maintain data integrity. This includes examining various aspects of the system, including data protection, encryption / decryption, authentication of device identities, etc.
- Performance testing: This includes validating and guaranteeing consistent performance of reading, writing and retrieving data. Including load tests, streaming and timing analyzes.
- Compatibility testing: Here it is assessed whether the existing combination of hardware, software, protocols and operating systems are compatible with the standards and specifications of the IoT framework.
- Functional testing: Here the end result is tested. Aspects such as network size and environmental conditions are also tested.
- Regulatory Testing: Testing whether IoT applications comply with the privacy rules.
- Scalability testing: This includes testing all functional and non-functional use cases to determine if the system can be easily scaled to allow future upgrades.

To stay at the forefront of the software development industry, test professionals need to stay abreast of the latest test trends. Although integration in most organizations is still a matter of the future, organizations should already delve into these new trends by looking at which processes could strengthen integration. This prevents disturbances in the future, because we can no longer ignore the fact that these subjects are increasingly playing a role.

In this article you have read about a couple of trends in software development and what testing as a discipline has to do with that. In the follow-up series, we will explore the trends individually by zooming in further on how we can put these trends in to practice within the test discipline.
