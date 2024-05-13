---
id: compression 
title: Build an compression Machine 
sidebar_label: Compression 
---
<div class="videocontainer">
  <iframe width="800" height="400" src="https://www.youtube.com/embed/ogI8kt0w43Y" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> 
</div> 
<style> 
:root { 
  --highlight: #f29094; 
  --hover: #f29094; 
} 
</style> 
<div class="videoChapters">
<div class="videoChaptersMain">

# 圧縮機を作る 

### この機械は何ですか？ 
コンプレッション・マシンは基本的に、プラスチックを加熱するためのキッチン用電気オーブンと、金型に圧力を加えるための圧縮機構（カージャック）を備えている。工程は他のプレシャス・プラスチックの機械より遅いが、その分大きな型を使うことができる。シートや形状のような原料を作り、それをさらに加工して新しい製品を作ることができ、プラスチックに特殊なフレークのような外観を与えることができる（見た目は素晴らしい！）。 
> アドバイス：圧縮機はテストや試用には適しています。しかし、安定した生産には押出成形機か射出成形機をお勧めします。 
</div> 

<div class="videoChaptersSidebar">

### ビデオ・チャプター 
- 00:00 はじめに 
- 00:39 オーブンを作る 
- 03:51 フレームワーク 
- 04:55 プレス体制 
- 08:02 電子 
- 11:21 その仕組み 
</div> 
</div> 

# 技術情報 
📓 Type | Compression Machine 
--- | --- 
💎 Version | 2.0 
💰 Price new material in NL | +/- €350 
💰 Price scrap material in NL | +/- €150 
⚖️ Weight | 30 kg 
📦 Dimensions | 500 x  590 x 1590 mm 
⚙️ Compression | 2t car jack 
🔌 Voltage | 220V 
⚡️ AMP | 2.6A 
♻️ Input Flake Size  | Medium, Small  | 
# 3Dモデル 
<iframe width="500" height="500" src="https://b2b.partcommunity.com/community/partcloud/embedded.html?route=embedded-viewer&name=Compression+Basic+V2.0&model_id=96647&portal=b2b&noAutoload=false&autoRotate=false&hideMenu=true&topColor=%23dde7ed&bottomColor=%23ffffff&cameraParams=false&varsettransfer=" frameborder="0" id="EmbeddedView-Iframe-96647" allowfullscreen></iframe> 

# 必要な機械と技術 
Build Compression  | Machines needed | Skills needed 
--- | ---| --- 
<img style="margin-left: 0;" src="../assets/build/thumb-compression.jpg" width="100"/>  | - Drill press <br> - Welding machine (not specific) <br> - Angle grinder | - Welding (intermediate) <br> - Assembling (intermediate) <br> - Electronics (intermediate) 

# ⚡️ 電子ボックス 
本機内部の電気部品の説明。詳細と回路図はダウンロードキットにあります。 
<b>PIDコントローラー：</b>マシンの頭脳で、希望の温度を設定できます。PV（ポイント変数）がSV（設定値）に一致するまで、ヒーターに電力を送ります。これは、熱電対とSSRからの読み取り値を使用して行われます。 
<b>SSR:</b> ソリッドステートリレーは、（PIDからの）信号に応じて開閉する電子「スイッチ」です。 
<b>熱電対：</b>基本的には温度計。 
<b>バンドヒーター：</b>パイプの周囲に取り付ける発熱体。 
<b>電源スイッチ：</b>メカニカルスイッチ。 
<b>LED インジケーター:</b> 電源が入ると光る LED (電源スイッチによく付いています)。 
<b>電源ケーブル：</b>一般的な家庭用電源ケーブル。 
> プロからのアドバイス：ここに[エレクトロニクスに関する良いフォーラム・トピック](https://davehakkens.nl/community/forums/topic/the-big-electronics-topic/)がある。 

# 🛠作業中のヒントとコツ 

- 中古やスクラップのオーブンを探す。 
- オーブンへの穴は、必要な大きさだけ開けるようにする。そうすれば断熱材を節約できる。 
- これらのプランに飛び込む前に、Compression v2.1のアップデートをご覧ください。 
- 
# ♻️ 入出力 
<b>タイプ：</b> HDPE、LDPE、PP、PS<br> 
<b>生産量：</b> 40分間に1個。金型によるところが大きい<br>。 

# ⚙️ 走行＆メンテナンス 
コンプレッションは理解しやすく、適切に使いこなせば非常にパワフルだ。ほとんどの場合、一人で操作できる。繰り返しになるが、制作工程は金型と型作りに非常に関係している。正確な型があれば、美しい製品を作ることができます。私たちが提供する金型は非常に基本的なものなので、誰でもそのプロセスを理解することができますが、私たちはあなたやチームが、あなたの地域で役立つ新しい金型を作ることに目を向けることを強く勧めます。 
### 圧縮の操作方法 
### スタートアップ 

1.オーブンのスイッチを入れ、希望の温度に設定する。 
2.希望の温度になるまで20分待つ。 
### 生産 

1.ムードに必要な材料の量＋20％を量る。 
2.型に材料を詰める。 
3.型の上部をプラスチックの上に置く。 
4.型をオーブンに入れる。 
5.15分間放置する。 
6.オーブンの中で型を180度回転させる。 
7.さらに15分間放置する。 
8.型を圧縮する。 
9.オーブンから型を取り出す。 
10.型にクランプをつけ、圧力を保つ。 
11.別の型をオーブンに入れる。 

### クールダウン 

1.オーブン内部の溶けたプラスチックを清掃する。 
2.使用中のヒントとコツ 
3.プラスチックが溶けるまで温めてから圧力をかけるとよい。 
4.焦らず、プラスチックが型の中で完全に溶けていることを確認する。

# トラブルシューティング 
- プラスチックが金型の片側から溢れる。これは多くの場合、金型、プレスプレート、またはオーブン自体の間のずれの結果です。できるだけすべてが地面と平行になるようにしてください。 
- 製品がモールドに付着している。型をやわらかく温めて離型しやすくするか、離型剤を塗ってみてください。 
- 
# 🌦 長所と短所 
Pros | Cons 
--- | --- 
Easy to manufacture     | Process is slow 
Can use found oven | Mould size limited to oven 
Runs on 220V |  Not energy efficient 
Bigger products than injection    | 
Unique patterns |   

# 🌎 コミュニティによって建設された 

<div class="j-slideshow">

![Community Compression](assets/Build/community/compression3.jpg) 

![Community Compression](assets/Build/community/compression1.jpg) 

![Community Compression](assets/Build/community/compression2.jpg) 

</div> 

# 🙌 役立つリンク 

- ⭐️Upgrade: [圧縮 V2.1](https://community.preciousplastic.com/how-to/compression-machine-21) 
- ハック：[圧縮](https://davehakkens.nl/community/forums/topic/machine-development-compression-oven/) 
- ハック：[太陽電池式溶解マシン](https://davehakkens.nl/community/forums/topic/solar-powered-melting-machine/) 
- ハウツー：[壁掛け時計](https://www.youtube.com/watch?v=e_jqIvSFfI4)<br> 
**助けが必要な場合、質問がある場合、孤独な寒いワークスペースで話せる人を探している場合。Discordの[#build](https://discordapp.com/invite/XQDmQVT)チャンネルへどうぞ。ここでは機械についてオタクな話をします。 
