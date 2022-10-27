# Cluster World Tools
## 概要
CCKでのワールド制作を便利にするエディタ拡張です。

## 導入方法
unitypackageをインポートしてください

## 使い方（メニュー機能）
上部メニュー「WorldTools」から利用できる機能です。

### Webトリガー生成（かんたん）
シーン内からboolとsignal形式のKeyの一覧を表示し、選択してWebトリガーを生成しJSONに書き出すことができます。

### Webトリガー生成（詳細）
詳細な設定をしてWebトリガーを生成しJSONに書き出すことができます。
手入力のほか、ギミックコンポーネントのついたオブジェクトを読み込むことでいくつかの項目を自動入力できます。
既存のJSONを読み込むこともできます。

### レイヤー自動設定
CCKで利用できるレイヤーを自動で設定します。

### トリガーモニター
プレビュー実行中にトリガーの値を確認できます。
Key検索やアイテム検索で抽出して表示することもできます。

### テクスチャインポート設定
テクスチャインポート時にサイズ上限とモバイルでの圧縮形式を自動で設定します。
PC・モバイル別のサイズ上限と、モバイルでの圧縮品質を選択できます。

### 改善チェック
よくある不具合・エラーの原因をチェックしてConsoleに表示します。
一部は自動修正することができます。

## 使い方（その他の機能）

### 基本オブジェクト作成
GameObjectメニューからSpawnPoint, DespawnHeight, MainScreenを作成できます。

### Audio Listener自動削除
Camera設置時などに追加されるAudio Listenerコンポーネントを自動で削除します。
