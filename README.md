# Mazhar Umut Yılmaz — GitHub Pages Portfolio

Bu klasör doğrudan GitHub Pages üzerinde kullanılabilecek basit ve responsive bir portföy sitesidir.

## Dosyalar

- `index.html` → Sayfanın içeriği
- `styles.css` → Tasarım, renkler ve responsive ayarlar
- `assets/banner.jpeg` → Üst kısımda kullanılan banner görseli

## Düzenleme

Metinleri değiştirmek için `index.html` dosyasını açıp ilgili paragraf ve başlıkları değiştirin.

Renkleri değiştirmek için `styles.css` dosyasının en üstündeki `:root` alanını düzenleyin:

```css
:root {
  --bg: #030712;
  --bg-alt: #07111f;
  --card: #0b1628;
  --text: #f8fafc;
  --muted: #a9b5c7;
  --accent: #1687ff;
}
```

## GitHub Pages'e yükleme

1. GitHub'da `kullaniciadi.github.io` isminde public repository oluşturun.
2. Bu klasördeki `index.html`, `styles.css` ve `assets` klasörünü repository'nin ana dizinine yükleyin.
3. Repository → Settings → Pages bölümüne gidin.
4. Source olarak `Deploy from a branch` seçin.
5. Branch: `main`, Folder: `/ (root)` seçin.
6. Birkaç dakika sonra site yayına alınır.

Alternatif olarak repository başka bir isimdeyse, GitHub Pages proje sitesi olarak da çalışır.
