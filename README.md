# vim-hue
vim-hue is colorful Vim config for all your SRE/DevOps needs. 

It features "vim-hue" dark Vim colorscheme and complete Vim configuration. Ideal for anyone using Vim and any of the following on daily basis:

* Shell (Bash)
* Golang
* Python
* Terraform
* Ansible
* Docker (Dockerfile)
* Kubernetes (templates)
* et cetera ...

*Please note:* vim-hue will only work on Linux and MacOS. I strongly suggest using "dark mode" or using a dark colorscheme on your terminal of choice. Only Vim >= 8 version is supported.

![vim-hue running on MacOS (iTerm2)](https://foolcontrol.org/wp-content/uploads/2019/02/vim-hue-screenshot-macos.png)

### Sounds good, how do I get vim-hue?

#### Get vim-hue source code:

`git clone https://github.com/AdnanHodzic/vim-hue.git`

#### Install requirements

##### Requirements installation for Debian/Ubuntu and their derivatives

All requirements can be installed by running:

`sudo apt install vim python3 python3-pip python3-distutils python3-click -y`

That's it, you're ready to [run vim-hue installer](https://github.com/AdnanHodzic/vim-hue#vim-hue---installer)!

##### Requirements installation for MacOS

1: You need to have [Brew](https://brew.sh/), if not Brew can be installed by running:

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

2: Install Python3 if missing and update Vim to >= 8.1

```
brew install python3 vim
```

*Please note:* if running `vim --version` doesn't return >= 8, you may need to restart terminal for Vim symlink to be updated.

3: Use `pip3` to install [Click](https://github.com/pallets/click) python package which is used as CLI for vim-hue installer.

```
pip3 install click
```

Now you're ready to [run vim-hue installer](https://github.com/AdnanHodzic/vim-hue#vim-hue---installer)!

### vim-hue - installer

vim-hue can be installed by simply running the installer and following on screen instructions, i.e:

```
python3 vim-hue.py
```

### Technical rationale

Goal of `vim-hue` is to being "vanilla" Vim as much as possible, yet to include all necessary functionality. As such it consits of:
* [vimrc](https://github.com/AdnanHodzic/vim-hue/blob/master/vimrc) Vim configuration with each setting in use.
* [vim-hue.py](https://github.com/AdnanHodzic/vim-hue/blob/master/vim-hue.py) Python3 installer
* Dark ["vim-hue" color scheme](https://github.com/AdnanHodzic/vim-hue/blob/master/colors/hue.vim)
* [pathogen](https://github.com/AdnanHodzic/vim-hue/blob/master/pathogen.vim) for easy of plugin and runtime installation. 
* [golang](https://github.com/AdnanHodzic/vim-hue/tree/master/bundle/vim-go) plugin.
* [terraform](https://github.com/AdnanHodzic/vim-hue/tree/master/bundle/vim-terraform) plugin.
* [git-branch-info](https://github.com/AdnanHodzic/vim-hue/blob/master/plugin/git-branch-info.vim) plugin.


### Discussion

* [vim-hue: colorful Vim config for all your SRE/DevOps needs](https://foolcontrol.org/?p=3051)
