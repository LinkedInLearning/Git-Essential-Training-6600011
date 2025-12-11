# Git 基本講座
LinkedInラーニングの「Git 基本講座」コース用のリポジトリです。このコースは [LinkedInラーニング][lil-course-url]で視聴できます。

![course-name-alt-text][lil-thumbnail-url] 

Gitはファイルの変更履歴を管理するためのバージョン管理システムです。2025年現在もっとも主流なシステムであり多くの開発現場で利用されています。このコースではGitの基本的な機能について学びます。Gitの特徴である分散型や環境ごとの利用方法、ブランチやマージなどのしくみを解説します。また各機能をVisual Studio Codeとコマンドラインの2通りの方法で実行する手順も紹介します。このコースを受講することで、Gitの基本とその使い方を学ぶことができるでしょう。

##  インストール

　これらの練習ファイルを使用するには、以下がインストールされている必要があります。
 
   Git
   Visual Studio Code

　[補足]GitHub Codespacesを使用する場合は上記インストールは必要ありません。

　・手順

　1.本リポジトリのフォークを作成します。
　2.GitまたはVisual Studioを使用してリポジトリのCloneを行います
　3.レッスンに合わせたブランチに切り替えることで動画と同様の作業を行うことができます。

## リポジトリの使い方
このリポジトリには必要に応じてブランチが設けられています。ブランチのポップアップメニューを使用して、使用するブランチに切り替えたあとにコースを視聴してください。またURLに`「/tree/ブランチ名」`を追加することで、アクセスしたいブランチに移動することも可能です。

## ブランチ
使用するブランチはコース内で指定されます。例えばch3_02という形式です。
　各ブランチはレッスンの開始時の状態になっています。

　ファイルに変更を加えた後、ある演習ファイルのブランチから次のブランチに切り替えると、次のようなメッセージが表示される場合があります。

error: Your local changes to the following files would be overwritten by checkout:        [files]
Please commit your changes or stash them before you switch branches.
Aborting

　この問題を解決するには:

Add changes to git using this command: git add .
Commit changes using this command: git commit -m "some message"

 ## GitHub Codespacesについて
プログラミング言語を学ぶ最良の方法は、実際にそれを使用することです。それがこのコースがGitHub Codespacesと統合されている理由です。GitHub Codespacesは、あなたが普段使っているIDEのすべての機能を提供するクラウド上の手軽な開発環境です。ローカルマシンのセットアップも必要ありません。 GitHub Codespacesを使えば、あなたが職場で使っている他のツールを使用しながら、どのパソコンからでもいつでもプログラミングの実践的な練習ができます。

## インストラクター

西村誠

プログラマー、Microsoft MVP

この講師の他のコースを視聴する：[LinkedInラーニング](https://www.linkedin.com/learning/instructors/13315091)

[0]: # (Replace these placeholder URLs with actual course URLs)

[lil-course-url]: https://www.linkedin.com/learning/
[lil-thumbnail-url]: https://media.licdn.com/dms/image/v2/D4E0DAQG0eDHsyOSqTA/learning-public-crop_675_1200/B4EZVdqqdwHUAY-/0/1741033220778?e=2147483647&v=beta&t=FxUDo6FA8W8CiFROwqfZKL_mzQhYx9loYLfjN-LNjgA

