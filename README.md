# 🌍 Deprem Bilinci – Farkındalık ve Eğitim Platformu

Türkiye’deki öğrenci, öğretmen, ebeveyn ve çocuklara yönelik hazırlanan **görsel ağırlıklı deprem eğitim platformu**.
Amacımız, afetlere karşı bilinç düzeyini artırmak, testlerle öğrenmeyi pekiştirmek ve başarılı katılımcılara dijital sertifikalar sunmaktır.

🔗 [Katkıda Bulunma Rehberini Görüntüle](./KatkıdaBulunmaRehberi.md)
🔗 [MVP Özelliklerini Görüntüle](./MVP.md)


---

## 📌 Proje Hakkında

Bu web tabanlı platform, 4 farklı hedef kitleye özel içeriklerle deprem konusunda bilgilendirme sağlar:

* 🎓 **Öğrenciler**
* 👩‍🏫 **Öğretmenler**
* 👨‍👩‍👧‍👦 **Ebeveynler**
* 🧒 **Çocuklar**

Her kullanıcı grubuna özel **görsel destekli eğitimler**, **etkileşimli testler** ve **otomatik sertifika** üretimi sunulmaktadır.

---

## *🛠️ Teknolojiler*

| *Katman*           | *Teknoloji*               |
| ------------------ | ------------------------- |
| *Framework*        | *Next.js (React Tabanlı)* |
| *Backend*          | *Firebase Functions*      |
| *Hosting*          | *Vercel*        |
| *Veritabanı*       | *Firebase Firestore*      |
| *Kimlik Doğrulama* | *Firebase Auth*           |
| *Sertifika*        | *jsPDF, html2canvas*      |

---

## *📁 Dosya Yapısı (Planlanan)*

```plaintext
deprem-bilinci/
├── assets/                # Görseller, ikonlar
├── components/            # Vue bileşenleri
├── layouts/               # Sayfa düzenleri
├── pages/                 # Route bazlı Nuxt.js sayfaları
│   ├── ogrenciler.vue
│   ├── ogretmenler.vue
│   ├── ebeveynler.vue
│   └── cocuklar.vue
├── plugins/              # Firebase entegrasyonu vb.
├── store/                # Vuex store (opsiyonel)
├── static/               # Statik dosyalar (manifest, favicon)
├── utils/                # Test kontrolü, sertifika üretici
├── .gitignore
├── nuxt.config.ts
├── package.json
└── README.md
```

---

## *📜 Lisans*

*Bu proje topluma katkı amacıyla açık kaynak olarak geliştirilmektedir.*
**MIT Lisansı** ile sunulmaktadır.

---

## *📧 İletişim*
