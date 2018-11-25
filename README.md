# itamae_centos7_rails_sample

CentOS7にRuby on Railsの動作環境を自動構築するItamaeスクリプト。

# How to run

## 事前準備

- Rubyの環境構築（省略）
- Bundlerのセットアップ（省略）

## Itamaeの準備

```
$ git@github.com:tetsushi-ito/itamae_centos7_rails_sample.git
$ cd itamae_centos7_rails_sample
$ bundle install
```

- サーバーに登録するSSH公開鍵を`./remote_files/user/authorized_keys`に記入する。