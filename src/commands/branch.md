# Gitの基本操作
## ブランチの作成と切り替え
※`<GitHubのアカウント名>`の部分は自分のGitHubのアカウント名に**置き換えてください**。

### ブランチの概要
- **ブランチ（branch）** は、リポジトリ内で独立した開発ラインを作成するための機能です。
- ブランチを使用すると、メインの開発ラインに影響を与えずに新機能の追加やバグ修正を行うことができます。
- 各ブランチは、リポジトリのスナップショットを表し、他のブランチとは独立して進化させることができます。

### ブランチの利点
- 安全な開発環境を提供し、メインのコードベースに影響を与えない。
- 複数の機能や修正を同時に並行して開発できる。
- コードレビューやテストのために、変更を簡単に分離できる。

### Fork
1. `Branch`ボタンを押します。
![Fork-Branch](./images/fork/branch.png)
2. `Branch name`に`dev/feature/<GitHubのアカウント名>`を入力します。
![Fork-branch](./images/fork/branch2.png)

### コマンド
1. 新しいブランチを作成します。
    ```sh
    git branch dev/feature/<GitHubのアカウント名>
    ```
2. 作成したブランチに切り替えます。
    ```
    git switch dev/feature/<GitHubのアカウント名>
    ```

![ブランチの作成と切り替え](./images/branch.png)
