# EONET - Internet Bebas Batas

Landing page modern untuk layanan penyedia internet [EONET](https://eonet.id/), dibangun menggunakan [Astro Framework](https://astro.build/) untuk performa maksimal dan di-deploy ke jaringan global Cloudflare.

## Fitur Utama

- **Desain Modern:** Menggunakan palet warna vibrant dan efek glassmorphism.
- **Performa Tinggi:** Dibangun dengan arsitektur Islands Architecture dari Astro.
- **Responsif:** Tampilan optimal di berbagai perangkat (Desktop, Tablet, Mobile).
- **Cloudflare Workers:** Deployment edge-native untuk kecepatan akses global.

## Tech Stack

- **Framework:** [Astro](https://astro.build/)
- **Styling:** Vanilla CSS (Modern CSS Variables, Gradients, Glassmorphism)
- **Deployment:** [Cloudflare Pages / Workers](https://workers.cloudflare.com/)

## Struktur Project

```text
/
├── public/           # Aset statis
├── src/
│   ├── components/   # Komponen UI (Header, Hero, Packages, dll)
│   ├── layouts/      # Layout utama halaman
│   ├── pages/        # File halaman (routing berbasis file)
│   └── styles/       # Global CSS
└── astro.config.mjs  # Konfigurasi Astro
```

## Cara Menjalankan

Berikut adalah perintah-perintah yang tersedia untuk pengembangan:

| Command | Action |
| :--- | :--- |
| `npm install` | Menginstall dependensi project |
| `npm run dev` | Menjalankan server development lokal di `localhost:4321` |
| `npm run build` | Melakukan build untuk produksi ke folder `./dist/` |
| `npm run preview` | Melihat preview hasil build secara lokal |
| `npm run deploy` | Deploy langsung ke Cloudflare menggunakan Wrangler |

### Development

```bash
# Clone repository
git clone https://github.com/username/eonet.git
cd eonet

# Install dependencies
npm install

# Jalankan server development
npm run dev
```

### Deployment

Project ini dikonfigurasi untuk deployment ke Cloudflare.

```bash
# Build dan Deploy
npm run deploy
```

Pastikan Anda telah login ke Cloudflare menggunakan `npx wrangler login` jika melakukan deploy dari lokal.

## Kredit

Dikembangkan untuk [portal online](https://portalonline.id/).
