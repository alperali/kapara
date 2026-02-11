# Giriş
Bir defa bile sitelerini kullanmamış olmama rağmen 10 yıldan fazla bir süredir kumar ve bahis konulu SMS mesajları mağduruyum.
Bir ara bu mesajları şikayet edebildiğimiz Ticaret Bakanlığının bir web sitesi vardı, orada 100'den fazla kayıt açtım
fakat hiçbir sonuç çıkmadı, ve o site de artık kapandı. Bu mesajları gönderen numaralar, kullandıkları telefon operatörleri
ve aldıkları ticari SMS paketlerinin faturaları bilinmesine rağmen neden haklarında işlem yapılamadığı bir muammadır.

2026 Ocak itibarıyla bana gelen kumar ve bahis konulu SMS mesajlarını ekran görüntüleri ve JSON dosya halinde burada ifşa ediyorum.

Ekran görüntüleri `ekran` klasöründedir.

# Bulgular
- Kumar ve bahis konulu SMS mesajlarında [B Kodları](https://www.btk.gov.tr/haberler/sms-ler-icin-btk-dan-4-haneli-kod-uygulmasi) yoktur.
- Mesajları gönderen numaraya bir SMS atarsanız faturanıza "yurt dışı sms" ücreti yansımakta ve alıcısı olarak Kuzey Kıbrıs görünmektedir.
- Telefondaki SMS uygulaması (Google Mesajlar gibi) bir istenmeyen mesaj (_spam_) filtreleme imkanı sunmasına rağmen bu özellik bazen yanlış pozitif (_false positive_) üreterek iş ve zaman kaybına neden olmaktadır (bir ödeme sistemi ve bir de seyahat şirketinden gelen mesajları spam zannetmiş, ödeme yapamadım, biletimi alamadım), bu nedenle spam engelleme benim için bir çözüm değildir ve devre dışıdır.

# Tartışma
1. B kodları olmayan SMS mesajı nasıl olup da bana ulaşmaktadır? Telefon operatörü neden bunu engellememektedir?
2. Yıllardır bir defa bile sitesini kullanmamış kişilere neden hala SMS mesajları göndermektedirler? Acaba kumar/bahis oynatma kisvesi altında toplu ticari SMS paketleri alım satımı ile mi aslında kara para aklanmaktadır?

---

- [ ] JSON dosya eklenecek.
- [ ] Numaralar tablo olarak README'de görüntülensin.
