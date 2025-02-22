---
title: 'AdGuard VPNが他社製品より優れている理由'
sidebar_position: 2
---

[長期VPNプラン](subscription.md)を検討する場合、ユーザーはその速度、セキュリティ、価格を第一に評価する方が多いです。 この３つはとても重要なポイントですが、それ以外にもたくさん注目すべき点があります。 AdGuard VPNには、ユニークなメリットが何個もあります。

*まず始めに、他のVPNにはないAdGuard VPN機能について説明したく思います。*

## 1. 独自開発プロトコル
当初から、既存のプロトコルに満足できず、独自VPNプロトコルを自社で開発し、実装することを決めていました。 その結果、 [AdGuard VPNプロトコル](adguard-vpn-protocol.mdx)が登場しました。

VPNサービスを選択する際、高速性と安全性のどちらかを優先して選ばないといけないケースが多いです。 そこで、AdGuard VPNプロトコルは、速度とセキュリティの完璧な調和であり、遅いインターネット接続を我慢する必要も、プライバシーを犠牲にする必要もないのです。 なかでも、AdGuard VPNプトロコルは通常のトラフィックに偽装しているため、検知対策やブロック対策がしっかりしています。

## 2. VPN対象外リスト
*VPN対象外リスト*を使って、VPNを有効にするサイトと無効にするサイトを指定することができます。 AdGuard VPNには、 「*一般*」 と 「*指定*」という2つの動作モードがあります。 *一般モード*では、「VPN対象外リスト」に追加されたウェブサイトに対してAdGuard VPNはオフになります。 逆に、*指定モード*では、「VPN対象外リスト」に追加されたウェブサイトに対してのみAdGuard VPNはオンになります。 また、対象外リストのインポート/エクスポートも簡単に行えます。 この機能については、各製品の*機能概要*記事において、その方法をご確認いただけます。

![指定モードの対象外リストの例](https://cdn.adguardvpn.com/public/Adguard/Blog/vpn_export_exclusions.png)

Webサイトを手動で対象外リストに追加したり、人気のあるサービスのリストから選択することもできます。 リストは8つのカテゴリーに分けられています（SNS、メッセンジャー、動画・音楽配信サービス、ゲーム、ショッピング、検索エンジン、ワークコミュニケーションツール）。

> この機能は、iOSを除いて、すべてのプラットフォームで利用可能です。

## 3. DNSサーバーの選択
もう、インターネットプロバイダが提供するDNSサーバーに頼らなくていいんです。 まず、お使いのISP（インターネットプロバイダー）は、あなたの閲覧履歴にアクセスできる可能性が高いのです。 また、DNS機能は軽視されがちですが、広告やトラッカー（個人情報追跡）を除去したり、マルウェアからデバイスを保護したり、セーフサーチを適用にしたり、アダルトコンテンツをブロックしたりすることができます。

You can choose DNS servers from [known DNS providers](https://adguard-dns.io/kb/general/dns-providers/) such as AdGuard, Cisco, Cloudflare, Google, or Quad9, or even configure to use your own DNS server.

## 4. 一番速いロケーション

AdGuard VPNを際立たせているもう一つの特徴は、pingに基づいて接続速度が一番速いロケーションを選択できることです。 簡単で言えば、pingは、あなたの端末から送信されたデータパケットがサーバーに到達して、端末に戻ってくるまでの時間です。 ping数字が小さいほど、サーバーは近くにあり、速度が速いということです。 いろいろなところに接続できるように、ロケーションは随時拡大しています。

> ※すべてのAdGuard VPNサーバーロケーションにアクセスするには、AdGuard VPNサブスクリプションを購入する必要があります。

## 5. AdGuard広告ブロッカーとの併用モード

PCアプリやブラウザ拡張機能の場合、言うまでもありません。アンチウイルスやその他の類似ソフトウェアを除けば、PCでアプリケーション間で競合が発生することはほとんどありません。

一方、モバイル端末の場合は、問題が起こったりします。 AndroidとiOSの両方において、ほとんどの場合、OSに起因する制限が存在するため、2つのVPNベースアプリは一緒に同時動作しません。

しかし、私たちはAdGuard VPNとAdGuard広告ブロッカーを併用するための解決策を見つけることができました。 When you have both AdGuard apps installed on one device, they will automatically become compatible without any input required from you. 通常であればどちらかを選択しなければならない2つの機能セット（VPNと広告ブロッカー）を同時に利用できるということです。

## 6. QUIC対応
[QUIC](https://adguard.com/blog/dns-over-quic.html) is a cutting-edge protocol that has many perks. 主なメリットは、モバイル端末や公衆Wi-Fi接続時など、理想的でない接続環境で接続品質を改善できることです。 QUICプロトコルは、接続が問題なく安定している場合には速度に影響を与えませんが、インターネットが遅いユーザーにとっては状況が良くなることは間違いありません。

*さて、ここでまともなVPNには欠かせない機能をみてましょう。*

## 7. キルスイッチ
モバイルネットワークや、ショッピングモール、カフェ、地下鉄、空港などで公衆Wi-Fiネットワークに接続することが多い場合、「キルスイッチ」は欠かせません。 理由は簡単で、VPNが突然切断され、接続が不安全になると、あなたの機密情報が詐欺師やサイバー犯罪者にさらされる可能性があるからです。

何らかの理由でVPN接続が遮断された場合、「キルスイッチ」が自動的にインターネット接続を切断し、攻撃者に情報を奪われないようにします。 キルスイッチがあれば安心です。 プライバシーを重視する方、個人情報を大切にする方は、この頑丈な対策をぜひ見逃さないでください。

## 8. Split tunneling (VPN対象外アプリ)
この機能は、前述の「VPN対象外リスト」に似ています。 唯一の違いは、Webサイトではなくアプリを除外できることです。

## 9. 通信の自動保護
この機能は、セキュリティのないネットワークのために特別に開発されました。 ユーザーの利便性を考慮し、公共の場を訪れる際にVPNを有効にすることを忘れることがないようにしました。 例えば喫茶店に立ち寄って、そのWi-Fiネットワークに接続すると、自動的にAdGuard VPNに接続される、という機能です。

## 10. 同時に最大5台の端末を接続可能
AdGuard VPNは、有料ユーザーには5つの同時接続を提供します。 「*同時*」という言葉に重きを置いていますが、その理由は以下の通りです。 VPNプロバイダによっては、サービスにログインできる*端末が最大5台*になっています。 AdGuard VPNでは、アカウントにログインできるデバイスの数に*制限はなく*、同時に5台の端末をVPNに接続することができます。 有料サブスクリプションをご利用でない方は、AdGuard VPNを*2台の端末*で使用することができます。VPNサービスのほとんどは、無料版を*1台の端末でしか*使えないため、これもまた、競合他社に比べてAdGuard VPNの大きなメリットです。

## 11. 配信（ストリーミング）サービス対応
ストリーミングサービス（動画・音楽配信サービス）がVPNを嫌う理由は明白です。統計によると、約20％のユーザーが、地域ブロッキングを回避して番組、テレビ番組、映画を見るためにVPNをインストールしています。 そのため、ストリーミング・プラットフォームは、VPNトラフィックを検出し、ブロックするためにあらゆる手段を講じる傾向があります。

しかし、自分の地域に特化したコンテンツを安心して視聴したい場合はどうすればいいのでしょうか？ また、海外旅行中・出張中で、コンテンツを見るのをやめたくない時は？ AdGuard VPNは、そのユニークなプロトコルのおかげで、配信サービスからVPN利用が見えないようにすることができます。

> ※私たちは、著作権規制を回避するためにAdGuard VPNを使用することは推奨しません。

## 12. ダークモード

![ダークモード](https://cdn.adguardvpn.com/public/Adguard/Blog/vpn/main_en_black.png)

この小さな機能は特筆に価します。 多くのユーザーがダークモードを利用しているため、すべてのAdGuard VPN製品にテーマスイッチを追加しています。 ライト、ダーク、システムのうち、好きなテーマをお選びいただけます。
