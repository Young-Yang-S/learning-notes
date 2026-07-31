# WSL (Windows Subsystem for Linux)

## What is WSL?

**WSL (Windows Subsystem for Linux)** allows Linux environments to run directly inside Windows.

It allows Windows users to use Linux tools, commands, and applications without installing a separate Linux operating system.

Conceptually:

```text
Windows
│
├── Windows Applications
│
└── WSL
    └── Linux Environment
```

For example, with WSL, Linux commands can be used directly on a Windows machine:

```bash
ls
cd
grep
sudo apt install
```

A Linux distribution such as **Ubuntu** can also run through WSL:

```text
Windows
   ↓
WSL
   ↓
Ubuntu
```

---

## WSL 1 vs WSL 2

There are two major versions:

- WSL 1
- WSL 2

**WSL 2** is the modern and commonly used version.

Unlike WSL 1, WSL 2 uses a real Linux kernel, which provides much better Linux compatibility.

WSL 2 is commonly used for:

- Linux development
- Docker
- Bash
- Git
- Python
- Node.js
- Linux command-line tools

---

## WSL and Docker

Docker containers are commonly based on Linux.

On Windows, Docker Desktop can use **WSL 2** to provide the Linux environment required to run Linux containers.

Conceptually:

```text
Windows
   ↓
WSL 2
   ↓
Linux Environment
   ↓
Docker Desktop / Docker Engine
   ↓
Docker Container
   ↓
Application
```

For example, when running Memos:

```text
Windows
   ↓
WSL 2
   ↓
Docker
   ↓
Memos Container
   ↓
http://localhost:5230
```

Therefore, if WSL 2 is not installed or working correctly, Docker Desktop may not be able to start its Linux container environment.

---

## WSL vs Virtual Machine

A traditional virtual machine usually runs an entire guest operating system:

```text
Windows
   ↓
VMware / VirtualBox
   ↓
Linux Virtual Machine
   ↓
Linux Applications
```

WSL provides a Linux environment that is much more tightly integrated with Windows:

```text
Windows
   ↓
WSL
   ↓
Linux Environment
```

For development purposes, this makes using Linux tools on Windows much more convenient.

---

## Key Idea

> **WSL provides a Linux environment inside Windows.**

For Docker:

> **WSL 2 can provide the Linux foundation that Docker Desktop uses to run Linux containers on Windows.**
