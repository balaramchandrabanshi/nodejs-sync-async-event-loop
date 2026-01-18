# Node.js Sync, Async & Event Loop (Day 1)

## About

This project demonstrates how Node.js executes synchronous and asynchronous code,
and how the Event Loop prioritizes different queues.

## Concepts Covered

- Synchronous (blocking) execution
- Asynchronous (non-blocking) execution
- Event Loop phases
- Microtask queue (Promises)
- Timer queue (setTimeout)
- I/O callbacks
- Check queue (setImmediate)

## Observation

Microtasks are executed before timers and I/O callbacks.
This explains how Node.js handles concurrency despite being single-threaded.

## Key Takeaway

Understanding the Event Loop is essential for writing efficient Node.js applications.
