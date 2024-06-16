# Gitの導入

# 1. Gitのインストール

## Windowsへのインストール
1. [Git公式サイト](https://git-scm.com/)からWindows用のインストーラーをダウンロードします。
2. ダウンロードしたインストーラーを実行し、画面の指示に従ってインストールします。

## Macへのインストール
1. ターミナルを開きます。
2. 以下のコマンドを実行してHomebrewを使用してインストールします。
    ```sh
    brew install git
    ```

## Linuxへのインストール
1. ターミナルを開きます。
2. ディストリビューションに応じて以下のコマンドを実行します。
    - Debian/Ubuntu系:
      ```sh
      sudo apt-get install git
      ```
    - Fedora:
      ```sh
      sudo dnf install git
      ```

# 2. リポジトリの作成
今回は既に作成したリポジトリを利用して作業を進めるので紹介だけします。

## 新しいリポジトリの作成
### Fork
1. Forkを開きます。
2. `File`>`Init new repositry`でフォルダ選択画面を開きます。
3. リポジトリとして初期化したいフォルダを選択して`フォルダーの選択`を押します。

### コマンドライン
1. ターミナルまたはコマンドプロンプトを開きます。
2. プロジェクト用のディレクトリを作成します。
    ```sh
    mkdir my_project
    cd my_project
    ```
3. Gitリポジトリを初期化します。
    ```sh
    git init
    ```

![Gitリポジトリの初期化](./images/init.png)
