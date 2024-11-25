# Deploying my neovim config

This is only a personnal repository to store and deploy my neovim configuration accross the different VM and PC I use.

Download latest neovim appimage :

```console
wget https://github.com/neovim/neovim/releases/latest/download/nvim.appimage
```

Move it to /usr/bin/nvim :

```console
sudo mv nvim.appimage /usr/bin/nvim
```

Get the config files :

```console
git clone https://github.com/bzbzz/nvim/ ~/.config/nvim && nvim
```

Run :MasonInstallAll and :checkhealth
