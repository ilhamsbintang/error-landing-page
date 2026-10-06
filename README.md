# 🌸 Error & Maintenance Landing Page for NihongoN3

Halaman landing page darurat / maintenance / error statis yang dirancang khusus dengan visual identity, tema warna, dan nuansa penuh kasih sayang dari website **NihongoN3** (`n3.ilhamandsekar.site`).

Dibuat untuk memberikan rasa tenang dan kejelasan status saat website utama sedang dalam proses perbaikan sistem oleh Ilham untuk Sekar.

---

## ✨ Fitur & Keunggulan

1. **Desain Identik & Harmonis**: Mengikuti tema warna resmi NihongoN3 (Navy `#0F172A`, Sweet Pink `#F472B6` - `#DB2777`, dan Paper `#FAFAF9`), tipografi Plus Jakarta Sans & Noto Sans JP, serta badge & rounded cards ala macOS Safari modern.
2. **Surat Penenang Hati (Reassurance)**: Pesan hangat personal agar Sekar tidak khawatir tentang progress belajar atau streak SRS-nya.
3. **Live Server Connection Check**: Tombol interaktif untuk menguji apakah server `n3.ilhamandsekar.site` sudah kembali online secara langsung di browser.
4. **Mini Flashcard Darurat**: Fitur interaktif tebak kosakata JLPT N3 dengan animasi flip dan efek konfeti hati sehingga waktu tunggu tetap produktif dan menyenangkan.
5. **WhatsApp Quick Action**: Tombol langsung untuk menghubungi Ilham jika ada kendala darurat.
6. **Zero Dependencies & Ultra Fast**: Berbasis file HTML murni dengan Tailwind CSS via CDN & Lucide Icons. Siap dideploy ke Cloudflare Pages, Vercel, Netlify, Nginx static fallback, atau GitHub Pages dalam hitungan detik.

---

## 🚀 Cara Menjalankan Secara Lokal

Cukup buka file `index.html` langsung di browser favoritmu (Safari, Chrome, Arc, dll.), atau jalankan local server:

```bash
# Menggunakan Python
python3 -m http.server 3000

# Atau menggunakan npx serve
npx serve .
```

Buka `http://localhost:3000` di browser.

---

## 🌐 Opsi Deployment

### 1. GitHub Pages
1. Buka repository di GitHub: `https://github.com/ilhamsbintang/error-landing-page`
2. Masuk ke tab **Settings** -> **Pages**.
3. Di bagian **Build and deployment** -> **Source**, pilih `Deploy from a branch`.
4. Pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.
5. Landing page akan langsung aktif di `https://ilhamsbintang.github.io/error-landing-page/`.

### 2. Cloudflare / Nginx Custom Error Page
Gunakan file `index.html` ini sebagai fallback error template (misal untuk status code HTTP 500, 502, 503, atau Cloudflare Waiting Room / Maintenance Page) untuk domain `n3.ilhamandsekar.site`.

---

Dibuat dengan segenap cinta oleh **Ilham** untuk **Sekar** ❤️️ · Menuju Lulus JLPT N3 Desember 2026!
