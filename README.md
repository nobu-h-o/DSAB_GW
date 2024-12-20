## 目的
本レポジトリはアルゴリズムとデータ構造Bのグループワークのソースコードとorgdataを保存するためのレポジトリである。  

## 注意事項
本番ではenc.c, dec.cと設定ファイルconf_0.txtしか提出せず、他のファイルは向こうが用意するので、上記３ファイル以外は触らないように注意してください。
## 環境構築
UbuntuのインストールはWindowsならWSLでできます。Macはわからないので、頑張って調べてください、、AzureLinuxでは一応動くらしいので、
一旦そっちを使ってください。本番の環境は　Ubuntuなので、最後はUbuntuで確認したいです。

## テスティング
本番では本レポジトリのファイル(orgdata含まない)をtarに圧縮して以下のコードを実行する（らしい）
```
tar xvf grpwk24.tar
cd grpwk24
make
chmod 755 test.sh
./test.sh 1 0 0 0 0 0
```
が、ローカル環境では、
```
make
chmod 755 test.sh
./test.sh 1 0 0 0 0 0
```
でよい。