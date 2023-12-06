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
