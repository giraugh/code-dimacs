# 🎛 DIMACS Language Support for VS Code

[![VSCode Marketplace version](https://img.shields.io/visual-studio-marketplace/v/giraugh.code-dimacs)](https://marketplace.visualstudio.com/items?itemName=giraugh.code-dimacs)
[![VSCode Marketplace version](https://img.shields.io/visual-studio-marketplace/d/giraugh.code-dimacs)](https://marketplace.visualstudio.com/items?itemName=giraugh.code-dimacs)

[DIMACS CNF](https://jix.github.io/varisat/manual/0.2.0/formats/dimacs.html) is a standard format for representing boolean formulas in conjunctive normal form.

This extension provides syntax highlighting for `.cnf` files using the DIMACS CNF format.

![DIMACS syntax highlighting in VS Code](./images/example.png)

## Contributing

The files that are used to define the language are below:

- `syntaxes/dimacs.tmLanguage.json` - the Text mate grammar file that is used for tokenization.
- `language-configuration.json` - the language configuration, defining the tokens that are used for comments and brackets.

To test, press `F5` when editing the extension with VS Code to open a new window with the extension loaded.
