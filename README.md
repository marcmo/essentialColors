# essentialColors

some vim color schemes

* aldmeris
* blackboard
* BusyBee
* camo
* delek-local
* dracula
* eclipse-like
* freya
* greens
* molokai
* solarized
* wombat
* smyck

## WOMBAT

This is a mirror of http://www.vim.org/scripts/script.php?script_id=1778

Dark gray background with easy-on-the-eyes font colors. It shares some similarities with the Desert color scheme.

A few screens at: http://dengmao.wordpress.com/2007/01/22/vim-color-scheme-wombat/

## Dracula Theme

![Dracula](https://cloud.githubusercontent.com/assets/398893/3528156/4d3d53a8-078c-11e4-8518-820d61886e7a.gif)

## aldmeris

Aldmeris is a vim colorscheme based on oblivion for gedit.

Features:

* tango colors palette
* support 256 colors for terminal emulators
* option to use terminal base colors in the colorscheme: by setting term colors
with a tango palette, the result is very close to the gui version
* support terminal transparency
* tpope's fugitive integration: well recognizable colors for the output of
:Gstatus, and for git objects.

### Installation

If you wish to use a transparent terminal, you can put this option in your
vimrc:

    let g:aldmeris_transparent = 1

### Screenshots

Ruby example on a terminal:

![Ruby in terminal](https://github.com/veloce/vim-aldmeris/raw/master/
screenshots/aldmeris-small.png "Ruby in terminal")

Fugitive commit example:

![Fugitive commit](https://github.com/veloce/vim-aldmeris/raw/master/
screenshots/aldmeris-gstatus.png "Fugitive commit")

## Molokai

Molokai is a Vim port of the monokai theme for TextMate originally created by Wimer Hazenberg.

By default, it has a dark gray background based on the version created by Hamish Stuart Macpherson for the E editor.

![Gray Background](http://www.winterdom.com/weblog/content/binary/WindowsLiveWriter/MolokaiforVim_8602/molokai_normal_small_3.png)

![Molokai Original](http://www.winterdom.com/weblog/content/binary/WindowsLiveWriter/MolokaiforVim_8602/molokai_original_small_3.png)

256-Color terminals are also supported, though there are some differences with the Gui version. Only the dark gray background style is supported on terminal vim at this time.

### Installation

If you prefer the scheme to match the original monokai background color, put this in your .vimrc file: 
```
let g:molokai_original = 1
```

There is also an alternative scheme under development for color terminals which attempts to bring the 256 color version as close as possible to the the default (dark) GUI version. To access, add this to your .vimrc:
```
let g:rehash256 = 1
```

## Smyck Color Scheme

This is a color scheme suitable for Terminal.app, iTerm2, Vim, gVim,
MacVim, Textmate and Sublime Text 2.

The colors are carefully chosen and the contrasts are tuned so that it
should not hurt the eyes even after a whole day of working.

### Screenshots

![Screenshot 1](http://smyck.org/smyck/color_1.jpg)

