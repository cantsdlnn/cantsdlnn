# Merhaba, ben Nusret Can Taşdelen 👋

Ankara Yıldırım Beyazıt Üniversitesi Bilgisayar Programcılığı öğrencisiyim. Yazılım alanındaki lise eğitimimin üzerine C#/.NET, Python ve TypeScript ile gerçek bir ihtiyacı çalışan, test edilen ve sınırları açıkça belgelenen yazılımlara dönüştürmeye odaklanıyorum.

Benim için iyi bir proje yalnızca güzel görünen bir ekran değildir: iş kuralı, veri modeli, hata davranışı, güvenlik sınırı ve doğrulama kanıtı birlikte anlaşılabilmelidir.

## Öne çıkan projeler

| Proje | Problem ve yaklaşım | Teknoloji | Doğrulama |
|---|---|---|---|
| [Kameralı Plaka Tanımalı Otopark Otomasyonu](https://github.com/cantsdlnn/kamerali-plaka-tanimali-otopark-otomasyonu) | Kamera/OCR, araç giriş-çıkışı, park yeri, ücret ve ödeme akışlarını tek sistemde birleştirir. PBKDF2 parola geçişi, yerel OCR sınırı ve tehdit modeli içerir. | C#, .NET 8 WinForms, SQL Server, FastAPI, EasyOCR, OpenCV, Tesseract | 21 xUnit + 27 pytest, CI, bağımlılık taraması |
| [BelgeKalkan](https://github.com/cantsdlnn/belge-kalkan) | Türkçe metindeki T.C. kimlik, IBAN, telefon ve e-postayı harici modele göndermeden bulur; ham değeri API yanıtında tekrar taşımadan maskeler. | Python, FastAPI, checksum kuralları, HMAC | 18 test, %97 kapsam, Ruff, CI, Docker |
| [Ölçüm Pusulası](https://github.com/cantsdlnn/olcum-pusulasi) | Sınav maddelerini güçlük, ayırt edicilik ve KR-20 ile inceler; gerekçeli uyarı üretir, kararı öğretmende bırakır. | C#, .NET 8, ASP.NET Core | 5 xUnit, yöntem notu, CI, Docker |
| [Yörünge Gözcü](https://github.com/cantsdlnn/yorunge-gozcu) · [Canlı demo](https://cantsdlnn.github.io/yorunge-gozcu/) | TLE verisini SGP4 ile ilerletip yer istasyonu için geçiş pencerelerini hesaplar; eski veriyi güncelmiş gibi göstermeyen örnek modu içerir. | TypeScript, Vite, satellite.js, SGP4 | 8 test, %96 satır kapsamı, bağımlılık denetimi, CI |
| [TraceAI Karar Defteri](https://github.com/cantsdlnn/traceai-karar-defteri) | Bir sınıflandırmanın sonucuyla birlikte model/kural sürümünü, gerekçesini, insan kararını ve itirazını denetlenebilir biçimde kaydeder. Yalnız sentetik veri kullanır. | Python, FastAPI, SQLite, hash zinciri | 13 test, %92 kapsam, model/veri kartı, CI, Docker |
| [VeriYaşam](https://github.com/cantsdlnn/veri-yasam) | Veri envanteri ve saklama süresini izler; anonimleştirme/silme kararını otomatikleştirmek yerine gerekçeli insan onayına bırakır. | Python, FastAPI, SQLite | 8 test, audit bütünlük testi, CI, Docker |
| [Sıra Açık](https://github.com/cantsdlnn/sira-acik) | Küçük işletmeler için telefon veya e-posta toplamadan canlı sıra yönetir; beklemeyi medyan süreyle açıklanabilir biçimde tahmin eder. | .NET 8, ASP.NET Core, EF Core, SQLite | 8 test, SQLite entegrasyon testi, CI, Docker |
| [Adil Paylaş](https://github.com/cantsdlnn/adil-paylas) · [Canlı demo](https://cantsdlnn.github.io/adil-paylas/) | Ortak harcamaları tam sayı kuruşla böler, artıkları deterministik dağıtır ve küçük gruplarda en az transferli kapatma planını arar. | TypeScript, Vite, PWA | 15 test, özellik tabanlı testler, CI |
| [Son Kullan](https://github.com/cantsdlnn/son-kullan) · [Canlı demo](https://cantsdlnn.github.io/son-kullan/) | Ev stoğunu son kullanma tarihine göre önceliklendirir, çevrimdışı çalışır ve israf eğilimini yerel olarak görünür kılar. | TypeScript, Vite, PWA | 25 test, tarih sınır testleri, CI |

## Nasıl çalışıyorum?

- Koddan önce gereksinimleri ve kabul ölçütlerini yazıyorum.
- İş kurallarını arayüzden ayırıp birim ve entegrasyon testleriyle doğruluyorum.
- Kişisel veri toplamamayı, yetki sınırını ve saklama davranışını tasarım kararı olarak ele alıyorum.
- CI, bağımlılık taraması, güvenlik politikası ve mimari karar kayıtlarını projenin parçası sayıyorum.
- Eksik kalan noktaları “üretime hazır” diye gizlemek yerine README ve tehdit modelinde açıkça belirtiyorum.

## Yapay zekâyı nasıl kullanıyorum?

Üretken yapay zekâyı araştırma, alternatif tasarım üretme, test senaryolarını genişletme, kod inceleme ve dokümantasyon desteği için eşli geliştirme aracı olarak kullanıyorum. Çıktıları doğrudan doğru kabul etmiyorum; mimari karar, veri sınırı, güvenlik değerlendirmesi ve nihai doğrulama sorumluluğunu üstleniyorum.

Her projede neyin AI desteğiyle, neyin deterministik çalışma zamanı koduyla yapıldığını açıklayan bir `AI_USAGE.md` bulunur. Böylece AI kullanımını saklamadan, kullandığım kodu ve verdiğim kararları anlayabildiğimi gösteriyorum.

## Teknik odak

`C#` · `.NET 8` · `ASP.NET Core` · `WinForms` · `SQL Server` · `EF Core` · `Python` · `FastAPI` · `TypeScript` · `SQLite` · `OpenCV` · `SGP4` · `GitHub Actions` · `Docker`

## Kısa İngilizce özet

I am a Computer Programming student focused on turning everyday and operational problems into tested, documented software. My portfolio covers .NET, Python/FastAPI, TypeScript, computer vision, privacy-aware workflows, auditable decision systems, CI, and honest AI-assisted development disclosures.

## İletişim

- GitHub: [@cantsdlnn](https://github.com/cantsdlnn)
- E-posta: [tasdelennusretcan58@gmail.com](mailto:tasdelennusretcan58@gmail.com)
