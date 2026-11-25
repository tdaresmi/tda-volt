> # TDA Volt
>
> TDA Volt, elektriğin temel kavramlarını Türkçe ve mobil uyumlu, etkileşimli bir eğitim demosuyla tanıtır.
>
> ## Özellikler
>
> * Elektrik konularını anlatan eğitim kartları
> * Düşük gerilim kavramlarını gösteren basit devre simülasyonu
> * Üç soruluk mini sınav
> * Temel konular hakkında önceden hazırlanmış örnek yanıtlar veren demo asistan
> * Mobil uyumlu tasarım, çizimler ve animasyonlar
>
> Bu sürüm tek bir HTML dosyasından oluşur; harici kütüphane, derleme adımı veya sunucu tarafı kodu gerektirmez.
>
> ## Dosya yapısı
>
> ```text
> .
> ├── README.md
> ├── LICENSE
> └── voltusta/
>     └── index.html
> ```
>
> ## Yerel önizleme
>
> Python 3 kuruluysa terminalde şu komutları çalıştır:
>
> ```bash
> cd voltusta
> python3 -m http.server 8000
> ```
>
> Ardından tarayıcıda `http://localhost:8000` adresini aç. `voltusta/index.html` dosyasını doğrudan tarayıcıda açmak da mümkündür.
>
> ## GitHub ve Vercel ile yayınlama
>
> 1. GitHub’da yeni bir depo oluştur.
> 2. `README.md`, `LICENSE` ve `voltusta/index.html` dosyalarını yukarıdaki yapıyı koruyarak yükle.
> 3. Vercel’de **Add New → Project** seçip GitHub deposunu içe aktar.
> 4. **Root Directory** olarak `voltusta` klasörünü seç.
> 5. Framework sorulursa **Other** seç; build komutu gerekmez. Çıktı klasörü istenirse `.` kullan.
> 6. **Deploy**’a bas. Sonraki GitHub commit’lerin Vercel’de yeni dağıtımları tetikler.
>
> ## Lisans
>
> Bu proje Apache License 2.0 altında lisanslanmıştır. Lisansın tam metnini içeren `LICENSE` dosyasını depo köküne ekle.
>
> ## Önemli notlar
>
> * Asistan bu sürümde yalnızca önceden yazılmış örnek yanıtları verir; canlı yapay zekâ bağlantısı, kullanıcı hesabı veya veri saklayan bir arka uç yoktur.
> * Site eğitim ve temel kavramları tanıtma amaçlıdır; gerçek tesisat veya enerjili ekipman üzerinde çalışma talimatı değildir. Şebeke elektriğiyle çalışma uygun eğitim, yetkilendirme ve geçerli güvenlik prosedürleri gerektirir.
