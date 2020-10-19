# ZSH

> Installer zsh en version >= 5.4

## Installation

```bash
# Oh My ZSH : Gestionnaire de plugin et de thèmes
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

# Thème Powerlevel10K
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k

# Plugin zsh-autosuggestions
git clone --depth=1 https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

# Plugin zsh-syntax-highlighting
git clone --depth=1 https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

# Plugin fzf pour la recherche fuzzy dans historique (Ctrl+R) ou les fichiers (Ctrl+T)
git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf && ~/.fzf/install

# Enhancd : améliore la commande CD
git clone --depth 1 https://github.com/b4b4r07/enhancd ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/enhancd
```

## Configuration

- Fichier `zshrc` à placer dans `~/.zshrc`
- Fichier `zshrc.custom` à placer dans `~/.zshrc.custom`
- Fichier `p10k.zsh` à placer dans `~/.p10k.zsh`
