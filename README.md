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

First, put your fuc files in fuc directory with markdown format like the following:

<pre>
```bash
$ test
```
</pre>

**Note:** Currently search fuc files path is [hard coded](https://github.com/knakayama/fuc/blob/master/fuc-functions/sources/fuc-source-fuc). So, you must put your fuc files in `~/.antigen/repos/https-COLON--SLASH--SLASH-github.com-SLASH-knakayama-SLASH-fuc.git/fuc/*`.
Any idea to fix this silly remitation. I'm not zsh master ;)

Next, edit your `.zshrc` like the following:

```zsh
bindkey '^x^x' fuc-widget-fuc
```

Finally, source your `.zshrc` and hit `^x^x` in your terminal.

## License

MIT

## Author

knakayama
