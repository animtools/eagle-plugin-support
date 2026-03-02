# Eagle プラグインセット - クイックスタート

Eagle に VideoTileKun 系プラグインを入れて使うまでの最短の流れです。

---

## 1. ダウンロード

1. [Releases](https://github.com/animtools/eagle-plugin-support/releases) を開く。
2. 最新リリースの **VideoTileKun-plugins-vX.Y.Z.zip**（またはプラグイン別 zip）をダウンロードする。
3. zip を解凍する。

---

## 2. Eagle にインストール

1. Eagle を起動し、**設定 → プラグイン** を開く。
2. **「プラグインフォルダを開く」** でフォルダの場所を確認する。
3. 解凍したプラグインフォルダ（VideoTileKunInspector / VideoTileKunPlayer / VideoTileKunService）を、そのプラグインフォルダ内にコピーする。
4. 全プラグインで **FFmpeg** が必要です。Eagle のプラグイン一覧から FFmpeg をインストールしていなければ、ここでインストールする。
5. Eagle を再起動する。

---

## 3. 初回の流れ（Inspector）

1. Eagle で動画ファイルを選択する。
2. インスペクタに **VideoTileKun Inspector** のパネルが表示される。
3. グリッド数・間隔・サイズを設定し、**タイル生成** ボタンでサムネイルを生成する。
4. タイルにホバーすると、その位置から動画をプレビュー再生できる。

---

## 4. 初回の流れ（Player）

1. メニューや右クリックから **VideoTileKun Player で開く**（または同等の操作）でプレーヤーを起動する。
2. 動画の再生・一時停止、タイムライン上のマーカーでジャンプができる。
3. タイルビューペインでサムネイルを確認しつつ再生できる。

---

## 5. 初回の流れ（Service）

1. プラグインを入れて再起動すると、動画をライブラリに追加したときに **自動でタイル生成** のキューに乗る（設定で無効化も可能）。
2. Inspector の設定（グリッド・間隔など）に合わせてタイルが生成される。
3. 生成状況は Eagle の通知やプラグインの表示で確認できる。

---

## 6. 困ったとき

- **インスペクタにタイルが出ない**: 全プラグインで FFmpeg が必要です。FFmpeg プラグインが入っているか、動画形式が対応しているか確認する。
- **プレーヤーが開かない**: プラグインフォルダに VideoTileKunPlayer が正しく入っているか、Eagle を再起動したか確認する。
- **その他**: [Issues](https://github.com/animtools/eagle-plugin-support/issues) から不具合報告・質問ができます。

---

## 関連

- [README（概要・含まれるプラグイン）](./README.md)
- [USER_GUIDE（各プラグインの使い方）](./USER_GUIDE.md)
