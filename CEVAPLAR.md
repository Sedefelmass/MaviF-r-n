# SEO ve Web Analitiği – Hafta 1-2-3 Cevapları (Mavi Fırın)

## HAFTA 1 – SEO ve Web Sitesini Tanıma
**U1** "Eskişehir tam buğday ekmeği" aramasında kullanıcı: ürün bilgisi, bulunabilirlik ve işletme adresi ister.
**S1** "Yakınımdaki fırın": güncel adres, çalışma saatleri ve iletişim öne çıkmalı.
**U2** Sayfalar: index.html, urunler.html, hakkimizda.html, iletisim.html
**S2** Ana sayfa: tanıtım ve yönlendirme · Ürünler: ekmek/poğaça çeşitleri · Hakkımızda: işletmenin tanıtımı · İletişim: adres ve ulaşım.
**U3** Başlık: "Mavi Fırın | Eskişehir Taze Ekmek" — Açıklama: "Günlük ekmek çeşitlerini ve adresimizi keşfedin."
**S3** Ürünler sayfası: "Ekmek Çeşitleri | Mavi Fırın" — "Tam buğday, köy ekmeği, poğaça ve simit: Mavi Fırın'ın günlük taze ürün çeşitlerini inceleyin."
**U4** Ziyaretçi şu 3 bilgiye ulaşmalı: ürünler, adres/iletişim, işletme hakkında kısa bilgi.
**S4** Eksik olabilecek iki bilgi: güncel çalışma saatleri ve ürün fotoğrafları.

## HAFTA 2 – HTML, CSS ve Sayfa Yapısı
**U1** `<h1>` sayfanın ana konusunu belirtir (Mavi Fırın). → index.html
**S1** `<h1>Mavi Fırın – Günlük Taze Ekmek</h1>`
**U2** `<a href="urunler.html">Ürünleri Gör</a>` → index.html
**S2** `<a href="hakkimizda.html">Hakkımızda</a>` → index.html (menüde)
**U3** `h1 { color: #163b65; }` → style.css
**S3** `a { text-decoration: underline; }` → style.css
**U4** Tarayıcıyı daralttım: metin kaymıyor, bağlantılar tıklanabilir (menü alt satıra geçiyor).
**S4** Taşan öğe olursa sabit genişliği kaldırmak veya `max-width: 100%` kullanmak (style.css'te `img, table { max-width:100%; }`).

## HAFTA 3 – GitHub Pages ile Yayınlama
**U1** GitHub > New repository > ad: mavi-firin > Public.
**S1** Depo açıklaması: "SEO dersi için örnek Türkçe fırın web sitesi."
**U2** Add file > Upload files > tüm dosyalar > Commit changes (index.html ana dizinde).
**S2** İkinci commit: H1 başlığını değiştirip commit mesajı: "Ana sayfa başlığı güncellendi".
**U3** Settings > Pages > Deploy from a branch > main > /(root) > Save; adres açılana kadar 1-2 dk bekle.
**S3** Yayın adresini telefonda aç: menü ve metin görünmeli.
**U4** CSS görünmüyorsa: style.css dosyasının konumunu ve `<link rel="stylesheet" href="style.css">` yolunu kontrol et.
**S4** 404 verirse: urunler.html dosya adı ile href değerinin birebir aynı olduğunu (küçük/büyük harf dahil) kontrol et.
