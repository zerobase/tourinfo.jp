tourinfo.jp
===========

[観光IT政策「観光情報インフラ整備計画」](http://tourinfo.jp) のウェブサイトのソースコード。


リファレンス
----------

- [Wintersmith](http://wintersmith.io/)
- [Jade - Template Engine](http://jade-lang.com/reference/)


サイト公開手順
------------

1. `gem install s3_website` で [s3_website](https://github.com/laurilehmijoki/s3_website) をインストール
2. `wintersmith build` でビルド。
3. `s3_website push --site public` で Amazon S3 へプッシュ

ビルド＆デプロイ一発コマンド： `wintersmith build && s3_website push --site public`