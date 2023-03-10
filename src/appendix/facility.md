# ファシリティ

## OS

- EndeavourOS
- Ubuntu

WindowsおよびMacを選定候補外とし，Linuxディストリビューションの積極的に採用する．
さらに，DasS[^1]により端末はデータレス化する．

[^1]:Google CloudやAWSなどのソリューションから選定．

## グループウェア

業務を円滑に遂行するために，組織はグループウェアに対して下記の機能を要求する．
コミュニケーションについては，社外とのやりとりはメールを用い，社内での閉じた連絡はチャットを利用する．

|機能|社内標準|補足|
|-|-|-|
|Browser|Firefox|Rustを好む|
|Mail<br><社外限>|Tutanota|LinuxのメーラはThunderbirdが有名であり，かつMozillaが開発しているため利用したかったが，UIが肌に合わなかった．Tutanotaはセキュリティを強みにしているドイツ製のメールクライアント．Web形式のものでも無くはないが，メールの確認に逐一ブラウザを開くのは不便のため，基本的にはインストール型を採る．<br>OutlookやGmailと同様に，スケジュール共有機能も実装されている．|g|
|Chat<br><社内限>|Slack|Web会議も可|
|Cloud Storage|DropBox|チャットアプリではファイルの送受信を禁止する．|
|Portal|-|通達掲示板や承認ワークフローはスクラッチ開発により内製化|

## ITセキュリティ

平たく言えば，下記のようなことが間接的にも実現できればよい．

### ドメイン管理

- Google Domains
- SSO

### VPN

- [Cloudflare WARP](https://developers.cloudflare.com/warp-client/get-started/linux/)
- [Cloudflare Zero Trust](https://developers.cloudflare.com/cloudflare-one/connections/connect-apps/private-net/)

### 資産管理

要検討．
各PCにおいて，無許可のアプリインストールやUSBフラッシュメモリの使用は禁じたい．

### インターネットアクセス

- プロキシサーバー
- ホワイトリスト

## オフィス

リモートワーク推奨にしたいが，「自宅で勤務できない」というケースも想定して企業としてオフィスは準備すべきだろう．

- レンタルオフィス

## 福利厚生

?todo
