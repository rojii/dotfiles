:house_with_garden: dotfiles
========

#deploy
```
git clone git@github.com:rojii/dotfiles.git ~/dotfiles
git clone git://git.suckless.org/st
cd st
patch -p1 < ~/dotfiles/st/st_colors.patch
sudo make clean install
cd ~
rm -rf st
```

#desktop OSs
- OpenBSD
- Void Linux
- Arch Linux

#general
- st
- tmux
- fish - modern shell
- firefox
- chrome
- ranger - text based file manager
- slock - simple X display locker
- clipit - clipboard manager and synchronize PRIMARY, CLIPBOARD and cut buffer selections
- dmenu
- weechat - irc client
- nitrogen
- mutt - email reader
- keepassx2
- [fzf](https://github.com/junegunn/fzf) -  A command-line fuzzy finder
- [clf](https://github.com/ncrocfer/clf) - command line fu in CLI, 'cause i have bad memory
- feh - setting bg, also nice image viewer
- scrot
- udiskie - device automounting
- [nethogs](http://nethogs.sourceforge.net/) - net top tool that groups bandwidth by process
- [infinality](https://wiki.archlinux.org/index.php/Infinality) - improves freetype2 font rendering
- the silver searcher
- [mosh](https://mosh.mit.edu/) - mobile shell
- glances - system monitoring tool
- htop
- [ngrep](https://twitter.com/b0rk/status/759758932181147648) - grep your network
- [mtr](http://www.bitwizard.nl/mtr/) - combination of ping and traceroute
- tinc - simple p2p vpn
- wireshark - network protocol analyzer
- mitmproxy - interactive, SSL-capable man-in-the-middle proxy for HTTP with a console interface.
- [flux](https://justgetflux.com/) - makes the color of your computer's display adapt to the time of day


#firefox addons
- https everywhere
- noscript
- searchonymous
- self-destructing cookies
- ublock origin

#chrome extensions
- ublock - block ads
- one tab - reduce tab clutter
- https everywhere - automatically use HTTPS security on many sites
- lazarus - autosaves everything you type so you can easily recover from form-killing
- the great suspender - autosuspend tabs after t seconds
- trezor - trezor plugin

#coding
- emacs/[emacs-lunfardo](https://github.com/unbalancedparentheses/lunfardo)
- neovim/[vim-lunfardo](https://github.com/unbalancedparentheses/vim-lunfardo)
- [tig](http://jonas.nitro.dk/tig/) - ncurses-based text-mode interface for git
- [hub](https://github.com/github/hub) - fast github command line client
- [mc](https://github.com/minio/mc) - client for uploading, retrieving and managing data in Amazon S3
- [stalk](https://github.com/unbalancedparentheses/stalk) - watches a directory and runs a command every time a file inside the directory changes
- [icdiff](http://www.jefftk.com/icdiff) - shows the differences between similar files without getting in the way
- [ctags](http://ctags.sourceforge.net/) - generates an index file of names found in source and header files of various programming languages
- [gnu global](https://www.gnu.org/software/global/) - tagging system
- [pfff](https://github.com/facebook/pfff)- tools for code analysis, visualizations, or style-preserving source transformation
- cloc
- sloccount

##go
- [gox](https://github.com/mitchellh/gox) - Go cross compile tool
- [gvm](https://github.com/moovweb/gvm) - Go version manager

##clojure
- [boot](http://boot-clj.com/) - automating Clojure projects without setting your hair on fire

##nodejs
- [nodejs](https://github.com/nodejs/node)  
- [npm](https://github.com/npm/npm) - package manager
