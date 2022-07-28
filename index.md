# Welcome to My journey to full stack developer 
# Week 1:
## Front-End Web UI Frameworks and Tools
* Express what is meant by full stack in the context of web development

## What is full stack ?

```
In the world of software programming, it helps to have someone on the team who is something of a jack of all trades.

A full stack web developer is a person who can develop both client facing and server side software.
Full Stack Developers have to have some skills in a wide variety of coding niches, 
from databases to graphic design and UI/UX management in order to do their job well.

The modern full stack developer is an experienced generalist who can build a minimal viable product
— i.e., an application with enough functionality to please early customers and spark feedback for continued development on their own.
```

## front-end vs back-end vs client-side vs server-side

```Client side and server side are web development terms that describe where application code runs. Web developers will also refer to this distinction as the frontend vs. the backend, although client-side/server-side and frontend/backend aren't quite the same.

In web development, 'client side' refers to everything in a web application that is displayed or takes place on the client (end user device). This includes what the user sees, such as text, images, and the rest of the UI, along with any actions that an application performs within the user's browser.

*Client-side* refers solely to the location where processes run, while *frontend* refers to the kinds of processes that run client-side.

rendering, the process of combining data with HTML and CSS, can be done either client side or server side. 

In *server-side rendering* this combination of data (text, images, etc) and display rules is done entirely on the server. 

developers write code that tells the server to collect the nessasary data from it’s database, combine it with display rules (HTML & CSS) and send it to the browser.

Alternately , *client-side rendering* is where this combination (combining data with HTML & CSS) is done entirely on the browser using JavaScript.

*Front-end* is not always *client-side*, it is possible to have front-end code even if your web application uses server-side rendering. having it rendered on the server does not change the fact that it is frontend code (HTML & CSS) that will determine what the user sees. On the flip-side, anything that happens on the client-side is referred to as front-end.

a *front-end framework*, i.e a "client-side rendering framework", is a code library used to make client-side rendering (using JavaScript) easier, faster & more performant.
Examples of these are: React, Vue, Angular
React is a library, while Angular is a full-fledged framework. 

Libraries provide developers with predefined functions and classes to make their work easier and boost the development process.	

Frameworks, on the other hand, is like the foundation upon which developers build applications for specific platforms. 

The technical difference between a framework and library lies in a term called inversion of control.

When you use a library, you are in charge of the flow of the application. You are choosing when and where to call the library. When you use a framework, the framework is in charge of the flow. It provides some places for you to plug in your code, but it calls the code you plugged in as needed.
```

## Three-tier architecture

```
Three-tier architecture is a well-established software application architecture that organizes applications into three logical and physical computing tiers: 

*The presentation tier* is the user interface and communication layer of the application, where the end user interacts with the application. Its main purpose is to display information to and collect information from the user. This top-level tier can run on a web browser, as desktop application, or a graphical user interface (GUI), for example. Web presentation tiers are usually developed using HTML, CSS and JavaScript. Desktop applications can be written in a variety of languages depending on the platform.

*The application tier*, also known as the logic tier or middle tier, is the heart of the application. In this tier, information collected in the presentation tier is processed - sometimes against other information in the data tier - using business logic, a specific set of business rules. The application tier can also add, delete or modify data in the data tier.

The application tier is typically developed using Python, Java, Perl, PHP or Ruby, and communicates with the data tier using API calls. 

*The data tier*, sometimes called database tier or data access tier, is where the information processed by the application is stored and managed. This can be a relational database management system such as PostgreSQL, MySQL, MariaDB, Oracle, DB2, Informix or Microsoft SQL Server, or in a NoSQL Database server such as Cassandra, CouchDB or MongoDB. 

There is an increasing trend towards using a single language to implement the entire stack, i.e: JavaScript so you could have the frond end implemented, for example, as a single page application using frameworks like Angular or React.

the server-side or The application tier being implemented using technologies like NodeJS, which is also dependent on and JavaScript.

and then you have the data storage, being implemented using technologies like MongoDB, which stores data in the form of JSON documents.

```

  
