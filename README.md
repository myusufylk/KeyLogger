# 🔑 Klavye Dinleyici

> ⚠️ \*\*Önemli:\*\* Bu proje yalnızca eğitim ve araştırma amaçlıdır. İzinsiz klavye girdisi kaydetmek yasadışıdır ve ciddi sonuçlar doğurur.

## 📌 Açıklama

Bu proje, **C# (.NET Framework) ve Windows Forms** ile geliştirilmiş bir klavye dinleme prototipidir. Amaç, tuş yakalama mekanizmasının çalışma prensibini öğretmek ve giriş olaylarını zamanlı olarak analiz etmektir.

> 🔒 Gizli veri kaydı veya başkalarının girdilerini izinsiz yakalamak için kullanılmamalıdır.

---

## 🗂 İçerik

* **Proje Türü:** C# .NET Framework — WinForms
* **Ana Dosya:** `Form1.cs`
* **Kütüphaneler:** `globalKeyboardHook`, `System.Net.Mail` (opsiyonel, varsayılan kapalı)

---

## 🎯 Amaç ve Kapsam

* Klavye hook mekanizmasının öğretimi
* Girdi olaylarının nasıl yakalandığını göstermek
* Hata ayıklama ve senaryo analizleri için log üretmek
* Etik ve güvenlik odaklı geliştirme göstermek

---

## ✨ Özellikler

* Harf, rakam, Türkçe karakterler, Enter, Backspace, Space gibi tuşları yakalar
* CapsLock durumunu takip eder
* Log dosyasını yerel ortamda oluşturur
* Ağ veya e-posta gönderimi opsiyoneldir ve varsayılan kapalıdır

---

## 🛠 Kurulum ve Çalıştırma

1. Depoyu klonlayın:

   ```bash
   git clone  https://github.com/myusufylk/KeyLogger.git
   ```
2. Visual Studio ile açın (`.sln` dosyası)
3. **Mail() fonksiyonunu test öncesi kapatın veya mock SMTP kullanın**
4. Debug modunda kendi makinenizde çalıştırın
5. Log dosyası uygulama klasöründe `input\_log.txt` olarak oluşturulur

---

## 🔧 Yapılandırma Notları

* E-posta/sunucu varsayılan olarak kapalı olmalı
* Kimlik bilgileri kaynak kodunda olmamalı
* Log dosyalarını kısa süreli tutun, test sonrası silin
* Üretim sürümünde loglama fonksiyonu kaldırılmalı

---

## 📝 Örnek Log Formatı

```

\[2025-10-03 23:00:12.345] KEY\_DOWN: Space

\[2025-10-03 23:00:12.678] LEFT\_CLICK

\[2025-10-03 23:00:13.012] KEY\_DOWN: A

```

> Hassas veriler loglanmamalıdır.

---

## ✅ Test & Değerlendirme

* Testler sadece izinli kullanıcıda yapılmalı
* Log dosyasının beklenen format ve sıra ile doğru çalıştığını doğrulayın
* Log ile oyun/senaryo tekrarları oluşturup analiz yapabilirsiniz

---

## ⚖️ Etik ve Yasal Uyarılar

* Başkalarının bilgisayarında çalıştırmak için yazılı izin alın
* Projenin amacı, veri saklama yeri ve ağ özelliklerini belgeleyin
* Test sonrası log dosyalarını silin

---

## 🛡 Güvenlik Önerileri

* Log dosyalarını şifreli veya maskelenmiş tutabilirsiniz
* Kullanıcı onayı olmadan loglama etkinleşmemeli
* Kod incelemesi ve statik analiz ile veri sızıntısı önleyin

---

## 🎓 Ödev Savunması İçin İpuçları

* Projenin eğitim/prototip olduğunu vurgulayın
* Ağ ve kimlik bilgileri ile ilgili önlemleri gösterin
* Hangi etik kurallara uyduğunuzu belirtin
* Test izinlerini ve log temizleme süreçlerini kanıtlayın

---

## 📄 Lisans

* Bu proje öğretici amaçlıdır.
* İzinli olmayan kullanım yasaktır

---

## 📬 İletişim

Proje sahibi: Mehmet Yusuf Yılıkoğlu

> Güvenli bir iletişim bilgisi veya GitHub profil bağlantısı ekleyebilirsiniz.
