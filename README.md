# aws-vault zsh completion

[aws-vault](https://github.com/99designs/aws-vault) command's completion for zsh

![demo](https://user-images.githubusercontent.com/6639060/160246467-dba96515-a531-43e2-a68b-1878e8b0fe6d.gif)

## How to set up

1. Put `_aws-vault` in your completion's folder ( `/path/to/completion/` ).
1. Enable completions in `~/.zshrc`.
```shell:~/.zshrc
fpath=(/path/to/completion $fpath)
autoload -Uz compinit
compinit
```
