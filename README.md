# science-academy-2023
小学生向けサイエンスアカデミーのリポジトリです。

# 📝 手順

## 1. 機械学習モデルを作成する🤖
1. [TeachableMachine2.0(TM2)](https://teachablemachine.withgoogle.com/train/pose)を開く
    - [画像プロジェクトを作成する](https://teachablemachine.withgoogle.com/train/image)
    - [ポーズプロジェクトを作成する](https://teachablemachine.withgoogle.com/train/pose)
2. 学習データを用意します
    - 必要な数だけクラスを追加します
    - それぞれのクラスに名前をつけ、サンプルを追加します
3. モデルをトレーニングします
4. モデルをエクスポートします
    - `モデルをアップロードする`をクリックします
    - `共有可能なリンク`をコピーします
        - このリンクは作成したモデルを読み込む際に使います

## 2. ゲームを作成する🎮
1. [TM2向けにカスタマイズされたScratch3.0](https://stretch3.github.io/)を開く

### シューティングゲーム🛸
1. プロジェクトを読み込む
    - プログラムは以下から入手できます。
        - [画像プロジェクト用プログラム](https://github.com/IML-okuda/science-academy-2023/blob/main/src/Shooting%20Game-TM2Scratch.sb3)
        - [ポーズプロジェクト用プログラム](https://github.com/IML-okuda/science-academy-2023/blob/main/src/Shooting%20Game-TMPose2Scratch.sb3)
2. 作成したモデルを読み込みます
    1. `分類モデルのURL`に先ほどコピーしたリンクを`○○モデルのURL`に貼り付けます。
    2. 一度実行することで、モデルが読み込まれます。
3. プログラム（スプライト）を編集します
    - AI Manager
        - しきい値を指定します
        - クラス数を指定します（2 or 4 or 8）
    - Player
        - 「画像ラベル○○を受け取ったときに」のブロックを編集します。
4. 遊んでみましょう！

# 🗃️ 参考資料
- [TeachableMachine 向け Scratch 拡張機能 (TM2Scratch) 使い方 (日本語版)](https://mirapro.mext.go.jp/assets/tm2scratch.pdf) 
- [Teachable Machine Tutorial: Bananameter](https://medium.com/@warronbebster/teachable-machine-tutorial-bananameter-4bfffa765866)
- [Teachable Machine Tutorial: Head Tilt](https://medium.com/@warronbebster/teachable-machine-tutorial-head-tilt-f4f6116f491)