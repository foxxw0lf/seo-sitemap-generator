# SEO Sitemap Generator

SEO Sitemap Generator adalah sebuah proyek berbasis HTML yang bertujuan untuk membantu membuat sitemap untuk keperluan SEO website Anda. Dengan sitemap yang terstruktur, mesin pencari dapat lebih mudah menelusuri dan mengindeks semua halaman pada website, sehingga meningkatkan visibilitas website di hasil pencarian.

## Fitur

- **Pembuatan Sitemap Otomatis:** Membantu menghasilkan sitemap berbasis struktur website Anda.
- **Mudah Digunakan:** Antarmuka berbasis HTML yang sederhana dan mudah dipahami.
- **Output XML:** Menghasilkan file sitemap dalam format XML yang sesuai standar mesin pencari (Google, Bing, dll).
- **Customisasi:** Dapat disesuaikan untuk berbagai struktur website.
- **100% Client-side:** Semua proses dilakukan di sisi pengguna tanpa perlu backend.

## Cara Penggunaan

1. **Clone atau Unduh Repository**
   ```
   git clone https://github.com/foxxw0lf/seo-sitemap-generator.git
   ```
   atau unduh file ZIP dari halaman utama repository lalu ekstrak ke komputer Anda.

2. **Buka File HTML**
   - Buka file `index.html` (atau file utama generator) menggunakan browser favorit Anda.

3. **Masukkan URL Website**
   - Masukkan URL utama website Anda pada kolom yang disediakan.

4. **Konfigurasikan Opsi (Opsional)**
   - Pilih opsi yang disediakan untuk menyesuaikan sitemap sesuai kebutuhan.

5. **Generate Sitemap**
   - Klik tombol "Generate" dan sitemap XML akan muncul atau dapat diunduh.

## Contoh Output

```xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <url>
    <loc>https://example.com/</loc>
    <lastmod>2025-07-01</lastmod>
    <changefreq>monthly</changefreq>
    <priority>1.0</priority>
  </url>
  <!-- ... halaman lain ... -->
</urlset>
```


## Kontribusi

Kontribusi sangat terbuka untuk siapa saja! Jika Anda ingin menambah fitur, memperbaiki bug, atau meningkatkan dokumentasi, silakan:

1. Fork repository ini.
2. Buat branch fitur/bugfix baru.
3. Commit perubahan Anda.
4. Ajukan pull request.

## Lisensi

Proyek ini dilisensikan di bawah MIT License. Silakan lihat file [LICENSE](LICENSE) untuk detail lebih lanjut.

## Kontak

Jika Anda memiliki pertanyaan atau saran, silakan hubungi:
- [GitHub Issues](https://github.com/foxxw0lf/seo-sitemap-generator/issues)

---

Terima kasih telah menggunakan SEO Sitemap Generator! Jangan lupa untuk memberi bintang ⭐ pada repository ini jika Anda merasa terbantu.
