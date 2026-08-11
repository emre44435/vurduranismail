# Google Search Console yayın notu — darendedijital.com

Bu paket `https://darendedijital.com/` alan adına göre hazırlanmıştır.

## Yayından sonra

1. GitHub Pages özel alan adı olarak `darendedijital.com` kullanın. Paket kökündeki `CNAME` bu alan adıyla eşleşir.
2. Search Console'da mümkünse **Alan adı (Domain) mülkü** oluşturun ve Google'ın verdiği DNS TXT kaydıyla doğrulayın. Bu yöntem için HTML'e doğrulama etiketi eklemek gerekmez.
3. URL ön eki yöntemi kullanılacaksa Google'ın verdiği `google-site-verification` değerini ana sayfanın `<head>` bölümüne ekleyin. Doğrulanmamış/uydurma token eklenmemiştir.
4. Search Console > Site Haritaları bölümüne `sitemap.xml` gönderin.
5. Canlı yayında şu adresleri kontrol edin: `/robots.txt`, `/sitemap.xml` ve ana sayfanın canonical etiketi.
6. Tercih edilen tek alan adı `https://darendedijital.com` olmalıdır; başka alan adlarından gelen trafik varsa sunucu/DNS katmanında 301 yönlendirme yapılmalıdır.

## Pakette düzeltilen teknik sinyaller

- Canonical URL'ler: `https://darendedijital.com/...`
- Open Graph URL ve görsel mutlak URL'leri: `darendedijital.com`
- JSON-LD Organization / Service / Breadcrumb URL'leri: `darendedijital.com`
- `robots.txt` sitemap bildirimi: `https://darendedijital.com/sitemap.xml`
- `sitemap.xml` URL'leri: `https://darendedijital.com/...`
- GitHub Pages `CNAME`: `darendedijital.com`
- 404 sayfası: `noindex,follow`, kök dizinden çalışan varlık ve navigasyon yolları
