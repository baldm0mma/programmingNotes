## General Questions

### ORMs

Object-relational mapping. Basically a library (for whatever chosen language) to translate/manipulate SQL databases.

### IDEs

Integrated development environment. Basically a text editor with a bunch of extra features to make coding easier.

#### Spectrum

Vim on one side, and Visual Studio on another.

### GCP Specifics

- Cloud Storage
- Cloud Build
- Container Registry
- Cloud Functions
- Kubernetes Engine

### Event Driven APIs - Pizza Analogy

- Webhooks
  - Tell the pizza place to call me when my pizza’s ready.
- Websockets
  - Call the pizza place, and just hang out on the phone with the pizza guy, to talk about whatever.
- Polling
  - Call the pizza place every 5 seconds, and ask if my pizza’s done.
- HTTP streaming
- Server sent events
  - Call the pizza place, and they give me a live update of how my pizza is doing, until it’s ready. But I can’t chat with them. Hang up. Just a long req-res connection.

#### Long polling

- Call the pizza place and ask if the pizza’s ready. Silence until the pizza is ready, at which point they tell me my pizza’s ready.

### TCP vs HTTP?

- HTTP is built on TCP. TCP is only really concerned with delivering packets of data, while HTTP is another protocol built on top of the TCP functionality.

### JSON vs XML vs HTML?

- Marshall and unmarshall (Go)/serialize and deserialize/stringify and parse

### Prototypal vs class inheritance?

### Recursion vs iteration?

- Recursion: a function that calls itself repeatedly to iterate through a function. At its core, it’s just a function that calls itself.
- Iteration: step through a collection of items.
- Elixir tail call optimization? Why doesn’t everybody do this?

### Iteration vs Enumeration?

- What's the diff?

### OOP

- What's the point???

### Markup vs markdown language

- What's the diff?

### Bits and Bytes

- What’s the deal?
  - So, how do we get from bits/bytes to characters and strings?
  - Also, why is a byte 8 bits instead of 10? Seems easier.

### Functors and Monads?

### Kubernetes/Docker/Containers/Images/Pods/Clusters/Orchestration?

### Singleton Pattern?

- What is it's purpose?
  - Use cases?

### Dependency Injection?

### Design Patterns?

### MVC?

### Currying?

- What is it?
  - Why is it useful?

### Closures?

- What are they?
  - Why are they useful?

### Functional Programming?

- What is it?
  - Why is it useful?

### Object Oriented Programming?

- What is it?
  - Why is it useful?

### Declarative Programming?

- What is it?
  - Why is it useful?

### Imperative Programming?

- What is it?
  - Why is it useful?

### Procedural Programming?

- What is it?
  - Why is it useful?

### Functional Programming?

- What is it?
  - Why is it useful?

### Getters and setters

- What are they?
  - Why are they useful?
  - Are they a pattern?

