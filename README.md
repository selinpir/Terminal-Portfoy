# Terminal Portföy

Kişisel bilgilerimi ve projelerimi terminal görünümünde sunmak için HTML, CSS ve JavaScript ile geliştirdiğim portföy sitesi. Kullanıcı, komut yazarak istediği bölümü görüntüleyebilir.

## Komutlar

| Komut       | İşlev                                                 |
| ----------- | ----------------------------------------------------- |
| `help`      | Kullanılabilen komutları listeler.                    |
| `about`     | Hakkımda bölümünü gösterir.                           |
| `social`    | Sosyal profil, e-posta ve CV bağlantılarını gösterir. |
| `skills`    | Yetenekler bölümünü gösterir.                         |
| `education` | Eğitim bilgilerini gösterir.                          |
| `projects`  | Projeleri ve GitHub bağlantılarını listeler.          |
| `clear`     | Terminaldeki çıktıları temizler.                      |

Komutu yazıp Enter tuşuna basarak çalıştırabilirsiniz. Komutlar büyük/küçük harf ayrımı olmadan değerlendirilir. Tanımlanmayan komutlar için hata mesajı gösterilir.

## Teknik yapı

* **HTML:** Sayfa yapısı ve komutlara karşılık gelen içerik şablonları
* **CSS:** Terminal görünümü, renkler ve ekran boyutuna göre genişlik düzenlemesi
* **JavaScript:** Klavye olayları, komut seçimi, DOM işlemleri ve ekran temizleme

İçerikler HTML içinde tanımlıdır. JavaScript, girilen komuta karşılık gelen şablonu kopyalayarak terminal ekranına ekler. Uygulama tarayıcıda çalışır; sunucu veya veritabanı gerektirmez.

## Dosyalar

* `index.html`: Terminal arayüzü ve içerikler
* `style.css`: Görünüm ve yerleşim
* `script.js`: Komutların işlenmesi ve kullanıcı etkileşimleri

## Çalıştırma

Repoyu indirip `index.html` dosyasını tarayıcıda açın. Başlamak için `help` yazıp Enter tuşuna basın.

Ek paket kurulumu gerekmez. Google Fonts üzerinden yüklenen yazı tipi için internet bağlantısı kullanılır.
