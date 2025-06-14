# Til(Today is Learn)
##なにするの？
学習の記録を日記として残しつつ、GitやGitHubを使ったバージョン管理を体験しましょう。  

## 導入方法
- git(gitbash)をインストール
- githubのアカウントを作成
- プロジェクトのクローン
```
git clone https://github.com/Konagawa/PracticeGit.git
```


## Git日記作成手順(作成中)

1. 自分の名前のマークダウンファイルを作成する
  - (例)konagawa_til.md
2. 今日の日記をmdファイル内に記述する。
  - [Markdown記法 チートシート](https://qiita.com/Qiita/items/c686397e4a0f4f11683d)
3. ステージング
```
git add .
```
4. 変更をコミット
```
git commit -m'ここに何か書いてね'
```
5. リモートにプッシュしてリモートに反映させる。
```
git push
```


etc.
- 変更状況の確認
```
git status
```

- コミットログの確認
```
git log
```
- ブランチの確認
```
git branch
```

## 日記を書くための拡張機能
- Markdown Preview Enhanced
  - プレビュー画面にいろんな機能を追加する。
- Extension Pack for Java
  - VscodeでJavaの開発するなら必要
- GitLens
  - コードの更新履歴（日付）を確認できる
- Git Graph
  - Gitのソース管理状況をグラフで確認できる
- Todo Tree
  - TODOと記述した部分が強調されてり、タスク管理しやすくなる
- indent-rainbow
  - インデントが正しいかわかりやすくなる。


MarkDawnファイルのプレビュー確認方法

CTRL+K
　→Vを入力するとプレビュー画面が表示
※ 拡張機能
