# Install necessary dependencies
sudo apt install wget curl xclip git

# Install zsh
sudo apt install zsh

# Set your shell from bash to zsh
sudo chsh -s $(which zsh)

# Install oh-my-zsh
sh -c "$(wget https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)"

# Install zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

# Install zsh-syntax-highlighting
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

# Install the recommended fonts for powerlevel10k

# Install custom theme powerlevel10k
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k

# Set the theme in your .zshrc file to powerlevel10k
ZSH_THEME="powerlevel10k/powerlevel10k"

# Apply changes using following command
source ~ ./zshrc


