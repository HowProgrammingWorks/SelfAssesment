## Node.js and backend

- Internals and concepts
  - Strong and weak sides of node.js: 👂 heard
  - Stateful and stateless servers: 👂 heard
  - Nonblocking I/O and slocking code: 👂 heard
  - Event loop: phases: 👂 heard
  - Event loop: microtasks and macrotasks: 👂 heard
  - Garbage collection: 👂 heard
    <!-- - Node.js LTS schedule -->
    <!-- - I/O-bound, CPU-bound, memory-bound tasks -->
    <!-- - Interactive applications (close to real-time) -->
- Modularity, layers and dependencies
  - CommonJS modules: 🖐️ used
  - ECMAScript modules: 🖐️ used
  - node:module: 🖐️ used
  - Caching in CJS and ESM: 👂 heard
  - Modules as singletons: 🖐️ used
  <!-- - Contexts and scripts node:vm -->
  - Dependencies: npm, node_modules: 🖐️ used
  - Dependencies: package.json and package lock: 🖐️ used
  <!-- - Module-based permissions model -->
  - Isolation with modularity: 🎓 known
  - Dependency injection: 👂 heard
  - DI containers: 👂 heard
  - Coupling and cohesion: 🎓 known
  - Framework agnostic approach: 👂 heard
- Environment
  - Command line arguments: 🖐️ used
  - Node.js CLI: 🖐️ used
  - Process-based permissions: 🖐️ used
  - Graceful shutdown: 👂 heard
  - Clustering: 👂 heard
  - Watch filesystem changes with --watch: 🖐️ used
- Internal API
  - Streams API: 🎓 known
    <!-- - Web Streams API:  -->
    <!-- - Crypto API -->
  - Password hashing with node:crypto.scrypt: 👂 heard
  <!-- - Web Crypto API -->
  - File system API: sync and async: 🖐️ used
  - Copy folder recursively: 🖐️ used
  - Worker threads: 🎓 known
  - Performance hooks: 👂 heard
  - Native fetch and nodejs/undici: 🖐️ used
  - node:async_hooks: 🖐️ used
    <!-- - AsyncLocalStorage -->
    <!-- - AsyncResource -->
  - Deprecated domain API: 🎓 known
  - Node.js single executable: 🎓 known
  <!-- - Stream back pressure -->
  - SharedArrayBuffer: 🎓 known
  - node:worker_threads: 🎓 known
  - node:child_process: 🖐️ used
  - MessageChannel, MessagePort: 🎓 known
  <!-- - BroadcastChannel -->
  - Generating crypto random UUID: 🎓 known
  - node:url vs new URL: 🎓 known
  - node:assert: 🖐️ used
  - Internationalization: 🎓 known
  - Blob, File, Buffer, node:buffer: usde
  - Module node:zlib: 🎓 known
- Application structure and architecture
  <!-- - Isolation between layer -->
  - Multilayer approach: 🖐️ used
  - Separation of concerns: 🎓 known
  - Inversion of control: 🎓 known
  - Dependency injection: 🖐️ used
  - GRASP: 🎓 known
  - SOLID: 🎓 known
  - GoF patterns: 🎓 known
  - Distributed systems: 🎓 known
  - Highload applications: 🎓 known
  - Clean architecture: 🎓 known
  - DDD: 🎓 known
    <!-- - Message Queue -->
    <!-- - CQS -->
  - CQRS: 🖐️ used
  <!-- - Event sourcing -->
  - Load balancing: 🎓 known
  - Serverless clouds: 👂 heard
  - FaaS clouds: 👂 heard
  - Fat controller: 👂 heard
  - GoF for Node.js: 👂 heard
  - Leaking abstractions: 👂 heard
- Network
  - IP sticky sessions: 👂 heard
  <!-- - Endpoint throttling -->
  - HTTP(S): 🖐️ used
  - TCP/SSL: 🖐️ used
  - UDP: 🖐️ used
  - TLS: 🎓 known
  - Websocket: 🖐️ used
  - SSE: 🎓 known
  - HTTP/3 (QUIC): 🎓 known
  <!-- - Long polling -->
  - REST: 🖐️ used
  <!-- - RPC: 🎓 known -->
  - Routing: 🖐️ used
  <!-- - DoS -->
  - DDoS: 🖐️ used
  - XSS: 🎓 known
  - Path traversal: 🎓 known
  <!-- - CSRF -->
  - DNS: 🖐️ used
  - Fetch API: 🖐️ used
  - IncomingMessage: 🎓 known
  - SQL injection: 🎓 known
  <!-- - noDelay -->
  - keep-alive: 🎓 known
    <!-- - ALPN -->
    <!-- - SNI callback -->
  - SSL certificates: 🎓 known
  - Protocol agnostic approach: 👂 heard
- Technique and tools
  <!-- - Native test runner -->
  - Logging: 🖐️ used
  - Application configuring: 🖐️ used
  - Testing: 🖐️ used
  - CI/CD: 🖐️ used
  - Readable: 🖐️ used
  - Writable: 🖐️ used
  - Transform: 🎓 known
  <!-- - back pressure -->
  - Buffer: 🖐️ used
  - Console: 🖐️ used
  - Inspector: 🖐️ used
  - Reliability: 🖐️ used
  - Quality: 🖐️ used
  - Availability: 👂 heard
  - Flexibility: 🖐️ used
- Data access
  <!-- - Data access layer: 🖐️ used -->
  - Repository: 🖐️ used
  - Active record: 👂 heard
  - Query builder: 👂 heard
  - Object-Relational Mapping: 👂 heard
- Error handling and debugging
  - Error: 🎓 known
  - error.cause: 🎓 known
  - error.code: 🎓 known
  - error.message: 🖐️ used
  - error.stack: 🎓 known
  - How to avoid mixins: 👂 heard
  - Error.captureStackTrace: 🎓 known
  - Uncaught exceptions: 🖐️ used
  - Heap dump: 👂 heard
  - Debugging tools: 🖐️ used
  <!-- - Flame graph -->
  - Memory leaks: 🎓 known
  - Resource leaks: 🎓 known
  - Data race: 👂 heard
- Integrations and bindings
  - Native addons: 👂 heard
  - C and C++ addons: 👂 heard
  - Rust addons: 👂 heard
  - Zig addons: 👂 heard
    <!-- - NAN (Native Abstractions for Node.js) -->
    <!-- - Node-API (formerly N-API) -->
    <!-- - NAPI C and C++ -->
    <!-- - NAPI Rust -->
    <!-- - NAPI Zig -->
    <!-- - Webassembly WAT -->
    <!-- - Webassembly C and C++ -->
    <!-- - Webassembly Rust -->
    <!-- - Webassembly Zig -->
  - Webassembly AssemblyScript: 🎓 known
  - Shared memory: 👂 heard
  - SharedArrayBuffer: 👂 heard
  - V8 binary serialization: 👂 heard
