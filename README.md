# 一般ユーザ向けWindows軽量ランチャー
## 1.動作環境
Windows7

Windows8.1

Windows10

Windows11
## 2.動作環境について

ランチャーの導入環境ですが、ゲストアカウントとメインアカウントの分離が必須です。

導入時は、ゲストアカウントに導入するのがおすすめです。
launcherフォルダーからダウンロード可能です。

## 3.環境構築

1.設定にてローカルアカウント作成

2.Cドライブ直下にランチャーをインストール

3.C:\Users\（ユーザー名）\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startupでスタートアップ登録する

4.レジストリーエディターでHKEY_CURRENT_USER\Software\Microsoft\Windows NT\CurrentVersion\Winlogon
  
  で右側の空いているスペースを右クリックし、「新規」 ＞ 「文字列値」 をクリックします。

5.shellにインストールパスを入力します


