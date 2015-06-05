fuc
===

Frequently Used Commands

## Description

**Note:** This code is heavily inspired by [anyframe](https://github.com/mollifier/anyframe).

This zsh plugin shows your frequently used commands (fuc) with [peco style](https://github.com/peco/peco). You can quickly search and execute fuc.

## Install

### antigen

```bash
antigen bundle knakayama/fuc
```

## Usage

First, create your fuc repository like [this](https://github.com/knakayama/my-fuc).

And, clone your fuc repository to fuc directory like the following:

```bash
$ cd ~/.antigen/repos/https-COLON--SLASH--SLASH-github.com-SLASH-knakayama-SLASH-fuc.git
$ git clone git@github.com:<your name>/<your fuc repository>.git fuc
```

Next, edit your `.zshrc` like the following:

```zsh
bindkey '^x^x' fuc-widget-fuc
```

Finally, source your `.zshrc` and hit `^x^x` in your terminal.

## License

MIT

## Author

knakayama
