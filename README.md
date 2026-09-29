# Pythonプログラミング入門の教材

東京大学における[「Pythonプログラミング入門」](https://utokyo-ipp.github.io/course/)の教材を提供する公開レポジトリ．

## 4つの形式

* HTML版: <https://utokyo-ipp.github.io/>
* PDF版: <https://utokyo-ipp.github.io/IPP_textbook.pdf>
* Colab版: <https://colab.research.google.com/github/utokyo-ipp/utokyo-ipp.github.io/blob/master/colab/index.ipynb>
  * HTML版にある ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) から対応するノートブックを開ける．
* Jupyter版: <https://utokyo-ipp.github.io/IPP_textbook.zip>
  * ローカルでipynbを実行するためのファイル一式．

## 自動翻訳

本教材は日本語で提供されていますが，ブラウザの自動翻訳機能を使うことで他言語でも閲覧できます．

* Chrome / Edge:
  * ページ上で右クリックして「日本語（またはページの言語）を翻訳」を選択
  * またはアドレスバーの翻訳アイコンを利用
* Google翻訳経由でHTML版を開く:
  * <https://translate.google.com/translate?sl=ja&tl=en&u=https://utokyo-ipp.github.io/>

※ 自動翻訳の結果は参考情報です．コード・用語の厳密な意味は原文（日本語）を優先してください．

## 本レポジトリの管理ポリシー

* 本レポジトリは，最新公開版の提供を目的としており，改訂履歴の提供は目的としていない．
  * 履歴は予告なく削除されることがある．
* 著作権管理の都合で，全てのpull requestは機械的にrejectされる．
  * ただし，提案を例示する手段として，pull requestを作成することは止めない．
* 誤植等の報告として，issueの作成は歓迎する．
  * 教材改訂の際に適宜反映する予定．

## ビルドとデプロイ

Jupyter版をソースとして，他の形式がビルドされている．
ビルドとデプロイは，[ipynb_deployer](https://github.com/satoshigeyuki/ipynb_deployer)によって自動化されている．
