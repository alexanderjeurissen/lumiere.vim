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


A light black and white vim colorscheme with sparse use of color to denote important syntax elements.
Looks even more awesome when combined with [Sombre.tmux](https://github.com/alexanderjeurissen/sombre.tmux)

![image](https://raw.githubusercontent.com/alexanderjeurissen/lumiere.vim/master/assets/ruby.png)
![image](https://raw.githubusercontent.com/alexanderjeurissen/lumiere.vim/master/assets/python.png)

## Screenshots
### Low contrast mode(ruby)
![image](https://raw.githubusercontent.com/alexanderjeurissen/lumiere.vim/master/assets/low_contrast_mode.png)

### Git Diff
![image](https://raw.githubusercontent.com/alexanderjeurissen/lumiere.vim/master/assets/gitdiff.png)

### Vim diff (using neovim as git difftool)
![image](https://raw.githubusercontent.com/alexanderjeurissen/lumiere.vim/master/assets/vimdiff.png)

## Installation
I Personally use [pack](https://github.com/maralla/pack) as my vim plugin manager of choice.
Anyway, you can install Lumiere with whatever package manager you use. For example:

- Pathogen
`git clone https://github.com/alexanderjeurissen/lumiere.vim.git ~/.vim/bundle/lumiere`

- Vundle
Add `Plugin 'alexanderjeurissen/lumiere.vim'` to your .vimrc and run `:PluginInstall`

- NeoBundle
Add `NeoBundle 'alexanderjeurissen/lumiere.vim'` to your .vimrc and run `:NeoBundleInstall`

- vim-plug
Add `Plug 'alexanderjeurissen/lumiere.vim'` to your .vimrc and run `:PlugInstall`

Then add the line `colorscheme lumiere` to your .vimrc file, and restart vim.

## Color palette


## Customization variables
There are a couple of options that can be configured:

| option_name | default | effect |
|-------------|---------|--------|
| g:lumiere_bold | 1 | when set to 0, disables the usage of bold font |
| g:lumiere_italic | 1 | when set to 0, disables the usage of italic font |
| g:lumiere_inverse | 1 | when set to 0, disables the usage of inversing fg / bg of color groups |
| g:lumiere_invert_selection | 1 | when set to 0, disables the usage of inverting the color in visual cursor and HlSearch|
| g:lumiere_low_contrast_mode | 0 | When set to 1, reduces the background color brightness for easier use in low light conditions |
