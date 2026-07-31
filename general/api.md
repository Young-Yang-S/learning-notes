## API (Application Programming Interface)

### What is an API?

An **API (Application Programming Interface)** is an interface that allows one piece of software to interact with or use the functionality of another piece of software.

In simple terms:

> **API = A defined way for one software component to communicate with or use another software component.**

The caller does not need to know how the other software works internally. It only needs to know **how to call the API and what result to expect**.

### General API

In a broad sense, an API does **not** have to involve the Internet or a frontend/backend architecture.

For example, in C#:

```csharp
File.ReadAllText("test.txt");
```

`ReadAllText()` is part of the .NET API. We can use it to read a file without knowing how .NET or the operating system performs the low-level file operation.

Conceptually:

```text
My Program
    ↓
   API
    ↓
Other Software / Library / System
```

### Web API

A **Web API** is an API that is accessed over a network, typically using **HTTP/HTTPS**.

For example:

```text
GET https://example.com/api/users/123
```

A client sends an HTTP **request** to the API, and the server sends back an HTTP **response**, often containing data in JSON format.

```text
Client
  ↓
HTTP Request
  ↓
Web API
  ↓
Backend / Database
  ↓
HTTP Response
  ↓
Client
```

The client does not have to be a web browser. It can be:

- A web frontend
- A mobile app
- Another backend service
- A C# or Python application
- An API testing tool such as Insomnia

### API vs. Web API

| Concept | Meaning |
|---|---|
| **API** | A general interface that allows software to interact with other software |
| **Web API** | An API that is accessed over a network, usually through HTTP/HTTPS |
| **Relationship** | A Web API is one type of API |

**Key idea:**

> All Web APIs are APIs, but not all APIs are Web APIs.
