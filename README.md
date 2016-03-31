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
