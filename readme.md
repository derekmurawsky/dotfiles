# Derek's Dotfiles

These are my daily driver dotfiles for my MacBook Pro. I use:

- [ChezMoi](https://www.chezmoi.io/) - Manage your [dotfiles](https://dotfiles.github.io/) across multiple diverse machines, securely.
- [HomeBrew](https://brew.sh/) - The Missing Package Manager for macOS (or Linux)
- [ZSH](https://zsh.sourceforge.io/)

## How to use this repo

- Install [ChezMoi](https://www.chezmoi.io/install/)
- Initialize ChezMoi by pointing to this repo `$ chezmoi init https://github.com/derekmurawsky/dotfiles.git`
- If not prompted for an email address, edit your `~/.config/chezmoi/chezmoi.toml` and add the following

```toml
[data]
    email = "your.email@here.com"
```
