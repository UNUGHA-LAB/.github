# Kebijakan Keamanan

Kami serius terhadap keamanan. Jika Anda menemukan kerentanan, mohon **jangan** membuka issue publik.

## Laporkan Kerentanan
- Email: **ssdi@unugha.ac.id** (subject: `[SECURITY]`)
- Sertakan deskripsi kerentanan, langkah reproduksi, dampak, dan PoC (jika ada).

Kami akan mengirim konfirmasi penerimaan laporan dalam 72 jam dan update status perbaikan secara berkala.

## Cakupan
- Semua repos di organisasi **UNUGHA-LAB**
- Layanan demo/staging terkait proyek UNUGHA-LAB

## Praktik Rekomendasi
- Simpan rahasia di secret manager (GitHub Actions, Vercel/CF).
- Gunakan **JWT + RBAC** untuk akses.
- Audit log untuk aksi sensitif; backup & restore teruji.
- Dependabot / security updates diaktifkan.

## Kredit
Kami menghargai pelapor (responsible disclosure) dan dapat menambahkan kredit setelah perbaikan rilis.
