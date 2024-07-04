# my-nvim-config

**Requirements:**
- Install Homebrew:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

- Add to Path (Silicon Apple - ARM arch):

```bash
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"
```

Install A Nerd Font:

brew tap homebrew/cask-fonts - deprecated

```bash
brew install font-meslo-lg-nerd-font
```

Install tree to view the tree directory:

```bash
brew install tree
```

Install Neovim, Ripgrep, Node:

```bash
brew install neovim
brew install ripgrep
brew install node
```

Create a folder for nvim config:

```bash
mkdir -p ~/.config/nvim
cd ~/.config/nvim
```

A few Vim cmd to get started in Vim:

:%filename + Enter - to create a file

:source % + Enter - to save the current source file and apply changes

:h autoindent + Enter - to show what we can do to change auto indent 

:e <filename> - to edit or add new files

:Explore - to go back to explore tree

Space t o/p/x -> open / previous / close 

Tmux:
Space s h -> horizontal split
Space s v -> vertical split
Space s x -> close the window 