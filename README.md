# Bilgisayarlı Görü ile Perakende Raf Uyumluluğu

Raf fotoğraflarından ürün tespiti ve tanıma yaparak planogram (raf yerleşim planı)
uyumluluğunun otomatik olarak kontrol edilmesini amaçlayan bir bilgisayarlı görü projesi.

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