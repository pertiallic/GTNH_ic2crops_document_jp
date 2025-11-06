# GTNH IC2農業101（日本語）

## はじめに

このドキュメントは[GregTech: New Horizons](https://www.gtnewhorizons.com/)におけるIC2農業について、やり方をまとめたドキュメントです。

自分用に書いていますが、わからないところや間違っているところがあれば気軽に[issue](https://github.com/pertiallic/GTNH_ic2crops_document_jp/issues)の方に書いておいてください。すぐに確認してほしければ、discordのpertiallicまで連絡してください。

IC2農業は一見複雑なように見えて、やることがわかってしまえばかなり単純です。ただ、交配がうまくいくかは運なので忍耐力が試されるかもしれません。とにかく、一番大切なことは楽しむことです。

<font size="7">HAVE FUN!</font>

Fiction0496(pertiallic)

<div style="page-break-before:always"></div>

### 目次

1. [はじめに](#はじめに)
1. [用意する道具](#用意する道具)
1. [作物](#作物)
    1. [作物の例](#作物の例)
1. [交配](#交配)
1. [雑草](#雑草)
1. [更新履歴](#更新履歴)

<div style="page-break-before:always"></div>

## 用意する道具

* Crop：大量に必要になります。
* Plant Lens：右クリックで未知の作物の名前や生育段階などを調べることができます。

    (これ以下のは最悪なくてもいいです)

* Hydration Cell：右クリックで水やりができます。
* Fertilizer：右クリックで肥料を与えることができます。
* Spade(もしくはWeeding Trowel)：右クリックで簡単に雑草を取り除けます。
* Weed-EX：しばらく雑草を出なくできます。

<figure>
    <img src="./images/items.png"
         alt="アイテム達">
    <figcaption>左から Crop, Plant Lens, Hydration Cell, Fertilizer, Spade, Weeding Trowel, Weed-EX</figcaption>
</figure>

<div style="page-break-before:always"></div>

## 作物

耕地にCropを1個(1本？)おくと種や種袋が植えられるようになります。

バイオームや高度、周囲の状況、水やりされているか、肥料を与えられたかどうかなどで成長スピードが決まります。バイオームは湿地かジャングル、高度はY=124が最適です。

水やりや肥料はしばらくしたら効果がなくなるので定期的に水やりしたり肥料を与えたりしてください。

<figure>
    <img src="./images/crop_placed.png"
         alt="Cropが設置されている画像">
    <figcaption>設置されたCrop</figcaption>
</figure>

<div style="page-break-before:always"></div>

### 作物の例

ここにあげた作物はあくまでも一例です。  
GTNHには様々なIC2作物があり、生育条件が特殊なものもあるので、詳しくは *[ここ](https://gtnh.miraheze.org/wiki/IC2_Crops_List)* を参照してください。

#### 鉱石ベリー系

鉱石ベリーからは、インゴットなどの金属に加工できるベリーを収穫することができます。

十分暗い場所(明るさレベル10以下)でのみ成長し、生えている耕地の1ブロック下に対応する金属ブロックがないと最終段階まで成長しません。  
最後まで成長していなくても収穫できます。  
触れるとダメージを受けます。

<div style="page-break-before:always"></div>

## 交配

Cropを2個おくと交配するための場所になります。その場所の周囲4ブロックに交配したい作物を(完全に成長させた状態で)植えると交配することができます。 

交配のレシピはNEIで確認することができます。ただし、理想的な条件下で、ということらしいので、実際には交配できない可能性があります。

<div style="page-break-before:always"></div>

## 雑草

何も植えてない状態でCropを放置すると(1個か2個かにかかわらず)雑草が生えることがあります。

雑草は放置すると周囲のCropに侵食してそこにあった作物を破壊するので、見かけ次第抜く必要があります。

SpadeかWeeding Trowelで右クリックすると雑草を抜くことができます。また、Weed-EXを使うと雑草の発生を抑制することができますが、永遠ではありません。  
雑草が生えているCropを壊してもいいです。

<figure>
    <img src="./images/weed.png"
         alt="雑草">
    <figcaption>設置されたCropに生えている雑草</figcaption>
</figure>

<div style="page-break-before:always"></div>

## 更新履歴

>現在のバージョン：v2.0

### v2.0

更新：**2025/11/6**

-mdをpdfにしました  
-画像を追加しました  
-作物の例を追加しました  
-githubにあげるようにしました  
-表現をかなり修正しました

### v1.1

更新：**2025/11/5**

-表現を修正しました  
-署名を追加しました


### v1.0

更新：**2025/11/5**

-ドキュメントの作成
