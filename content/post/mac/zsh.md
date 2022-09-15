
# 

mac の標準シェルが macOS Catalina（2019年）から `bash` から `zsh` に変わっている。


## 補完

```
brew install zsh-completions
```

```
$ mkdir -p ~/.zsh/completion
```


### エラー(1)

```
zsh compinit: insecure directories, run compaudit for list
```

```
$ compaudit
There are insecure directories:
/opt/homebrew/share
```
表示されているディレクトリの権限を `755` に修正するとエラーは出なくなる。


## フレームワーク

予め便利な設定ファイルが有効になっているものがフレームワークであり、また様々なプラグインがインストールされているもの。
プラグイン自体はフレームワークを使用しなくても適宜インストールできるものである。

- on-my-zsh
  - インストールすると `.zshrc` が専用のものに置き換わり、そこでプラグインの読み込みなどの設定をする。ただし動作が遅い、というデメリットがある。
- prezto
  - on-my-zshの後継で、起動が遅いという欠点を克服したもの

