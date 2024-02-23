Micro is a text/code editor for Linux terminal.

This is a colorscheme for micro based on the Rstudio [Vibrant ink flavoured theme](https://github.com/bgonzalezbustamante/v-ink-flavoured).

<img width="400" alt="Rstudio Vibrant ink flavoured theme" src="https://github.com/bgonzalezbustamante/v-ink-flavoured/raw/main/images/vink.png">


Micro [main page](https://micro-editor.github.io/index.html) and [GitHub page](https://github.com/zyedidia/micro) for more information.


-- Installation: 
- Navigate to the desired folder, then run the command below to install in this folder (this will download and install micro):

```
curl https://getmic.ro | bash
```


Make an alias, instead of typing micro, or ./micro, just m
```
nano ~/.bashrc
alias m=".././micro"
source ~/.bashrc
```

-- Adding custom color schemes

- Create the file into the colorscheme folder, it can be called "vibrantink.micro"

```
mkdir -p ~/.config/micro/colorschemes

touch ~/.config/micro/colorschemes/vibrantink.micro
```

- Edit the files with:

```
nano ~/.config/micro/colorschemes/vibrantink.micro
```

- Add colors from:

Best if copy from the [raw file](https://raw.githubusercontent.com/Gelsleichter/micro_theme_vibrant_ink/main/vibrant_ink.micro) or [file](https://github.com/Gelsleichter/micro_theme_vibrant_ink/blob/main/vibrant_ink.micro).

```
color-link default "#FFFFFF"  
color-link comment "#9933CC"  
color-link constant "#339999"  
color-link constant.string "#8DE635"  
color-link constant.string.char "#8DE635"  
color-link constant.number "#CCCC33"  
color-link statement "#FF6600"  
color-link type "#FFCC00"  
color-link special "#DDE93D"  
color-link underlined "#268bd2"  
color-link error "bold #f20004"  
color-link todo "bold #268BD2"  
color-link statusline "#839496,#252525"  
color-link line-number "#404040"  
color-link current-line-number "#FFFFFF,#252525"  
color-link gutter-error "bold #f20004"  
color-link gutter-warning "bold #b58900"  
color-link cursor-line "#252525"  
color-link color-column "#252525"  
```

To change your colorscheme, go inside micro press `Ctrl-e` to bring up the command prompt, and type:

```
set colorscheme vibrantink
```
