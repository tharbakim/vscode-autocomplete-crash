# VSCode Autocompete Crash Example

This repository contains a file, `test.scss` which when you try and type on line 2 of the file will crash (or run endlessly, or block or something) behind the scenes and never complete.

This is particularly problematic if you use something like [VSCodeVim](https://github.com/VSCodeVim/VimVSCodeVim), as you lose the ability to perform any input actions in the window.

To clear this issue, reload the window (Ctrl + r by default).