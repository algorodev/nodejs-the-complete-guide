# Understanding the basics

## How the web works

```
Client => Request => Server => Response => Client
```

## Program Lifecycle & Event Loop

- Node.js runs non-blocking JS code and uses an event-driven code ("Event Loop") for running your logic.
- A Node program exits as soon as there is no more work to do.
- The createServer() event never finishes by default.

## Asynchronous Code

- JS code is non-blocking.
- Use callbacks and events => Order changes!

## Requests & Responses

- Parse request data in chunks (Streams & Buffers).
- Avoid "double responses".

## Node.js & Core Modules

- Node.js ships with multiple core modules (e.g. http, fs, path, etc.).
- Core modules can be imported into any file to be used there.
- Import via `require('module-name')`.

## The Node Module System

- Import via `require('path-to-file')` for custom files or `require('module-name')` for core & third-party modules.
- Export via `module.exports` or just `exports` for multiple exports.

## Useful Resources & Links

- [Official Node.js Docs](https://nodejs.org/en/docs/guides)
- [Node.js Core Modules](https://nodejs.org/dist/latest/docs/api/)
- [Node.js Event Loop](https://nodejs.org/en/docs/guides/event-loop-timers-and-nexttick/)
- [Blocking vs Non-Blocking Code](https://nodejs.org/en/docs/guides/blocking-vs-non-blocking/)
