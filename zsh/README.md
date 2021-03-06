# Zsh

    ├── .oh_my.zsh                Zsh theme and plugins
    ├── .zsh
    │   ├── aliases.zsh
    │   ├── config.zsh            Configure shell behavior
    │   ├── dircolors.256dark
    │   └── functions.zsh         Custom shell functions
    ├── .zshenv                   Routine loading all .zshenv files
    └── .zshrc                    Routine loading all .zsh files

This package [loads Oh-My-Zsh](https://github.com/Kraymer/F-dotfiles/blob/master/zsh/.oh_my.zsh) and activate powerlevel9k theme ([to install](https://github.com/bhilburn/powerlevel9k)).
It defines some [aliases](https://github.com/Kraymer/F-dotfiles/blob/master/zsh/.zsh/aliases.zsh) that adds sane options to core shell functions and GNU utilities.

![zsh prompt](https://raw.githubusercontent.com/Kraymer/bulkdata/master/F-dotfiles/zshprompt.png)

### Customization

Others packages define environment variables or functions by writing shell files into `~/.zsh`.

`~/.zsshenv` sources all **.zshenv* files present in `~/.zsh` subfolders at zsh startup, and `~/.zshrc` do the same with **.zsh* files.

### Requirements

- `oh-my-zsh` <<https://github.com/robbyrussell/oh-my-zsh>>
- `powerlevel9k` <<https://github.com/bhilburn/powerlevel9k>>
