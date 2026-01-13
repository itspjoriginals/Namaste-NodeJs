# 📘 Episode 2 – JavaScript on the Server & V8 Engine

## 🌐 What is a Server?

A **server** is a remote computer that:

- Receives requests from clients  
- Processes those requests  
- Sends responses back  

### Example

- Client (Browser) → Server → Response

---

## 🔁 JavaScript: From Browser to Server

### Initially
- JavaScript ran **only inside browsers**

### After Node.js
- JavaScript can run on **servers**
- Enabled **full-stack development** using a single language

---

## 🧩 Node.js Internals (Important)

- Node.js is written in **C++**
- V8 Engine is also written in **C++**
- JavaScript itself is **NOT fast enough** to communicate directly with hardware

---

## ⚙️ What is the V8 Engine?

V8 is Google’s **high-performance JavaScript engine** that:

- Converts JavaScript into **machine code**
- Follows **ECMAScript standards**
- Is embedded inside **Node.js**

### Execution Flow

- JavaScript Code
- ↓
- V8 Engine (C++)
- ↓
- Machine Code
- ↓
- Computer (Binary)


---

## 🚀 Node.js Superpowers

### V8 Alone
- Can execute JavaScript

### Node.js Adds
- File system access
- Database connections
- Network calls
- APIs

👉 This is why **Node.js is more powerful than V8 alone**.

---

## 📌 Key Takeaways

- **Node.js = C++ application + V8 Engine**
- V8 executes JavaScript, Node.js provides **system-level access**
- **ECMAScript defines JavaScript rules**, V8 follows them
