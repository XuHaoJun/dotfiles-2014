# dotfiles

This repo contains the configuration to setup my machines. This is using [Chezmoi](https://chezmoi.io), the dotfile manager to setup the install.

This automated setup is currently only configured for EndeavourOS machines.

## How to run

```shell
export GITHUB_USERNAME=xuhaojun
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply $GITHUB_USERNAME
# or aleady installed chezmoi
chezmoi init https://github.com/$GITHUB_USERNAME/dotfiles.git
```

## Reference
- [是時候同步你的 dotfiles 了——我選擇 yadm](https://blog.kyomind.tw/yadm/)
