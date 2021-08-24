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

```
$ npm run reveal PITCHME.md -- --static docs
```