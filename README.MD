# Dotfiles

Dotfiles, managed with [`chezmoi`](https://www.chezmoi.io/user-guide/command-overview/).

[[_TOC_]]

## Setup

### Prerequisites

Install [chezmoi](https://www.chezmoi.io/install/):

```sh
# linux
snap install chezmoi --classic

# or (MacOS)
brew install chezmoi

# or (binary)
sh -c "$(curl -fsLS get.chezmoi.io)"
```

### Installation 🚀

```sh
chezmoi init https://github.com/cbrwflo/dotfiles.git
chezmoi apply
```

Restart your shell to make sure the changes are fully applied.

[🔝](#top)

## Prior art

Inspired by the following, especially [this blog post](https://jerrynsh.com/how-to-manage-dotfiles-with-chezmoi/#getting-started-with-chezmoi):

* https://gitlab.com/dboe/dotfiles
* https://github.com/felipecrs/dotfiles
* https://github.com/narze/dotfiles
* https://github.com/gmenih/dotfiles
* https://github.com/twpayne/dotfiles
* others:
  - https://dotfiles.github.io/inspiration/
  - https://github.com/search?q=chezmoiscripts&type=code

