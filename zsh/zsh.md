
**install zsh-syntax-highlighting

```bash
sudo apt install zsh-syntax-highlighting
echo "source /usr/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc

```


**install zsh-autosuggestions
1. clone it from github
```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ~/.zsh/zsh-autosuggestions
```

2. add following to .zshrc
```
source ~/.zsh/zsh-autosuggestions/zsh-autosuggestions.zsh

```
