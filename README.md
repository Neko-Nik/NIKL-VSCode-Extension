# NIKL Language Support

Official Visual Studio Code extension for the **Nik Language (NIKL)**, a modern programming language designed for simplicity and efficiency.

> 🚧 **Warning:** NIKL is in a pre-alpha phase. Expect rapid changes and breaking updates.

---

## ✨ Features

* Syntax highlighting for `.nk` files
* Clear support for:
    * Keywords
    * Constants (`True`, `False`, `None`)
    * Built-in functions (`print`, `input`, `len`)
    * Single-line comments (`//`)
    * Numbers (integer and float)
    * Strings (single and double-quoted)
    * Operators (arithmetic, logical, comparison)
    * Function names and variable recognition

---

## 🧠 Syntax Highlighting Support

### 🔑 Control & Declaration Keywords

| Category          | Keywords                                                                                              |
| ----------------- | ----------------------------------------------------------------------------------------------------- |
| Control Flow      | `if`, `elif`, `else`, `while`, `for`, `loop`, `break`, `continue`, `return`                           |
| Function & Import | `fn`, `import`, `as`, `del`                                                                           |
| Declarations      | `let`, `const`                                                                                        |
| Membership Check  | `in`                                                                                                  |

---

### 📌 Constants

| Type      | Values          |
| --------- | --------------- |
| Boolean   | `True`, `False` |
| Null-like | `None`          |

---

### 🧰 Built-in Functions

| Built-in Functions |
| ------------------ |
| `print`            |
| `input`            |
| `len`              |

---

### 🧱 Built-in Types

| Types     |
| --------- |
| `Int`     |
| `Float`   |
| `Bool`    |
| `String`  |
| `Array`   |
| `HashMap` |
| `Tuple`   |

---

### ➕ Operators

#### Assignment & Arithmetic

| Type       | Operators          |
| ---------- | ------------------ |
| Assignment | `=`                |
| Arithmetic | `+`, `-`, `*`, `/` |

#### Logical

| Type    | Operators          |
| ------- | ------------------ |
| Logical | `and`, `or`, `not` |

#### Comparison

| Type       | Operators            |
| ---------- | -------------------- |
| Equality   | `==`, `!=`           |
| Comparison | `<`, `>`, `<=`, `>=` |

---

### 🔢 Numbers

| Type    | Example         |
| ------- | --------------- |
| Integer | `42`            |
| Float   | `3.14`, `0.001` |

---

### 🔤 Strings

| Type             | Example           |
| ---------------- | ----------------- |
| Double-quoted    | `"Hello, World!"` |
| Escape Sequences | `\n`, `\t`, `\\`  |

---

### 💬 Comments

| Type        | Syntax Example         |
| ----------- | ---------------------- |
| Single-line | `// This is a comment` |

---

## 🚀 Getting Started

1. **Install the Extension** via the VS Code Marketplace.
2. **Create a `.nk` file** and begin writing NIKL code.

```nk
fn greet(name) {
    print("Hello, " + name)
}

greet("World")
```

Syntax highlighting will be applied automatically.

---

## 📦 Resources

* 🔽 [Download NIKL Interpreter](https://github.com/Neko-Nik/NIKL-Core/releases)
* 📚 [NIKL Language Documentation](https://nikl.nekonik.com)
* 💬 [Join the Discord Community](https://discord.gg/PYqHVUGdwv)
* ⭐ [Star the GitHub Repository](https://github.com/Neko-Nik/NIKL-Core)

---

## 🛠️ Contributing

We welcome contributions! You can help by:

* Submitting bug reports and suggestions
* Opening pull requests
* Improving documentation or language definitions

> Note: Since the language is evolving, expect frequent changes.

---

## 💬 Feedback & Support

For help or to join the conversation, visit our [Discord](https://discord.gg/PYqHVUGdwv) or open an issue on [GitHub](https://github.com/users/Neko-Nik/projects/3).

---

Thanks for using **NIKL** 💜
