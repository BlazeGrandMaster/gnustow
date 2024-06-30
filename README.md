# My dotfiles

This directory contains the dotfiles for my system

## Requirements

### Git

```
pacman -S git
```

### Stow

```
pacman -S stow
```

## Installation

First, check out the dotfiles repo in your home directory using git

```
$ git clone git@github.com/BlazeGrandMaster/gnustow.git
$ cd dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```

#### Reference
[Stow youtube video](https://www.youtube.com/watch?v=y6XCebnB9gs)
