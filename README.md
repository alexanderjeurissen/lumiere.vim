![image](https://raw.githubusercontent.com/alexanderjeurissen/lumiere.vim/master/assets/lumiere_logo.png)

>Do not go gentle into that good night,
>Old age should burn and rave at close of day;
>Rage, rage against the dying of the light.
>
>Though wise men at their end know dark is right,
>Because their words had forked no lightning they
>Do not go gentle into that good night.
>
> ~ (Poem by Dylan Thomas)


A light black and white Vim 8 / Neovim colorscheme with sparse use of color to denote important syntax elements.
Looks even more awesome when combined with [Sombre.tmux](https://github.com/alexanderjeurissen/sombre.tmux)


![image](https://raw.githubusercontent.com/alexanderjeurissen/lumiere.vim/master/assets/lumiere_dim_inactive.png)

## Screenshots

### Ruby
![image](https://raw.githubusercontent.com/alexanderjeurissen/lumiere.vim/master/assets/lumiere_rb.png)

### Python
![image](https://raw.githubusercontent.com/alexanderjeurissen/lumiere.vim/master/assets/lumiere_py.png)

### Javascript
![image](https://raw.githubusercontent.com/alexanderjeurissen/lumiere.vim/master/assets/lumiere_js.png)

### Vimscript
![image](https://raw.githubusercontent.com/alexanderjeurissen/lumiere.vim/master/assets/lumiere_vim.png)

## Notable Features
### Dim inactive windows (neovim only)
Lumiere offers a configuration option, to reduce the opacity of inactive windows. This helps more clearly
distinguish the pane that is currently being focussed. This currently depends on the `hl-NormalNC` highlight group which
is only available in NeoVim. There is an open issue to add Vim8 support.

This setting is opt in and can be enabled by setting `let g:lumiere_dim_inactive_windows = 1`  in your vimrc
and restarting Vim.

### Git Diff
![image](https://raw.githubusercontent.com/alexanderjeurissen/lumiere.vim/master/assets/gitdiff.png)

### Vim diff (using Neovim as git difftool)
![image](https://raw.githubusercontent.com/alexanderjeurissen/lumiere.vim/master/assets/vimdiff.png)

## Installation
Lumiere can be installed using the native Vim packages feature, as well as your plugin manager of choice:

- Pathogen
`git clone https://github.com/alexanderjeurissen/lumiere.vim.git ~/.vim/bundle/lumiere`

- Vundle
Add `Plugin 'alexanderjeurissen/lumiere.vim'` to your .vimrc and run `:PluginInstall`

- NeoBundle
Add `NeoBundle 'alexanderjeurissen/lumiere.vim'` to your .vimrc and run `:NeoBundleInstall`

- vim-plug
Add `Plug 'alexanderjeurissen/lumiere.vim'` to your .vimrc and run `:PlugInstall`

Then add the line `colorscheme lumiere` to your .vimrc file, and restart Vim.

## Configuration options
There are a couple of options that can be configured:

| option_name | default | effect |
|-------------|---------|--------|
| g:lumiere_bold | 1 | when set to 0, disables the usage of bold font |
| g:lumiere_italic | 1 | when set to 0, disables the usage of italic font |
| g:lumiere_inverse | 1 | when set to 0, disables the usage of inversing fg / bg of color groups |
| g:lumiere_invert_selection | 1 | when set to 0, disables the usage of inverting the color in visual cursor and HlSearch|
| g:lumiere_dim_inactive_windows | 0 | When set to 1, reduces the background color opacity of inactive windows|
