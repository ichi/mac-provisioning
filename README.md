# mac-provisioning

## Usage

1. homebrew入れる
1. git入れる `brew install git`
1. ssh鍵用意する
1. このレポジトリとってくる
1. ansible入れる `brew install ansible`
1. `ansible-playbook` 実行
```sh
$ HOMEBREW_CASK_OPTS="--appdir=/Applications" ansible-playbook -i hosts localhost.yml -K -vv
```

## 自動化できてないもろもろ

### Atom

- [sync-settings](https://atom.io/packages/sync-settings)入れる。
- [keep](https://keep.google.com/)にgistのACCESS_KEYあるので使う。

### Terminal

- `~/Dropbox/_private/mac/Terminal/Terminal/Visor.terminal`のプロファイル使う

### iTerm2

- 設定の`Load preferenses from custom folder`で`~/Dropbox/_private/mac/iTerm2`指定

### Dash

- 設定の`Syncing`で`~/Dropbox/_private/mac/Dash`指定

### iStat Menus

- Import Settingsで`~/Dropbox/_private/mac/iStatMenus/iStat Menus Settings.ismp`
