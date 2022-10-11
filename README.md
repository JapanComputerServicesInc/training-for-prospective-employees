# 内定者、インターン等研修(LINE Bot開発)用資料リポジトリ

## 研修内容

[こちら](https://www.notion.so/LINE-Bot-4d8f81f29de142e09c06174435fd3ffd)をご覧ください

※閲覧権限を持っていない場合はSD2部 関口(司)までご連絡ください

## 当リポジトリの役割

上記研修の概要を説明するための資料を管理します

## 公開用URL

https://japancomputerservicesinc.github.io/training-for-prospective-employees/#/

※GitHub Pages、Markdown、Reveal.jsを利用しています

## ローカル環境でのスライド閲覧方法

1. ローカルにnpmをインストール
    - 手順は色々なサイトに載っているので割愛
2. リポジトリクローン
    - 手順は色々なサイトに載っているので割愛
3. パッケージインストール
    ```
    # リポジトリのルートディレクトリにて
    $ npm i
    ```
4. ローカルのスライド実行環境を起動
    ```
    # リポジトリのルートディレクトリにて
    $ npm run local
    ```
    これでローカル環境での閲覧が可能になります

## スライド編集方法

1. 上記閲覧方法を行う
2. 新規ブランチを作成する
    - ブランチ名は `研修日(YYYYMMDD)` とする
        - 例: 2022/10/01の内定者研修の場合は `20221001`
3. PITCH.mdを修正する
4. PITCH.mdの修正内容を静的ファイルに出力する
    ```
    $ npm run build
    ```
5. commit及びpushする

## スライド公開方法

GitHubのリポジトリページを開き、GitHub -> Settings -> Pagesにて公開対象ブランチを選択し、Saveします

![image](https://user-images.githubusercontent.com/12994726/195010213-59083433-db76-42ae-9b09-bd0632e3a8a1.png)

※上記変更の反映には10-15分ほど掛かる場合があります