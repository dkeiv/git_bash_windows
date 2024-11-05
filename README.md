# Git bash for windows powerline theme

Light & simple powerline theme for Git bash for windows

![ScreenShot](screenshot.png)


## Install:

I recommend the following:

```bash
cd $HOME
mkdir -p .bash/themes/git_bash_windows_powerline
git clone https://github.com/dkeiv/git_bash_windows.git .bash/themes/git_bash_windows_powerline
```

then add the following to your .bashrc:

```bash
# Theme
THEME=$HOME/.bash/themes/git_bash_windows_powerline/theme.bash
if [ -f $THEME ]; then
   . $THEME
fi
unset THEME
```

## Requisites

* In order for this theme to render correctly, you will need a
[Nerd Font](https://github.com/ryanoasis/nerd-fonts).

## License

MIT
