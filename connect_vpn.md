# OpenVPNへの接続

tryhackmeで仮想環境を提供してくれるが、無料だと1日1時間しか使うことができないため、ローカルからopenvpnで接続する方法をとる


手順：https://tryhackme.com/access
1. 接続先サーバーをAUに変更する
    - EUだと接続出来なかった
1. open vpnの設定をダウンロード
2. openvpnのインストール
    - `sudo pacman -S openvpn`
3. `sudo openvpn --configure vintersnow.ovpn`
4. 接続確認
    - `curl 10.10.10.10`
