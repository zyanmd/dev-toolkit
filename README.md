# 🛠️ Dev Toolkit

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/zyanmd/dev-toolkit/pulls)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/zyanmd/dev-toolkit)

A lightweight, zero-dependency collection of modular utility functions and helper tools designed to streamline daily JavaScript/TypeScript development workflows.

---

## 🚀 Features

- ⚡ **Zero Dependencies** — Ultra-lightweight and tree-shakeable.
- 🔤 **String Formatting** — Slugify, capitalize, truncate, and sanitize text easily.
- 🔢 **Math & Number Utilities** — Clamp, interpolate, and range helpers.
- 📦 **Data Structures** — Deep cloning, empty checking, and object manipulation.
- 🛡️ **Type-Safe** — Standard JSDoc annotations ready for IDE autocompletion.

---

## 📦 Installation

```bash
npm install @zyanmd/dev-toolkit
# or
pnpm add @zyanmd/dev-toolkit
# or
yarn add @zyanmd/dev-toolkit
```

---

## 💡 Quick Start

```javascript
import { slugify, capitalize, clamp, randomString, isEmpty } from '@zyanmd/dev-toolkit';

// String helpers
console.log(slugify("Hello World & Dev Toolkit!")); // "hello-world-dev-toolkit"
console.log(capitalize("frontend and backend developer")); // "Frontend And Backend Developer"

// Number helpers
console.log(clamp(150, 0, 100)); // 100

// Utility helpers
console.log(randomString(12)); // e.g. "aB3x9Z7kLmQp"
console.log(isEmpty([])); // true
```

---

## 📖 API Reference

### `slugify(str: string): string`
Converts input strings into clean, URL-friendly kebab-case strings.

### `capitalize(str: string): string`
Capitalizes the initial character of each word in a string.

### `clamp(num: number, min: number, max: number): number`
Restricts a value within a specified minimum and maximum range.

### `randomString(length?: number): string`
Generates a random alphanumeric string of custom length (default: 8).

### `deepClone<T>(obj: T): T`
Creates a deep clone copy of objects and arrays without mutating references.

### `isEmpty(val: any): boolean`
Returns `true` if the passed value is `null`, `undefined`, empty string, empty array, or empty object.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to check out the [issues page](https://github.com/zyanmd/dev-toolkit/issues) or submit a Pull Request.

---

## 👥 Authors & Contributors

* **Hanz** ([@zyanmd](https://github.com/zyanmd)) — *Lead Maintainer*
* **Muhammad Bayu Ariyadi** ([@BayuAriyadi](https://github.com/BayuAriyadi)) — *Contributor*

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
