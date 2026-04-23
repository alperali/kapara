# Giriş
Bir defa bile sitelerini kullanmamış olmama rağmen 10 yıldan fazla bir süredir yasadışı kumar ve bahis konulu SMS mesajları almaktayım.
Bir ara bu mesajları şikayet edebildiğimiz Ticaret Bakanlığının bir web sitesi vardı, orada 100'den fazla kayıt açmıştım
fakat hiçbir sonuç çıkmadı, ve o site de artık kapandı. Bu mesajları gönderen numaralar, kullandıkları telefon operatörleri
ve satın aldıkları toplu ticari SMS paketlerinin faturaları bilinmesine rağmen neden haklarında işlem yapılamadığı bir muammadır.

2026 Ocak itibarıyla bana gelen yasadışı kumar ve bahis konulu SMS mesajlarını ekran görüntüleri ve JSON dosya halinde burada ifşa ediyorum.

Ekran görüntüleri `ekran` klasöründedir. JSON dosyadaki tarih biçimi [standart Javascript tarih formatı](https://tc39.es/ecma262/multipage/numbers-and-dates.html#sec-date-time-string-format)ndadır.

# Bulgular
- Kumar ve bahis konulu SMS mesajlarında [B Kodları](https://www.btk.gov.tr/haberler/sms-ler-icin-btk-dan-4-haneli-kod-uygulmasi) yoktur. Listelerinden çıkma isteği iletebileceğimiz bir numara mesaj sonunda yoktur.
- Mesajları gönderen numaraya bir SMS atarsanız faturanıza "yurt dışı sms" ücreti yansımakta ve alıcısı olarak Kuzey Kıbrıs görünmektedir.
- Telefondaki SMS uygulaması (Google Mesajlar gibi) bir istenmeyen mesaj (_spam_) filtreleme imkanı sunmasına rağmen bu özellik bazen yanlış pozitif (_false positive_) üreterek iş ve zaman kaybına neden olmaktadır (bir ödeme sistemi ve bir de seyahat şirketinden gelen mesajları spam zannetmiş, ödeme yapamadım, biletimi alamadım), bu nedenle spam engelleme benim için bir çözüm değildir ve devre dışıdır.

# Tartışma
1. B kodları olmayan SMS mesajı nasıl olup da bana ulaşmaktadır? Telefon operatörü neden bunu engellememektedir?
2. Yıllardır bir defa bile sitesini kullanmamış kişilere neden hala SMS mesajları göndermektedirler? Acaba kumar/bahis oynatma kisvesi altında toplu ticari SMS paketleri alım satımı ile mi aslında kara para aklanmaktadır?

# Numaralar
Ekran görüntüleri alınmış kumar/bahis SMS mesajları gönderen numaralar aşağıda listelenmiştir:
```
0850 270 0103
0850 270 0159
0850 270 0212
0850 270 0263
0850 270 0663
0850 420 2891
0850 425 0497
0850 425 0852
0850 425 0946
0850 434 0555
0850 434 1014
0850 434 1041
0850 434 1042
0850 435 0920
0850 435 5454
0850 545 4830
0850 552 9244
0850 552 9400
0850 552 9444
0850 552 9901
0850 552 9999
0850 633 0380
0850 633 0596
0850 633 0636
0850 633 0929
0850 678 1077
0850 678 1109
0850 678 1431
0850 678 1434
0850 678 1445
0850 678 1447
0850 678 1464
0850 678 1560
0850 745 9349
0850 771 0138
0850 771 0144
0850 771 0146
0850 771 0196
0850 771 0252
0850 771 0269
0850 771 0270
0850 966 0674
```
Aşağıdaki numaralardan sesli arama yapılarak yasadışı kumar/bahis konulu bant kaydı dinlettirilmiştir:
```
0312 703 0396
```

# Sonuç
Burada aylardır yaptığım ifşa çalışması işe yaramadı.
USOM'a yazdım, "benim işim değil" dedi.
Ticari Elektronik İleti Şikayet Sistemi kumar/bahis şikayetlerini kabul etmiyor.
Sonunda dayanamayıp telefon operatörünü aradım, bağırıp çağırdım. Sonra e-devlet'e girip İleti Yönetim Sistemi'nden tüm izinleri kaldırdım (orada bankalar, mağazalar, şirketler vs var, hepsinden izinleri kapattım).
Bilmiyorum hangisi işe yaradı ama yaklaşık 1 aydır kumar/bahis mesajları artık gelmiyor.
