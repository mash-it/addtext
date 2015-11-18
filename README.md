# addtext
Add text on a image by command line
コマンドラインで画像に文字を付与する

required
----
* python (>2.7 or >3.3)
* PIL (python image library)
```
$ sudo pip install pillow
```


supported OS
----
Ubuntu 14.04 のみ動作確認。option でフォント `-f` さえ手動で指定すれば大体動くと思う


install
----
addtext に実行権限をつけて path の通った適当な場所に置く

usage
----

```
$ addtext input.png hogehoge output.png
$ addtext input.png 日本語もOK output.png
```

options
----

| option |    mean   |     default value     |                |
|:------:|:---------:|:---------------------:|----------------|
|   -m   |   margin  |           5           | 角からの距離   |
|   -p   |  position |        lefttop        | テキストの位置 |
|   -c   |   color   |         black         | 文字の色       |
|   -f   |    font   | /path/to/FreeSans.ttf | フォント       |
|   -s   | font size |           24          | フォントサイズ |
