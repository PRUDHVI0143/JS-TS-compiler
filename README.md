# JS-TS Compiler

> A lightweight compiler built in **JavaScript** and **TypeScript** that demonstrates the fundamental stages of compiler design, from lexical analysis to code generation. This project serves as both an educational resource for learning compiler internals and a foundation for building language processing tools.

---

## 📖 Summary

**JS-TS Compiler** is a compiler implementation designed to showcase how modern programming languages are processed internally. It converts source code into executable output through multiple compilation stages, including tokenization, parsing, Abstract Syntax Tree (AST) generation, semantic analysis, and code generation.

The project emphasizes clean architecture, modular design, and readability, making it suitable for students, developers, and anyone interested in compiler construction. Whether you're learning how compilers work or experimenting with language features, this project provides a practical implementation of core compiler concepts.

---

## ✨ Features

* 🔤 Lexical Analysis (Lexer)
* 🌳 Abstract Syntax Tree (AST) Generation
* 📑 Syntax Parsing
* ✅ Semantic Analysis
* ⚡ JavaScript & TypeScript Support
* 🛠️ Error Detection and Reporting
* 📦 Modular Compiler Architecture
* 🚀 Command-Line Interface (CLI)
* 📚 Educational and Beginner Friendly
* 🔄 Extensible Design for Future Enhancements

---

## 🏗️ Compiler Workflow

```
Source Code
     │
     ▼
 Lexer (Tokenizer)
     │
     ▼
 Parser
     │
     ▼
 Abstract Syntax Tree (AST)
     │
     ▼
 Semantic Analysis
     │
     ▼
 Code Generation
     │
     ▼
 Output JavaScript
```

---

## 📂 Project Structure

```
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

## 🚀 Getting Started

### Prerequisites

* Node.js (v16 or later)
* npm

---

## 📥 Installation

Clone the repository:

```bash
git clone https://github.com/PRUDHVI0143/JS-TS-compiler.git
```

Navigate into the project:

```bash
cd JS-TS-compiler
```

Install dependencies:

```bash
npm install
```

---

## ▶️ Running the Project

Development mode:

```bash
npm run dev
```

Build the project:

```bash
npm run build
```

Run the compiled output:

```bash
npm start
```

---

## 💻 Example

### Input (TypeScript)

```ts
function greet(name: string): string {
    return `Hello ${name}`;
}

console.log(greet("Compiler"));
```

### Output (JavaScript)

```js
function greet(name) {
    return `Hello ${name}`;
}

console.log(greet("Compiler"));
```

---

## ⚙️ Compilation Stages

### 1. Lexical Analysis

The lexer scans source code character by character and converts it into meaningful tokens such as:

* Keywords
* Identifiers
* Operators
* Literals
* Symbols

Example:

```
let x = 10;
```

becomes

```
LET
IDENTIFIER(x)
ASSIGN
NUMBER(10)
SEMICOLON
```

---

### 2. Parsing

The parser validates the token stream against the language grammar and builds an Abstract Syntax Tree (AST).

---

### 3. AST Generation

The AST provides a structured representation of the source program.

Example:

```
BinaryExpression
├── Identifier(x)
└── NumberLiteral(10)
```

---

### 4. Semantic Analysis

This stage verifies:

* Variable declarations
* Type compatibility
* Scope resolution
* Invalid identifiers
* Semantic correctness

---

### 5. Code Generation

The final stage traverses the AST and generates executable JavaScript output.

---

## 📦 Available Scripts

| Command         | Description             |
| --------------- | ----------------------- |
| `npm install`   | Install dependencies    |
| `npm run dev`   | Start development mode  |
| `npm run build` | Build the compiler      |
| `npm start`     | Execute compiled output |
| `npm run test`  | Run tests               |
| `npm run lint`  | Lint project files      |

---

## 🛠️ Technologies Used

* TypeScript
* JavaScript
* Node.js
* npm
* ESLint
* Prettier
* ts-node

---

## 🎯 Learning Objectives

This project demonstrates:

* Compiler Design
* Parsing Techniques
* AST Construction
* Tree Traversal
* Semantic Analysis
* Code Generation
* Language Processing
* TypeScript Internals

---

## 🚧 Future Improvements

* Support Classes
* Interfaces
* Enums
* Generics
* Type Inference
* Source Maps
* Optimizer
* Constant Folding
* Dead Code Elimination
* Better Error Recovery
* Plugin System
* Incremental Compilation

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Push to your branch.
5. Open a Pull Request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Prudhvi**

GitHub: https://github.com/PRUDHVI0143

---

## ⭐ Support

If you found this project useful:

* ⭐ Star the repository
* 🍴 Fork it
* 🐞 Report issues
* 💡 Suggest improvements
* 🤝 Contribute to development

Every contribution helps improve the project and makes it more useful for the developer community.
