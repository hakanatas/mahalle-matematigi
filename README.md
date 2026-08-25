# Mahalle Matematiği 🏘️➕

MEB 5. sınıf matematik müfredatının tamamını (7 ünite, 15 konu) kapsayan interaktif eğitim sitesi.

## Yapı

Site ünitelere bölünmüştür; her ünitenin kendi klasörü ve kendi kapak sayfası vardır. Üniteler öğrencilerle tek tek, ayrı sayfalar/linkler olarak paylaşılabilir; her ünite klasörü kendi başına (internetsiz de) çalışır.

```
index.html                  → 7 üniteye açılan ana menü
unite1-geometrik-sekiller/
  index.html                → ünite kapak sayfası (konu kartları)
  konu1-kayip-cizgiler/
    index.html              → interaktif hikâye kitabı (5 sayfa, sesli okuma, görevler)
    arac.html               → akıllı tahta için çok sekmeli interaktif araç
    assets/                 → kapak ve sayfa görselleri
  konu2-acilar/ ...
unite2-dogal-sayilar/ ...
```

## Üniteler

1. **Geometrik Şekiller** — 5 konu (`unite1-geometrik-sekiller/`)
2. **Sayılar ve Nicelikler: Doğal Sayılar** — 2 konu (`unite2-dogal-sayilar/`)
3. **Geometrik Nicelikler** — 1 konu (`unite3-geometrik-nicelikler/`)
4. **Sayılar ve Nicelikler: Kesirler** — 2 konu (`unite4-kesirler/`)
5. **İstatistiksel Araştırma Süreci** — 2 konu (`unite5-istatistik/`)
6. **İşlemlerle Cebirsel Düşünme** — 2 konu (`unite6-cebirsel-dusunme/`)
7. **Veriden Olasılığa** — 1 konu (`unite7-olasilik/`)

Hiçbir dış kütüphane gerekmez; internetsiz çalışır (yalnızca Google Fonts çevrimiçiyken yüklenir).
