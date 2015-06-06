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

Next, create your fuc path file to `${HOME}/.fuc` like the following:

```text
/home/your-name/path/to/fuc/dir
```

Then, edit your `.zshrc` like the following:

```zsh
bindkey '^x^x' fuc-widget-fuc
```

Finally, source your `.zshrc` and hit `^x^x` in your terminal.

## License

[MIT](https://github.com/knakayama/fuc/blob/master/LICENSE)

## Author

knakayama
