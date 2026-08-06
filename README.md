# Derece — Eğitim Platformu (Demo)

Apple × ChatGPT hissiyatında, tek dosyalık LGS deneme takip platformu demosu.

- **4 rol:** Okul Yönetimi · Öğretmen · Öğrenci · Veli
- Öğretmen: öğrenci arama, net/derece analizleri, interaktif grafikler, AI gelişim raporu, veli görüşme özeti, AI asistan (chat), Excel/PDF içe aktarma sihirbazı, manuel D/Y girişi
- Veli/Öğrenci: gelişim grafikleri, ders karnesi, sınav geçmişi
- Yönetim: şube analizi, ısı tablosu, okul → şube → öğrenci → veli hiyerarşisi

> **Not:** Tanıtım amaçlı statik demodur; tüm okul/öğrenci verileri kurgusaldır ve tarayıcıda deterministik olarak üretilir. Harici bağımlılık yoktur (vanilla JS + el yazımı SVG grafikler).

## Çalıştırma

Herhangi bir statik sunucu yeterli:

```bash
python3 -m http.server 3000
# http://localhost:3000
```
