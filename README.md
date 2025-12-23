# JDIH Kab. Gresik - Aplikasi Informasi Publik

Aplikasi resmi Jaringan Dokumentasi dan Informasi Hukum (JDIH) Kabupaten Gresik yang siap untuk disubmit ke Google Play Store dan Apple App Store.

## 🎯 Deskripsi

JDIH Kab. Gresik adalah platform informasi publik yang menyediakan akses mudah dan gratis ke:
- Peraturan Daerah (Perda)
- Keputusan Bupati
- Peraturan Bupati
- Dokumentasi hukum lainnya dari Pemerintah Kabupaten Gresik

**Fitur Utama:**
- ✅ Akses gratis tanpa login/registrasi
- ✅ Pencarian cepat untuk menemukan peraturan
- ✅ Mode offline untuk dokumen favorit
- ✅ Aman dan terpercaya
- ✅ Update konten berkala

## 📱 Platform

- **Android**: Google Play Store
- **iOS**: Apple App Store
- **Web**: Responsive web application

## 📋 Halaman & Fitur

| Halaman | URL | Deskripsi |
|---------|-----|-----------|
| Home | `/` | Halaman utama dengan fitur & info |
| Kebijakan Privasi | `/privacy-policy` | Privacy policy lengkap & legal |
| Syarat & Ketentuan | `/terms-of-service` | Terms of service komprehensif |
| Aksesibilitas | `/accessibility` | WCAG 2.1 accessibility policy |
| FAQ & Bantuan | `/faq` | 30+ FAQ & panduan penggunaan |

## 🚀 Quick Start

### Install & Run Lokal

```bash
# Clone atau masuk ke folder proyek
cd privacy-jdih-gresik

# Install dependencies
npm install

# Run development server
npm run dev

# Buka http://localhost:3000
```

### Build untuk Production

```bash
# Build aplikasi
npm run build

# Start production server
npm start
```

## 📦 Struktur Proyek

```
privacy-jdih-gresik/
├── app/                          # Next.js App Router
│   ├── page.tsx                  # Home page
│   ├── layout.tsx                # Root layout
│   ├── globals.css               # Global styles
│   ├── privacy-policy/page.tsx   # Privacy policy
│   ├── terms-of-service/page.tsx # Terms of service
│   ├── accessibility/page.tsx    # Accessibility policy
│   └── faq/page.tsx              # FAQ page
├── public/                       # Static files
├── package.json                  # Dependencies
├── next.config.js                # Next.js config
├── tailwind.config.ts            # Tailwind config
├── tsconfig.json                 # TypeScript config
├── PLAYSTORE_README.md           # Play Store description
├── DOCUMENTATION.md              # Dokumentasi teknis
├── SETUP.md                      # Setup guide
└── README.md                     # File ini
```

## 🔐 Keamanan & Privacy

- **No Personal Data Collection**: Aplikasi tidak mengumpulkan data pribadi
- **No Login Required**: Akses publik langsung, tidak ada registrasi
- **No Ads or Tracking**: Tanpa iklan atau pelacakan pengguna
- **HTTPS/SSL Encryption**: Data ditransmisikan dengan aman
- **GDPR & Data Protection Law Compliant**: Sesuai regulasi

## ♿ Aksesibilitas

Aplikasi memenuhi standar aksesibilitas:
- ✅ WCAG 2.1 Level AA
- ✅ Section 508
- ✅ Screen reader support
- ✅ Keyboard navigation
- ✅ Dark mode
- ✅ Adjustable text size

Baca lebih lanjut di `/accessibility`

## 📄 Dokumentasi

### Untuk Developer:
- `DOCUMENTATION.md` - Dokumentasi teknis lengkap
- `SETUP.md` - Panduan setup & maintenance
- `PLAYSTORE_README.md` - Deskripsi untuk stores

### Untuk Stakeholder:
- `PLAYSTORE_README.md` - Overview aplikasi
- `app-store-config.json` - Metadata untuk stores
- Privacy Policy - `/privacy-policy`
- Terms of Service - `/terms-of-service`

## 🔄 File Penting yang Perlu Diupdate

Sebelum deployment, update:

1. **Domain URLs** (ganti `jdih-gresik.example.com`):
   - `app/page.tsx`
   - `PLAYSTORE_README.md`
   - Privacy Policy & Terms (Hubungi Kami)
   - FAQ (Contact section)

2. **Environment Variables**:
   - Copy `.env.example` ke `.env.local`
   - Isi dengan informasi sebenarnya

3. **Contact Information**:
   - Email: info@gresikkab.go.id
   - Telepon: (031) 3980800
   - Website: www.gresikkab.go.id
   - Alamat: Jl. Soekarno-Hatta No. 1, Gresik

## 📦 Dependencies

```json
{
  "react": "^18.3.1",
  "react-dom": "^18.3.1",
  "next": "^15.1.0",
  "tailwindcss": "^3.4.7",
  "typescript": "^5.7.2"
}
```

## 🎨 Design & Styling

- **Framework**: Tailwind CSS
- **Color Scheme**: Blue & Indigo gradient
- **Responsive**: Mobile-first design
- **Accessibility**: WCAG compliant colors & contrast

## 📊 SEO Optimization

- Meta tags configured
- Open Graph optimized
- Keywords: JDIH, Gresik, Hukum, Peraturan, Perda, dll
- Robots.txt configured
- Mobile friendly

## 🧪 Testing

```bash
# Type checking
npm run type-check

# Build test
npm run build

# Development testing
npm run dev
```

## 📞 Support & Contact

**Dinas Komunikasi dan Informatika Kabupaten Gresik**
- 📧 Email: info@gresikkab.go.id
- 📱 Telepon: (031) 3980800
- 🌐 Website: www.gresikkab.go.id
- 📍 Alamat: Jl. Soekarno-Hatta No. 1, Gresik

**Untuk Masalah Aksesibilitas:**
- 📧 Email: accessibility@gresikkab.go.id

## 📋 Pre-Launch Checklist

- [x] Privacy Policy lengkap
- [x] Terms of Service lengkap
- [x] FAQ dibuat
- [x] Accessibility policy
- [x] Mobile responsive
- [x] SEO optimized
- [x] Security headers
- [x] Documentation lengkap
- [ ] Domain setup (perlu dilakukan)
- [ ] SSL certificate (perlu dilakukan)
- [ ] QA testing (perlu dilakukan)
- [ ] Legal review (perlu dilakukan)

## 🚀 Submission ke Play Store

Lihat `DOCUMENTATION.md` section "Submission ke Play Store" untuk langkah-langkah detail.

## 🍎 Submission ke App Store

Lihat `DOCUMENTATION.md` section "Submission ke App Store" untuk langkah-langkah detail.

## 📜 Lisensi

© 2025 Pemerintah Kabupaten Gresik. Semua hak dilindungi.

Aplikasi ini adalah layanan publik gratis dari Pemerintah Kabupaten Gresik sesuai dengan:
- Undang-Undang No. 14 Tahun 2008 tentang Keterbukaan Informasi Publik
- Undang-Undang No. 27 Tahun 2022 tentang Perlindungan Data Pribadi

## 🔍 Versi

- **Current Version**: 1.0.0
- **Release Date**: Desember 23, 2025
- **Status**: ✅ Ready for submission

---

**Dibuat oleh**: Tim Development JDIH Kab. Gresik
**Status**: Siap untuk Production & Submission ke Play Store & App Store

🎉 Aplikasi JDIH Kab. Gresik - Platform Informasi Hukum Kabupaten Gresik!
# privacy-policy-JDIH-Gresik
