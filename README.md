# Hafshi Jaya Konveksi — Website & Digital Presence

Website company profile & landing page B2B untuk **Hafshi Jaya Konveksi**, vendor konveksi seragam kerja (kemeja PDH/PDL, polo, wearpack, jaket) yang berbasis di Cilodong, Depok, Jawa Barat. Target utama proyek ini adalah membangun kredibilitas digital untuk menarik klien B2B (corporate, instansi, EO) melalui landing page konversi tinggi sekaligus SEO yang kuat di kata kunci konveksi seragam Jabodetabek & nasional.

## Tech Stack

- **Framework:** Astro
- **Deployment target:** _(isi sesuai provider — misal Vercel/Netlify/VPS)_
- **Styling:** _(isi sesuai pilihan — misal Tailwind CSS)_
- **Font:** `next/font/google`-equivalent di Astro (Inter / Plus Jakarta Sans) dengan `font-display: swap`
- **Image format:** WebP / AVIF (next-gen image format wajib)
- **SEO:** Meta tags manual + JSON-LD structured data (LocalBusiness & Service schema)

---

## 📋 Roadmap & Feature Breakdown

### Tahap 1 — Audit Bisnis & Strategi

- [ ] Finalisasi target pasar Tier 1 (Jabodetabek/Depok) & Tier 2 (Nasional)
- [ ] Finalisasi target keyword per tier
- [ ] Konfirmasi 3 kategori layanan utama: Seragam Kerja, Kaos & Polo, Jaket & Outerwear
- [ ] Konfirmasi buyer persona (HRD/GA/Purchasing, Panitia Pengadaan/EO/Pengurus)
- [ ] Konfirmasi value proposition/USP: garansi produksi, lokasi workshop jelas, free mockup & konsultasi
- [ ] Tentukan CTA utama (RFQ via WhatsApp) & CTA sekunder (lihat katalog)
- [ ] Siapkan foto mockup produk sementara untuk portofolio (sebelum data foto klien asli tersedia)
- [ ] Tentukan skema MOQ berupa dropdown range (bukan angka pasti di teks website)

### Tahap 2 — Arsitektur & Konten Website

#### Site Architecture (Hybrid Single-Page Landing + Category Pages)
- [ ] `/` — Homepage / landing page konversi B2B
- [ ] `/layanan/seragam-kerja` — Kemeja PDH/PDL, Wearpack, Uniform Kantor
- [ ] `/layanan/kaos-polo` — Polo Promosi, Kaos Event, Gathering
- [ ] `/layanan/jaket-outerwear` — Jaket Bomber, Parka, Vest, Almamater
- [ ] `/tentang-kami` — Company profile, legalitas, fasilitas produksi

#### Homepage Sections
- [ ] **Section 1 — Hero**
  - [ ] Visual background workshop (foto/video, dark overlay)
  - [ ] Badge: "Pabrik & Konveksi Seragam B2B — Depok / Jabodetabek"
  - [ ] H1: "Mitra Pengadaan Seragam & Apparel Kantor Terpercaya dengan Garansi Tepat Waktu"
  - [ ] Sub-headline layanan
  - [ ] CTA primer: "Konsultasi WhatsApp & Minta Penawaran" (link WA dengan template chat)
  - [ ] CTA sekunder: "Unduh Katalog Produk (PDF)"
  - [ ] 3 trust badge (garansi tepat waktu, gratis sampel & mockup, kirim seluruh Indonesia)
- [ ] **Section 2 — Value Proposition / Why Choose Us**
  - [ ] H2 + grid 4 pilar: Kualitas Standard Industri, Garansi Tepat Waktu & Retur, Sampel & Mockup Gratis, Workshop Fisik Transparan
- [ ] **Section 3 — Katalog Produk & Jasa Utama**
  - [ ] Card 1: Seragam & Kemeja Kerja (PDH/PDL/Wearpack)
  - [ ] Card 2: Kaos & Polo Shirt Custom
  - [ ] Card 3: Jaket, Outerwear & Rompi
  - [ ] Card 4: Jas Almamater & Seragam Komunitas
- [ ] **Section 4 — Cara Order / Alur Kerja (4 Steps)**
  - [ ] Langkah 1: Konsultasi & Brief
  - [ ] Langkah 2: Mockup & Penawaran (RFQ)
  - [ ] Langkah 3: Pembayaran DP & Sampel
  - [ ] Langkah 4: Produksi & Pengiriman
- [ ] **Section 5 — Portofolio & Spesifikasi Produksi**
  - [ ] Filter tabs: All | Kemeja PDH | Polo Shirt | Jaket | Wearpack
  - [ ] Gallery foto produk close-up + caption (jenis bahan + jenis aplikasi)
- [ ] **Section 6 — Legitimasi & Profil Workshop**
  - [ ] Kolom kiri: deskripsi & legitimasi usaha
  - [ ] Kolom kanan: lokasi, fasilitas produksi, area layanan
- [ ] **Section 7 — Testimoni & FAQ**
  - [ ] Testimoni placeholder
  - [ ] FAQ accordion (MOQ, sampel sebelum produksi massal, estimasi waktu, retur/cacat produk, pengiriman luar Jabodetabek)
- [ ] **Section 8 — Kontak, Form RFQ, & Maps**
  - [ ] Form RFQ: Nama/Perusahaan, Jenis Produk (dropdown), Estimasi Jumlah (Pcs), Catatan/Upload Desain
  - [ ] Embed Google Maps lokasi workshop Cilodong, Depok

### Tahap 3 — Technical SEO

#### Meta Data
- [ ] Meta title & description Homepage
- [ ] Canonical URL Homepage
- [ ] Meta title & description tiap sub-page layanan (`/layanan/seragam-kerja`, dst.)
- [ ] Canonical URL tiap sub-page

#### Heading Structure
- [ ] Implementasi hierarki H1–H3 sesuai struktur berikut:
  ```
  [H1] Konveksi Seragam Kantor & Vendor Apparel B2B Terpercaya
  ├── [H2] Mengapa Memilih Hafshi Jaya Konveksi?
  │   ├── [H3] Jaminan Garansi Tepat Waktu
  │   ├── [H3] Gratis Mockup & Sampel Bahan
  │   └── [H3] Lokasi Workshop Fisik Jelas
  ├── [H2] Layanan Pengadaan Apparel Utama
  │   ├── [H3] Kemeja PDH / PDL & Seragam Kantor
  │   ├── [H3] Kaos Event & Polo Shirt Promosi
  │   └── [H3] Jaket, Outerwear & Wearpack Custom
  ├── [H2] Alur Pemesanan B2B
  ├── [H2] Portofolio & Katalog Hasil Produksi
  ├── [H2] Profil Workshop Cilodong Depok
  ├── [H2] Pertanyaan Yang Sering Diajukan (FAQ)
  └── [H2] Hubungi Kami & Minta Penawaran Harga
  ```

#### Open Graph & Social Tags
- [ ] `og:type`, `og:title`, `og:description`, `og:image`, `og:url`
- [ ] `twitter:card` (summary_large_image)

#### Schema Markup (JSON-LD)
- [ ] `LocalBusiness` schema (nama, alamat, geo, jam operasional, telepon)
- [ ] `Service` schema dengan `OfferCatalog` (Kemeja PDH/PDL, Polo Promosi, Wearpack & Jaket)
- [ ] Pasang di `<head>` — komponen layout Astro (mis. `Layout.astro` atau lewat `<script type="application/ld+json">`)

#### Technical Assets
- [ ] `public/robots.txt`
- [ ] `public/sitemap.xml` (Homepage + 4 halaman layanan)
- [ ] `public/manifest.json` (PWA support)
- [ ] Favicon set (192x192, 512x512)

#### Core Web Vitals & Image Optimization
- [ ] Semua gambar dikompres ke format `.webp`/`.avif`
- [ ] Semua `<img>`/`<Image/>` pakai alt text deskriptif B2B (contoh: `"Hasil jahit kemeja PDH bahan Taipan Drill oleh Hafshi Jaya Konveksi Depok"`)
- [ ] Font loading pakai `display: swap` untuk cegah layout shift (CLS)
- [ ] Target skor Google PageSpeed Insights > 90 (mobile & desktop)

---

## Referensi Data Bisnis

| Item | Detail |
|---|---|
| Lokasi Workshop | Cilodong, Depok, Jawa Barat |
| Model Bisnis | B2B — Pengadaan Seragam & Apparel Massal |
| Area Layanan | Jabodetabek (kurir/instan) & Seluruh Indonesia (cargo/ekspedisi) |
| Fasilitas | Meja potong presisi, mesin jahit high-speed, mesin bordir komputer |
| Jam Operasional | Senin–Sabtu, 08:00–17:00 |

> Catatan: Data seperti alamat lengkap, nomor telepon, dan koordinat geo di JSON-LD masih placeholder — update sebelum go-live.
