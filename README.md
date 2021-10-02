# circleci-sandbox

## 準備

* dockerのインストール
* circle ciのインストール（config.ymlをローカルでバリデートチェックするため）
  * インストール方法はこちら
``` sh
$ curl https://raw.githubusercontent.com/CircleCI-Public/circleci-cli/master/install.sh --fail --show-error |bash
```

## コマンド

``` sh
# .circleci/config.ymlのフォーマット確認
$ yarn check-format

# circle ci上のdockerを確認
$ yarn check-docker

# circle ci上で行う単体テスト
$ yarn test
``` 