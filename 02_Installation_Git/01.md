# **1. Linuxのバイナリでの配布**

## **DebianまたはUbuntu**

DebianとUbuntuのほとんどのシステムではGitは一連のパッケージとして提供されており,必要に応じて個別にインストールすることもできる. 基礎的なパッケージはgit-coreと呼ばれており, ドキュメントはgit-docに含まれている.

- **git-arch, git-cvs, git-svn**

    プロジェクトをArchやCVS, SubversionからGitへ移行させたり, その逆を行う場合に使う.

- **git-gui, gitk, gitweb**

    リポジトリをグラフィカルなアプリケーションやWEBブラウザで見たい場合に使う.

- **git-email**

    Gitのパッチを電子メールで受け取る場合に使う.

- **git-daemon-run**

    リポジトリを共有する場合に使う.

        # apt-get install git-core git-doc gitweb git-gui gitk git-email git-svn

## **その他のバイナリ配布**
