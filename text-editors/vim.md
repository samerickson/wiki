---
description: >-
  This page contains all of my notes on vim. I tried to stay away from writing
  things that are in every vim tutorial ever written, and instead only list
  things that I have to look up frequently.
---

# 🚀 Vim

## 🗻 Quick Tips

* You can copy the highlighted text in `visual-mode` by typing `:w <name-of-file>`
* You can convert tabs to spaces, or vice versa by setting the tab setting that you want then typing `:retab` 
* You can format a visual selection by pressing = while still in visual mode

## ⚙ Settings \(.vimrc\)

```text
" This will make the background transparent
"    this is really useful if you use tmux
hi Normal guifg=#44cc44 guibg=NONE ctermbg=none

" This will disable the bell and flashing within vim
set vb t_vb=

" Show invisible characters
set listchars=tab:»\ ,extends:⟩,precedes:⟨,space:·,trail:•


```

