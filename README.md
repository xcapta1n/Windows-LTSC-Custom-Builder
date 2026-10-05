# Windows 11 LTSC Custom Optimization & Gaming Preset 🚀

[English](#english) | [Türkçe](#türkçe)

---

<a name="english"></a>
## 🇬🇧 English

This repository contains my custom NTLite configuration preset and documentation for building an optimized, lightweight, and **gaming-focused** Windows 11 Enterprise LTSC (24H2) image.

### 📌 Project Overview
Standard operating systems come pre-loaded with excessive telemetry, background resource hogs, and unnecessary bloatware that negatively impact system latency and frame rates. This project is specifically engineered around deep component removal and Windows service/setting adjustments to maximize hardware efficiency for gaming and productivity workloads.

### 🛠 Key Optimizations & Adjustments
* **Component Removal & Debloating:** Safely stripped non-essential legacy components, media players, and resource-heavy system apps via DISM/NTLite integration to free up RAM and CPU overhead.
* **Windows Settings & Service Tuning:** Configured targeted Windows settings and shifted redundant system/diagnostic services to manual or disabled states to reduce background CPU usage.
* **Privacy & Telemetry Hardening:** Disabled cloud search tracking, Bing integration, Windows Copilot, and background telemetry data collection.
* **Gaming & Dev Compatibility:** Carefully preserved core dependencies (DirectX, Visual C++, .NET runtimes) to ensure zero friction for gaming and software development tasks.

### ⚠️ Important Note on Copyright & Licensing
Due to Microsoft’s copyright policies and distribution terms, **pre-built ISO images are NOT provided** in this repository. However, you can use the included `windows-ltsc-debloat-preset.xml` file inside NTLite to build your own clean, optimized image legally from an official Microsoft ISO.

### 🚀 How to Use
1. Download an official Windows 11 Enterprise LTSC ISO.
2. Open **NTLite** and load the image.
3. Import the `windows-ltsc-debloat-preset.xml` file into NTLite.
4. Review the components/tweaks and hit **Process** to generate your custom optimized ISO.

---

<a name="türkçe"></a>
## 🇹🇷 Türkçe

Bu repo, maksimum düzeyde hafifletilmiş, gereksiz yüklerden arındırılmış ve **oyun odaklı** bir Windows 11 Enterprise LTSC (24H2) imajı oluşturmak için hazırladığım özel NTLite yapılandırma preset (ayar) dosyasını ve belgelerini içerir.

### 📌 Proje Özeti
Standart işletim sistemleri; arka planda çalışan gereksiz servisler, telemetri araçları ve sistem kaynaklarını sömüren şişkin uygulamalarla (bloatware) birlikte gelir. Bu proje; derinlemesine bileşen temizliği (debloat) ve Windows dahili ayar/servis yapılandırmaları üzerine odaklanarak donanım verimliliğini artırmayı ve oyun performansını optimize etmeyi amaçlar.

### 🛠 Temel Optimizasyonlar ve Ayarlamalar
* **Bileşen Temizliği ve Debloat:** RAM ve CPU yükünü hafifletmek için DISM ve NTLite entegrasyonuyla eski, gereksiz sistem bileşenleri, medya oynatıcılar ve arka plan uygulama katmanları güvenli bir şekilde ayıklandı.
* **Windows Ayarları ve Servis Yapılandırması:** Arka plan CPU tüketimini azaltmak amacıyla hedef odaklı Windows ayarları yapıldı ve gereksiz tanı/sistem servisleri manuel veya devre dışı duruma getirildi.
* **Gizlilik ve Telemetri Sıkılaştırması:** Arka planda kaynak harcayan bulut arama takipleri, Bing entegrasyonu, Windows Copilot ve veri toplama servisleri kapatıldı.
* **Donanım ve Geliştirici Uyumluluğu:** Oyunlar ve yazılım geliştirme araçları için hayati önem taşıyan DirectX, Visual C++, .NET çalışma zamanları eksiksiz bir şekilde korundu.

### ⚠️ Telif Hakkı ve Lisanslama Üzerine Önemli Not
Microsoft'un telif hakkı politikaları ve dağıtım koşulları nedeniyle bu repoda **hazır ISO görüntüleri YER ALMAMAKTADIR**. Ancak, resmi bir Microsoft ISO'sundan kendi temiz imajınızı yasal olarak oluşturmak için NTLite içinde ürünle birlikte gelen `windows-ltsc-debloat-preset.xml` dosyasını kullanabilirsiniz.

### 🚀 Nasıl Kullanılır?
1. Resmi bir Windows 11 Enterprise LTSC ISO dosyası indirin.
2. **NTLite** programını açın ve imajı yükleyin.
3. `windows-ltsc-debloat-preset.xml` dosyasını NTLite'a aktarın (import edin).
4. Bileşenleri/ayarları inceleyin ve özel imajınızı oluşturmak için **Process (İşle)** butonuna basın.
