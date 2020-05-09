# Zsh-Configuration
Repository to store my Oh-My-Zsh Terminal Configs.
<br></br>
## Instructions for my future dumb self
Helpful installation and setup guide:  
https://hackernoon.com/how-to-trick-out-terminal-287c0e93fce0.<br></br>
Guide for in case you want to further customize your design:  
https://github.com/Powerlevel9k/powerlevel9k/wiki/Stylizing-Your-Prompt
<br></br>
### 1. Upgrade to Zsh if you're still using Bash.<br></br>

### 2. Install [Oh-My-Zsh](https://github.com/ohmyzsh/ohmyzsh#via-curl).

Basically just type the following into the terminal:
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
For the sake of convenience, if needed for whatever reason, here is the link to the [official website](https://ohmyz.sh/).
<br></br>
### 3. Install this [font](https://github.com/ryanoasis/nerd-fonts/blob/master/patched-fonts/DejaVuSansMono/Regular/complete/DejaVu%20Sans%20Mono%20Nerd%20Font%20Complete%20Mono%20Windows%20Compatible.ttf), then change the terminal font through the Preferences.

Alternatively, you can find more free fonts in [here](https://github.com/ryanoasis/nerd-fonts#font-installation).
<br></br>
### 4. Install the [Powerlevel9k](https://github.com/Powerlevel9k/powerlevel9k) theme for Zsh.

#### First, get the homebrew tap:
```
brew tap sambadevi/powerlevel9k
```

#### Then install it like so:
```
brew install powerlevel9k
```

#### Finally, set the theme in the .zshrc.
Open the .zshrc directory:
```
open ~/.zshrc
```
Then add the following line:
```
source /usr/local/opt/powerlevel9k/powerlevel9k.zsh-theme
```
Or alternatively, you can simply do it all in one go like so:
```
echo "source /usr/local/opt/powerlevel9k/powerlevel9k.zsh-theme" >> ~/.zshrc
```

Look [here](https://github.com/Powerlevel9k/powerlevel9k/wiki/Install-Instructions#step-1-install-powerlevel9k) for more detailed installation instructions.
