# AozoraEditor
青空文庫エディタ

https://kyukyunyorituryo.github.io/AozoraEditor/

TinyMCEとturndownとAozoraJavaScriptParser
# 使い方
　基本的な操作はブログなどのエディターと同じ感覚で使える。「青空文庫変換」ボタンを押すことで下のテキストエリアに青空文庫形式として出力する。「エディターへ出力」ボタンを押すと青空文庫形式を読み込んでエディター側に表示する。

## テキストの貼り付け
　文章やHTMLやワードなどからコピー＆ペーストでテキストを張り付ける。

## ルビ
　ルビをつけたい漢字などを選択してから「ルビ」ボタンを押すとふりがなを振ることできる。

## 縦書き
　縦書き表示で確認したい場合は「縦書」ボタンを押す。するとエディターのテキストエリアが縦書きになる。もう一度押すと横書きに戻る。この機能はクロームブラウザでしか機能していない。

## 縦中横
　縦中横は半角文字が縦書き時に横倒しになるのを縦にする。12月12日の12を選んで「縦中横」ボタンを押すと縦中横になる。縦書きモードにした方が確認がしやすい、標準では縦中横になっている。

## その他
太字、斜体、下線、取り消し線、下付け、上付け、エディターとしての操作で編集が可能。

＜＞はHTMLコードが見れる。HTMLで加工して保存時に青空文庫形式に変換している。

## 使用しているライブラリ ##

TinyMCE　https://www.tiny.cloud/

turndown　https://github.com/mixmark-io/turndown

html2aozora　https://github.com/kyukyunyorituryo/html2aozora

AozoraJavaScriptParser　https://github.com/gearsns/AozoraJavaScriptParser