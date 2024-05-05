# vim-config-files
---
*I really like vim, and it wouldn't be wrong on my behalf to say. That, that i use vim fulltime (even though, i haven't mastered it yet.)*

This particular repository hold's The settings or more accurately `.vimrc` which i use for my **Vim Setup**.

> There is nothing fancy in here. I use vim for Primarily Coding. So my vimrc is suitable for coding (and i have kept things to a bare `minimal`)

## .vimrc
You could `git clone` the repo/file || instead just copy the **config** form here.

```bash
" Disable compatiabilty with VI, use pure VIM.
set nocompatible

" File type detection
filetype on

" suitable indent depending on the filetype
filetype indent on

" Syntax hightlighting
"syntax on
"syntax enable

" Number column
set number

" relative number
set relativenumber

" hightlight the cursor Line
" set cursorline

" number of columns of whitespace \t
set tabstop=4

" convert tabs to spaces
set expandtab

" hwo many columns of whitespace (level of intentation)
set shiftwidth=4

" vim saves backup fies, dont want those
set nobackup

" dont let cursor go above the view screen
set scrolloff=10

" hightlight while searching
set incsearch

" ignore case while searching
set ignorecase

" override the ignore case if serched for UPPAR CASE
set smartcase

" show the mode
set showmode

" auto completion
set wildmenu

" wild menu act like bash
set wildmode=list:longest

" There are certain files that we would never want to edit with Vim.
" Wildmenu will ignore files with these extensions.
set wildignore=*.docx,*.jpg,*.png,*.gif,*.pdf,*.pyc,*.exe,*.flv,*.img,*.xlsx

" enable mouse drag only
set mouse=a

" set theme 
"colorscheme habamax

" change color of the brace hightlighting.
highlight MatchParen ctermfg=blue ctermbg=NONE

" mark the column length with 80 characters
set colorcolumn=80


set laststatus=2 " Always show the status line
set statusline=%t " Display only the file name and extension in the status line
```