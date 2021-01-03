##### When we start install linux operation system (Ubuntu), every time I just install package, tool or programming language link Rust go etc.

```bash
sudo apt update; sudo apt upgrade -y; reboot
```
install programming language
```bash
sudo apt install python3 python3-pip golang clang cmake git zsh curl wget neovim -y
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
# install auto suggestion from source
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
plugins=(zsh-autosuggestions)
```

```bash
cd ~ curl -sL https://deb.nodesource.com/setup_14.x -o nodesource_setup.sh; bash nodesource_setup.sh

curl -sL https://deb.nodesource.com/setup_14.x | sudo bash -
```
```bash
sudo apt install -y nodejs npm
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
sudo apt update && sudo apt install yarn -y
sudo apt install apt-transport-https ca-certificates curl software-properties-common -y
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable" \
sudo apt update \
sudo apt install docker-ce -y \
sudo usermod -aG docker ${USER} \
su - ${USER} \
id -nG
```
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh; >>1
source $HOME/.cargo/env
export GOPATH="/home/enwuft/go"
export PATH="$GOPATH/bin:$PATH"
```

```bash
git config --global user.email "enwuft@gmail.com"
git config --global user.name "Vit"
git config --global core.ui true
git config --global core.editor vim
```
