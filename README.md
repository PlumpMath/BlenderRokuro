# BlenderRokuro
　メッシュオブジェクトを回転させ続けます。ろくろで作る器のような形状を作る時に便利です。

## 使用条件
* Blender 2.78 以上

## 機能
* 回転軸の選択
* 回転方向の選択
* 一周の分割数の選択
* 時間のステップ数の選択

## 使い方
1. アドオンをインストールして有効にします
2. メッシュを選択してスカルプトモードにします
3. ツールシェルフに "Rokuro" パネルが開きます
4. お好みの設定をして "Enable Rokuro" ボタンを押すと選択したメッシュが回転し始めます
5. "Disable Rokuro" ボタンを押して終了します

　Start, End 値で一周を何分割するか、Step 値で１フレーム当たりいくつ進めるかが決まります。

(オマケとしてテクスチャペイントモードでも動作します)

## 上手く作るコツ
* Stroke Method で Airbrush を有効にする
* Symmetry / Lock で Mirror を切る
* Brush で Front Faces Only を有効にする
* 厚みは後で Solidify などでつける
* あまり早く回さない

## ライセンス
[MIT ライセンス](http://takuro.mit-license.org/)

## 既知のバグ
* 回転前の Rotation 値が戻らないことがあります
