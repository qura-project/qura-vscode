# QuRA Language Support

Syntax highlighting for QuRA (specification 0.1.0) in Visual Studio Code, for files with the `.qura` extension.

Highlighted: keywords (`module`, `import`, `let`, `if`, ...), the prefix constructs (`not`, `lift`, `force`, `box`, `apply`), quantum primitives (`Hadamard`, `CNot`, `R(n)`, ...), booleans, naturals, the base types and `Circ`, the bang operator `!`, lambdas, operators, top-level names, module paths, `--` line comments and nested `{- -}` block comments.

## Installing

- Copy this folder to `~/.vscode/extensions/qura-language` and restart VS Code, or
- package it with `npx @vscode/vsce package` and install the `.vsix` through "Extensions: Install from VSIX...".

`examples/sample.qura` exercises every token class.
