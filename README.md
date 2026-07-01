<div align="center">
  <h1>📊 İstatistik V2: Dijital Laboratuvarlar</h1>
  <p><i>"İstatistiksel bilginin statik sayfalardan çıkıp dinamik laboratuvarlara dönüştüğü yer."</i></p>
  <br/>
</div>

## 📖 Proje Hakkında

Bu proje, geleneksel bir istatistik ders kitabını, **QR kod entegrasyonlu interaktif dijital laboratuvarlar** ile birleştirerek öğrencilerin teoriden pratiğe geçiş hızını artırmayı hedeflemektedir.

Öğrenciler artık formülleri sadece okumakla kalmıyor; Merkezi Limit Teoremi'ni, Bayesçi Çıkarımı veya Hipotez Testlerini doğrudan **kendi tarayıcılarında simüle ederek, verilerle oynayarak ve sonuçları anlık görerek öğreniyorlar**.

---

## 🚀 Öne Çıkan Özellikler

| Özellik | Açıklama |
| :--- | :--- |
| 🧪 **İnteraktif Laboratuvarlar** | Her bölüm sonunda yer alan, doğrudan tarayıcıda çalışan web tabanlı simülatörler. |
| 📱 **QR Kod Entegrasyonu** | Kitabın sayfalarından dijital laboratuvarlara anında geçiş sağlayan akıllı karekod yapısı. |
| ⚡ **Sıfır Kurulum** | Tüm simülatörler HTML, Vanilla JS ve TailwindCSS ile hazırlanmıştır. Eklenti, sunucu veya ekstra yazılım gerektirmez. |

---

## 🔬 Laboratuvarlar (Bölümden Bölüme)

Projemiz toplam 9 ana bölümden oluşan bir istatistik serüvenini kapsar. Sayfayı ziyaret ederek veya kitaptaki karekodu okutarak anında pratik yapmaya başlayabilirsiniz!

* **[Bölüm 1: Merkezi Limit Teoremi](https://ibrahimguney.github.io/istatistik-lab/lab/bolum_1_laboratuvar.html)** - Örneklem boyutunun dağılım üzerindeki mucizevi etkisini simüle edin.
* **[Bölüm 2: Sapma ve Varyans](https://ibrahimguney.github.io/istatistik-lab/lab/bolum_2_laboratuvar.html)** - Hedef tahtası metaforu üzerinden modelin bias ve varyans dengesini keşfedin.
* **[Bölüm 3: Güven Aralıkları](https://ibrahimguney.github.io/istatistik-lab/lab/bolum_3_laboratuvar.html)** - Çekilen farklı örneklemlerle güven aralığının parametreyi kapsama oranını görselleştirin.
* **[Bölüm 4: Hipotez Testleri](https://ibrahimguney.github.io/istatistik-lab/lab/bolum_4_laboratuvar.html)** - Tip I ve Tip II hataların tahterevalli dengesini güç analiziyle interaktif olarak inceleyin.
* **[Bölüm 5: Regresyon Analizi](https://ibrahimguney.github.io/istatistik-lab/lab/bolum_5_laboratuvar.html)** - En Küçük Kareler (OLS) doğrusunu verilere uydurma oyununu oynayın.
* **[Bölüm 6: ANOVA](https://ibrahimguney.github.io/istatistik-lab/lab/bolum_6_laboratuvar.html)** - F-İstatistiği ile gruplar arası sinyalin grup içi gürültüye oranını anlık grafikte analiz edin.
* **[Bölüm 7: Ki-Kare Testleri](https://ibrahimguney.github.io/istatistik-lab/lab/bolum_7_laboratuvar.html)** - Beklenen ve gözlenen frekansların kategorik veri matrisindeki sapmalarını görselleştirin.
* **[Bölüm 8: Parametrik Olmayan Testler](https://ibrahimguney.github.io/istatistik-lab/lab/bolum_8_laboratuvar.html)** - Aykırı değerlerin sonuçlara olan etkisini ve non-parametrik testlerin dayanıklılığını (robustness) deneyimleyin.
* **[Bölüm 9: Bayesçi Çıkarım](https://ibrahimguney.github.io/istatistik-lab/lab/bolum_9_laboratuvar.html)** - Yeni kanıtlar ışığında (Likelihood) önceki inançların (Prior) nasıl güncellendiğini görün.

---

## 🛠️ Teknik Altyapı

Bu proje, performans ve erişilebilirlik odaklı olarak inşa edilmiştir:
- **Frontend:** HTML5, TailwindCSS (Tasarım), Chart.js (Grafik Çizimi).
- **Backend/Hosting:** Statik barındırma (GitHub Pages üzerinden yayımlanmaktadır, sunucu tarafında kod çalışmaz).

<img width="803" height="385" alt="image" src="https://github.com/user-attachments/assets/1f1bcb62-582a-4977-b3ae-476b94d0d375" />

---

## 📂 Dosya Yapısı

```text
/
├── index.html                  # Tüm laboratuvarlara erişim sağlayan ana portal
├── lab/                        # Simülatör dosyaları klasörü
│   ├── bolum_1_laboratuvar.html    # Bölüm 1 Simülatörü
│   ├── bolum_2_laboratuvar.html    # Bölüm 2 Simülatörü
│   └── ...
└── README.md                   # Proje dokümantasyonu
```

---

## 💡 Katkıda Bulunma

Bu proje, istatistik eğitimini interaktif ve anlaşılır hale getirmeyi amaçlayan bir açık kaynak girişimidir. Yeni simülatörler eklemek, kodları iyileştirmek veya hataları bildirmek isterseniz her zaman **Pull Request (PR)** gönderebilirsiniz.

**İstatistik öğrenmek artık sadece okumak değil, bizzat deneyimlemektir!**

*İstatistik V2 © 2026 | Eğitim Teknolojileri Bölümü*
