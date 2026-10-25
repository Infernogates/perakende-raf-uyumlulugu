# Bilgisayarlı Görü ile Perakende Raf Uyumluluğu

Raf fotoğraflarından ürün tespiti ve tanıma yaparak planogram (raf yerleşim planı)
uyumluluğunun otomatik olarak kontrol edilmesini amaçlayan bir bilgisayarlı görü projesi.

## Literatür Özeti
Perakende zincirlerinde raf yerleşim planlarına (planogram) uyumsuzluk yaygın bir sorundur
ve manuel denetimler zaman alıcıdır. Literatürde raf fotoğraflarından ürün tespiti için
YOLO tabanlı nesne tespit modelleri, çok sayıda ürün (SKU) içeren kataloglar için ise
sınıflandırıcı eğitmek yerine görsel vektör temsilleri ve en yakın komşu araması ile
tanıma yaklaşımları öne çıkmaktadır. Görsel olarak benzer ürünlerin ayırt edilmesinde
OCR tabanlı metin eşleştirme destekleyici bir yöntem olarak kullanılmaktadır.

## Yöntem
Python, OpenCV ile perspektif düzeltme ve ızgara haritalama, YOLO ile nesne tespiti,
görsel benzerlik araması ile ürün tanıma, OCR ile metin eşleştirme.

## Veri Seti
Raf fotoğrafları ve planogram dosyaları.

## Klasör Yapısı
- `data/` – raf fotoğrafları, planogram dosyaları
- `notebooks/` – Colab / Jupyter denemeleri
- `src/` – kaynak kod
- `reports/` – haftalık raporlar