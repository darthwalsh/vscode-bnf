
# vscode-bnf for YAML's BNF flavor
[![Version](https://vsmarketplacebadge.apphb.com/version/darthwalsh.vscode-bnf.svg)](https://marketplace.visualstudio.com/items?itemName=darthwalsh.vscode-bnf)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/darthwalsh.vscode-bnf.svg)](https://marketplace.visualstudio.com/items?itemName=darthwalsh.vscode-bnf)

This extension adds BNF syntax highlighting to Visual Studio Code.

Files with the extension `.bnf` will automatically be highlighting.

Some differences with standard BNF grammar:

- `/* C-style comments */`
- Unquoted unicode escape sequences like `#xFEFF`
- Production names can have a parenthesized context like `s-indent(<n)`
- Add operators `⇒` and `×`

![Syntax Highlighting](screenshot.png)
