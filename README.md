# Prezto — Instantly Awesome Zsh


Prezto is the configuration framework for Zsh; 

You should use the main one: https://github.com/sorin-ionescu/prezto

## Installation

This is my fork with nothing interesting. 

# Installation

Clone it

```console
git clone --recursive git@github.com/tedroden/prezto.git "${ZDOTDIR:-$HOME}/.zprezto"
```

And link the files

```console
setopt EXTENDED_GLOB
for rcfile in "${ZDOTDIR:-$HOME}"/.zprezto/runcoms/^README.md(.N); do
  ln -s "$rcfile" "${ZDOTDIR:-$HOME}/.${rcfile:t}"
done
```

