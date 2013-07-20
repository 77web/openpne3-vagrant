[English version](https://github.com/77web/openpne3-vagrant/blob/master/README.md)

OpenPNE3 Vagrant環境
=================================

OpenPNEはオープンソースのSNSシステムです。
openpne3-vagrantは、OpenPNE3を誰でも簡単にパソコンにインストールして試用できるようにしたものです。

使い方
--------

0. gitをインストールしてください。（お使いのPCのOSごとに利用できるソフトが違うので、「Windows git」「MacOS git」等と検索して、利用できるgitを入手してください）
1. [VirtualBox](https://www.virtualbox.org/wiki/Downloads)をインストールしてください。
2. [Vagrant](http://downloads.vagrantup.com/)をインストールしてください。
3. openpne3-vagrantをcloneしてください。 git clone git://github.com/77web/openpne3-vagrant
4. サブモジュールを更新してください: git submodule init && git submodule update
5. (必要な場合のみ）設定を修正してください。OpenPNE3を試用するだけの場合は何もしなくて良いです。
6. vagrant upを実行してください。
7. ブラウザでhttp://192.168.33.10にアクセスすると、OpenPNE3のログイン画面が表示されます。

設定
----------

[openpne3-cookbook](https://github.com/77web/openpne3-cookbook/blob/master/README-ja.md)を参照してください。

利用可能なbox
--------------------------

* presice64

phpmatsuri
-----------------

このopenpne3-vagrantとopenpne3-cookbookはphpmatsuri 2013のハッカソンで作成しました。来年はあなたも参加して何か作ってみませんか？→http://phpmatsuri.net
