# 各種アプリケーションの設定

## VsCode

### setting.json

```
ln -s ~/my_preferences/vscode/settings.json ~/Library/ApplicationSupport/Code/User/settings.json
```

## Homebrew

[homebrew-bundle](https://github.com/Homebrew/homebrew-bundle)を利用している

```
ln -s ~/my_preferences/homebrew/Brewfile ~/Brewfile
cd ~/
brew bundle
```
