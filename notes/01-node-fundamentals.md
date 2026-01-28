# Node.js Fundamentals

## 1. What is Node.js?
It's a JavaScript runtime environment, that allow us to execute JavaScript outside the web browser.

## 2. What makes Node.js unique?
It's open source powered by Google's V8 engine, and designed to handle asynchronous I/O efficiently, managing communication between the client and the server.

## 3. Why Node.js exists
Node.js was created to handle asynchronous I/O efficiently, solving scalability problems found in traditional blocking server models.

## 4. How Node.js works
- Single-threaded
- Event Loop
- Non-blocking I/O
    - Hardly any Node.js functions block I/O, so we can have handle many requests without blocking our server. 

## 5. Key Concepts
- Event Loop
- Call Stack
- Callback Queue
- Promise Microtasks

## 6. Common Mistakes
- Blocking the event loop
- Using sync FS methods in production
- Forgetting to handle errors in async code

## 7. When to use it
- APIs with high I/O operations
- Real-time applications
- Background workers

## 8. Interview Notes
- Node.js uses a single-threaded event loop for concurrency.
- It excels at I/O-bound workloads.

