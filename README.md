# Voidrice

aj10k's fork of [Luke Smith](http://lukesmith.xyz)'s [dotfiles](https://github.com/lukesmithxyz/voidrice).

These are the dotfiles deployed by my fork of [LARBS](https://github.com/aj10k/LARBS)

- My scripts are in `~/.local/bin/lpp`
	- br: Brightness Redshift
	- qmd: Quick Music Downloader
	- qpm: Quick Password Manager (also bookmarks)
	- rsserr: rss link fetcher
- Settings for:
	- vim/nvim (text editor)
	- zsh (shell)
	- lf (file manager)
	- mpd/ncmpcpp (music)
	- sxiv (image/gif viewer)
	- mpv (video player)
	- other stuff like xdg default programs, inputrc and more, etc.
- I try to minimize what's directly in `~` so:
	- All configs that can be in `~/.config/` are.
	- Some environmental variables have been set in `~/.zprofile` to move configs into `~/.config/`
- Bookmarks in text files used by various scripts (like `~/.local/bin/shortcuts`)
	- File bookmarks in `~/.config/shell/bm-files`
	- Directory bookmarks in `~/.config/shell/bm-dirs`

## Usage

These dotfiles are intended to go with numerous suckless programs I use:

- [dwm](https://github.com/aj10k/dwm) (window manager)
- [dwmblocks](https://github.com/aj10k/dwmblocks) (statusbar)
- [st](https://github.com/aj10k/st) (terminal emulator)

## Install these dotfiles and all dependencies

Use [LARBS](https://github.com/aj10k/LARBS) to autoinstall everything

or clone the repo files directly to your home directory and install the
[dependencies](https://github.com/LukeSmithxyz/LARBS/blob/master/static/progs.csv).

## Default Desktop Artwork

Thomas Thiemeyer's *The Road to Samarkand* ([fb](https://www.facebook.com/t.thiemeyer/), [insta](https://www.instagram.com/tthiemeyer/), [shop](https://www.redbubble.com/de/people/TThiemeyer/shop))
