nicodl
=====================

nicovideo-dl を自動的に実行するスクリプト。Debian の init スクリプト向け。

起動・停止
-------------

端末で:

```sh
./nicodl start
./nicodl stop
```

設定
--------------

`$CONFIG` が指すファイルが設定ファイル（デフォルトは `./nicodl-config`）。

実行
-----------------

`$POOL_FILE` に `http://www.nicovideo.jp/watch/smXXXXXXXXX` を列挙する。例えば:

	http://www.nicovideo.jp/watch/sm19861011
	http://www.nicovideo.jp/watch/sm19902648
	http://www.nicovideo.jp/watch/sm20185100
	http://www.nicovideo.jp/watch/sm19610773
