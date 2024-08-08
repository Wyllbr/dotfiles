# dotfiles
Versionamento ubuntu

Comandos para a restauracao.
```sh
git clone --depth 1 "https://github.com/limaon/dotfiles.git" ~/dots
cp -rfT ~/dots ~/
cp -rf ~/.git ~/.config/dotfiles
rm -rf -- ~/dots ~/.git
dot config --local status.showUntrackedFiles no
```
