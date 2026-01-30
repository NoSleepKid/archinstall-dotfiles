<!-- <div align="center"> -->
<img src="https://github.com/archlinux/archinstall/raw/master/docs/logo.png" alt="drawing" width="200"/>

<!-- </div> -->
# Arch Installer (With dotfiles)
[![Lint Python and Find Syntax Errors](https://github.com/archlinux/archinstall/actions/workflows/flake8.yaml/badge.svg)](https://github.com/archlinux/archinstall/actions/workflows/flake8.yaml)

### A fork of [archinstall](https://github.com/archlinux/archinstall) that provides options to automaticilly install dotfiles from a repository, file, or our library.

## Installing on a Live CD
### Installing is pretty straight forward.
Assuming you already have internet set up, installing Git is the first thing you need to do.

```sudo pacman -S git``` This installs Git using pacman for arch.

Then, clone the repository.

```git clone https://github.com/NoSleepKid/archinstall-dotfiles``` This uses Git to download the contents of 
