# zellij-config
my personal zellij configuration

## Installation

```bash
git clone https://github.com/ldoo22/zellij-config.git ~/.config/zellij
```

## Additional Configuration

Add the following alias to your shell configuration file (e.g. `~/.bashrc`, `~/.zshrc`, etc.):

```bash
alias zz="zellij"
```

Or autostart with:

## bash

```bash
echo 'eval "$(zellij setup --generate-auto-start bash)"' >> ~/.bashrc
```

## zsh


```bash
echo 'eval "$(zellij setup --generate-auto-start zsh)"' >> ~/.zshrc
```
