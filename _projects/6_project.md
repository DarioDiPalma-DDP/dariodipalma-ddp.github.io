---
layout: page
title: Swift Interpreter in Go
description: A Go-based interpreter for the Swift programming language, developed as part of a Master's thesis project.
img: assets/img/Swift_Interpreter_Pipeline.png
importance: 5
category: work
---

## Project Overview

This project presents a Go-based interpreter for the Swift programming language, developed as part of a Master's thesis. The interpreter is designed to parse and execute Swift code, providing insights into language interpretation and compiler construction.

## Features

- **Swift Language Parsing**: Implements a parser capable of understanding Swift syntax and semantics.
- **Code Execution**: Executes Swift code by interpreting the parsed abstract syntax tree (AST).
- **Educational Resource**: Serves as a learning tool for those interested in language interpreters and the Swift language.

## Usage

To explore and utilize the Swift interpreter:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/DarioDiPalma-DDP/Swift-Interpreter-in-GO.git
   ```
2. **Set Up the Environment**:
   Ensure Go 1.16 or later is installed. Navigate to the project directory and build the interpreter:
   ```bash
   cd Swift-Interpreter-in-GO
   go build -o swift_interpreter main.go
   ```
3. **Run the Interpreter**:
   Execute the built interpreter:
   ```bash
   ./swift_interpreter
   ```
   You can then input Swift code to be interpreted.

## Dependencies

- **Go**: Version 1.16 or later

## Links

- [GitHub Repository](https://github.com/DarioDiPalma-DDP/Swift-Interpreter-in-GO)

For detailed information and updates, please refer to the [GitHub repository](https://github.com/DarioDiPalma-DDP/Swift-Interpreter-in-GO).
