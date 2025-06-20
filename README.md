# Intro to Node.js
  
**Definition/Overview:** Node.js provides developers with an open source and cross-platform (e.g., hardware architectures, operating systems) JavaScript (JS) runtime environment, allowing for the use of JS code (which is ran outside of a web browser, via the V8 JS engine) to perform server-side scripting and create command line based utilities.

A common implementation of Node.js is to have code execute server-side, producing dynamic web page content prior to pages being sent to a client (web browser). Web apps with high scalability and performance obligations (such as HTML web browser games and messaging platforms) benefit from Node.js's asynchronous input/output functionality.
  
#### Table of Contents
  
1. [Installing Node.js](#installation)
2. [Getting Started](#getting-started)
3. [14 Techniques for Optimizing Node.js](#techniques)
4. [MEAN and MERN Stack Development](#stackdev)
5. [Supplemental Resources](#supplemental)
  
<hr />
  
## 1. <a name="installation">Installing Node.js</a>
  
Directions for installing Node.js via a variety of platforms and package managers can be found at the technology's <a href="https://nodejs.org/en/download">official website</a>.
  
<hr />
  
## 2. <a name="getting-started">Getting Started</a>

Node can be run at command line using the ``node`` command/keyword.
  
A popular naming convention for the core file of a JS app is 'app.js.'. Thus, to run a file named app.js in Node:

```
node app.js
```

Node integrates a package management tool known as *npm*, which is used for fetching and installing third-party libraries to enhance apps. As an example: MEAN and MERN stack developers utilize a JS framework technology known as *ExpressJS* to create server-side (backend) APIs (in other words, to handle client requests by serving back data to clients). To install Express, the following command could be used:

```
npm install express
```

Within actual JS code, Express might then be imported using the following statement:
  
```
const express = require('express');
```
  
<hr />
  
## 3. <a name="techniques">14 Techniques for Optimizing Node.js</a>
   
* **Asynchronous Function Utilization**
  + Asynchronous functions enable processors to handle more than one request at the same time, with non-blocking input/output functionality.
* **Circuit Break Functions that are Likely to Fail**
  + If a function is highly plausible to fail upon execution, it can be kept from running at all.  
* **Decrease the 'Time to First Byte' (TTFB) Metric**
  + How long it takes for a client (e.g., web browser) to receive its first data byte from a server can be minimized.
* **Do Not Use API Cookies and Sessions**
  + Authentication controls can be supplied by stateless API systems, with the client storing authentication tokens (reducing processor burden for the server).
* **Employ Throttling**
  + This reduces how many client requests are to be accepted for processing at one time.
* **Enable Caching**
  + When repeated requests are anticipated, they can be handled predictably (and more quickly).
* **Error Script Logging**
  + Bugs might be acknowledged and solved more rapidly when logs are consulted/employed.
* **Improve Database Query Processing Efficacy**
  + Discover the queries that slow the processor down, and modify them appropriately. 
* **Keep Apps Alive by Using PM2 Clustering**
  + Apps can be kept up and refreshed via PM2 (a load balance that is built into Node.js for production process management).
* **Keep Node.js Updated**
  + Utilizing the latest versions of Node.js can lead to stronger performance for various reasons (such as more robust logic and patching).
* **Make Use of Profilers**
  +  Profilers can discover processor performance issues, and be of assistance with error correction.
* **Modularize  Architecture and Code Design**
  + This makes apps less complicated and easier to understand and maintain.
* **Run Parallel Tasks**
  + This can improve processor performance (decreased wait times).
* **Utilize HTTP/2**
  + Advantages of HTTP/2 over HTTP include multiplexing and header compression.
  
<hr />
  
## 4. <a name="stackdev">MEAN and MERN Stack Development</a>
  
MEAN and MERN stack developers are JavaScript web app creators who combine client and server side development with database operations. For more information, consult: [Intro to MERN and MEAN Stack Guide](https://github.com/chaseofthejungle/intro-to-mern-and-mean-stack).
  
<hr />
  
## 5. <a name="supplemental">Supplemental Resources</a>

* *[Intro to MERN and MEAN Stack Guide](https://github.com/chaseofthejungle/intro-to-mern-and-mean-stack)*
* *[Intro to ReactJS Guide](https://github.com/chaseofthejungle/intro-to-reactjs)*  
* *[JavaScript Concepts Guide](https://github.com/chaseofthejungle/js-concepts-guide)*
