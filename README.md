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

First, create your fuc repository like [this](https://github.com/knakayama/my-fuc), and clone your fuc repository to your machine.

Then, edit your `.zshrc` like the following:

```zsh
bindkey '^x^x' fuc-widget-execute-fuc
bindkey '^x^i' fuc-widget-put-fuc
export FUC_PATH=path/to/your-fuc
```

Finally, source your `.zshrc` and hit `^x^x` or `^x^i` in your terminal.

## License

[MIT](https://github.com/knakayama/fuc/blob/master/LICENSE)

## Author

knakayama
