---
title: iPhone ve iPad uygulamaları için AdGuard VPN otomasyonu nasıl ayarlanır
sidebar_position: 1
sidebar_label: AdGuard VPN otomasyonu nasıl ayarlanır
---

AdGuard VPN'de bir *İstisnalar* bölümü ve iki çalışma modu vardır – *Genel* ve *Seçici*. *Genel modda* AdGuard VPN, istisnalara eklenen siteler dışında her yerde çalışır. Tam tersine olan, *Seçici modda* VPN, istisna listesinde listelenen siteler dışında hiçbir yerde çalışmaz. Her mod için ayrı bir liste oluşturmanız gerektiğini unutmayın.

Fark edebileceğiniz gibi, *İstisnalar* bölümüne yalnızca siteler eklenebilir. AdGuard VPN'i uygulamalara göre ayarlamak için başka bir özellik kullanmanız gerekir. Masaüstü uygulamalarımız *Bölünmüş tünelleme* modülüne ve Android uygulamasında *Uygulama ayarlarına* sahiptir — bu ayarlar AdGuard VPN'nin hangi uygulamalarda çalıştırılacağına karar vermenizi sağlar.

Ancak, çoğu zaman olduğu gibi, bir takım teknik ince ayrıntılar nedeniyle, iOS için bu kadar kullanışlı bir işlevi uygulamak en azından şimdilik imkansızdır. Bu nedenle, iPhone ve iPad'lerdeki uygulamalar için AdGuard VPN'i otomatikleştirmenin alternatif bir yolunu sunuyoruz.

## AdGuard VPN otomatik etkinleştirmeyi ayarlama

Bir veya daha fazla uygulama için bir VPN'e ihtiyacınız varsa, AdGuard VPN'i, onları açıp kapattığınızda otomatik olarak açılacak ve kapanacak şekilde ayarlayın. İstisnalar sekmesine gidin, Genel modu seçin ve talimatları takip edin. Burada Twitter için otomasyonun nasıl oluşturulacağını açıklıyoruz, ancak başka herhangi bir uygulamayı seçebilirsiniz.

![Talimat. Bölüm 1](https://cdn.adguardvpn.com/public/Adguard/Blog/VPNauto/vpn_on1_en.jpg)
1. App Store'dan [*Kestirmeler* uygulamasını](https://apps.apple.com/us/app/shortcuts/id915249334) indirin ve ekranın alt kısmındaki saat simgesine dokunarak *Otomasyon* bölümüne gidin.
2. *Kişisel Otomasyon Yarat* düğmesine dokunun, ardından açılan listede *Uygulama* öğesini bulun ve ona dokunun.
3. Bir sonraki pencerede, *Açıldı* öğesinin seçili olduğundan emin olun ve ardından uygulamayı seçmek için *Seç* öğesine dokunun.

![Talimat. Bölüm 2](https://cdn.adguardvpn.com/public/Adguard/Blog/VPNauto/vpn_on2_en.jpg)
4. Uygulamanın adını girmeye başlayın, bizim durumumuzda bu Twitter'dır ve onu seçin. Ardından ekranın sağ üst köşesindeki *Bitti* öğesine dokunun. Ardından ekranın sağ üst köşesindeki *Sonraki* öğesine dokunun. Ve açılan pencerede *İşlem Ekle* öğesine dokunun.

![Talimat. Bölüm 3](https://cdn.adguardvpn.com/public/Adguard/Blog/VPNauto/vpn_on3_en.jpg)

5. “AdGuard VPN” yazmaya başlayın ve AdGuard VPN uygulamasını seçin. Yeni pencerede *VPN bağlantısı kur* öğesine dokunun.

![Talimat. Bölüm 4](https://cdn.adguardvpn.com/public/Adguard/Blog/VPNauto/vpn_on4_en.jpg)
6. Değişkenlerin *Ayarla* VPN bağlantısı *Açık* olduğundan emin olun ve *İleri* öğesine dokunun.
7. Bir sonraki pencerede, *Çalıştırmadan önce sor* seçeneğinin yanındaki kaydırıcıyı etkin olmayan konuma getirin. Seçiminizi onaylayın, *Bitti* öğesine dokunun.

Artık yeni bir senaryonuz var: Twitter uygulamasını başlattığınızda AdGuard VPN otomatik olarak etkinleştirilecektir. Şimdi, uygulamayı kapattığınızda AdGuard VPN'nin otomatik olarak kapanmasını sağlayacak başka bir komut oluşturmanız gerekiyor.

## AdGuard VPN otomatik kapanmasını yapılandırma

![Talimat. Bölüm 1](https://cdn.adguardvpn.com/public/Adguard/Blog/VPNauto/vpn_off1_en.jpg)
1. Aynı *Kestirmeler* uygulamasında yeni bir otomasyon oluşturmaya başlayın: ekranın sağ üst köşesindeki *+* öğesine ve ardından *Kişisel Otomasyon Yarat* düğmesine tıklayın. Açılan pencerede *Uygulama* öğesini seçin.
2. *Kapalı* seçeneğinin seçili olduğundan emin olun ve yandaki seçeneğin altındaki kutunun işaretini kaldırın. Ardından *Seç* öğesine dokunun.

![Talimat. Bölüm 2](https://cdn.adguardvpn.com/public/Adguard/Blog/VPNauto/vpn_off2_en.jpg)
3. *Twitter* yazmaya başlayın ve uygulamayı seçin. Ardından ekranın sağ üst köşesindeki *Bitti* öğesine dokunun. *İşlem Ekle* öğesine dokunun ve AdGuard VPN'i seçin.

![Talimat. Bölüm 3](https://cdn.adguardvpn.com/public/Adguard/Blog/VPNauto/vpn_off3_en.jpg)

4. Yeni pencerede *VPN bağlantısı kur* öğesine dokunun.
5. Ardından, *Kapalı* kelimesine dönüşmesi için *Açık* kelimesine dokunun, ardından ekranın sağ üst köşesindeki *Sonraki* öğesine dokunun.
6. *Çalıştırmadan önce sor* seçeneğini devre dışı bırakın ve seçiminizi onaylayın. Ardından işlemi tamamlamak için ekranın sağ üst köşesindeki *Bitti* öğesine dokunun.

Tamamlandı! AdGuard VPN artık Twitter uygulamasını her açtığınızda cihazınızda etkinleştirilecek ve kapattığınızda devre dışı bırakılacaktır. Başka bir uygulama için aynı adımları tekrarlayabilirsiniz. 