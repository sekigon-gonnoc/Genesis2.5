# Genesis2.5ビルドガイド

## 必要なもの
- 時間
- 折れない心

## あると便利なもの
- マスキングテープ
- プレートマウントのスイッチ(10個くらい、組み立て中に取り外しやすいため)

## 行基板の組み立て
大体1時間くらいの工程です
1. IOエキスパンダをはんだ付けする  
 モールドの角が面取りされている側が1番ピン
1. ソケットをはんだ付けする
1. アドレス設定用ランドをジャンパする  
 左手1行目から順にV-D, V-C, V-G, D-V, D-C, D-G...という順にジャンパするのが標準です。  
 わからなくならないようにマジックでメモするとよいです。あとから補強基板を重ねるので雑に書いても隠れます。
 アドレス設定を間違えたとしてもソフト側で対応することはできます。
1. スイッチとキーキャップをとりつける  
四角いランドがある側が手前です
両サイドのスイッチはあとで一度取り外すのでマウントプレートのスイッチを仮止めするのがおすすめです

## 枠の組み立て
大体15分くらいの工程です
1. 底面用基板にピンヘッダをはんだ付けする
1. 底面用基板の余ったピンヘッダを切断する
1. TRRSジャックを側面用基板にはんだ付けする
1. 側面基板と底面用基板をはんだ付けする
  1. 仮組してマスキングテープで固定する
  1. 一か所ずつはんだ付けする  
 一つのピンヘッダについて4か所を一気にはんだ付けするのではなく、1か所ずつはんだ付けしていくと歪みにくいです  
 側面基板がしっかり設置し、ガタガタしないように気をつけてください

## 行基板の取り付け
色んなパターンを試してみるといつまでたっても終わりません。
自分が一番使いやすい傾斜を探しましょう
1. ピンヘッダの短いほうを側面基板の好きな位置に差し込む
1. 行基板を差し込む  
1. 満足のいく配置を探す  

## 行基板のはんだ付け
1. 側面側のピンヘッダを1か所ずつはんだ付けする
1. 両サイドのスイッチを取り外し、行基板側のピンヘッダを1か所ずつはんだ付けする  
 面倒くさがってスイッチを取り外さずにはんだ付けするとキーキャップやスイッチを溶かしてしまう恐れがあります
1. 干渉が発生しないことを確認出来たら、残りの部分もはんだ付けする
1. 補強用行基板を各行に重ね、ネジを通してナットで止める
1. 両サイドのスイッチを取り付ける
