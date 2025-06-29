# Kur'an Sayfaları Projesi

[![Netlify Status](https://api.netlify.com/api/v1/badges/ce490aad-e24a-4255-9835-dbea7d70f30f/deploy-status)](https://app.netlify.com/projects/quran-pages/deploys)

Bu proje, Kur'an-ı Kerim'in tüm sayfalarını modern ve erişilebilir bir web arayüzünde sunmayı amaçlayan açık kaynaklı bir çalışmadır. Projenin kalbi, tüm Kur'an metnini sayfa sayfa içeren `kuran.js` adlı bir JavaScript dosyasıdır.

Amaç, geliştiricilerin, araştırmacıların ve meraklıların Kur'an metnine kolayca erişebileceği ve kendi projelerinde kullanabileceği basit bir kaynak oluşturmaktır.

## 🚀 Canlı Demo

Projenin canlı versiyonuna şu adresten ulaşabilirsiniz:
**[https://quran-pages.netlify.app/](https://quran-pages.netlify.app/)**

## ✨ Özellikler

*   **Tam Metin:** Kur'an-ı Kerim'in 600'den fazla sayfasının tamamını içerir.
*   **Sade ve Okunaklı Arayüz:** Göz yormayan, krem ve beyaz tonlarında, minimalist bir tasarıma sahiptir.
*   **Özel Arapça Font:** Metinlerin estetik ve okunaklı olması için Google Fonts üzerinden "Amiri" fontu kullanılmıştır.
*   **RTL Desteği:** Arapça metin, doğru şekilde sağdan sola (`rtl`) olarak hizalanmıştır.
*   **Duyarlı Tasarım (Responsive):** Proje, farklı ekran boyutlarına (mobil, tablet, masaüstü) uyum sağlayacak şekilde tasarlanmıştır.
*   **Açık Kaynak ve Kolay Kullanım:** Kod yapısı oldukça basittir ve `kuran.js` dosyası herhangi bir web projesine kolayca entegre edilebilir.

## 🛠️ Kullanılan Teknolojiler

Bu proje, modern web geliştirme karmaşıklığından uzak durarak, temel ve sağlam teknolojiler üzerine inşa edilmiştir:

*   **HTML5:** Sayfanın yapısal iskeleti.
*   **CSS3:** Görsel stil, renkler ve sayfa düzeni.
*   **Vanilla JavaScript:** Çerçeve (framework) kullanılmadan, saf JavaScript ile dinamik içerik oluşturma.
*   **Google Fonts:** Amiri fontu için.
*   **Netlify:** Ücretsiz ve hızlı statik site barındırma ve dağıtım (deployment).

## 📂 Dosya Yapısı

Proje, kolayca anlaşılabilir basit bir dosya yapısına sahiptir:

```
.
├── index.html     # Ana HTML dosyası, sayfanın iskeletini içerir
├── kuran.js       # Tüm Kur'an verisini içeren JavaScript dizisi
└── style.css      # Sayfanın tüm stillerini barındıran CSS dosyası
```

## 💻 Yerel Geliştirme Ortamı Kurulumu

Projeyi kendi bilgisayarınızda çalıştırmak ve geliştirmek için aşağıdaki adımları izleyebilirsiniz:

1.  **Depoyu klonlayın:**
    ```bash
    git clone https://github.com/reactkick/quran-pages.git
    ```
2.  **Klasöre gidin:**
    ```bash
    cd quran-pages
    ```
3.  **`index.html` dosyasını tarayıcınızda açın:**
    Herhangi bir sunucuya ihtiyaç duymadan, dosyayı doğrudan tarayıcınızda açarak projeyi görüntüleyebilirsiniz.

## 🤝 Katkıda Bulunma

Bu projeye katkıda bulunmak isterseniz, her türlü yardım memnuniyetle karşılanır! Hata düzeltmeleri, arayüz iyileştirmeleri veya yeni özellikler eklemek için:

1.  Bu depoyu **Fork**'layın.
2.  Yeni bir dal (branch) oluşturun (`git checkout -b ozellik/yeni-bir-ozellik`).
3.  Değişikliklerinizi yapın ve **Commit**'leyin (`git commit -m 'Yeni bir özellik eklendi'`).
4.  Dalınızı itin (`git push origin ozellik/yeni-bir-ozellik`).
5.  Bir **Pull Request** (Çekme İsteği) oluşturun.

Özellikle aşağıdaki gibi konularda yardıma açığız:
*   Sayfaya gitme (Go to page) özelliği ekleme.
*   Metin içinde arama fonksiyonu.
*   Daha iyi bir mobil deneyim için arayüz iyileştirmeleri.
*   Koyu mod (Dark mode) desteği.

## 📄 Lisans

Bu proje, MIT Lisansı altında lisanslanmıştır. Detaylar için `LICENSE` dosyasına bakabilirsiniz.

## 🙏 Teşekkür

Bu projenin temelini oluşturan `kuran.js` dosyasındaki veriler, sağlanan PDF dosyasından OCR (Optik Karakter Tanıma) yöntemiyle elde edilmiştir. Bu değerli kaynağı sağlayanlara teşekkürler.
