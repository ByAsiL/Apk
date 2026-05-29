# İhale Kayıt Paneli v4

Bu paket GitHub Pages üzerinde yayınlanabilecek mobil uyumlu bir PWA uygulamasıdır.

## İçerik

- `index.html` — ana uygulama
- `manifest.json` — mobil uygulama/PWA bilgileri
- `service-worker.js` — offline çalışma ve önbellek
- `icons/` — uygulama ikonları
- `.nojekyll` — GitHub Pages'in dosyaları değiştirmeden yayınlaması için

## GitHub Pages'e yükleme

1. GitHub'da yeni bir repository açın. Örnek ad: `ihale-kayit-paneli`
2. Bu ZIP içindeki dosyaları repository içine yükleyin. Dosyalar repo kök dizininde olmalı.
3. GitHub'da repository sayfasında **Settings > Pages** bölümüne girin.
4. **Source** alanında `Deploy from a branch` seçin.
5. Branch olarak `main`, klasör olarak `/root` seçin ve kaydedin.
6. GitHub birkaç dakika içinde size bir Pages linki verir.
7. Linki telefonda açın.
8. Android Chrome'da menüden **Ana ekrana ekle** seçeneğini kullanın.

## Kullanım

1. Uygulamayı açın.
2. **İhale Kaydet** butonuna basın.
3. ChatGPT'den aldığınız ihale notunu metin alanına yapıştırın.
4. **Otomatik Doldur** butonuna basın.
5. Eksik/düzeltilecek alan varsa düzenleyin.
6. **Kaydet** butonuna basın.
7. **Kayıtlı İhaleler** ekranında sadece İKN ve ihaleye kalan gün görünür.

## Önemli güvenlik notu

Bu uygulama verileri cihazın tarayıcı hafızasında `localStorage` ile saklar. Bu yapı ihale notları, yaklaşık maliyet, teklif stratejisi ve malzeme listeleri için uygundur.

Bu uygulamaya kesinlikle şifre, banka bilgisi, EKAP/Maliye/SGK giriş bilgisi veya e-posta şifresi kaydetmeyin.

## Yedekleme

Ana ekrandaki **Dışa Aktar** butonuyla kayıtları JSON olarak indirin. Telefon değişirse veya tarayıcı verileri silinirse kayıtları geri almak için **İçe Aktar** butonunu kullanabilirsiniz.


## v4 Güncellemesi
- Ana ekran toplam/gelecek/bugün/geçmiş ihale butonları tıklanabilir hale getirildi.
- Mal, Hizmet, İnşaat/Yapım ve Danışmanlık ihale türü eklendi.
- Kayıtlı ihalelerde durum ve ihale türü filtreleri eklendi.
- Ana ekrandaki cihaz uyarısı ve tümünü sil butonu kaldırıldı.
- Detay sayfasındaki Ham Metin ve Meta bölümü kaldırıldı.
