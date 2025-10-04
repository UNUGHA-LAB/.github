<!-- UNUGHA-LAB — Organization Profile README
Letakkan file ini di: .github/profile/README.md
-->

<p align="center">
  <img src="/unugha-badge.svg" alt="UNUGHA–LAB Badge" width="360">
</p>

<p align="center">
  <img src="/unugha-hero-banner.svg" alt="UNUGHA-LAB Hero Banner" width="100%">
</p>

<h1 align="center">UNUGHA-LAB</h1>
<h2 align="center">https://github.unugha.ac.id</h2>
<p align="center">
  https://github.unugha.ac.id
  Laboratorium inovasi digital Universitas Nahdlatul Ulama Al Ghazali (UNUGHA) — 
  membangun solusi terbuka untuk kampus: sistem peminjaman, HR/SDM, SSDI, otomasi WA, dan ekosistem data.
</p>

<p align="center">
  <a href="#🚀-program-utama">Program Utama</a> •
  <a href="#🧩-proyek-unggulan">Proyek Unggulan</a> •
  <a href="#🤝-cara-berkontribusi">Kontribusi</a> •
  <a href="#📅-komunitas--agenda">Agenda</a> •
  <a href="#📚-guides--templates">Guides</a>
</p>

---

## 🔭 Misi
- **Akselerasi transformasi digital** layanan kampus melalui perangkat lunak terbuka yang **terpakai nyata**.
- **Kolaborasi lintas unit** (SSDI, Sarpras, Akademik, Humas) dengan best-practice rekayasa perangkat lunak.
- **Pembelajaran berbasis proyek (PBL)** untuk mahasiswa & dosen: dari desain hingga deployment produksi.

## 🧭 Prinsip
- **Open by default** — repos publik saat memungkinkan.
- **DX yang ramah** — starter kit, seeder, dan dokumentasi jelas.
- **Interop & otomasi** — integrasi WhatsApp API, ICS kalender, CSV/Excel, dan PDF resmi.
- **Keamanan & privasi** — auth berbasis peran, audit trail, dan review kode.

---

## 🚀 Program Utama
- **Peminjaman Ruangan & Kendaraan** — booking, approval berjenjang, QR check-in/out, kalender aset.
- **Platform HR/SDM Kampus** — presensi, cuti, payroll, KPI, arsip dokumen pegawai.
- **SSDI Portal & Layanan TI** — kanal layanan jaringan, email, domain/hosting, status page.
- **PKKMB & Event** — landing page, registrasi, tiket QR, notifikasi WA.
- **Konten & SEO** — blog dinamis, OG generator, pipeline kurasi konten.

---

## 🧩 Proyek Unggulan
> *Tambahkan link repo Anda di tabel ini.*

| Proyek | Deskripsi | Teknologi | Status |
|---|---|---|---|
| **univ-booking-system** | Sistem peminjaman ruangan & kendaraan (multi-approval, PDF surat + QR) | React, Laravel, Supabase/CF | 🚧 Beta |
| **hr-sdm-suite** | HR/SDM kampus lengkap (Filament, Spatie Permission) | Laravel, Filament, MySQL | 🧪 Pilot |
| **ssdi-portal** | Portal SSDI + status layanan + formulir WA | React, Tailwind, Workers | ✅ Prod |
| **waha-notifier** | Plugin notifikasi WhatsApp (broadcast, rate limit, CSV) | PHP, WAHA API | ✅ Prod |
| **trend-unique-blog** | Blog AI-assisted (OG gen, SEO, cron tren) | Next/React, Supabase, Vercel | 🚧 Dev |

> 📌 Gunakan label: `good first issue`, `help wanted`, `needs-docs`.

---

## 🛠️ Tech Stack
- **Frontend**: React + Vite/Next, TypeScript, Tailwind, shadcn/ui
- **Backend**: Laravel + Filament (admin), Cloudflare Workers/Pages
- **Data**: Supabase (Postgres + Auth), MySQL/MariaDB, D1 (edge)
- **Build & Ops**: Vercel/Cloudflare Pages, Wrangler, GitHub Actions
- **Integrasi**: WAHA API, ICS/Calendar, CSV/Excel Import–Export, PDF (kop surat + QR)

---

## 📚 Guides & Templates
- **Starter Repo Template**: standar folder, CI, lint, formatter, commit conv.
- **Blueprint ERD + Diagram**: ERD besar + sub-ERD modul (Presensi, Cuti, dll).
- **Doc & Demo**: skrip seeder, data contoh, dan skenario uji cepat.
- **Security Checklist**: .env, JWT/Role, audit log, backup & restore.

> 💡 Simpan dokumentasi proyek di `/docs` dan tambahkan **demo GIF** di README repo masing-masing.

---

## 🤝 Cara Berkontribusi
1. **Fork** repos terkait, buat branch fitur: `feat/nama-fitur`.
2. **Commit** sesuai konvensi: `type(scope): subject`.
3. **PR** dengan ringkasan, screenshot/demo, dan checklist uji.
4. **Code Review** oleh maintainer; mohon ikuti style & linter project.
5. **Docs!** Sertakan update README/CHANGELOG bila ada perubahan.

**Kode Etik**: Lihat `CODE_OF_CONDUCT.md` (wajib).  
**Lisensi**: Default **MIT** (kecuali dinyatakan lain pada repo).

---

## 📅 Komunitas & Agenda
- **#OpenLab Night**: sesi bulanan—showcase, code review, bug bash.
- **TechTalk@UNUGHA**: topik Edutech, DevOps, DX, dan AI-assisted dev.
- **Issue Sprint**: pekanan untuk label `help wanted`.

> Ikuti tab **Discussions** untuk pengumuman & voting topik meetup.

---

## 🗺️ Roadmap Singkat
- [ ] Starter monorepo + template GitOps.
- [ ] Hardening auth & RBAC lintas aplikasi.
- [ ] Observability (logs, metrics, uptime status page).
- [ ] Paket komponen UI kampus (branding UNUGHA).
- [ ] Integrasi notifikasi lintas kanal (WA/Email).

---

## 📣 Kontak
- **Website SSDI**: https://ssdi.unugha.ac.id
- **Email**: ssdi@unugha.ac.id
- **Lokasi**: Cilacap, Jawa Tengah, Indonesia

> Ingin bergabung atau kolaborasi? Buat issue di repos terkait atau mulai diskusi di **Discussions**.

<p align="center">
  Dibangun bersama ❤️ oleh komunitas <b>UNUGHA-LAB</b>. 
  Ayo kontribusi, belajar, dan berdampak nyata untuk kampus!
</p>
