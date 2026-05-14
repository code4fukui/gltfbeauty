# gltfbeauty

[
![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)
](https://code4fukui.github.io/gltfbeauty/)

テクスチャのリサイズと圧縮を行うことで、GLTF/GLBファイルをWeb公開に適した形に最適化するクライアントサイドのWebツールです。

## デモ

**[https://code4fukui.github.io/gltfbeauty/](https://code4fukui.github.io/gltfbeauty/)**

![gltfbeauty screenshot](https://code4fukui.github.io/gltfbeauty/gltfbeauty.png)

## 機能

- **テクスチャの最適化:** テクスチャをJPEG形式に圧縮し、品質の調整や指定した解像度（例: 1024x1024、2048x2048）へのリサイズが可能です。
- **フォーマット変換:** 出力ファイルを `.gltf`（テキストベース）と `.glb`（バイナリ）から選択できます。
- **バッチ処理:** 複数のファイルやフォルダ全体をドラッグ＆ドロップして、一度に処理できます。
- **クライアントサイド処理:** すべての処理はブラウザ上で直接行われます。サーバーへのファイルアップロードが発生しないため、プライバシーと高速性が保たれます。
- **カラースペース制御:** テクスチャにsRGBカラースペースを強制するオプションがあります。

## 使い方

1. [gltfbeauty デモページ](https://code4fukui.github.io/gltfbeauty/)を開きます。
2. `.gltf` または `.glb` ファイルを指定のエリアにドラッグ＆ドロップするか、「ファイルを選択」ボタンを使用します。
3. ファイルをドロップする前に、出力設定を行います:
    - **テクスチャサイズ:** テクスチャの最大幅/高さをピクセル単位で選択します。
    - **品質:** JPEGの圧縮品質を設定します（0.0〜1.0の値）。
    - **sRGB強制:** チェックを入れると、sRGBカラースペースが強制されます。
    - **glTF出力:** チェックを入れると出力が `.gltf` 形式に変換され、入れない場合は `.glb` 形式になります。
4. 変換が自動的に開始されます。単一のファイルは直接ダウンロードされ、複数のファイルは1つの `.zip` アーカイブとしてダウンロードされます。

## クレジット

- 作者: [Taisuke Fukuno](https://fukuno.jig.jp/) (@taisukef)
- コントリビューター: [@nknhb966](https://github.com/nknhb966)
- ベースプロジェクト: [GLTF.js](https://github.com/code4fukui/GLTF/)

## ライセンス

MIT License — 詳細は [LICENSE](LICENSE) を参照してください。
