# (1)Purpose 目的
I want to express all figures, graphs and formulas in letters! You should be able to do that without using Markdown.  
図やグラフや数式を、すべて文字で表現したい！　マークダウンを使わなくてもできるはずだ。  
  
Note:  補足
"GeoMathMonospace"   ->  Geometric and Math Symbols are Monospaced font.  
"GeoMathMonospace"   は、 Geometric and Math Symbols　の 等幅フォントから名付けてます。
  
  
# (2)Preferred font conditions 欲しいフォント 

No.|Target character<br>対象とする文字|sample
---|---|---
1|Ascii<br>英数字|ABC abc 123 
2|kana and Chinese character<br>仮名と漢字|いろは　イロハ　漢字
3|Geometry sign<br>幾何学記号|▲　■　〇
4|Mathematical Symbol<br>数学記号|∂　×　∇　

No.|conditions<br>条件
---|---
1|The border is continuous, not a chain line. <br>罫線が鎖線にならず連続
2|Half-width alphanumeric: Full-width character = 1:2 <br>半角英数：全角文字＝1:2
3|The aspect ratio of full-width characters is square.1:1　<br>全角文字の縦横比は正方形＝1:1
4|Lightweight License　<br>軽量ライセンス（改変可・商業・再配布可）

# (3)Method 方法
Based on the font 'migmix1m', the arrow symbols have also been modified aiming for monospaced fonts.  
等幅フォント「MigMix-1M」のregularをベースに、矢印記号をはじめとした幾何学記号や数学記号を等幅フォントに追加・修正しました。  

## Usage Data 利用したデータ 
- Font「MigMix1M 」のData

## Use Software フォント修正に使用したソフト
- メモ帳 (notepad.exe)
- 秀丸エディタ(Hidemaru editor)
- FontForge
- Visual studio code
- AutoCAD

## 作成するフォントの内容
項目|内容
:-: |:-: 
基盤フォント<br>Base fonts|MigMix-1M
基準文字<br>Standard letter|罫線素片<br>BOX DRAWING
基準文字太さ<br>Standard letter thickness|46
全角文字サイズ<br>Full-width character size|1000×1000
半角文字サイズ<br>Half-width character size|1000×500
文字隙間<br>Character gap|0
半角と全角の等幅比|1（英+数）:2（仮名+漢字+記号）


# (4)変更したフォント
文字|unicode番号<br>「&#x〇〇〇〇；」
:-: |:-:  
→  |2192 
←  |2190 
↑  |2191 
↓  |2193 
↔  |2194 
↕  |2195 
↰  |21B0 
↱  |21B1 
↲  |21B2 
↳  |21B3 
⇄  |21C4 
⇅  |21C5 
⇆  |21C6 
⇤  |21E4 
⇥  |21E5 
⍅  |2345 
⍆  |2346 
⍏  |234F 
⍖  |2356 
─  |2500 
│  |2502 
╭　|256D  
╮　|256E  
╯　|256F  
╰　|2570  
╱　|2571  
╲　|2572  
╳　|2573  
◉　|25C9
○  |25CB
●  |25CF
■  |25A0 
◇  |25C7 
◢  |25E2 
◣  |25E3 
◤  |25E4 
◥  |25E5 
◸　|25F8  
◹　|25F9  
◺　|25FA 
◿　|25FF 
⤒  |2912 
⤓  |2913 
⭰  |2B70 
⭱  |2B71 
⭲  |2B72 
⭳  |2B73 

# (5)Sample
## UML
### 入力元文字 Input letter
```
╭────╮
│クラス図│
╰────╯
┌─────────┐
│神戸住民　　　　　│
├─────────┤
│名前　　　　　　　│
│住所　　　　　　　│
│電話番号　　　　　│
│年齢　　　　　　　│
├─────────┤
│通勤する（）　　　│
│買い物に行く（）　│
└─┬───────┘
　　│0..*
　　│
　　│
　　◇1
┌─────────┐
│会社　　　　　　　│
├─────────┤
│会社名　　　　　　│
│住所　　　　　　　│
│電話番号　　　　　│
├─────────┤
│所属する（）　　　│
│脱退する（）　　　│
└─────────┘
```

### 出力結果　Output
![UML](https://github.com/kobe2018/migmix1m4Fig/blob/master/Fig_sample/uml.png "UML図")



## 電気回路
```
　┌────────●──┐
　│　　　　　　　　│　　│┌─
　⦚　　　　　　　　│　　└┤
　⦚　　　　　　　　│　　　│
　│　　　　　　　├┘　　　┤
　●─　　　───┤
　│　　　　　　　├┐
　│　　　　　　　　⭳
　│
　│　　　　　　　　　●
　┷　　　　　　　　　　　╱
─┬─　　　　　　　　　╱
　│　　　　　　　　　●
　└─⟛───────┘
　　　

　　　　I
　　　──→
　　┌─────●───●───┐
　　│　　　　　│　　　│　　　│
V ─┴─　　　　⦚　　　⦚　　　⦚
　　┯　　　　　⦚　　　⦚　　　⦚
　　│　　　　　│　　　│　　　│
　　└─────●───●───┘
```

## 材料力学
```
Ｐ
　↓　　　　　　　│
　┌───────┤
Ａ│┄┄┄┄┄┄┄│┄┄→ｘ
　└───────┤
　　　　　　　　　│

⎾　⎿　⏉　⏊　⏋　⏌　＿　￣

　　 ＿＿＿＿＿＿＿ │
　　↓↓↓↓↓↓↓↓│
　　⎾￣￣￣￣￣￣￣⏋
　┄│┄┄┄┄┄┄┄│┄┄→ｘ
　　⎿＿＿＿＿＿＿＿⏌
　　△　　　　　　　│
　　　　　　　　　　│
```

## 機械力学
```
┌──────┐
│　　ｍ　　　│
└─┬──┬─┘
　　⦚　│┴│
　　⦚　└┬┘
──┴──┴──
```


## 配列
```
⎧⎫
⎨⎬
⎩⎭

⎧1,2,3⎫
⎨4,5,6⎬
⎩7,8,9⎭
```


## 文字数字
▗▌　│▀▌　│▀▌　│▌▌　│▛▘  │▛▘  │▛▌  │▛▌　│▛▌  │▛▌  
　▌　│▛▘　│▀▌　│▀▌　│▀▌  │▛▌  │  ▌  │▛▌　│▀▌  │▌▌  
　▘　│▀▘　│▀▘　│　▘　│▀▘  │▀▘  │  ▘  │▀▘　│　▘  │▀▘  

▞▖  │▛▖  │▛▌  │▛▖  │▛▘　│▛▘  │▛▌  
▛▌  │▛▖  │▌▖  │▌▌  │▛▘  │▛▘  │▌▖  
▘▘  │▀▘  │▀▘  │▀　  │▀▘  │▘    │▀▘  

▗▌▀▌▀▌▌▌▛▘▛▘▛▌▛▌▛▌▛▌  
　▌▛▘▀▌▀▌▀▌▛▌　▌▛▌▀▌▌▌  
　▘▀▘▀▘　▘▀▘▀▘　▘▀▘　▘▀▘  

