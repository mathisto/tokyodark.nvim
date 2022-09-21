![tokyodark.nvim](https://user-images.githubusercontent.com/30515389/141231977-82476546-eb48-47e4-a5fc-45ace7eacb0d.png)

![image](https://user-images.githubusercontent.com/30515389/115807570-42385080-a3bf-11eb-8286-c981b5093ffa.png)

### About

A clean dark theme written in lua for neovim 0.7.

### Features

- Support for numerous plugins
- Customizable
- Italic Support

### Installation

Install with your favorite package manager:

[packer](https://github.com/wbthomason/packer.nvim)

``` lua
use 'tiagovla/tokyodark.nvim'
```

[vim-plug](https://github.com/junegunn/vim-plug)

``` vim
Plug 'tiagovla/tokyodark.nvim'
```

### Available configuration

Note:** The configuration options should be placed before
`colorscheme tokyodark` .

- `tokyodark_transparent_background`: Set to enable transparent
  background.
- `tokyodark_enable_italic_comment`: Set to enable italic in `Comment` .
- `tokyodark_enable_italic`: Set to italicize keywords. This option is
  designed to use with fonts that support italic styles, for example
  [Fira Code, MonoLisa, Dank Mono](https://www.nerdfonts.com/).
- `tokyodark_color_gamma`: Change to adjust the brightness of the theme.
  (Darker \< 1.0 \< Lighter).

#### Default configuration

``` lua
-- init.lua
vim.g.tokyodark_transparent_background = false
vim.g.tokyodark_enable_italic_comment = true
vim.g.tokyodark_enable_italic = true
vim.g.tokyodark_color_gamma = "1.0"
vim.cmd("colorscheme tokyodark")
```

``` vim
" .vimrc
let g:tokyodark_transparent_background = 0
let g:tokyodark_enable_italic_comment = 1
let g:tokyodark_enable_italic = 1
let g:tokyodark_color_gamma = "1.0"
colorscheme tokyodark
```

### Inspiration

- [tokyonight-vim](https://github.com/ghifarit53/tokyonight-vim)
- [tokyo-night-vscode-theme](https://github.com/enkia/tokyo-night-vscode-theme)

### Ports & Extras

- [Vivaldi](https://themes.vivaldi.net/themes/RqZvdka2l9o)
-

### Color Palette

| Color&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Use |
| ---------- | ------------------------------------------------------------ |
| ![#dd657d](https://place-hold.it/15/dd657d/dd657d?text=+) `#dd657d` | This keyword, HTML elements, Regex group symbol, CSS units, Terminal Red |
| ![#f2945a](https://place-hold.it/15/f2945a/f2945a?text=+) `#f2945a` | Number and Boolean constants, Language support constants |
| ![#d7a65f](https://place-hold.it/15/d7a65f/d7a65f?text=+) `#d7a65f` | Function parameters, Regex character sets, Terminal Yellow |
| ![#90c05e](https://place-hold.it/15/90c05e/90c05e?text=+) `#90c05e` | Strings, CSS class names |
| ![#73daca](https://place-hold.it/15/73daca/73daca?text=+) `#73daca` | Object literal keys, Markdown links, Terminal Green |
| ![#b4f9f8](https://place-hold.it/15/b4f9f8/b4f9f8?text=+) `#b4f9f8` | Regex literal strings |
| ![#2ac3de](https://place-hold.it/15/2ac3de/2ac3de?text=+) `#2ac3de` | Language support functions, CSS HTML elements |
| ![#7dcfff](https://place-hold.it/15/7dcfff/7dcfff?text=+) `#7dcfff` | Object properties, Regex quantifiers and flags, Markdown headings, Terminal Cyan, Markdown code, Import/export keywords |
| ![#7aa2f7](https://place-hold.it/15/7aa2f7/7aa2f7?text=+) `#7aa2f7` | Function names, CSS property names, Terminal Blue |
| ![#a081d8](https://place-hold.it/15/a081d8/a081d8?text=+) `#a081d8` | Control Keywords, Storage Types, Regex symbols and operators, HTML Attributes, Terminal Magenta |
| ![#c0caf5](https://place-hold.it/15/c0caf5/c0caf5?text=+) `#c0caf5` | Variables, Class names, Terminal White |
| ![#a9b1d6](https://place-hold.it/15/a9b1d6/a9b1d6?text=+) `#a9b1d6` | Editor Foreground |
| ![#9aa5ce](https://place-hold.it/15/9aa5ce/9aa5ce?text=+) `#9aa5ce` | Markdown Text, HTML Text |
| ![#cfc9c2](https://place-hold.it/15/cfc9c2/cfc9c2?text=+) `#cfc9c2` | Parameters inside functions (semantic highlighting only) |
| ![#565f89](https://place-hold.it/15/565f89/565f89?text=+) `#565f89` | Comments |
| ![#414868](https://place-hold.it/15/414868/414868?text=+) `#414868` | Terminal Black |
| ![#24283b](https://place-hold.it/15/24283b/24283b?text=+) `#24283b` | Editor Background (Storm) |
| ![#1a1b26](https://place-hold.it/15/1a1b26/1a1b26?text=+) `#1a1b26` | Editor Background (Night) |

# tokyodark
```
#dd2f45
#dd657d
#f2945a
#d7a65f
#90c05e
#3572a5
#8193b4
#6946bf
#a081d8
#11121d
#1a1b2a
#464b53
#6d8086
```
