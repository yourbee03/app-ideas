### Nama Proyek
**Task Timekeeper** – Aplikasi untuk mengatur dan melacak tugas harian dengan durasi waktu terukur

### Tingkat Kesulitan
Beginner

### Deskripsi
Aplikasi Task Timekeeper memungkinkan pengguna untuk membuat, mengedit, dan menghapus tugas harian mereka, tetapi dengan fitur tambahan yang dapat melacak berapa lama waktu yang dihabiskan pada setiap tugas. Pengguna dapat menetapkan durasi target dan aplikasi akan menghitung waktu yang telah digunakan untuk setiap tugas. Selain itu, aplikasi ini menyediakan notifikasi jika waktu yang telah dihabiskan melebihi target yang telah ditetapkan, membantu pengguna mengelola waktu secara efisien.

### Fitur
- **Buat tugas baru**: Pengguna dapat membuat tugas baru dengan memasukkan judul, deskripsi, dan menetapkan waktu target penyelesaian.
- **Edit tugas**: Pengguna dapat memperbarui tugas yang sudah ada.
- **Hapus tugas**: Pengguna dapat menghapus tugas yang tidak lagi diperlukan.
- **Mulai/Pause**: Pengguna dapat memulai atau menghentikan timer saat mengerjakan tugas.
- **Waktu yang dihabiskan**: Tampilkan durasi waktu yang telah dihabiskan pada setiap tugas.
- **Peringatan waktu**: Berikan notifikasi jika waktu yang digunakan melebihi target yang telah ditentukan.
- **Filter tugas berdasarkan status**: Saring tugas menjadi tugas yang sedang dikerjakan, sudah selesai, atau belum dimulai.
- **Riwayat tugas**: Simpan catatan riwayat tugas yang selesai dengan waktu yang telah dihabiskan.

### Bonus Fitur
- **Statistik harian/mingguan**: Tampilkan ringkasan berapa lama waktu yang dihabiskan untuk setiap tugas atau kategori dalam satu hari atau minggu.
- **Sinkronisasi dengan kalender**: Integrasikan aplikasi dengan Google Calendar atau aplikasi kalender lainnya untuk menjadwalkan dan memantau tugas secara langsung.
- **Pengingat berbasis lokasi**: Berikan pengingat untuk memulai atau menyelesaikan tugas saat pengguna mencapai lokasi tertentu.
- **Tema gelap/terang**: Berikan opsi untuk beralih antara mode gelap dan terang.

### Teknologi
- HTML, CSS, JavaScript (untuk aplikasi web dasar)
- Framework front-end seperti React atau Vue.js (untuk memperluas fitur)
- LocalStorage atau IndexedDB (untuk penyimpanan data lokal)
- PWA (Progressive Web App) jika ingin mengimplementasikan aplikasi yang dapat diakses secara offline

### Ketergantungan API
Tidak diperlukan untuk versi dasar, tetapi integrasi API kalender eksternal (misalnya Google Calendar API) dapat ditambahkan untuk bonus fitur.

### Langkah Pengembangan
1. **Buat UI dasar** untuk daftar tugas dengan form untuk menambah dan mengedit tugas.
2. **Tambahkan timer** yang memulai dan menghentikan penghitungan waktu untuk setiap tugas.
3. **Tambahkan penyimpanan lokal** untuk menyimpan tugas dan riwayat waktu.
4. **Implementasikan notifikasi** saat waktu melebihi target.
5. **Bonus**: Tambahkan fitur sinkronisasi dan statistik untuk peningkatan fungsionalitas.

### Referensi
- Gunakan aplikasi [Todoist](https://todoist.com/) sebagai inspirasi untuk tampilan dan pengelolaan tugas.
