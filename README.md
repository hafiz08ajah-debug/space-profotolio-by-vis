# Portfolio Website — GitHub + Vercel

Website portfolio statis dengan latar bintang animasi, navigasi Home/About/Portfolio/Contact, filter proyek, tech stack, dan formulir kontak berbasis `mailto:`.

## Cara upload lewat HP Android

1. Ekstrak ZIP ini.
2. Buka GitHub dan buat repository baru, misalnya `portfolio-website`.
3. Pilih **Add file → Upload files**, lalu upload `index.html` dan `README.md` dari folder hasil ekstrak. Commit perubahan.
4. Buka Vercel dan login dengan GitHub.
5. Tekan **Add New → Project**, pilih repository `portfolio-website`, lalu **Deploy**.
6. Vercel akan memberi domain seperti `portfolio-website.vercel.app`.

## Sebelum dipublikasikan

Buka `index.html`, lalu cari dan ubah:
- `Nama Kamu` → nama kamu.
- `ganti-email-kamu@example.com` → email yang kamu gunakan.
- Link GitHub, LinkedIn, dan Instagram → akun kamu.
- Deskripsi, statistik, proyek, dan teknologi → data yang benar.
- Bagian `Foto Kamu` → bisa diganti dengan foto milikmu.

## Catatan penting

Website bisa berjalan sebagai situs statis tanpa backend. Form kontak membuka aplikasi email pengunjung (tidak menyimpan/mengirim data ke database). Untuk formulir yang mengirim langsung tanpa aplikasi email, perlu layanan backend/form seperti Formspree atau fungsi server.
