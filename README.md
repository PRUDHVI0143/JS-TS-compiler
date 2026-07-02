# 🚀 JS-TS Compiler

> A lightweight compiler built with **JavaScript** and **TypeScript** that demonstrates the complete compiler pipeline—from lexical analysis to JavaScript code generation. Designed for learning compiler internals, experimenting with language design, and building language-processing tools.

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-5.x-blue?logo=typescript" />
  <img src="https://img.shields.io/badge/Node.js-16+-green?logo=node.js" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
  <img src="https://img.shields.io/badge/Status-Active-success" />
</p>

---

## 🌐 Live Demo

Explore the compiler in your browser:

👉 **https://codesketchbook.vercel.app/**

---

## 📖 Overview

**JS-TS Compiler** is an educational compiler implementation that demonstrates how modern programming languages are processed internally.

It transforms source code into executable JavaScript through a series of well-defined compilation stages:

* 🔤 Lexical Analysis (Tokenization)
* 🌳 Parsing
* 📑 Abstract Syntax Tree (AST) Construction
* ✅ Semantic Analysis
* ⚡ JavaScript Code Generation

The project focuses on **clean architecture**, **modular design**, and **readable implementation**, making it an excellent learning resource for students, developers, and anyone interested in compiler construction.

---

# ✨ Features

* 🔤 Lexical Analysis (Lexer)
* 🌳 AST Generation
* 📑 Recursive Descent Parser
* ✅ Semantic Analysis
* ⚡ JavaScript & TypeScript Support
* 🛠️ Detailed Error Detection & Reporting
* 📦 Modular Architecture
* 🚀 Command-Line Interface (CLI)
* 📚 Beginner Friendly
* 🔄 Easily Extensible Design

---

# 🏗️ Compiler Pipeline

```text
           Source Code
                │
                ▼
      Lexical Analysis (Lexer)
                │
                ▼
             Token Stream
                │
                ▼
               Parser
                │
                ▼
      Abstract Syntax Tree
                │
                ▼
       Semantic Analysis
                │
                ▼
        Code Generation
                │
                ▼
        JavaScript Output
```

---

# 📂 Project Structure

```text
JS-TS-compiler/
│
├── src/
│   ├── lexer/
│   ├── parser/
│   ├── analyzer/
│   ├── generator/
│   ├── utils/
│   └── index.ts
│
├── examples/
├── tests/
├── dist/
├── package.json
├── tsconfig.json
└── README.md
```

---

# 🚀 Getting Started

## Prerequisites

* Node.js **v16+**
* npm

---

## 📥 Installation

Clone the repository

```bash
git clone https://github.com/PRUDHVI0143/JS-TS-compiler.git
```

Navigate into the project

```bash
cd JS-TS-compiler
```

Install dependencies

```bash
npm install
```

---

# ▶️ Usage

### Development

```bash
npm run dev
```

### Build

```bash
npm run build
```

### Run

```bash
npm start
```

---

# 💻 Example

## Input (TypeScript)

```ts
function greet(name: string): string {
    return `Hello ${name}`;
}

console.log(greet("Compiler"));
```

## Output (JavaScript)

```js
function greet(name) {
    return `Hello ${name}`;
}

console.log(greet("Compiler"));
```

---

# ⚙️ Compilation Stages

## 1️⃣ Lexical Analysis

The lexer scans source code character by character and converts it into a stream of meaningful tokens.

Supported token types include:

* Keywords
* Identifiers
* Numbers
* Strings
* Operators
* Symbols
* Punctuation

Example

```ts
let x = 10;
```

becomes

```text
LET
IDENTIFIER(x)
ASSIGN
NUMBER(10)
SEMICOLON
```

---

## 2️⃣ Parsing

The parser validates the token stream according to the language grammar and constructs an Abstract Syntax Tree (AST).

---

## 3️⃣ AST Generation

The AST is a structured representation of the source program.

Example

```text
BinaryExpression
├── Identifier(x)
└── NumberLiteral(10)
```

---

## 4️⃣ Semantic Analysis

The semantic analyzer performs:

* Variable declaration validation
* Type checking
* Scope resolution
* Undefined identifier detection
* Semantic correctness checks

---

## 5️⃣ Code Generation

The final stage traverses the AST and emits executable JavaScript code.

---

# 📦 Available Scripts

| Command         | Description                  |
| --------------- | ---------------------------- |
| `npm install`   | Install project dependencies |
| `npm run dev`   | Start development mode       |
| `npm run build` | Compile the project          |
| `npm start`     | Execute compiled output      |
| `npm run test`  | Run test suite               |
| `npm run lint`  | Lint the source code         |

---

# 🛠️ Tech Stack

* TypeScript
* JavaScript
* Node.js
* npm
* ESLint
* Prettier
* ts-node

---

# 🎯 Learning Objectives

This project demonstrates practical implementations of:

* Compiler Design
* Lexical Analysis
* Recursive Descent Parsing
* Abstract Syntax Trees (AST)
* Semantic Analysis
* Tree Traversal
* Code Generation
* Language Processing
* TypeScript Internals

---

# 🚧 Roadmap

Future enhancements include:

* Classes
* Interfaces
* Enums
* Generics
* Type Inference
* Optimizer
* Constant Folding
* Dead Code Elimination
* Source Maps
* Incremental Compilation
* Plugin System
* Better Error Recovery

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/my-feature
```

3. Commit your changes

```bash
git commit -m "Add amazing feature"
```

4. Push your branch

```bash
git push origin feature/my-feature
```

5. Open a Pull Request

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

**Prudhvi**

GitHub: https://github.com/PRUDHVI0143

Portfolio / Live Demo:

**https://codesketchbook.vercel.app/**

---

# ⭐ Show Your Support

If you found this project useful, consider:

* ⭐ Starring the repository
* 🍴 Forking the project
* 🐞 Reporting issues
* 💡 Suggesting new features
* 🤝 Contributing to development

Every contribution helps make this project better for the developer community.
