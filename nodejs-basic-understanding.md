# Node.js Basic Understanding 
<!-- 
  Thought Process:
  1. Definition of the concept.
  2. Difference between with Nodejs and traditional server-side technologies. 
-->

## 1. Definition 
 - it is a  cross-platform, open-source, server-side  asynchronous event-driven JavaScript runtime (that can run on Windows, Linux, Unix, macOS etc)
   designed to build scalable network applications.

## 2.Difference between with Nodejs and traditional server-side technologies.
  - While Node.js uses JavaScript (via the V8 engine) for both client and server-side development, 
    traditional server-side technologies such as  PHP, Java, ASP.NET are predominantly used for backend technologies.
  - In terms of Use Cases: Node.js Best for real-time apps (chat, gaming), APIs, and microservices while 
    Traditional servers are better for monolithic applications, server-rendered pages such as  WordPress.
  - In terms of Concurrency Model: Node.js uses an event-driven, non-blocking I/O model, handling multiple requests in a single thread via callbacks, Promises, or async/await.
    while traditional Servers such as Apache, Tomcat, Often use multi-threaded blocking I/O, where each request spawns a new thread, leading to higher memory usage.

##  Resources:
  - Node.js Official Docs: https://nodejs.org/en/docs/
  - "Node.js Design Patterns" by Mario Casciaro (Book)
  - Stack Overflow Developer Survey 2023
  - IBM Developer: Why Node.js?
