# NIKL Language Support for VS Code

This is a **very early-stage** Visual Studio Code extension providing syntax highlighting for the **NIKL** programming language.

> ⚠️ **Note:** NIKL is currently in its infancy and not yet even at alpha stage. Expect many changes, incomplete features, and potential instability in the language and tooling.

---

## Features

- Syntax highlighting for `.nk` files
- Basic support for:
  - Keywords (`if`, `fn`, `return`, etc.)
  - Constants (`True`, `False`)
  - Built-in functions (`print`, `input`, `len`)
  - Comments (single-line with `//`)
  - Numbers, strings, operators, and punctuation
  - Function names and variables

---

## Installation

Currently, the extension is **not published** on the VS Code Marketplace.

To use it locally:

1. Clone this repository:
    ```bash
    git clone https://github.com/Neko-Nik/NIKL-VSCode-Extension.git
    cd NIKL-VSCode-Extension
    ```
2. Open this folder in VS Code.
3. Press `F5` to launch a new Extension Development Host window with the extension loaded.
4. Open or create `.nk` files to see syntax highlighting.

---

## Usage

Create `.nk` files containing NIKL code. Here’s a tiny example:

```nikl
let x = 7
print(x * 12 + 2)
// Output: 86 
````

---

## Contributing

This project is in very early development. Contributions are welcome but expect ongoing refactors and breaking changes.

Feel free to open issues or pull requests for bug fixes, suggestions, or improvements.
