Windowsでの
JAVA_HOME
環境変数の設定方法


Javaのインストールディレクトリを確認する:


Javaがインストールされているディレクトリを確認します。通常は
C:\Program Files\Java\jdk<version>
のようなパスです。
<version>
はインストールしたJDKのバージョンです。


環境変数の設定画面を開く:


画像の右側にある「環境変数」ボタンをクリックします。


システム環境変数にJAVA_HOMEを追加する:


「システム環境変数」セクションで「新規」ボタンをクリックします。
「変数名」に
JAVA_HOME
と入力します。
「変数値」にJavaのインストールディレクトリのパスを入力します（例:
C:\Program Files\Java\jdk<version>
）。


設定を保存する:


「OK」ボタンをクリックして設定を保存します。


設定を反映する:


コマンドプロンプトを再起動し、
echo %JAVA_HOME%
コマンドを実行して設定が正しく反映されているか確認します。
