# Syntax highlighting for Collagraph single file components

A VSCode extension that adds syntax highlighting for Collagraph single file components (.cgx files). CGX files are basically standard Vue files, but with Python instead of JavaScript. Hence, this extension is a simple conversion from [vue.tmLanguage](https://github.com/vuejs/vue-syntax-highlight/blob/master/vue.tmLanguage) modified to state `source.python` instead of `source.js`.


## Features

<p align="center">
  <img width="685px" src="https://raw.githubusercontent.com/fork-tongue/cgx-syntax-highlight-vscode/main/samples/screenshot.png">
</p>


## Known Issues

Collagraph is currently under heavy development, and as of yet does not support all syntax features from Vue (yet).


## Release Notes

### 0.0.1

Initial release with basic syntax highlighting
