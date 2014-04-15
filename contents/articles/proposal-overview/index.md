---
title: ハイパー・ピクトグラム整備事業の提案
description: 「検索性向上のためのタグ付け」と「ローコストな多言語化」が同時に達成できる「ハイパー・ピクトグラム整備事業」という公共事業を提案します。
author: ishibashi
date: 2014-04-15
template: article.jade
---

ウェブ上の観光情報には「施設情報」と「イベント情報」があります。それらに「ハイパー・ピクトグラム」を貼ることで、「検索性向上のためのタグ付け」と「多言語化」が同時に達成されます。そのような観光情報インフラを実現するために、「ハイパー・ピクトグラム整備事業」という公共事業を提案します。

<span class="more"></span>

なお、「ハイパー・ピクトグラム」は造語です。


ハイパー・ピクトグラムは多言語キャプションを持つ
----------------------------------------

![温泉 / Hot spring][3]

これは交通エコロジー・モビリティ財団が提供している「[標準案内用図記号][2]」のなかの「温泉」のピクトグラムです。このピクトグラムには、日英併記で「温泉」「Hot spring」というキャプションだけがつけられています。それ以外の言語情報はありません。

このピクトグラムを、リンクト・オープン・データ (LOD) の考え方でデジタル化および多言語化すると、次のようになります。

あらかじめ中国語（繁体）の「溫泉」や、韓国語の「온천」といったキャプションを用意しておきます。そのうえで、このピクトグラムを施設やイベントに「貼ります」。そうすることで、それらの施設やイベントをスマートフォンなどの端末で閲覧したとき、「ユーザーの言語に応じたキャプション」が表示されます。

つまり、ある施設やイベントに「温泉」のハイパー・ピクトグラムを「貼る」だけで、多言語で「温泉」という意味付けがなされたことになります。「貼る」作業は日本語のみで行うことができます。特殊な能力は必要ありません。

また、各国語のキャプションを用意する作業は、誰かが一度だけ行えばよいです。つまり、社会共通資本として公共事業で整備しておき、それを全国の企業・自治体が無償で利用できるようにするといった構想に向いています。


パーソナル・デバイスに向けて多言語化するメリット
----------------------------------------

デジタル端末はユーザー毎に言語を設定でき、それにあわせた情報提供することが可能です。したがって、デジタルなピクトグラムでは「ユーザーの言語にあわせたキャプションを出す」ことができます。現実のサイン（看板など）には空間的制約がありますから、あまり多くの言語で説明することはできません。しかし、「ユーザーが持っているデジタル端末に、そのユーザーの言語で情報提供する」ならば、そのような制約とは無縁です。

また、ピクトグラムにスマートフォン等を「かざす」ことで、そのユーザーの言語でキャプションが出るようにすることも可能です。例えば[グーグル・ゴーグル (Google Goggles)][4]という画像認識アプリは、2011年にメトロポリタン・ミュージアムと提携して、その収蔵作品を高い精度で画像認識できるようにしました。ハイパー・ピクトグラムをスマートフォンに高精度で認識させることも技術的にはそれほど難しくないと考えられます。


自治体等の現場における効果
----------------------

ハイパー・ピクトグラムによって、自治体職員等の観光情報作成担当者が翻訳の苦労から開放されます。彼らは日本語でピクトグラムを取り扱うだけでよくなります。労なくして観光情報の多言語化が達成できるのです。

翻訳・多言語化のコストは、一回の公共事業に一本化できます。日本中の自治体や企業が個別に翻訳作業をする必要はありません。つまり、その分のコストが浮きますので、とても効率的に全国の観光情報を多言語化することができます。

ある施設に「温泉」のハイパー・ピクトグラムを「貼る」という操作を具体的にイメージしてみましょう。それは「ウェブサイトのコンテンツ管理システム (CMS) の編集画面で、ピクトグラム（アイコン）を選択する操作」になるでしょう。具体的なユーザー・インターフェイスはこれから提案していきますが、例えば「温泉」というキーワードでピクトグラムを検索する機能も便利でしょう。ピクトグラムを「貼る」のは、とても簡単な操作になるはずです。


ハイパー・ピクトグラムは「タグ」でもある
---------------------------------

ハイパー・ピクトグラムは、リンクト・オープン・データとして実現されます。つまり、「ピクトグラムを貼る」という操作が、システムの中では「ピクトグラムにリンクする」という処理になります。

そのリンクを逆に辿ることで、検索にも利用できます。例えば「温泉」のピクトグラムを貼った施設やイベントを検索することができます。さらには「車いす可」「英語説明あり」の「温泉」を探すといったことができます。つまり「複数のピクトグラムで検索条件を絞り込む」ことができます。いわゆる「AND検索」です。（※専門的にはRDFとSPARQLという技術を使う想定です）


観光情報の共通語彙基盤としてのハイパー・ピクトグラム
-------------------------------------------

デジタル・ピクトグラム化すべき「観光情報の共通語彙」は数百あると考えられます。例を挙げると「駐車場あり」「禁煙」「車椅子可」「音声案内あり」「英語応対可」「クレジットカード可」などが考えられます。

このように「共通語彙」を「インフラ（基盤）」とみなして整備していく考え方は、独立行政法人情報処理推進機構 (IPA) の「[共通語彙基盤構築プロジェクト][5]」と共通しています。


[1]: https://www.mlit.go.jp/kankocho/news03_000100.html
[2]: http://www.ecomo.or.jp/barrierfree/pictogram/picto_top.html
[3]: hot_spring.png
[4]: http://www.google.com/mobile/goggles
[5]: https://www.ipa.go.jp/osc/20131120.html