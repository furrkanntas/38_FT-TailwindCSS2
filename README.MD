# Food Ninja

Bu proje, Tailwind CSS kullanılarak geliştirilmiş bir web sayfasıdır. Projenin amacı, kullanıcıların çeşitli tariflere göz atabileceği ve favori tariflerini bulabileceği bir tarif sitesi oluşturmaktır.

![Site Image](/public/img/1.jpg)

## İçindekiler
- [Genel Bakış](#genel-bakış)
- [Kullanılan Teknolojiler](#kullanılan-teknolojiler)
- [Proje Yapısı](#proje-yapısı)
- [Kurulum](#kurulum)
- [Kullanım](#kullanım)
- [Tailwind CSS Sınıfları](#tailwind-css-sınıfları)
- [Özellikler](#özellikler)
- [Gelecekteki Geliştirmeler](#gelecekteki-geliştirmeler)

## Genel Bakış

Bu proje, bir yemek tarifleri sitesinin temel bir örneğini içerir. Tailwind CSS kullanılarak responsive ve modern bir tasarım oluşturulmuştur. Sayfa, anahtar bileşenleri ve tasarım unsurlarını içermektedir.

## Kullanılan Teknolojiler

- HTML5
- Tailwind CSS
- JavaScript (sayfa içi etkileşimler için)


- `index.html`: Ana HTML dosyası.
- `/public/styles.css`: Tailwind CSS ile oluşturulmuş stil dosyası.
- `/public/index.js`: JavaScript dosyası.
- `/public/img`: Tarif resimlerinin bulunduğu dizin.

## Kurulum

Projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları izleyin:

1. Projeyi klonlayın:
    ```bash
    git clone https://github.com/kullanici/food-ninja.git
    ```
2. Proje dizinine gidin:
    ```bash
    cd food-ninja
    ```
3. Gerekli bağımlılıkları yükleyin:
    ```bash
    npm install
    ```

## Kullanım

Projeyi yerel bir sunucuda çalıştırmak için aşağıdaki komutu kullanabilirsiniz:
```bash
npm run start
```
Bu komut, projeyi tarayıcınızda açar ve değişiklikleri anında görebilirsiniz.

## Tailwind CSS Sınıfları

Projede kullanılan bazı önemli Tailwind CSS sınıfları şunlardır:

- `grid`, `md:grid-cols-3:` Sayfayı grid düzenine göre düzenler ve medium (md) ekran boyutunda üç sütunlu hale getirir.
- `text-gray-600`, `font-body:` Metin rengini ve font ailesini ayarlar.
- `hover:bg-primary`, `hover:text-white:` Hover durumunda arka plan ve metin rengini değiştirir.
- `transition ease-out duration-300:` Geçiş efektlerini düzenler.
- `flex`, `justify-end`, `items-center:` Flexbox düzenlemeleri.

## Özellikler

- **Responsive Tasarım:** Farklı ekran boyutlarına uyum sağlar.
- **Navigasyon Menüsü:** Üst kısımda gezinme menüsü.
- **Tarif Kartları:** Tarifleri gösteren kartlar.
- **Hover Efektleri:** Hover durumunda değişen stiller.
- **Geçiş Animasyonları:** Buton ve kartlarda yumuşak geçiş efektleri.

## Gelecekteki Geliştirmeler

- Daha fazla tarif eklenmesi.
- Kullanıcı yorumları ve derecelendirme sistemi.
- Gelişmiş arama ve filtreleme özellikleri.
- Kullanıcı kayıt ve giriş sistemi.

Bu proje, Tailwind CSS ile web tasarımı yapma konusunda temel bir örnek sunmaktadır. Daha fazla bilgi ve dökümantasyon için [Tailwind CSS](https://tailwindcss.com/) resmi sitesi ziyaret edilebilir.

#### Teşekkürler :)
#### Furkan Taş