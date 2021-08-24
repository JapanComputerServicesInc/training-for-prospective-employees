# training-for-prospective-employees

内定者研修用Gitpitchリポジトリ

## ローカルでのスライド作成、閲覧方法

1. ローカルにnpmをインストール
    - 手順は色々なサイトに載っているので割愛
2. パッケージインストール
    ```
    # リポジトリのルートディレクトリにて
    $ npm i
    ```
3. ローカルのスライド実行環境を起動
    ```
    # リポジトリのルートディレクトリにて
    $ npm run reveal PITCHME.md -- -w
    ```

## スライド公開方法

### 前提

- GitHub -> Settings -> Pagesにて `20211001` ブランチの `docs` を公開ディレクトリに指定しているため、ブランチまたはディレクトリの変更が必要な場合はGitHub上から変更してください
- 上記変更の反映には10-15分ほど掛かる場合があります

### 手順

1. PITCH.mdを何らか修正する
2. PITCH.mdの修正内容を静的ファイルに出力する
```
$ npm run reveal PITCHME.md -- --static docs
```
3. commit及びpushする
