📊 İstatistik V2: Dijital Entegrasyon Projesi

"İstatistiksel bilginin statik sayfalardan çıkıp dinamik laboratuvarlara dönüştüğü yer."

📖 Proje Hakkında

Bu proje, geleneksel bir istatistik ders kitabını, QR kod entegrasyonlu interaktif dijital laboratuvarlar ve RAG (Retrieval-Augmented Generation) tabanlı yapay zeka asistanı ile birleştirerek öğrencilerin "teoriden pratiğe" geçiş hızını artırmayı hedeflemektedir.

Artık öğrenciler; Merkezi Limit Teoremi'ni, Bayesçi Çıkarımı veya Hipotez Testlerini sadece formül olarak okumak yerine, kendi tarayıcılarında simüle ederek öğreniyorlar.

🚀 Öne Çıkan Özellikler

Özellik

Açıklama

İnteraktif Lablar

Her bölüm sonunda yer alan, doğrudan tarayıcıda çalışan web tabanlı simülatörler.

RAG AI Asistan

Kitabın içeriğiyle eğitilmiş, sadece kitabınızdaki tanımları baz alan özel yapay zeka desteği.

QR Kod Entegrasyonu

Kitabın sayfalarından dijital laboratuvarlara anında geçiş sağlayan akıllı karekod yapısı.

Sıfır Kurulum

Tüm simülatörler "vanilla" JS/HTML/Tailwind kullanır; sunucu maliyeti gerektirmez.

🧪 Laboratuvarlar (Bölümden Bölüme)

Projemiz toplam 9 ana bölümden oluşan bir istatistik serüvenini kapsar:

Bölüm 1: Örnekleme ve Merkezi Limit Teoremi Simülasyonu

Bölüm 2: Sapma (Bias) ve Varyans Dengesi (Hedef Tahtası)

Bölüm 3: Güven Aralığı Kapsama Simülatörü

Bölüm 4: Tip I ve II Hata - Güç Analizi (Tahterevalli Modeli)

Bölüm 5: OLS (En Küçük Kareler) Doğrusu Uydurma Oyunu

Bölüm 6: ANOVA - F-İstatistiği ve Sinyal/Gürültü Dengesi

Bölüm 7: Ki-Kare Testleri ve Kategorik Veri Matrisi

Bölüm 8: Non-Parametrik Testlerin Sağlamlık (Robustness) Analizi

Bölüm 9: Bayesçi İnanç Güncelleme (Prior & Likelihood)

🛠️ Teknik Altyapı

Bu proje, performans ve erişilebilirlik odaklı olarak inşa edilmiştir:

Frontend: HTML5, TailwindCSS, Chart.js.

Backend: Statik barındırma (GitHub Pages / Vercel için optimize).

AI: Vektör veritabanı destekli RAG (Retrieval-Augmented Generation) mimarisi.
<img width="803" height="385" alt="image" src="https://github.com/user-attachments/assets/1f1bcb62-582a-4977-b3ae-476b94d0d375" />


📂 Dosya Yapısı

/
├── lab/
│   ├── bolum1_mcl_lab.html
│   ├── bolum5_regression_lab.html
│   └── ... (Tüm bölümler)
├── assets/
│   ├── qr_codes/      # Kitap için üretilen yüksek çözünürlüklü QR kodlar
│   └── images/
└── README.md


💡 Katkıda Bulunma

Bu proje, istatistik eğitimini demokratikleştirmeyi amaçlayan bir açık kaynak girişimidir. Yeni simülatörler eklemek veya mevcut olanları geliştirmek isterseniz Pull Request gönderebilirsiniz.

İstatistik öğrenmek artık sadece okumak değil, bizzat deneyimlemektir!

İstatistik V2 © 2026 | Eğitim Teknolojileri Bölümü
