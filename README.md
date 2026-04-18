# 🚀 Redis Clone in Java

A minimal, from-scratch implementation of a Redis-like in-memory key-value store built using Java.

---

## 📌 Overview

This project is a deep dive into how Redis works internally. Instead of treating Redis as a black box, this implementation focuses on:

- TCP server fundamentals
- Event-driven architecture
- Redis Serialization Protocol (RESP)
- In-memory data storage

The goal is to understand backend systems from first principles.

---

## ⚙️ Features

- ✅ Basic TCP server
- ✅ RESP command parsing
- ✅ `PING` command
- ✅ `SET` & `GET` operations
- 🚧 Concurrent client handling (in progress)
- 🚧 Expiry & persistence (planned)

---

## 🧠 Key Learnings

- Socket programming & networking
- Protocol design (RESP)
- Concurrency basics
- Efficient in-memory data handling

---

## 🏗️ Project Structure

```
src/
 └── main/
     └── java/
         └── Main.java
```

---

## ▶️ Running the Project

Ensure Java & Maven are installed.

```bash
./the_evolver_program.sh (example)
```

---

## 🧪 Example Usage

Connect using:

```bash
redis-cli
```

Then run:

```
PING
SET key value
GET key
```

---

## 🎯 Why This Project

Most developers use Redis, but few understand how it works internally.  
This project focuses on building that understanding from scratch.

---

## 📌 Future Improvements

- Event loop (non-blocking I/O)
- Persistence (RDB/AOF)
- More Redis commands
- Performance optimizations

---

## 🙌 Acknowledgment

Inspired by hands-on system design and low-level backend challenges.
