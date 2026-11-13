# Petualangan Rasio - Matematika Kelas 6 SD (Fase C)

Aplikasi media pembelajaran interaktif berbasis web untuk materi Rasio Matematika Kelas 6 SD menggunakan konsep kartu bergambar.

## Fitur Utama
1. **Identitas Siswa**: Input nama dan kelas untuk memulai sesi pembelajaran.
2. **Tujuan Pembelajaran**: Memahami rasio, bagian ke bagian (part-to-part), dan bagian ke keseluruhan (part-to-whole).
3. **Materi Inti Interaktif**: Penjelasan konsep rasio dan cara menyederhanakan rasio.
4. **Eksplorasi Kartu Bergambar**: Simulasi interaktif membalik kartu dan menjawab rasio.
5. **Kuis Evaluasi (10 Soal)**: Pilihan ganda dengan feedback visual instan dan pembahasan.
6. **Laporan Hasil & Refleksi**: Skor akhir, bintang prestasi, cetak sertifikat, dan refleksi diri.
7. **Fitur Logout & Ganti Sesi**: Tombol logout di header navigasi dan halaman hasil dilengkapi modal konfirmasi bertema sama.

## Cara Deploy ke Netlify

### Metode 1: Hubungkan ke GitHub / GitLab / Bitbucket (Direkomendasikan)
1. Push project ini ke repositori GitHub Anda:
   ```bash
   git add .
   git commit -m "feat: Petualangan Rasio siap deploy"
   git remote add origin <URL_REPO_ANDA>
   git push -u origin master
   ```
2. Buka [app.netlify.com](https://app.netlify.com/) dan login.
3. Klik **"Add new site"** > **"Import an existing project"**.
4. Pilih penyedia Git Anda (GitHub) dan pilih repositori ini.
5. Konfigurasi build otomatis terdeteksi via file `netlify.toml`:
   - **Build command**: *(kosongkan)*
   - **Publish directory**: `.` *(atau biarkan default)*
6. Klik **"Deploy site"**.

### Metode 2: Netlify Drop (Drag & Drop Langsung Tanpa Git)
1. Buka [app.netlify.com/drop](https://app.netlify.com/drop).
2. Seret (drag & drop) seluruh folder `petualanganRasio` ke browser.
3. Website akan langsung aktif dalam hitungan detik dengan URL gratis Netlify!

---

## Cara Menghapus Badge / Watermark "Powered by Netlify"
Badge tersebut otomatis disisipkan oleh fitur bawaan Netlify (*Netlify Drawer / Feedback Badge*). Anda dapat mematikannya melalui dashboard Netlify:
1. Masuk ke **[app.netlify.com](https://app.netlify.com/)** dan pilih situs Anda.
2. Buka menu **Site configuration** (atau **Site settings**).
3. Pilih **General** > cari bagian **Powered by Netlify badge**, lalu ubah posisinya ke **Off** (Nonaktif).
4. Jika masih muncul (sebagai *Netlify Drawer / Collaboration Tools*):
   - Masuk ke **Site configuration** > **Continuous deployment** > **Collaboration tools**.
   - Klik **Configure**, hilangkan centang pada opsi **Netlify Drawer** (untuk Deploy Previews / Branch deploys), lalu klik **Save**.


