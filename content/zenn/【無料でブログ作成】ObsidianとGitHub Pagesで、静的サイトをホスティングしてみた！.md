# まえがき

今回は、ObsidianとGitHub Pagesを使って静的サイトを無料で公開する方法を紹介したいと思います。
Obsidian公式もPublic機能を提供しているのですが、年間96$、約 14000 円もするので、今回は、GitHub Pagesを使って無料でサイトを公開する方法を公開したいと思います！

この記事では、ObsidianやGitHub Pagesの詳細説明は省かせて頂きます。

今回は、Obsidianを公開するための静的サイトフレームワークとしては、**Quartz4**を利用しています！
理由は単純にUIがかっこいいからです！

# ステップ1. Quartz4を自分のリポジトリへForkしよう！
https://github.com/jackyzha0/quartz

を自分のリポジトリへForkしてきてください。公開リポジトリでないと、Github Pagesは無料で使うことはできないので、注意してください！

# ステップ2. ローカルへcloneして、記事を追加しよう。

自分のリポジトリを、ローカルへcloneしてください。
```
$ git clone https://github.com/takumifujiwaradairy/obsidian-quartz.git
```

contentディレクトリ配下へ、mdファイルを格納してください。

```
$ npx quartz build
$ npx serve public
```
で、ローカル環境でブログの状態を確認できます。

# ステップ3.