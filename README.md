# privacy-policies

Primary Dice が提供する各アプリの、プライバシーポリシーをまとめて公開するリポジトリです。GitHub Pages で配信します。

## ページ一覧

| アプリ | ファイル | URL |
|---|---|---|
| マネログ | `manelog.html` | https://primarydice.github.io/privacy-policies/manelog.html |
| レートハント | `ratehunt.html` | https://primarydice.github.io/privacy-policies/ratehunt.html |
| トリップキット | `tripkit.html` | https://primarydice.github.io/privacy-policies/tripkit.html |

各アプリの URL は Google Play Console などのストアに登録します。**登録後はファイル名を変更しないでください。変更するとストアの掲載情報のリンクが切れます。**

## 新しいアプリを追加するとき

1. このリポジトリ直下に `<アプリ名>.html` を追加する(既存ファイルをコピーして書き換えるのが早い)
2. `index.html` の一覧にリンクを追加する
3. `git add . && git commit -m "◯◯のプライバシーポリシーを追加" && git push`
4. 数分で `https://primarydice.github.io/privacy-policies/<アプリ名>.html` に反映される
5. そのストアの管理画面(Google Play Console 等)にこの URL を登録する

## 更新するとき

該当する `<アプリ名>.html` を直接編集し、ページ内の「最終更新日」も合わせて更新してから push してください。

## 注意

このリポジトリは**公開(Public)**です。署名キー・パスワードなど、公開してはいけないファイルは絶対に置かないでください。
