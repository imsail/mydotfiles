


## starship
### install starship

```bash
    curl -sS https://starship.rs/install.sh | sh
```

### init starship
```bash
    eval "$(starship init zsh)"
```
### config starship
```bash
    mkdir -p ~/.config && touch ~/.config/starship.toml
```

### remove starship
Locate and delete the starship binary
```
sh -c 'rm "$(command -v 'starship')"'
```
