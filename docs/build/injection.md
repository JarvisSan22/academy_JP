---
id: injection 
title: Build an Injection Machine 
sidebar_label: Injection 
---

<div class="videocontainer">
  <iframe width="800" height="400" src="https://www.youtube.com/embed/qtZv96ciFIU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> 
</div>
<style> 
:root { 
  --highlight: #f29094; 
  --hover: #f29094; 
} 
</style> 
<div class="videoChapters">
<div class="videoChaptersMain">

# 射出成形機を作る 
### この機械は何ですか？ 

射出成形機は高精度で短時間の生産が可能だが、金型の設計や製作に手間がかかる。細断されたプラスチックがホッパーに入り、加熱され、長いバレルを通って金型に押し込まれる。樽の中で色を混ぜ合わせると、出力される色は予測できないことが多く、美しい（そして驚くような）模様ができ、世界にひとつだけの製品を作ることができます。 
> プロからのアドバイス：良い金型に投資しましょう。良い型、良い出力 :) 
> Pro-tip: A new improved version of the injection machine which can be disassembled and has some additional safety features can be found in the [how-tos](https://community.preciousplastic.com/how-to/injection-machine---designed-for-disassembly). If you are building a new one consider taking a look at this one before ordering parts. 
</div> 
<div class="videoChaptersSidebar">

### ビデオ・チャプター 
- 00:07 はじめに 
- 00:43 ホッパー 
- 02:01 バレル 
- 03:58 ノズル 
- 04:53 フレームワーク 
- 06:55 エレクトロニクス 
- 10:30その仕組み 
</div> 
</div> 

# 技術情報 
📓 Type | Injection 
--- | --- 
💎 Version | 1.0 
💰 Price new material in NL | +/- €300 
💰 Price scrap material in NL | +/- €150 
⚖️ Weight | 23 kg 
📦 Dimensions | 830 x 700 x 1300 mm 
⚙️ Barrel volume | 150 cm³ 
⚙️ Leverage | 3 
⚙️ Injection pressure | 45 bars 
⚙️ Max mould size | 360 x 330 mm 
⏱ Injections p/h | 10 - 30     
🔌 Voltage | 220V     
⚡️ AMP | 2.6A 
| ♻️ Input Flake Size                   | Medium, Small  | 
![Injection machine](assets/build/injection.jpg) 

# 3Dモデル 
<iframe width="500" height="500" src="https://b2b.partcommunity.com/community/partcloud/embedded.html?route=embedded-viewer&name=Injection+Basic+V2.0&model_id=96645&portal=b2b&noAutoload=true&autoRotate=false&hideMenu=true&topColor=%23dde7ed&bottomColor=%23ffffff&cameraParams=false&varsettransfer=" frameborder="0" id="EmbeddedView-Iframe-96645" allowfullscreen></iframe> 

# 必要な機械と技術 
Build Injection  | Machines needed | Skills needed 
--- | ---| --- 
<img style="margin-left: 0;" src="../assets/build/thumb-injection.jpg" width="100"/>  | - Drill press <br> - Welding machine (not specific) <br> - Angle grinder | - Welding (intermediate) <br> - Assembling (intermediate) <br> - Electronics (intermediate) 
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
- ホッパー・タブ周辺の溶接には注意してください。熱で簡単にバレルが歪み、完璧なスライドが台無しになります。 
- 断熱バレルカバーを追加すれば、効率が上がり、使用者が誤って熱いバレルに触れる可能性も減る。   
- 建築の際、レバーは四角い形状のものより円形の形状の方が強度が増します。そのため、曲げる可能性が低くなります。 
# ♻️ 入出力 
<b>タイプ：</b> HDPE、LDPE、PP、PS<br> 
<b>生産量：</b>型によって異なるが、1時間あたり10～30本<br>。 

# ⚙️ 走行＆メンテナンス 
射出成形機を使えば、美しく安定した製品を非常に効率的に作ることができますが、金型を作るなど、前もって少し手間がかかります。金型が精密であればあるほど、生産はより簡単で合理的になります。簡単なヒントをいくつか： 
### スタートアップ 
1.本機の電源を入れ、温度を希望の温度より20度高く設定する。レバーが一番低い位置にあることを確認する。 
2.少なくとも20分間待つ。 
3.温度を下げ、目的のプラスチックでバレルを満たす。 
4.プラスチックが溶けるまでさらに15分待つ。最初のプラスチックは、マシンをすすぎ、前のセッションのプラスチックを取り除くために使用される。 
5.機械からプラスチックの最初のバッチを押し出す。 
6.これでマシンは生産準備が整った！ 
### 生産 
1.マシンが温まり、金型を使用する準備が整いました。 
2.樽に選んだプラスチックを入れる。 
3.バレルのレバーを押す。 
4.5～10分ごとにレバーを引き上げ、プラスチックを追加する。 
5.少なくとも10分待つ。 
6.今度は金型だ。底にある真鍮のネジを外す。 
7.金型をねじ込む（手早くしないとプラスチックが流れ出てきます！）。 
8.金型が機械に固定されたら、レバーを可能な限り引き下げる。 
9.金型を機械から外します。 
10.レバーを引き上げる。 
11.真鍮ネジを所定の位置にねじ込みます。 
12.新しい製品を充填する。 
13.型を冷ます。 
14.型が冷めたら開ける。 
> プロからのアドバイス：プラスチックの種類にもよりますが、レバーを引き下げるには1人か、場合によっては2人が必要です。 
金型に注入する前に、金型の全領域を満たすために、バレル内のプラスチックが完全に溶けていることを確認してください。そのためには、機械を通常より数度高く運転し、プラスチックが完全に溶けていることを確認する。 
### クールダウン 
1.マシンの電源を入れたら、バレルを完全に空にしてください。 
2.レバーを下げきった状態でマシンを離れる。 
3.マシンの電源を切る。 
### 使用上のヒント 
1.プラスチックが高温であればあるほど、最終製品のヒケは大きくなる。 
2.まだ温かいうちにプラスチックから型を取り除く。 
3.金型に離型剤を使う。 
4.注入するたびに少しずつプラスチックを加えながら、常にバレルをプラスチックで満杯にしておく。 
5.射出機での作業が終わったら、バレルからプラスチックを空にする。 
6.効率的なプロセスを作るには、一度マシンを起動させたら数時間稼働させることが望ましい。 
# トラブルシューティング 
* バレルの先端でプラスチックが詰まり、より高い圧力をかけても出てこない場合は、ノズルヒーターの温度を上げてプラスチックを完全に溶かし、ブロックを解放してください。 
このような場合は、型を軽く再加熱してプラスチックを柔らかくし、離型しやすくする。 
# 🌦 長所と短所 
Pros | Cons 
--- | --- 
Easy to manufacture     | Process can be tedious| 
Runs on 220V | Only a small amount of waste recycled| 
Relatively cheap || 
Batch production || 
# 🌎 コミュニティによって建設された 
<div class="j-slideshow">

![Community Shredder](assets/Build/community/community-injection4.jpg) 

![Community Shredder](assets/Build/community/community-injection1.jpg) 

![Community Shredder](assets/Build/community/community-injection2.jpg) 

![Community Shredder](assets/Build/community/community-injection3.jpg) 

![Community Shredder](assets/Build/community/community-injection5.jpg) 

</div> 

# 🙌 役立つリンク 
- [How-to: Injection Machine - Designed for disassembly](https://community.preciousplastic.com/how-to/injection-machine---designed-for-disassembly)<br> 
- アップグレード：クイックリリースモールドを作る](https://community.preciousplastic.com/how-to/make-a-quick-release-opening-system-for-injection-moulds)<br> 
- ハック：[ベンチトップ・インジェクター](https://davehakkens.nl/community/forums/topic/benchtop-smaller-machines/)<br> 
- ハック：[インジェクションノズルの改良](https://davehakkens.nl/community/forums/topic/injectionextrusion-nozzle-refinement/) 
- ハウツー：[カラビナ](https://community.preciousplastic.com/how-to/make-a-carabiner-cnc-vs-lasercut)<br> 
- ハウツー：[クイックリリース](https://community.preciousplastic.com/how-to/make-a-quick-release-for-the-extrusion-machine)<br> 
- ハウツー：[鋳造アルミ型](https://www.youtube.com/watch?v=5LhHUBz9uL0)<br> 
- ハウツー：[CNC iPhoneケース型](https://www.youtube.com/watch?v=ZYFoWP-3MYE)<br> 
- ハウツー：[ジオデシック・ドーム](https://community.preciousplastic.com/how-to/build-a-geodesic-dome)<br> 
- ハウツー：[プレシャス・プラスチック・モナッシュ・マシン](https://www.preciousplasticmonash.com/download-kit)<br> 
- ハウツー：[ハンドプレーン](https://community.preciousplastic.com/how-to/make-a-handplane-simple-mould)<br> 
- ハウツー：[ほうきハンガー](https://community.preciousplastic.com/how-to/make-a-broom-hanger)<br> 
- 開発：[ピランハクランプの裏話](https://davehakkens.nl/community/forums/topic/the-story-behind-the-piranhaclamp/)<br> 
  
**助けが必要な場合、質問がある場合、孤独な寒いワークスペースで話せる人を探している場合。

Discordの[#build](https://discordapp.com/invite/XQDmQVT)チャンネルへどうぞ。

ここでは機械についてオタクな話をします。 
