# Yol Çizgisi Tespiti

## 🌍 Dil Seçenekleri / Language Options
- 🇹🇷 [Türkçe](README.md) (Mevcut)
- 🇺🇸 [English](README_EN.md)

---

Bu proje, video dosyalarında yol çizgilerini tespit etmek için geliştirilmiş bir Python uygulamasıdır.

## 📸 Ekran Görüntüleri / Screenshots


---

## Özellikler
- Video dosyalarında yol çizgisi tespiti
- OpenCV kullanarak görüntü işleme
- Gerçek zamanlı analiz
- Gelişmiş bilgisayarlı görü algoritmaları

## Kurulum
```bash
pip install -r requirements.txt
```

## Kullanım
```bash
python Yol_cizgisi_tespiti.py
```

## Gereksinimler
- Python 3.7+
- OpenCV
- NumPy

## Proje Hakkında
Bu proje, sürüş güvenliğini artırmak amacıyla geliştirilmiş bir yol çizgisi tespit sistemidir. OpenCV ve NumPy kütüphaneleri kullanılarak video akışında gerçek zamanlı olarak yol çizgileri tespit edilir.

## Nasıl Çalışır
Sistem video karelerini birkaç aşamada işler:
1. **Görüntü Ön İşleme**: Gri tonlama dönüşümü ve gürültü azaltma
2. **Kenar Tespiti**: Canny kenar tespit algoritması
3. **İlgi Alanı**: Yol bölgesine odaklanma
4. **Çizgi Tespiti**: Hough dönüşümü ile çizgi tespiti
5. **Şerit Takibi**: Tespit edilen çizgileri filtreleme ve yumuşatma

## Proje Yapısı
```
├── Yol_cizgisi_tespiti.py    # Ana uygulama dosyası
├── video1.mp4                # Örnek video 1
├── video2.mp4                # Örnek video 2
├── requirements.txt           # Python bağımlılıkları
├── README.md                 # Türkçe dokümantasyon
├── README_EN.md              # İngilizce dokümantasyon
├── screenshots/              # Ekran görüntüleri
└── LICENSE                   # MIT Lisansı
```

## Katkıda Bulunma
Katkılarınızı bekliyoruz! Lütfen:
- Hata bildirimi veya özellik istekleri için issue açın
- İyileştirmeler için pull request gönderin
- Geliştirme veya optimizasyon önerilerinde bulunun

## Geliştirme Kurulumu
1. Repository'yi klonlayın
2. Bağımlılıkları yükleyin: `pip install -r requirements.txt`
3. Uygulamayı çalıştırın: `python Yol_cizgisi_tespiti.py`

## Lisans
Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakın.

## Teşekkürler
- Bilgisayarlı görü araçları için OpenCV topluluğu
- Sayısal hesaplama yetenekleri için NumPy
- Bu projenin katkıda bulunanları ve test edenleri
