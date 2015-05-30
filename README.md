# elegant-zsh-theme

![](http://i.imgur.com/2xBfJfD.png)

 - Terminal: [iTerm2](https://www.iterm2.com/)
 - Color: [Tomorrow Night](https://github.com/chriskempson/tomorrow-theme/tree/master/iTerm2)

## Installation

1.  You will need to create this directory if it doesn't already exist:
    
    ```bash
    mkdir ~/.oh-my-zsh/custom/ 
    ```
    Change to `oh-my-zsh` custom themes directory:

    ```bash
    cd ~/.oh-my-zsh/custom/themes
    ```


2. Download the .zsh-theme file to your themes directory, you can use curl:
    
    ```bash
    curl -O https://raw.githubusercontent.com/jigsawye/elegant-zsh-theme/master/elegant.zsh-theme
    ```
    or wget:
    
    ```bash  
    wget https://raw.githubusercontent.com/jigsawye/elegant-zsh-theme/master/elegant.zsh-theme
    ```

3.  Change the `ZSH_THEME` of your .zshrc:

    ```zsh
    ...
    ZSH_THEME="elegant"
    ...
    ```

4. Restart your terminal application.
