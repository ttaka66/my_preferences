# 各種アプリケーションの設定

## Homebrew

[homebrew-bundle](https://github.com/Homebrew/homebrew-bundle)を利用している

### 初期設定

```
ln -s path/to/my_preferences/homebrew/Brewfile ~/Brewfile
```

### 更新

```
cd ~/
brew update
brew upgrade --cask
brew bundle
```
