# 🧠 ɿɘƚɘɿqɿɘƚᴎI-ʞɔ-Ꮈᴎiɒɿᙠ 🧠

---

**Table of Contents**

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Introduction

- Brainfk is a Python package that provides an interpreter for the Brainfuck programming language. It allows you to execute Brainfuck code and see the output.

## Features

- Simple and intuitive interface to run Brainfuck code.
- Supports reading Brainfuck code from a file or direct input.
- Handles the basic Brainfuck commands: `+`, `-`, `<`, `>`, `.`, `,`, `[`, `]`.
- Supports nested loops in Brainfuck code.

## Installation

You can install Brainfk using pip:

```
pip install brainfk
```

Brainfk requires Python 3.7 or higher.

## Usage

You can run the Brainfuck interpreter by executing the `brainfk` command followed by the path to a file containing Brainfuck code or by providing the code directly as input.

To execute Brainfuck code from a file:

```
brainfk path/to/brainfuck_file.bf
```

To provide Brainfuck code as input:

```
brainfk
```

The interpreter will prompt you to enter the Brainfuck code. Type or paste the code, and press Enter.

## Examples

Here are some examples to demonstrate how to use Brainfk:

1. Execute Brainfuck code from a file:

```
brainfk examples/hello_world.bf
```

2. Execute Brainfuck code by providing input:

```
brainfk
```

Enter the Brainfuck code: `,.[.,]`

Enter the input: `Hello, Brainfuck!`

## Contributing

If you would like to contribute to Brainfk, feel free to open pull requests for bug fixes, enhancements, or new features. Please ensure that your code follows the existing coding style and includes appropriate tests.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
