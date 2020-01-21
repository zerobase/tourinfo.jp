tourinfo.jp
===========

[観光IT政策「観光情報インフラ整備計画」](http://tourinfo.jp) のウェブサイトのソースコード。


リファレンス
----------

- [Wintersmith](http://wintersmith.io/)
- [Jade - Template Engine](http://jade-lang.com/reference/)


サイト公開手順
------------

1. `npm install` で wintersmith 静的サイトジェネレーターをインストール
2. `wintersmith preview` でローカル開発環境（ソース監視・自動更新機能付きのウェブサーバー）を起動
3. `bundle install` で s3_website デプロイツールをインストール 
4. `wintersmith build` でビルド。
5. `bundle exec s3_website push --site public` で Amazon S3 へプッシュ

※要注意： `wintersmith preview` では public が更新されないので `wintersmith build` コマンドを使う。
※初期設定： `bundle exec s3_website cfg create` で s3_website.yml を作成し、Amazon S3へのアクセストークンを記入する。