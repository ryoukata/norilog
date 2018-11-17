=====-==========
乗りログアプリ
================
目的
====
Webブラウザーでコメントを投稿するアプリの練習
====
ツールのバージョン
====
:Python:        3.6.4
:pip:           9.0.1
====
インストール、起動方法
====
リポジトリからコードを取得し、その配下にvenv環境を用意::

        $ git clone https://github.com/ryoukata/norilog
        $ cd norilog
        $ python3.6 -m venv venv
        $ source venv/bin/activate
        (venv) $ pip install .
        (venv) $ norilog
         * Running on http://127.0.0.1:8000/

====
開発手順
====
開発用インストール
------------------
1. チェックアウトする
2. 以下の手順でインストールする::
   (venv) $ pip install -e .
