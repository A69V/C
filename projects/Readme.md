
# 🛠️ Systems Programming Projects (in C)

This repository contains a collection of **foundational C programming projects** designed to strengthen my knowledge of **low-level systems, algorithms, and operating system concepts**.  
Each project has been built with the aim of gaining a **deep engineering understanding** that will be valuable for both research internships (e.g., GSoC, academic projects) and industry roles.

---

## 📂 Project Directory

### 1. **Custom Shell (`myshell/`)**
- A Unix-like command-line shell implemented in C.  
- Supports:
  - Running system commands (`ls`, `cd`, `cat`, etc.)
  - Input/output redirection (`>`, `<`)  
  - Piping (`|`)  
- **Concepts Covered:** Process creation, system calls, file descriptors, OS internals.

---

### 2. **File Compression Tool (`compression/`)**
- A simple implementation of **Huffman coding** for file compression/decompression.  
- Reads a file, compresses it to a smaller size, and decompresses it back.  
- **Concepts Covered:** File I/O, trees, bit manipulation, encoding/decoding.

---

### 3. **HTTP Client & Server (`http/`)**
- Basic **HTTP server**: serves static HTML pages.  
- Basic **HTTP client**: fetches and displays webpages from a server.  
- **Concepts Covered:** Sockets, TCP/IP networking, request parsing, client-server architecture.

---

### 4. **Tiny Database Engine (`tinydb/`)**
- A lightweight database engine inspired by **SQLite internals**.  
- Features:
  - `INSERT`, `SELECT`, `DELETE` operations  
  - File-based storage with indexing (hashing or B-trees)  
- **Concepts Covered:** File structures, indexing, query execution, persistence.

---

### 5. **Custom Memory Allocator (`allocator/`)**
- A reimplementation of `malloc()` and `free()` in C.  
- Manages a fixed-size memory pool with block allocation and deallocation.  
- **Concepts Covered:** Pointers, memory management, fragmentation handling, OS-level memory.

---

## 📑 Index of Files
. ├── myshell/ # Project 1: Custom Shell 
  │   ├── shell.c 
  │   ├── README.md 
  │   └── Makefile 
  │ 
  ├── compression/ # Project 2: File Compression Tool 
  │   ├── huffman.c 
  │   ├── README.md 
  │   └── Makefile 
  │ 
  ├── http/  # Project 3: HTTP Client & Server 
  │   ├── server.c 
  │   ├── client.c 
  │   ├── README.md 
  │   └── Makefile 
  │ 
  ├── tinydb/  # Project 4: Tiny Database Engine 
  │   ├── tinydb.c 
  │   ├── README.md 
  │   └── Makefile 
  │ ├── allocator/  # Project 5: Custom Memory Allocator │   ├── allocator.c │   ├── README.md │   └── Makefile │ └── README.md             # Main repository description

---

## 🎯 Goal
By completing these projects, I aim to:
- Build a **strong foundation** in system-level programming.  
- Understand how **operating systems, compilers, and databases** work internally.  
- Prepare myself for **open-source contributions (GSoC)** and **future internships**.  

---
