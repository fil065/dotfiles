# .dotfiles

User-specific application configuration is traditionally stored in so called dotfiles (files whose filename starts with a dot). It is common practice to track dotfiles with a version control system such as Git to keep track of changes and synchronize dotfiles across various hosts

```bash
#Clone repo into new hidden directory.
git clone git@github.com:fil065/dotfiles.git ~/.dotfiles

#Create symlinks in the Home directory to the real files in the repo.
ln -s ~/.dotfiles/.zshrc ~/.zshrc
ln -s ~/.dotfiles/.gitconfig ~/.gitconfig
```


## Resources:

[~/.dotfiles in 100 Seconds](https://www.youtube.com/watch?v=r_MpUP6aKiQ)

[https://github.com/eieioxyz/Beyond-Dotfiles-in-100-Seconds](https://github.com/eieioxyz/Beyond-Dotfiles-in-100-Seconds)

[Dotfiles - ArchWiki](https://wiki.archlinux.org/title/Dotfiles)