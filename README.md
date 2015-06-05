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

First, create your fuc repository like [this](https://github.com/knakayama/my-fuc) and, use `git subtree` to manage your fuc in your repository like the following commands:

```bash
$ cd ~/.antigen/repos/https-COLON--SLASH--SLASH-github.com-SLASH-knakayama-SLASH-fuc.git
$ git remote add my-fuc-remote git@github.com:<your name>/<your fuc repository>.git
$ git fetch my-fuc-remote
$ git branch my-fuc-branch my-fuc-remote/master
$ git subtree add --prefix=fuc my-fuc-remote master
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
