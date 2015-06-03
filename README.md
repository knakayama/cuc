cuc
===

Commonly Used Commands

## Description

**Note:** This code is heavily inspired by [anyframe](https://github.com/mollifier/anyframe).

This zsh plugin shows your commonly used commands (cuc) with [peco style](https://github.com/peco/peco). You can quickly search and execute cuc.

## Install

### antigen

```bash
antigen bundle knakayama/cuc
```

## Usage

First, put your cuc files in cuc directory with markdown format like the following:

````markdown
```bash
$ test
```
````

**Note:** Currently search cuc files path is [hard coded](https://github.com/knakayama/cuc/blob/master/cuc-functions/sources/cuc-source-cuc). So, you must put your cuc files in `~/.antigen/repos/https-COLON--SLASH--SLASH-github.com-SLASH-knakayama-SLASH-cuc.git/cuc/*`.
Any idea to fix this silly remitation. I'm not zsh master ;)

Next, edit your `.zshrc` like the following:

```zsh
bindkey '^x^x' cuc-widget-cuc
```

Finally, source your `.zshrc` and hit `^x^x` in your terminal.

## License

MIT

## Author

knakayama
