# 前書き
https://jp.mathworks.com/products/matlab/whatsnew.html
を参照して書きました。

　まだ全部見れていませんが、MATLABのリリースノートは[こちら](https://jp.mathworks.com/help/matlab/release-notes.html?rntext=&startrelease=R2019b&endrelease=R2019b&groupby=release&sortby=descending&searchHighlight=)にあります。意外にハイライト以外にも使えそうなのが多かったです。


# ライブタスク
https://jp.mathworks.com/help/matlab/release-notes.html#mw_d36791b1-b8cc-4145-b440-cc4becca73a9
https://jp.mathworks.com/help/matlab/release-notes.html#mw_5b034a52-ea51-46de-831e-d4918f83e41e

　ライブエディタ上で前処理の内容とその入力データをGUI上で入力できる機能です。出力の内容はfigureとして見れる他、コードとして出力することも可能です。
　上のリンクは平滑化の例、下のリンクにはタスク生成可能な前処理の内容がリストアップされています。ここでもリストアップすると

- テーブル配列の生成
- データ平滑化
- 外れ値の除去
- 欠損データの除去
- トレンド除去
- 極値の検出
- 不連続点（？）の検出

# groupfilter関数
https://jp.mathworks.com/help/matlab/ref/double.groupfilter.html

　テーブル配列にフィルタを適用できる関数です。scatter関数とかでクラスごとにデータを分割してプロットする際に使えそう。

# tiledlayout関数とnexttile関数
https://jp.mathworks.com/help/matlab/release-notes.html?searchHighlight=%22lay%20out%20a%20tiling%20of%20multiple%20plots%20within%20a%20figure%22&s_tid=doc_srchtitle

　tiledlayout関数とnexttile関数自体は前からあるsubplotよりも使い勝手のよさそうな表分割用の関数ですが、ラベルや数値の表示位置などにありがたいオプションが付き、リンク先の様なきれいなグラフの書き方を楽々に表示できるようになったみたいです。

# 座標軸の保存・コピー
https://jp.mathworks.com/help/matlab/release-notes.html#mw_43869aeb-aa66-42f2-963e-b36fecb32427

　axesツールバーを使って、座標軸単位での図・PDFファイルとしての保存、pngイメージとしてのクリップボードへのコピー、ベクター形式としてのクリップボードへのコピーができるようになりました。

 　axesツールバーについてはこちらの例を[参照](https://jp.mathworks.com/help/matlab/ref/axtoolbar.html)

# 関数の入力の型指定
https://jp.mathworks.com/help/matlab/release-notes.html#mw_945f14f4-10fa-4f11-bab3-dba68e7bec1a

　やっと来たかって感じです。functionにargumentブロックをぶっこむことによって、if ~isなんちゃらって書かなくても型の検証ができるようになりました。ある意味、一番のハイライト。詳しくは[こちら](https://jp.mathworks.com/help/matlab/matlab_prog/function-argument-validation-1.html)を参照。

# 16進数と2進数
https://jp.mathworks.com/help/matlab/release-notes.html#mw_601d9180-2748-4660-a8d6-e0e1aed1d795

　ヘキサデシマル表記とバイナリ表記が使えるようになりました。0xf1とか0b11010001とかみたいな書き方です。こちらも詳しくは[こちら](https://jp.mathworks.com/help/matlab/matlab_prog/specify-hexadecimal-and-binary-numbers.html)で。
