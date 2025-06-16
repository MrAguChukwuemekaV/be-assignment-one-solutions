# Basic Understanding

## Relationship between Node.js and the V8 JavaScript engine.
  - V8 as the Core JavaScript Engine for Node.js: Node.js uses V8 as its core engine to execute JavaScript code. V8 takes the JavaScript code,          compiles it into machine code, and then executes it. This process allows Node.js to run JavaScript efficiently on the server side, just as V8       allows for fast execution of JavaScript in the browser.
    
  - Performance Benefits: V8’s JIT compilation and other optimization techniques provide significant performance benefits. Node.js leverages these      benefits to handle a large number of simultaneous connections with high throughput and low latency.

  - Integration of V8 into Node.js: Node.js embeds the V8 engine directly into its runtime. This embedding enables Node.js to execute JavaScript        independently of a web browser. The integration is seamless, allowing Node.js to run JavaScript applications on any platform that V8 supports.

  - Access to V8 APIs: Node.js exposes some of V8’s internal APIs, allowing developers to tap into V8’s advanced features, such as custom memory        management and optimization settings. This integration provides more control and flexibility when developing high-performance applications.

  - Extension of V8 Capabilities: Node.js provides a set of APIs and built-in modules (e.g., fs for file system operations, http for creating           servers) that extend V8's capabilities. These APIs are written in C++ and exposed to JavaScript, allowing developers to perform operations          beyond the scope of what V8 alone can handle.

  - Asynchronous I/O and V8(Event Loop Integration): Node.js uses an event loop to handle asynchronous I/O operations, such as reading from a file      or making a network request. While V8 executes JavaScript code, the event loop manages these non-blocking operations. This integration allows       Node.js to handle thousands of concurrent operations without blocking the execution of JavaScript code.

 ## Resources.
    - https://www.geeksforgeeks.org/node-js/what-is-the-relationship-between-node-js-and-v8/
