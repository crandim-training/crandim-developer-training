# 研修生向けマニュアル Cloud9編

## Cloud9とは

'AWS Cloud9' は統合開発環境のひとつです。先頭の`AWS`は、`Amazon Web Services`というクラウドサービスのブランド名で、`AWS Cloud9`は、その一部として提供されるSaaSです。以降、単に`Cloud9`と呼ぶことにします。

「統合開発環境」とは、プログラミングやシステム開発の作業に必要な様々な機能を1つのソフトウェアにしたものです。`IDE`と略されます。

通常のIDEは、PCにインストールして使用するタイプのものが多いですが、Cloud9は、クラウド環境側でセットアップをしておけば、ブラウザからすぐに使い始めることができます。

Crandim Developer Trainingでは、Cloud9を使って、プログラミングの演習を行います。

CDTでは、受講生ごとに用意された Cloud9環境を使用します。

自分用のCloud9環境へのアクセス方法については、[こちら](./../) を参照してください。

Cloud9について更に知りたい場合は、[AWS Cloud9 ユーザーガイド](https://docs.aws.amazon.com/ja_jp/cloud9/latest/user-guide/welcome.html) を参照してください。

## Cloud9環境の画面

### Environment(環境)ウィンドウ

画面の左には、ファイル一覧が表示されています。ファイル名をクリックすると、そのファイルを編集することができます。
このファイル一覧のことを、`Environment(環境)ウィンドウ`と呼びます。

* `Environment (環境)ウィンドウ`には、その環境のフォルダとファイルのリストが表示されます。
* フォルダをクリックすると、そのフォルダ内のファイル一覧が表示されます。
* ファイルをクリックすると、そのファイルを表示/編集することができます。

Environment(環境)ウィンドウについて更に知りたい場合は、[こちら](https://docs.aws.amazon.com/ja_jp/cloud9/latest/user-guide/tour-ide.html#tour-ide-editor) を参照してください。

### エディタ、タブ、ペイン

環境ウィンドウでファイルをクリックすると、画面の右側には、そのファイルの内容が、編集可能な状態で表示されます。この画面のことをエディタといいます。

エディタでは、コードの記述、ターミナルセッションの実行、IDE 設定の変更などを行うことができます。

複数のファイルを開くと、それぞれのファイルがタブとして表示されます。タブをクリックすると、そのファイルを表示/編集することができます。

エディタ、タブ、ペインについて更に知りたい場合は、[こちら](https://docs.aws.amazon.com/ja_jp/cloud9/latest/user-guide/tour-ide.html#tour-ide-editor) を参照してください。

### コンソール（ターミナル）

画面の下部には、コンソール（ターミナル）が表示されています。ターミナルでは、linuxのコマンドを入力して、シェルを実行することができます。
* Cloud9環境では、複数のターミナルセッションを実行できます。
* ターミナルセッションを開始するには、メニューバーで、［Window (ウィンドウ)］、［New Terminal (新しいターミナル)］の順に選択するか、［Console (コンソール)］タブの横にある 「プラス」アイコンを選択し、［New Terminal (新しいターミナル)］を選択します。

linuxのコマンド、シェルについては、クランディム新入社員研修の指定教科書「新 Linux/UNIX 入門」の他、初心者向けのWEB記事も大量に公開されていますので、Google等で探してみてください。

cloud9のターミナルについて更に詳しく知りたい場合は、[こちら](https://docs.aws.amazon.com/ja_jp/cloud9/latest/user-guide/tour-ide.html#tour-ide-terminal) を参照してください。


### Cloud9のその他の項目について

その他、 Cloud9の画面について更に知りたい場合は、[AWS Cloud9 IDEのツアー](https://docs.aws.amazon.com/ja_jp/cloud9/latest/user-guide/tour-ide.html) を参照してください。

## 次のステップ

Cloud9についておおよそ理解できたら、[Crandim Developer Trainingの使い方](./../cdt/)を参照してください。