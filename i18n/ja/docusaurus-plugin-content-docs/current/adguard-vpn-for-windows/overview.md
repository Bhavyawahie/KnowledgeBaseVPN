---
title: 機能概要
sidebar_position: 1
---

## AdGuard VPN for Windows とは？

A VPN, acronym for "Virtual Private Network", is a service that makes your Internet connection safe and helps you stay anonymous online. その仕組みは？ VPNを使用せずにウェブサイトを訪問するたびに、ISP（インターネットプロバイダ）はそれを見れます。 あなたが誰で、何を検索しているのか、どこにアクセスしたりしているのはを知り、そのデータを収集し、販売することができるのです。 さらに、アクセスしたWebサイトも、あなたの行動を追跡することができます。 そこでVPNアプリを有効にすると、トラフィック（通信）は暗号化されたトンネルを経由してリモートのVPNサーバーにリダイレクトされ、プライバシーが保証されます。ISPは、あなたがリクエストをどこに送信するかを知らず、サイトもあなたがどこからアクセスしたのかをわかりません。

**AdGuard VPN for Windows の機能・効果**

* ネットワークトラフィックの傍受（スプーフィング）から保護します。 AdGuard VPNは、お使いの端末とVPNサーバーの間に暗号化トンネルを作成します。 すべてのインターネットトラフィックはこのトンネルを通過することによって、データ・個人情報は保護されます。 また、 [AdGuardの独自開発プロトコル](/general/adguard-vpn-protocol.mdx)のおかげで、高速で安全な接続が保証されます。

* IPアドレスを隠します。 サイバー犯罪者にとって、あなたの実際のIPアドレスは、あなたの個人情報を把握するための鍵です。 IPを隠さないと、名前、メールアドレス、電話番号、クレジットカード情報などがすべて詐欺師等の手に渡ってしまう可能性があるのです。 AdGuard VPNを使えば、すべてのトラフィックが暗号化されたトンネルを通過してVPNサーバーにたどり着きます。 そのため、オンライン上ではあなたの端末がそのVPNサーバーのIPアドレスを持っているように見えるのです。

* 現在位置を隠します。 AdGuard VPN サーバーのいずれかを選択することで、その場所に瞬時に「テレポート」します。 その効果は？ 例えば、地元の人の料金でホテルを予約できたり、地域をもとにターゲットしてくる広告から隠れることができたりします。

AdGuard VPN for Windows には多くのメリットがあるので、よければ優れているところを[別記事で詳しく](/general/why-adguard-vpn.md)ご確認いただけます。 本記事では、アプリそのものと、その仕組みに焦点を当てたいと思います。

## AdGuard VPN for Windows を使い始める方法

AdGuard VPN for Windows の使用を開始するには、[こちら](https://adguard-vpn.com/ja/welcome.html)からアプリをダウンロードしてください。 The installation takes no more than a minute — and you'll see a dialog window where you'll need to check at least one box applying the terms of the User Agreement and the Privacy policy. AdGuardがアプリの使用状況に関する匿名化されたデータを収集することを許可するかどうかは、お客様次第です。 最後に、[AdGuardアカウント](https://auth.adguard.com/login.html)またはSNS (Apple、Google、Facebook) 経由でログインします。 これで、AdGuard VPN for Windowsの利用が可能になります。

## ホーム画面

![AdGuard VPN for Windows のホーム画面](https://cdn.adguardvpn.com/content/release_notes/vpn/windows/v2.0/new_main_window_en.png)

**ホーム画面**で最も目立つ項目は、AdGuard VPNの接続/切断ボタンです。 ボタンの上には、アプリの現在の[除外モード](#exclusions)（一般／指定）が表示され、ボタンの下には選択されているサーバー（ロケーション）が表示されます。 画面右側には、利用可能なすべてのロケーションが表示されます。 The fastest location, i.e. the one with the lowest ping, is shown at the top of the list.

画面上部には、タブ4つ（ **ホーム画面**、**VPN対象外リスト**、**サポート**、**設定**）のナビゲーションパネルがあります。

## VPN対象外リスト（除外機能）

AdGuard VPN for Windows には、「**一般**」と「**指定**」という2つの除外モードがあります。 これは一体どういうことなのか？ 一部のサイトだけに対して、AdGuard VPNを常時オフにしたい場合は、**一般モード** を有効にして、除外したいサイトをリストに追加してください。 **指定モード**は、その逆で、リストにあるWebサイトのみに対して、AdGuard VPNが有効になります。 ※それぞれのモードの除外リストは、別々のリストであることにご注意ください。

![VPN対象外リスト（除外機能）](https://cdn.adguardvpn.com/content/kb/VPN/windows/exclusions_en.png)

ドメイン名を入力することで、ウェブサイトを**手動**で対象外リストに追加することができます。 また、**既存リストから**人気のあるウェブサイトを選択するオプションもあります。

![対象外項目を追加する](https://cdn.adguardvpn.com/content/kb/VPN/windows/exclusions_add_en.png)

![リストから対象外項目を追加する](https://cdn.adguardvpn.com/content/kb/VPN/windows/exclusions_from_list_en.png)

> 手動でドメインを追加する場合、いくつかのニュアンスに注意する必要があります。 例えば、ドメイン`google.com`を手動で追加すると、サブドメイン `*.google.com` のすべても除外対象になります。 ただし、この場合、`google.es` や `google.it`など、他のトップレベルドメインを持つドメイン名は除外対象になりません。 もう一つの例として、例えば `youtube.com` を除外リストに追加しても、同サービスのドメインである `youtu.be` は除外対象になりません。

**リストから選択する**オプションを使用することをお勧めします。 既存リストは8つのカテゴリーに分けられています（SNS、メッセンジャー、動画・音楽配信サービス、ゲーム、ショッピング、検索エンジン、仕事コミュニケーションツール）。 リストには最も人気のあるサービスがあり、各サービスの各プラットフォームに関連するドメイン名とサブドメインも全部含まれています。

### VPN対象外リストのインポート・エクスポート

AdGuard VPN for Windows から除外リストをコンピュータにエクスポートするには、「**対象外項目をアクスポート**」をクリックし、保存するフォルダを選択し、「**保存する**」をクリックします。 2つの`.txt`ファイル（ **一般**リスト用と**指定**リスト用）を含む`exclusions.zip`アーカイブがダウンロードされます。 必要に応じて、新しい除外項目を追加したり、古い除外項目を削除したりして、ファイルを編集することができます。

除外リストを他のデバイスに転送するには、 `.zip` ファイルを転送先端末に送信します。 アーカイブをインポートするデバイスでAdGuard VPNを開き、「*VPN対象外リスト*」→「*対象外項目をインポート*」をクリックし、転送したアーカイブを選択します。

## 設定

![設定](https://cdn.adguardvpn.com/content/release_notes/vpn/windows/v2.0/settings_en.png)

4番目の「設定」タブには、アプリの機能をカスタマイズ・調整するためのセクションがあります。 そのうちの2つ、**本アプリの設定** と **VPN対象外アプリ** を詳しく見てみましょう。

### 本アプリの設定

![本アプリの設定](https://cdn.adguardvpn.com/content/release_notes/vpn/windows/v2.0/app_settings_en.png)

「**本アプリの設定**」では、アプリの言語を設定したり、「**キルスイッチ**」（VPN接続が落ちた場合にインターネットへのアクセスをブロックする安全対策機能）を有効にしたりすることができます。 キルスイッチは、公共Wi-Fiやモバイルネットワークに接続しているときに、万が一接続が落ちてVPNによる保護がなくなった場合でも、ハッカー・侵入者があなたのデータ・個人情報にアクセスするのを防ぎます。

You can also activate the following features with a single click: **Auto-update**, **Launch AdGuard VPN at Windows startup**, **Auto-connect on app launch**, and allow AdGuard to collect anonymized app usage data so that the AdGuard team gets the info on potential usability issues. また、AdGuard VPNのカラーテーマを「**ライト**」「**システムに合わせる**」「**ダーク**」に変更することも可能です。

画面の下部には、「**DNS サーバー**」と「**詳細設定**」という2つのセクションがあります。

#### DNSサーバー

「**DNS サーバー**」タブでは、独自のカスタムDNSサーバーを追加することができます。 任意のプロバイダーのDNSサーバーを設定できます。 We recommend adding [AdGuard DNS](https://adguard-dns.io/kb/general/dns-providers/#adguard-dns), a server that can protect against advertising, tracking, and phishing, in addition to the standard functions.

#### 上級者向けの設定

基本的に、上級者向け設定に一切触れずに AdGuard VPN for Windows を使用することも可能ですが、時間をかけて理解することができれば、便利な詳細設定もあったりします。

**動作モード**

VPNとSOCKS5という2つの動作モードがありますが、デフォルトで選択されているほう（VPNモード）のみを使用することがお勧めです。 **VPNモード** が有効な場合、デバイスのトラフィックは すべて AdGuard VPN を介して通過されます。一方、**SOCKS5 モード**でAdGuard VPNは、ローカルプロキシサーバーを使用します（端末上の他のアプリも、トラフィックをリダイレクトするためにこのプロキシサーバーを使えます）。

**ログのレベル**

ログの記録レベルは、2つから選択できます。「**通常の記録**」および「**すべてを記録**」です。 前者はデフォルトで有効になっています。 「**すべてを記録**」レベルは、AdGuardのサポートチームから依頼された場合のみ、有効にしてください。 「すべてを記録」モードで長時間アプリを使用すると、バッテリーの消費量が増加します。

すべてのログは端末でローカルに保存され、必要に応じて不具合検証などのためにAdGuardサポートに送信することができます。

**QUICを使用する**

AdGuard VPNが最新で高度なQUIC暗号化プロトコルを使用できるようにするための実験的な機能です。 QUICの主なメリットは、モバイル端末や公共フリーWi-Fi接続時など、不安定な接続環境で接続品質を改善できることです。

### VPN対象外アプリ

![VPN対象外アプリを追加する](https://cdn.adguardvpn.com/content/release_notes/vpn/windows/v2.0/add_app_en.png)

AdGuard VPNは、ブラウザだけでなく、PC上の他のアプリのトラフィック（通信）も暗号化します。 一部のアプリだけに対してAdGuard VPNを常時オフにしたい場合は、 この**VPN対象外アプリ**機能をお使いください。

## その他のタブ

### このアプリについて

The **About** tab provides information about the current version of AdGuard VPN for Windows, an update button, and links to the AdGuard VPN website, forum, EULA, and Privacy policy.

### アカウント

ここには、お客様のライセンス（お使いのプラン）に関する情報と、お客様のAdGuardアカウントへのリンクが表示されます。AdGuardアカウントでは、現在のサブスクリプション（プラン）を管理したり、新しいサブスクリプションを購入したりできます。

## サポート

このタブは、ユーザーのご質問・お困りの点を解決することを目的としています。FAQページへのリンクがあり、バグを報告したり、フィードバックを寄せたり、サポートチームから求められた場合にログをエクスポートしたりすることができます。
