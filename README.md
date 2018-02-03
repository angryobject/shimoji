# ShImoji

> Put some emoji in your prompt

A simple scripts to randomly choose a emoji from a unicode range or from a list (or both) to use in your prompt. Works with zsh. May or may not work with bash or other shells. Inpired by this [tweet](https://twitter.com/ftrain/status/360833985187807233).

![Demo](https://raw.githubusercontent.com/angryobject/shimoji/master/demo.gif)

## Install

```bash
npm i -g shimoji
```

## Usage

In your `.zshrc`:

```bash
PROMPT='$(/usr/local/share/zsh/site-functions/shimoji)  → '
```