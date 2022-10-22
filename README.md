# Sample dotfiles

This is a sample that includes minimal settings, so please create your own dotfiles.

## Install manually

```sh
git clone https://github.com/nextgem-jp/sample-dotfiles

sh ./sample-dotfiles/dotfiles/install.sh
```

## Install Visual Studio Code

Add following lines to user settings.json
```json
{
  "dotfiles.repository": "nextgem-jp/sample-dotfiles",
  "dotfiles.installCommand": "~/dotfiles/install.sh",
}
```
