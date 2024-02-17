# PseudoCode Syntax Highlighter

## Overview

This is a syntax highlighter for PseudoCode, inspired by popular programming languages such as C, C++, Java, Python, JavaScript, TypeScript, Kotlin, Swift, Go, Ruby, Rust, and Bash. It is designed to provide a visually appealing representation of PseudoCode in various code editors that support TextMate language grammars.

## Installation

To use this syntax highlighter, follow these steps:

1. Download the `tmlanguage.json` and `configuration.json` files.
2. Install a code editor that supports TextMate language grammars, such as Visual Studio Code.
3. Copy the contents of `tmlanguage.json` into a new language configuration file in your editor.
4. Copy the contents of `configuration.json` into the editor's configuration settings.

## Features

### Syntax Highlighting

- Supports highlighting for comments, keywords, strings, numbers, booleans, variables, and storage modifiers.
- Recognizes common programming constructs such as loops, conditionals, functions, classes, interfaces, and structs.

### Comment Styles

- Single-line comments: `// comment`
- Block comments: `/* block comment */`

### Brackets and Auto-Closing Pairs

- Recognizes various brackets and auto-closes them during typing.
  - `{}`, `[]`, `()`, `do` ... `end`

### Surrounding Pairs

- Allows surrounding selections with appropriate pairs.

### Word Pattern

- Defines a word pattern to match variable and function names.

### Indentation Rules

- Specifies rules for increasing and decreasing indentation based on language constructs.

## Usage Example

```pseudo
missNum(arr, n):
    found = FALSE
    for i in 0..<n:
        for j in 0..<arr.len:
            if i == arr[j]:
                found = TRUE
                break
        
        if NOT found:
            return i
```

## Contributions

Feel free to contribute by reporting issues or submitting pull requests to improve the syntax highlighter.

## License

This PseudoCode Syntax Highlighter is licensed under the [MIT License](LICENSE).
