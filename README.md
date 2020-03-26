# Mephistopheles
Warm and minimal colourscheme like beelzebub.

For Emacs version look at [peregrinator/mephistopheles.el](https://gitlab.com/peregrinator/mephistopheles.el)

>> TODO: ![](screenshots/mephistopheles-dark.png)

## Installation

With VimPlug:

```vim
Plug 'peregrinat0r/vim-mephistopheles'
```

Or just throw mephistopheles.vim in your colors directory.

## Usage

```vim
set background=dark
colorscheme mephistopheles
```

## Settings
```vim
" You can adjust colors you want like this:
let g:mephistopheles_bg="233"
let g:mephistopheles_fg="250"
let g:mephistopheles_mute="60"

" Add color noises for syntax highlightning:
let g:mephistopheles_syntax_mute=1

" And make parts of it bold:
let g:mephistopheles_syntax_bold=1

" Then set light variant of colorscheme
set background=light
colorscheme mephistopheles

" And ask yourself: "What have I done?!"
```

## Inspired by
...a bunch of great emacs monochrome themes, [nofrils](https://github.com/robertmeta/nofrils) and :SYNTAX OFF discussions on the internet.

