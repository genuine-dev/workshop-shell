# workshop-shell
シェルスクリプト講座用リポジトリ

## 準備 ( Winrows10 )

※ Hyper-Vを利用する想定 (VirtualBoxがいい人は調べてね！)

### 1. Vagrantをインストールする

https://www.vagrantup.com/

vagrant -v でバージョン番号が出力されることを確認してください。

### 2. vagrant-vbguestをインストール

``` cmd
> vagrant plugin install vagrant-vbguest
```

### 3. リポジトリのクローン

PCのお好きな場所にクローンしてください。

### 4. vagrant up

コマンドプロンプトで、クローンした場所にあるinfraフォルダに移動し、``` vagrant up ``` を実行してください。
vagrant upが正常に終了したら ``` vagrant status ``` でboxの起動状況を確認してください。
runningと表示されればOKです。

### 5. vagrant ssh

 ``` vagrant ssh ``` コマンドでログインします。
 
 ※ もしPermissionエラーが表示される場合はWindowsにインストールされているOpen SSHクライアントをアンインストールする必要があります。
 
以上
