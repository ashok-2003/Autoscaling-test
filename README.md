# ⚡ Vertical Scaling in JavaScript with Cluster Module

This project demonstrates how to implement **vertical scaling** in a Node.js environment using the built-in `cluster` module.

## 🚀 Overview

JavaScript (Node.js) is traditionally single-threaded, which means by default, it doesn't utilize all available CPU cores. However, with the help of the `cluster` module, we can **spawn multiple worker processes** that run simultaneously, enabling Node.js to handle multiple tasks in parallel — **all while listening on the same port**.

### 💡 What This Project Showcases

- How to leverage the power of Node.js’s `cluster` module
- Creating a **primary (master)** process that manages **worker processes**
- Efficient task delegation across multiple CPU cores
- Unlocking the full performance potential of your machine through **vertical scaling**

## 🛠️ How to Run

1. Clone the repository
2. Install dependencies:

   ```bash
   npm install

3. Run the project
   ```bash
   npm start
