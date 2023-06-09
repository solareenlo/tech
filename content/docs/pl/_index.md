---
weight: 2
title: "Programming Language"
bookFlatSection: false
bookCollapseSection: true
---

# プログラミング言語とは
- コンピュータに解釈できるようにつくられた人工言語.
- コンピュータへの指令であるプログラムを書くのに使われる.
- いろんな特徴を持っている.

## いろんな指標によるランキング
- [TIOBE Index](https://www.tiobe.com/tiobe-index/) (TOIBEによる検索エンジンによる各種プログラミング言語の話題度ランキング)
- [RedMonk](https://redmonk.com/data/) (RedMonkによるランキング)
- [Interactive: The Top Programming Languages 2019](https://spectrum.ieee.org/static/interactive-the-top-programming-languages-2019) (IEEEによる2019年度のランキング)
- [Interactive: The Top Programming Languages 2018](https://spectrum.ieee.org/static/interactive-the-top-programming-languages-2018) (IEEEによる2018年度のランキング)
- [PYPL PopularitY of Programming Language](http://pypl.github.io/PYPL.html) (PYPLによるGoogleによるチュートリアル検索ランキング)
- [madnight/githut](https://github.com/madnight/githut) (GitHub 上のコードを言語別に Pull Requests, Pushes, Stars, Issues の数で集計してくれているサイト)
- [Which programming language is fastest?](https://benchmarksgame-team.pages.debian.net/benchmarksgame/index.html)

## プログラミング言語の型
代表的なもの3つ

|種類|説明|特徴|
|---|---|---|
|手続き型|上から下まで単調なルールで文章を読むように動作する.|
|オブジェクト指向型| 「モノ」を組み立てるように表現して, コンピュータに動作をさせる.|設計より|
|関数型|数学の関数のイメージでデータに何かしらの処理をして答えを取得するように動作する.|コーディングより|

### オブジェクト型と関数型の共通点
- 関心毎にコードを集めて粗結合な部品を組み立てる．
- プログラムの分割（モジュール化）と組み立て（合成）を行う．

### オブジェクト指向型プログラミング
|原則|説明|
|---|---|
|カプセル化|自由なアクセスからデータを保護する仕組み|
|継承|再利用性を高めて, 冗長性を避けるための強力なツール|
|ポリモーフィズム|メッセージの送信側とメッセージの受信側が動的に決まる仕組み|

- オブジェクトは, オブジェクトに含まれるデータを操作する関数を有している.
- クラスはオブジェクトのインスタンスを作成するために使用されるテンプレート.
- OOPは冗長だが, 他のコーディングパラダイムに比べて読みやすい.
- オブジェクト同士のメッセージングによるプルグラミンぐ手法
- コード同士の依存関係を上手く管理したい
- 依存関係を上手く扱うことで変更に強いソフトウェアへ
  - DDD などの設計手法
- コードの分割
- コードの再利用を高め，利用しやすいインターフェースを提供する手法．

### 関数型プログラミング
|特徴|説明|
|---|---|
|参照透過性|その式をその式の値と置き換えてもプログラムの振る舞いが変わらない性質|
|カリー化|引数が1つの関数を返す引数が1つの関数|
|純粋関数|副作用のない関数|
|副作用|外部の状態を変化させる|
|高階関数|関数を引数に取ったり関数を返したりする関数|

- 副作用を出来るだけ使わないプログラミング手法
  - 副作用とは計算以外のこと
- 状態を排除する->文脈に依存しないコードへ
  - 読みやすくなる
  - バグが少なくなる
- コードの分割と合成
- モジュール性や並行性が高まり，テストや一般化が容易になる．
- 処理をより抽象的に扱う手法．

### 2020年以降のプログラミング言語の特徴
- 並列並行サポート
- 代数的データ型とパターンマッチ，無名関数
- 所有権
- などなど
- Reference: [オブジェクト指向言語と関数型言語](https://keens.github.io/slide/obujiekutoshikougengotokansuugatagengo/)
