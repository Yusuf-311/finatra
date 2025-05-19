# Finatra - Pembiayaan UMKM

![Finatra Logo](images/logo-big-finatra.png)

[![Website Status](https://img.shields.io/website?url=https%3A%2F%2Ffinatra.co.id)](https://finatra.co.id)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Bootstrap](https://img.shields.io/badge/bootstrap-5.0-purple.svg)](https://getbootstrap.com/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

Finatra adalah brand service dari FIFGROUP yang fokus pada pembiayaan usaha UMKM. Platform ini menyediakan solusi pembiayaan yang mudah dan cepat untuk membantu pertumbuhan usaha kecil dan menengah di Indonesia.

## 📸 Screenshots

| Homepage                              | Formulir Pengajuan                |
| ------------------------------------- | --------------------------------- |
| ![Homepage](screenshots/homepage.png) | ![Formulir](screenshots/form.png) |

| Kalkulator Pembiayaan                     | Dashboard UMKM                          |
| ----------------------------------------- | --------------------------------------- |
| ![Kalkulator](screenshots/calculator.png) | ![Dashboard](screenshots/dashboard.png) |

## 🌟 Fitur Utama

- **Proses Cepat**: Pengajuan pembiayaan diproses dalam 3 hari kerja setelah dokumen lengkap
- **Tenor Fleksibel**: Pilihan tenor hingga 5 tahun
- **Terpercaya**: Berizin dan diawasi oleh OJK (Otoritas Jasa Keuangan)
- **Jaminan Fleksibel**: Menerima jaminan berupa BPKB Motor, Mobil, atau Properti

## 🚀 Teknologi yang Digunakan

- HTML5
- CSS3
- Bootstrap 5
- JavaScript
- Font Awesome Icons
- Google Fonts

## 🔧 Development Setup

### Prerequisites

```bash
# Install Node.js dependencies
npm install

# Install development tools
npm install -g sass
npm install -g http-server
```

### Development Environment

```bash
# Compile SASS
sass --watch scss:css

# Start development server
http-server -p 3000
```

### Build Process

```bash
# Compile and minify CSS
sass scss:css --style compressed

# Optimize images
npm run optimize-images

# Build for production
npm run build
```

### Code Quality

```bash
# Run linter
npm run lint

# Run tests
npm run test

# Check for accessibility
npm run a11y
```

## 📋 Project Structure

```
finatra/
├── css/                  # Compiled CSS files
├── js/                   # JavaScript files
├── images/              # Image assets
├── scss/               # SASS source files
├── vendor/             # Third-party libraries
├── docs/               # Documentation
└── index.html          # Main entry point
```

## 📊 Performance Metrics

- Lighthouse Score: 95+
- Page Load Time: < 3s
- First Contentful Paint: < 1.5s
- Time to Interactive: < 3.5s

## 🔐 Security

- SSL/TLS Encryption
- Data Encryption at Rest
- Regular Security Audits
- OWASP Compliance

## 📝 Syarat dan Ketentuan Pembiayaan

### Persyaratan Dokumen

- KTP Pemohon (dan pasangan jika sudah menikah)
- Kartu Keluarga
- NPWP
- Dokumen Jaminan (BPKB/Sertifikat)
- Bukti usaha produktif

### Plafond Pembiayaan

- Minimum: Rp 25 Juta
- Maksimum: Rp 500 Juta

## 🤝 Kontribusi

Kami sangat menghargai kontribusi Anda untuk pengembangan platform ini. Untuk berkontribusi:

1. Fork repository
2. Buat branch baru (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan Anda (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buat Pull Request

## 🐛 Known Issues

See the [open issues](https://github.com/yourusername/finatra/issues) for a list of known issues and proposed features.

## 📄 Lisensi

Distributed under the MIT License. See `LICENSE` for more information.

## 📞 Kontak

Website: [https://finatra.co.id](https://finatra.co.id)  
WhatsApp: [+62 821-1610-9549](https://wa.me/6282116109549)

## ⚡ Quick Links

- [Pengajuan Pembiayaan](https://finatra.co.id/apply)
- [Tentang Kami](https://finatra.co.id/about)
- [FAQ](https://finatra.co.id/faq)
- [Hubungi Kami](https://finatra.co.id/contact)

## 📈 Roadmap

- [x] Landing Page Launch
- [x] Online Application Form
- [ ] Digital KYC Integration
- [ ] Mobile App Development
- [ ] AI-Powered Risk Assessment
- [ ] Real-time Application Tracking

---

© 2024 Finatra - FIF Group. All Rights Reserved.
