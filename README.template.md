gitlab-i18n-patch
=================

[![Build Status](https://travis-ci.org/ksoichiro/gitlab-i18n-patch.svg?branch=master)](https://travis-ci.org/ksoichiro/gitlab-i18n-patch)

[GitLab Community Edition](https://gitlab.com/gitlab-org/gitlab-ce)を勝手に日本語化していくプロジェクトです。

GitLabはi18nに対応しないとのことですが、  
社内で使う場合等で英語であるために導入の抵抗があるケースのために作っています。

このパッチを適用することによって生じたいかなる問題についても責任は負いかねます。  
各自の判断でご利用ください。

## 対応バージョン

:mega: v8.3.0以降のパッチは [i18n-patch](https://github.com/ksoichiro/i18n-patch) で生成しています。

@VERSIONS@

以下は旧来の方式(手作業)で作成したパッチです。

1. [GitLab CE v8.2.0](https://gitlab.com/gitlab-org/gitlab-ce/commits/v8.2.0 "GitLab CE v8.2.0") → [patches/v8.2.0ディレクトリ](patches/v8.2.0)
1. [GitLab CE v8.1.0](https://gitlab.com/gitlab-org/gitlab-ce/commits/v8.1.0 "GitLab CE v8.1.0") → [patches/v8.1.0ディレクトリ](patches/v8.1.0)
1. [GitLab CE v8.0.0](https://gitlab.com/gitlab-org/gitlab-ce/commits/v8.0.0 "GitLab CE v8.0.0") → [patches/v8.0.0ディレクトリ](patches/v8.0.0)
1. [GitLab CE v7.14.0](https://gitlab.com/gitlab-org/gitlab-ce/commits/v7.14.0 "GitLab CE v7.14.0") → [patches/v7.14.0ディレクトリ](patches/v7.14.0)
1. [GitLab CE v7.13.5](https://gitlab.com/gitlab-org/gitlab-ce/commits/v7.13.5 "GitLab CE v7.13.5") → [patches/v7.13.5ディレクトリ](patches/v7.13.5)
1. [GitLab CE v7.13.4](https://gitlab.com/gitlab-org/gitlab-ce/commits/v7.13.4 "GitLab CE v7.13.4") → [patches/v7.13.4ディレクトリ](patches/v7.13.4)
1. [GitLab CE v7.13.3](https://gitlab.com/gitlab-org/gitlab-ce/commits/v7.13.3 "GitLab CE v7.13.3") → [patches/v7.13.3ディレクトリ](patches/v7.13.3)
1. [GitLab CE v7.13.2](https://gitlab.com/gitlab-org/gitlab-ce/commits/v7.13.2 "GitLab CE v7.13.2") → [patches/v7.13.2ディレクトリ](patches/v7.13.2)
1. [GitLab CE v7.13.1](https://gitlab.com/gitlab-org/gitlab-ce/commits/v7.13.1 "GitLab CE v7.13.1") → [patches/v7.13.1ディレクトリ](patches/v7.13.1)
1. [GitLab CE v7.13.0](https://gitlab.com/gitlab-org/gitlab-ce/commits/v7.13.0 "GitLab CE v7.13.0") → [patches/v7.13.0ディレクトリ](patches/v7.13.0)
1. [GitLab CE v7.12.0](https://gitlab.com/gitlab-org/gitlab-ce/commits/v7.12.0 "GitLab CE v7.12.0") → [patches/v7.12.0ディレクトリ](patches/v7.12.0)
1. [GitLab CE v7.11.0](https://gitlab.com/gitlab-org/gitlab-ce/commits/v7.11.0 "GitLab CE v7.11.0") → [patches/v7.11.0ディレクトリ](patches/v7.11.0)
1. [GitLab CE v7.10.0](https://gitlab.com/gitlab-org/gitlab-ce/commits/v7.10.0 "GitLab CE v7.10.0") → [patches/v7.10.0ディレクトリ](patches/v7.10.0)
1. [GitLab CE v7.9.4](https://gitlab.com/gitlab-org/gitlab-ce/commit/b10de29edbaff7219547dc506cb1468ee35065c3 "GitLab CE v7.9.4") → [patches/v7.9.4ディレクトリ](patches/v7.9.4)
1. [GitLab CE v7.9.0](https://gitlab.com/gitlab-org/gitlab-ce/commit/16d6f0e35b8bd3a88e3a2e2e3ae8bf98be426f85 "GitLab CE v7.9.0") → [patches/v7.9.0ディレクトリ](patches/v7.9.0)
1. [GitLab CE v7.8.0](https://gitlab.com/gitlab-org/gitlab-ce/commit/bcc8dbd0659b89a20f6cbd955c7022ea09dd0172 "GitLab CE v7.8.0") → [patches/v7.8.0ディレクトリ](patches/v7.8.0)
1. [GitLab CE v7.7.0](https://gitlab.com/gitlab-org/gitlab-ce/commit/c04f11dab5b8890278f9fe3b47729353cded1c54 "GitLab CE v7.7.0") → [patches/v7.7.0ディレクトリ](patches/v7.7.0)
1. [GitLab CE v7.6.0](https://gitlab.com/gitlab-org/gitlab-ce/commit/07bee141b9a6d32e38bbdba59ce7371d36f8c320 "GitLab CE v7.6.0") → [patches/v7.6.0ディレクトリ](patches/v7.6.0)
1. [GitLab CE v7.5.3](https://gitlab.com/gitlab-org/gitlab-ce/commit/b656b8592fc67b466ae2dd3b99ad35d663721b37 "GitLab CE v7.5.3") → [patches/v7.5.3ディレクトリ](patches/v7.5.3)
1. [GitLab CE v7.4.0](https://gitlab.com/gitlab-org/gitlab-ce/commit/ba76dbc3667c2eb0a1a3687f8b0481e619946d73 "GitLab CE v7.4.0") → [patches/v7.4.0ディレクトリ](patches/v7.4.0)
1. [GitLab CE v7.3.0](https://gitlab.com/gitlab-org/gitlab-ce/commit/a04f0e5b3dece759bc82d89d32a4cadb67e6bb71 "GitLab CE v7.3.0") → [patches/v7.3.0ディレクトリ](patches/v7.3.0)
1. [GitLab CE v7.2.0](https://gitlab.com/gitlab-org/gitlab-ce/commit/da5d33e13ec51006edfffd9e286b0f33781a4c12 "GitLab CE v7.2.0") → [patches/v7.2.0ディレクトリ](patches/v7.2.0)
1. [GitLab CE v7.1.0](https://gitlab.com/gitlab-org/gitlab-ce/commit/68a9203bcef1e44bdf72acf4cc8d4977eec79b7a "GitLab CE v7.1.0") → [patches/v7.1.0ディレクトリ](patches/v7.1.0)
1. [GitLab CE v7.0.0](https://gitlab.com/gitlab-org/gitlab-ce/commit/d1e424bd5c403d73d399bf0f92e39aefde56e638 "GitLab CE v7.0.0") → [patches/v7.0.0ディレクトリ](patches/v7.0.0)
1. [GitLab CE v6.9.2](https://gitlab.com/gitlab-org/gitlab-ce/commit/e46b644a8857a53ed3f6c3f64b224bb74b06fd8e "GitLab CE v6.9.2") → [patches/v6.9.2ディレクトリ](patches/v6.9.2)
1. [GitLab CE v6.9.0](https://gitlab.com/gitlab-org/gitlab-ce/commit/f0a32c69494a1d4dda4c5ec8a7f3b94bc7ceed65 "GitLab CE v6.9.0") → [patches/v6.9.0ディレクトリ](patches/v6.9.0)
1. [GitLab CE v6.8.2](https://gitlab.com/gitlab-org/gitlab-ce/commit/bfdcbc5380119b82bfbe1927c7daf2ae1d53fe19 "GitLab CE v6.8.2") → [patches/v6.8.2ディレクトリ](patches/v6.8.2)
1. [GitLab CE v6.8.1](https://gitlab.com/gitlab-org/gitlab-ce/commit/319799073b502392fec9e45d617f566a90bef81e "GitLab CE v6.8.1") → [patches/v6.8.1ディレクトリ](patches/v6.8.1)
1. [GitLab CE v6.7.5](https://gitlab.com/gitlab-org/gitlab-ce/commit/00aa5c16ee6b06dabb5cd63349942f70bb131dda "GitLab CE v6.7.5") → [patches/v6.7.5ディレクトリ](patches/v6.7.5)
1. [GitLab CE v6.7.2](https://gitlab.com/gitlab-org/gitlab-ce/commit/dbbf4ea24c7bed7f1eddcfcbfebb3593bc30e92d "GitLab CE v6.7.2") → [patches/v6.7.2ディレクトリ](patches/v6.7.2)
1. [GitLab CE v6.6.4](https://gitlab.com/gitlab-org/gitlab-ce/commit/42e34aec97818981338401a47560cd40c05e686d "GitLab CE v6.6.4") → [patches/v6.6.4ディレクトリ](patches/v6.6.4)

## 動作確認環境

| ソフトウェア | バージョン等                                     |
| ------------ | ------------------------------------------------ |
| マシン       | MacBookPro                                       |
| OS           | OS X 10.10.1                                      |
| VM           | VirtualBox 4.3.20                                |
| ゲストOS     | Ubuntu Precise 64 VirtualBox                     |
| GitLab       | GitLab Omnibus Package                           |
| Vagrant      | Vagrant 1.5.4                                    |

## 適用方法

### 前提

[GitLab Community Editionのパッケージ](https://about.gitlab.com/downloads/)がインストールされているものとします。  

### 基本

`patches/[GitLabバージョン]/app_ja.patch`がパッチです。  
パッチを適用するGitLabのバージョンと完全に一致するものを選びます。  
リポジトリをクローンするか、wget、curl などで直接パッチファイルをダウンロードします。  
以下は wget で v8.16.6 のパッチを取得する例です。

    $ wget https://raw.githubusercontent.com/ksoichiro/gitlab-i18n-patch/master/patches/v8.16.6/app_ja.patch

例えばホームディレクトリにパッチファイルを配置した場合、以下で適用します。

    $ cd /opt/gitlab/embedded/service/gitlab-rails
    $ patch -p1 < ~/app_ja.patch


### 既に稼働させている場合

Javascriptファイルを変更するため、パッチ適用後にプリコンパイルされたファイルを一度削除してプリコンパイルし直してください。

例：

    $ cd /opt/gitlab/embedded/service/gitlab-rails
    $ rm -rf public/assets
    $ export PATH=/opt/gitlab/embedded/bin:$PATH
    $ bundle exec rake assets:precompile RAILS_ENV=production


## Vagrantでの動作確認

各バージョンのパッチのメンテナンスができるよう、Vagrantでこのプロジェクトから直接、  
日本語反映版のGitLabを動かすことができます。

### 起動

以下のコマンドで、各バージョン用の仮想マシン起動、GitLab Omnibusパッケージをダウンロード、パッチ適用を一度に行います。(非常に時間がかかります)

    $ vagrant up

特定のバージョンのみ起動するには、例えば v6.6.4 ならば以下のようにします。

    $ vagrant up v664

### 停止

以下で停止します。

    $ vagrant halt

### 破棄

以下で仮想マシンを破棄します。

    $ vagrant destroy

### ポート番号

Webのポート番号(80)は、 `config/gitlab.yml` に定義する `base_port` の番号を起点として  
バージョン番号(v6.6.4なら664)を加えた番号にポートフォワードします。  
例えば、 `base_port: 9000` の状態で `vagrant up v664` を実行した場合は  
`http://localhost:9664` でGitLabにアクセスできます。  
v7.10.0の場合は(番号が飛びますが)7100 + 9000で16100です。

## ライセンス

Copyright (c) 2014 Soichiro Kashima  
Licensed under the MIT license.
