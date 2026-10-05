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
Due to Microsoft’s copyright policies and distribution terms, **pre-built ISO images are NOT provided** in this repository. However, you can use the included `clean-ltsc-preset.xml` file inside NTLite to build your own clean, optimized image legally from an official Microsoft ISO.

### 🚀 Step-by-Step Guide: How to Build Your Custom LTSC Image
1. **Download the Official ISO:** Obtain an official evaluation or licensed **Windows 11 Enterprise LTSC** ISO from the official Microsoft Evaluation Center or your MSDN/VLSC portal.
2. **Extract or Mount the ISO:** Right-click the downloaded ISO file and select **Mount** (or extract its contents using 7-Zip/WinRAR to a local folder on your drive).
3. **Set Up NTLite:** Download and install the free version of **NTLite** on your host machine.
4. **Load the Source Image:** 
   * Open NTLite, click on **Add** at the top left, and select **Image directory (folder)** pointing to your mounted/extracted Windows 11 LTSC files.
   * Select the specific edition (e.g., *Windows 11 Enterprise LTSC*) when prompted and let NTLite load the image.
5. **Import the Preset:** 
   * Go to the **Presets** tab in NTLite.
   * Click on **Import** and select the **`clean-ltsc-preset.xml`** file from this repository.
   * Load/apply the preset to configure all component removals and settings automatically.
6. **Review and Process:** 
   * Review the changes across the Components, Services, and Settings tabs if desired.
   * Navigate to the **Apply** tab, check **Save changes to image**, enable **Create ISO**, and hit the **Proceed** (Play) button at the top.
7. **Done:** Once the process finishes, your customized, game-optimized LTSC ISO file will be ready on your disk for a clean installation via USB!

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
Microsoft'un telif hakkı politikaları ve dağıtım koşulları nedeniyle bu repoda **hazır ISO görüntüleri YER ALMAMAKTADIR**. Ancak, resmi bir Microsoft ISO'sundan kendi temiz imajınızı yasal olarak oluşturmak için NTLite içinde ürünle birlikte gelen `clean-ltsc-preset.xml` dosyasını kullanabilirsiniz.

### 🚀 Adım Adım Rehber: Özel LTSC İmajınızı Nasıl Oluşturursunuz?
1. **Orijinal ISO'yu İndirin:** Microsoft Evaluation Center veya resmi lisanslı kanallar üzerinden orijinal **Windows 11 Enterprise LTSC** ISO dosyasını temin edin.
2. **ISO'yu Sürücüye Bağlayın (Mount):** İndirdiğiniz ISO dosyasına sağ tıklayıp **Bağla (Mount)** seçeneğini seçin (Alternatif olarak 7-Zip ile klasöre de çıkartabilirsiniz).
3. **NTLite'ı Hazırlayın:** Bilgisayarınıza **NTLite** programının güncel sürümünü kurun.
4. **Kaynak İmajı NTLite'a Yükleyin:** 
   * NTLite'ı açın, sol üstteki **Ekle (Add)** butonuna basın ve bağladığınız/çıkarttığınız Windows 11 LTSC klasörünü seçin.
   * Listeden uygun sürümü (*Windows 11 Enterprise LTSC*) seçerek imajın yüklenmesini bekleyin.
5. **Preset Dosyasını İçe Aktarın:** 
   * NTLite içindeki **Presets (Ön Ayarlar)** sekmesine gelin.
   * **İçe Aktar (Import)** diyerek bu repodan indirdiğiniz **`clean-ltsc-preset.xml`** dosyasını seçin ve yükleyin.
6. **İnceleyin ve İşlemi Başlatın:** 
   * İsterseniz bileşenler ve servisler sekmesinden yapılan ayarları gözden geçirebilirsiniz.
   * **Apply (Uygula)** sekmesine gelin, değişiklikleri imaja kaydet seçeneğini işaretleyin, **ISO oluştur (Create ISO)** kutucuğunu aktif edin ve üstteki **Proceed (İşle / Başlat)** butonuna tıklayın.
7. **Hazır!** İşlem tamamlandığında, USB belleğe yazdırarak temiz kurulum yapabileceğiniz optimize edilmiş özel LTSC ISO dosfanız masaüstünüzde hazır olacaktır.
