# install zsh using following command

-> sudo apt install wget curl xclip git

# install zsh using following command

-> sudo apt install zsh

# set your shell from bash tot zsh using following command

# install oh-my-zsh using following command

-> sh -c "$(wget https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)"

# install autosuggestions for zsh using following command

-> git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

# install syntax highlighting for zsh using following command

-> git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

# install custom theme poweline10k using following command

-> git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k

# set the theme in your .zshrc file to the following theme

-> ZSH_THEME="powerlevel10k/powerlevel10k"
