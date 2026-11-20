# Türkiye Coğrafyası İnteraktif 3D Atlası

AGS 2027 ve KPSS için harita tabanlı Türkiye coğrafyası öğrenme projesi.

## İçerik
- `index.html`: 15 öğrenme modüllü Türkiye atlası; MapLibre GL JS, Esri World Topographic Map ve Terrarium DEM ile 3D arazi görünümü.
- `studio/index.html`: 3D Creative Studio'daki Three.js, OrbitControls ve Raycaster yaklaşımıyla oluşturulmuş etkileşimli yer şekilleri laboratuvarı. Kıvrım dağları, horst-graben, volkanik dağ, plato, delta ve karst modelleri.
- `studio/madde-donguleri.html`: Daha önceki 3D Creative Studio biyoloji örneğinin özgün dosyası; ana coğrafya atlasından bağımsız örnek olarak korunmuştur.
- `.github/workflows/pages.yml`: GitHub Pages otomatik yayın iş akışı.

## Yerelde çalıştırma
Statik site; derleme gerekmez. Harita ve 3D modülleri için internet bağlantısı gerekir.

## GitHub Pages
Repository Settings → Pages → Build and deployment → Source bölümünde **GitHub Actions** seç. Sonraki `main` push'ları siteyi otomatik yayımlar.

## Veri notu
Haritadaki noktalar eğitim amaçlı örnek odaklardır; her işaret bir alanın tüm yayılışını göstermez. 3D yer şekilleri modelleri jeomorfolojik süreçleri anlatan şematik modellerdir, ölçümsel jeolojik kesit değildir. Veri kaynakları ve sınırlamalar ana sayfanın alt kısmında belirtilmiştir.
