# Mini Dynamic Bootstrap

Mini Dynamic Bootstrap, modern web projeleri için esnek, ölçeklenebilir ve özelleştirilebilir bir CSS yardımcı sınıf (utility class) kütüphanesidir. Bootstrap’in temel felsefesinden ilham alarak, sade ve dinamik bir yapı sunar. SCSS ile yazılmıştır ve kolayca özelleştirilebilir.

## Özellikler

- **Dinamik Utility Sınıfları:** Margin, padding, gap, renkler, tipografi, grid ve daha fazlası için otomatik olarak üretilen yardımcı sınıflar.
- **SCSS ile Tamamen Özelleştirilebilir:** Değişkenler ve haritalar üzerinden tüm utility sınıflarını kendi projenize göre kolayca düzenleyebilirsiniz.
- **Responsive Grid Sistemi:** 12 kolonlu grid yapısı ve özelleştirilebilir breakpoint’ler ile mobil uyumlu tasarımlar.
- **Renk ve Tipografi Yönetimi:** Renk paletleri, font boyutları, font ağırlıkları, satır yükseklikleri ve daha fazlası.
- **Modern CSS Özellikleri:** Flexbox, gap, display, position, z-index, opacity gibi modern CSS özellikleri için yardımcı sınıflar.
- **Küçük ve Hafif:** Gereksiz kodlardan arındırılmış, sadece ihtiyacınız olan utility sınıfları.

## Klasör Yapısı

```
src/
  css/
    utilities/
      variables.css
  scss/
    utilities/
      _colors.scss
      _display.scss
      _grid.scss
      _position.scss
      _properties.scss
      _spacing.scss
      _typography.scss
      _breakpoints.scss
      variables.scss
index.html
```

## Başlangıç

1. **Projeyi klonlayın:**
   ```bash
   git clone https://github.com/rildir/customizable-bootstrap
   ```

2. **SCSS dosyalarını derleyin:**
   ```bash
   sass src/scss/utilities/variables.scss src/css/style.css
   ```

3. **HTML dosyanıza CSS’i ekleyin:**
   ```html
   <link rel="stylesheet" href="src/css/style.css">
   ```

## Kullanım

HTML’de Bootstrap benzeri utility sınıflarını kullanabilirsiniz(güncellenecek):

```html
<div class="container">
  <div class="row">
    <div class="col-6 p-4 bg-primary-900 text-white">
      Dinamik Bootstrap Utility!
    </div>
    <div class="col-6 p-4 bg-secondary-900 text-white">
      Kolay Responsive Grid!
    </div>
  </div>
</div>
```

```html
<header class="flex justify-between align-center py-8 px-16 bg-info-500">
  <h1 class="fs-32 font-600">Welcome to Mini Bootstrap</h1>
  <nav>
    <ul class="flex gap-4">
      <li class="list-style-none"><a class="text-decoration-none text-white" href="#home">Home</a></li>
      <li class="list-style-none"><a class="text-decoration-none text-white" href="#about">About</a></li>
      <li class="list-style-none"><a class="text-decoration-none text-white" href="#contact">Contact</a></li>
    </ul>
  </nav>
</header>
```

## Özelleştirme

- **Renkler, grid, tipografi ve diğer utility değerlerini** `src/scss/utilities/_properties.scss` ve ilgili SCSS dosyalarından düzenleyebilirsiniz.
- **Breakpoint ve grid ayarlarını** `src/scss/utilities/_breakpoints.scss` ve `_grid.scss` dosyalarından değiştirebilirsiniz.

## Katkı

Katkıda bulunmak isterseniz, lütfen bir pull request gönderin veya issue açın.

---

**Mini Dynamic Bootstrap** ile projelerinize hızlı ve esnek bir başlangıç yapın!
