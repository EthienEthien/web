---
title: Flutter WebView App
---
{% include_relative README.md %}

Flutter WebView Uygulaması

📌 Açıklama

Flutter ile oluşturulmuş basit ve çapraz platform bir uygulamadır. Web sitesini WebView içinde yükler. Android ve iOS üzerinde çalışır.
Bu durumda, playnileonline.com'daki futbol sonuçlarını doğrudan telefonunuzdan takip etmek için bir web görüntüleme uygulaması yaptık

🚀 Özellikler

Web sitesini uygulama içinde açma

JavaScript desteği

Çapraz platform desteği (Android/iOS)

📂 Kurulum ve Çalıştırma

1. Flutter Kurulumu (Eğer yüklü değilse)

Resmi Kurulum Kılavuzu

2. Depoyu Klonla

git clone https://github.com/app.git
cd flutter_webview_app

3. Bağımlılıkları Yükle

flutter pub get

4. Emulator veya Cihazda Çalıştır

flutter run

🔧 WebView Ayarları

Varsayılan olarak https://example.com yüklenir. Web sitesini değiştirmek için lib/main.dart dosyasını açın ve şu satırı değiştirin:

..loadRequest(Uri.parse("https://example.com"));

📦 APK/IPA Derleme

Android APK oluşturmak için:

flutter build apk

iOS için derleme (sadece macOS üzerinde):

flutter build ios

📄 Lisans

Bu proje MIT lisansı altında dağıtılmaktadır.

