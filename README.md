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
5. モデルをエクスポートします
    - `モデルをアップロードする`をクリックします
    - `共有可能なリンク`をコピーします
        - このリンクは作成したモデルを読み込む際に使います

### 学習データの収集手順

https://github.com/IML-okuda/science-academy-2023/assets/55625375/c3474a93-2030-45f8-ac3a-3b50f4d457dc

### クラスの追加・削除手順
https://github.com/IML-okuda/science-academy-2023/assets/55625375/f8bab077-7219-4a61-8473-c33232d47012

### モデルのトレーニング・エクスポート手順
https://github.com/IML-okuda/science-academy-2023/assets/55625375/52eb6674-a3f3-431a-871b-dcdf97d89001


## 2. ゲームを作成する🎮
1. [TM2向けにカスタマイズされたScratch3.0](https://stretch3.github.io/)を開く

### シューティングゲーム🛸
1. プロジェクトを読み込む
    - プログラムは以下から入手できます。
        - [画像プロジェクト用プログラム](https://github.com/IML-okuda/science-academy-2023/blob/main/src/Shooting%20Game-TM2Scratch.sb3)
        - [ポーズプロジェクト用プログラム](https://github.com/IML-okuda/science-academy-2023/blob/main/src/Shooting%20Game-TMPose2Scratch.sb3)
2. 作成したモデルを読み込みます
    1. 先ほどコピーしたリンクを`○○モデルのURL`に貼り付けます。
       
       <img width=800 src="https://github.com/IML-okuda/science-academy-2023/assets/55625375/25d415f8-80aa-46cd-ac59-35479da0f745" />

              
       |  貼り付け方1（ペースト Ctrl+V）  |  貼り付け方2（右クリック）  |
       | --- | --- |
       | <img width=500 src="https://github.com/IML-okuda/science-academy-2023/assets/55625375/88d55d86-eb52-4f62-8f24-f8f44e8993d4" /> | <video src="https://github.com/IML-okuda/science-academy-2023/assets/55625375/7451972d-0610-4185-9d37-4d174d7b5b17"/>  |
   
    3. **✅モデルを読み込むために、URLを貼り付けたら実行します**

       <img width=800 src="https://github.com/IML-okuda/science-academy-2023/assets/55625375/75a76066-7b42-44a3-aac6-9ab39a2ab6f1"/>

4. プログラム（スプライト）を編集します
   |  AI Manager  |  Player  |
   | --- | --- |
   |  <img width=400 src="https://github.com/IML-okuda/science-academy-2023/assets/55625375/5ce54c90-d09d-4572-8c46-6f245f8b784c"/>  |  <img width=400 src="https://github.com/IML-okuda/science-academy-2023/assets/55625375/538d8616-9a3c-4674-8b29-3d37c86cc865"/>  |
   | クラス数は（**2, 4, 8**） | 「画像ラベル○○を受け取ったときに」のブロックを編集します |

5. 遊んでみましょう！

# 🗃️ 参考資料
- [TeachableMachine 向け Scratch 拡張機能 (TM2Scratch) 使い方 (日本語版)](https://mirapro.mext.go.jp/assets/tm2scratch.pdf) 
- [キーボードショートカットキーの使い方](http://keyboard-shortcuts.jp/windows/copy-paste-cut.html)
- [Teachable Machine Tutorial 1: Gather](https://www.youtube.com/watch?v=DFBbSTvtpy4&t=20s)
