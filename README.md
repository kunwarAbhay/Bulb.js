<h1 align="center">⚡Tubelight.js</h1>
<h3 align="center">A pure javascrpt library providing most common data structures implementation.</h3>

## Table of Contents

- [Quick Start](#-quick-start)
- [Stack](#stack)
- [Queue](#queue)
- [Priority-Queue](#priority-queue)
- [Disjoint-Set](#disjoint-set)

## 🚀 Quick Start

### 👉 Installation

Install Tubelight with npm

```bash
npm install tubelight
```

## 🪨 Stack

A stack is a linear data structure that follows the principle of Last In First Out (LIFO).

```js
const Tubelight = require("tubelight");

const stack = new Tubelight.Stack();
```

### ⚒️ Operations that can be performed on Stack :

❄️ Push : Add an element to the top of a stack

```js
/**
 * Push element on the top of the stack
 * @param {Object} element
 */

stack.push(element);
```

❄️ Pop : Remove an element from the top of a stack

```js
/**
 * Remove the topmost element from the stack
 * @return {Object} element
 */

stack.pop();
```

❄️ IsEmpty : Check if the stack is empty

```js
/**
 * True if the stack is empty otherwise return false
 * @return {Boolean}
 */

stack.isEmpty();
```

❄️ Peek: Get the value of the top element without removing it

```js
/**
 * return the element at the top of stack without removing it
 * @return {Object} element
 */

stack.peek();
```

### ⏳ Time Complexity :

❄️ Push, pop, IsEmpty & peek Operations take O(1) time.

### 🗑️ Space Complexity :

❄️ Stack requires O(n) Space Complexity where n is no. of elements in stack.

## 🪨 Queue

```js
const Tubelight = require("tubelight");

const queue = new Tubelight.Queue();
```

## 🪨 Priority Queue

```js
const Tubelight = require("tubelight");

const priorityQueue = new Tubelight.PriorityQueue();
```

## 🪨 Disjoint Set

```js
const Tubelight = require("tubelight");

const disjointSet = new Tubelight.DisjointSet();
```

<!-- 🧱🪨📌⏳⏱️🗑️💼❄️🔥🌀🚫❗❓💯✅❎⏺️➡️⬅️↗️↘️🔴🟢🟡🟠🟨🟧🟩🟦🔺🔻🕐🕑 -->
