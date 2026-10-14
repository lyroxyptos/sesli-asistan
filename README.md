# Sesli Asistan (Türkçe)

Bu proje, Türkçe sesli komutları algılayarak çeşitli işlemleri gerçekleştiren bir **Sesli Asistan** uygulamasıdır.  
Kullanıcı "asistan" kelimesiyle asistanı tetikleyebilir ve ardından aşağıdaki komutları sesli olarak verebilir:

## 🔧 Özellikler

- **Ses Tanıma** (Google Speech Recognition ile)
- **Sesli Yanıt** (gTTS + pygame)
- **Google'da Arama**
- **Spotify'da Şarkı Arama**
- **Hava Durumu Sorgulama** (WeatherAPI ile)
- **Çöp Kutusu Boşaltma**
- **Program Kapatma (örn: Spotify)**
- **Masaüstündeki Kısayolları Açma**
- **Basit Tkinter GUI Arayüzü**

---

## ▶️ Kullanım

### 1. Gerekli Modüllerin Kurulumu

Projeyi çalıştırmadan önce gerekli kütüphaneleri aşağıdaki komutla yükleyin:

**pip install -r requirements.txt**

### 2. API Anahtarı

WeatherAPI üzerinden alınan bir API anahtarına ihtiyacınız var.  
Aşağıdaki satırı kendinize göre güncelleyin:

```python
API_KEY = "BURAYA_API_ANAHTARINIZI_YAZIN"
```

WeatherAPI: https://www.weatherapi.com/

Eğer API anahtarı almak istemiyorsanız bunu es geçebilirsiniz.

---

## 🎤 Örnek Sesli Komutlar

- `asistan` (Tetikleyici)
- `kapan` (Asistanı kapatır)
- `Google'da ara İstanbul hava durumu`
- `Spotify'da Aşk Yok Olmaktır aç`
- `çöp kutusunu boşalt`
- `kapat spotify`
- `masaüstünde Visual Studio Code aç`
- `hava durumu Ankara`

---

## 🖥 Arayüz

Program çalıştırıldığında basit bir pencere açılır ve kullanıcıdan `asistan` kelimesini söylemesi beklenir.  
Daha sonra kullanıcıdan komut alınır ve analiz edilerek ilgili işlem gerçekleştirilir.

---

## 📁 Dosya Yapısı

- `asistanım.py` — Uygulamanın tüm işlevlerini içerir.
- `requirements.txt` — Gerekli Python modülleri listesi.
- `LICENSE` — Kullanım koşulları.

---

## 🧠 Geliştirici

- **LyroXyptos**

---
