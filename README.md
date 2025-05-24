# PerancanganWeb-DesainGrafis-BisDig

# 1.Prinsip UI/UX untuk aplikasi web konsultasi kesehatan

Hierarki Visual
Tujuan: Mengarahkan perhatian pengguna ke elemen yang paling penting terlebih dahulu.
Penerapan: Judul utama (headline) dan CTA (call-to-action) seperti tombol “Mulai Konsultasi” harus paling menonjol. Gunakan ukuran font besar dan posisi strategis pada bagian atas halaman. Elemen pendukung seperti fitur layanan diletakkan secara berurutan sehingga pengguna mudah memahami struktur informasi.
Kontras

Kontras
Tujuan: Membuat informasi penting menonjol dan mudah dibaca.
Penerapan: Gunakan warna kontras antara teks dan latar belakang. Misalnya, teks gelap di atas latar terang atau sebaliknya. Untuk tombol CTA, gunakan warna yang mencolok agar langsung terlihat dan mengundang interaksi.
Whitespace (Ruang Kosong)

Whitespace(ruang kosong)
Tujuan: Memberikan ruang agar elemen tidak terasa berdesak-desakan sehingga memudahkan fokus pengguna.
Penerapan: Sisakan ruang di sekitar elemen penting seperti tombol, gambar, dan teks agar tampilannya bersih dan rapi. Whitespace juga membantu menciptakan rasa tenang dan profesional yang penting untuk layanan kesehatan.
Konsistensi

Konsistensi
Gunakan skema warna, tipe font, dan gaya tombol yang konsisten di seluruh halaman web untuk membangun kepercayaan dan mempermudah navigasi.

Navigasi yang Sederhana dan Jelas
Pastikan menu navigasi mudah ditemukan dan digunakan. Gunakan label yang familiar untuk pengguna agar mereka tahu ke mana tujuan tiap tautan.

Wireframe Kasar Halaman Homepage dengan Anotasi Elemen Utama
Saya buat wireframe sederhana dengan elemen-elemen utama berikut:

Header dengan logo dan menu navigasi
Hero section dengan headline, subheadline, dan tombol CTA utama
Seksi fitur layanan utama
Testimoni pengguna
Footer dengan informasi kontak dan sosial media

# 2. Prototipe Desain untuk Landing Page Promosi
### Manfaat Membuat Prototipe Desain Sebelum Implementasi

Membuat prototipe desain seperti di Figma sebelum mengimplementasikan ke dalam kode memberikan banyak manfaat, di antaranya:
1. Visualisasi Ide Awal
Prototipe membantu tim memahami bagaimana tampilan dan interaksi pengguna pada website, sebelum satu baris kode pun ditulis.
2. Mencegah Rework (Pekerjaan Ulang)
Dengan validasi desain terlebih dahulu, perubahan besar bisa dilakukan pada tahap desain, bukan saat pengembangan, sehingga menghemat waktu dan biaya.
3. Kolaborasi Tim Lebih Efektif
Desainer, developer, dan pemangku kepentingan (stakeholder) bisa melihat dan memberikan masukan lebih awal.
4. User Testing Lebih Cepat
Prototipe memungkinkan dilakukan pengujian pengguna lebih awal untuk mengetahui apakah desain sudah user-friendly.
5. Dokumentasi dan Pedoman Developer
Desain yang sudah diprototipe bisa menjadi referensi visual dan struktural bagi developer saat membangun website.

Komponen
- *PromoCard:* Menampilkan gambar promo, judul, dan tombol "Daftar Sekarang".
- *Desain Figma:* Disimpan dalam folder /desain.

# 3. Interaktivitas dengan JavaScript
### Penjelasan JavaScript
JavaScript digunakan untuk mengubah properti tampilan (CSS) dari elemen komentar. Saat tombol diklik, JavaScript akan memeriksa apakah komentar sedang terlihat atau tidak, lalu menampilkannya atau menyembunyikannya sesuai kondisi.

  ### Fitur: Tombol Tampilkan/Sembunyikan Komentar
Proyek ini menunjukkan cara membuat interaktivitas sederhana di halaman blog menggunakan HTML, CSS, dan JavaScript.
  ### Penjelasan
Fitur utama adalah tombol *"Tampilkan Komentar"* yang dapat digunakan untuk menyembunyikan atau menampilkan bagian komentar. Interaksi ini dibuat menggunakan JavaScript dengan cara mengubah properti display dari elemen div.
  ### Cara Kerja
- Komentar disembunyikan secara default menggunakan CSS (display: none)
- Saat tombol diklik, fungsi toggleKomentar() akan dijalankan
- Fungsi ini akan memeriksa kondisi saat ini dan mengubah teks tombol serta tampilan komentar

# 4.Halaman Profil Fotografer
### Struktur Dasar HTML5 untuk Halaman Profil Fotografer
HTML5 menyediakan elemen-elemen semantik seperti header,main, section, dan footer yang membantu menyusun halaman secara terstruktur dan mudah dipahami, baik oleh manusia maupun mesin pencari.
  ### Penjelasan Struktur

- header: Menampilkan nama fotografer dan profesinya.

- main: Menjadi wadah konten utama halaman.

- section Tentang Saya: Deskripsi singkat fotografer.

- section Galeri: Menampilkan beberapa contoh hasil foto.

- section Media Sosial: Tautan ke akun sosial media.

- footer: Hak cipta atau informasi tambahan.


# 5.Responsive Design untuk Portofolio Mahasiswa
### Penjelasan Konsep: Responsive Design dan Media Queries
Responsive Design adalah metode desain web yang memastikan tampilan situs tetap nyaman dan mudah diakses pada berbagai perangkat, mulai dari smartphone hingga desktop. Elemen-elemen halaman seperti gambar, teks, dan tata letak akan menyesuaikan secara otomatis berdasarkan ukuran layar pengguna.

Media Queries adalah fitur dalam CSS yang memungkinkan kita menerapkan aturan gaya yang berbeda tergantung pada karakteristik perangkat, seperti lebar layar. Dengan media queries, kita bisa menyembunyikan, memperkecil, atau mengatur ulang elemen agar tampil lebih baik pada layar kecil seperti smartphone.

Proyek ini menunjukkan cara membuat situs portofolio yang responsif menggunakan CSS dan media queries agar tampil rapi di semua perangkat, termasuk smartphone.
  # Masalah yang Diatasi
- Gambar terlalu besar di layar kecil
- Teks meluber ke luar layar
  # Solusi
- Menggunakan Flexbox untuk membuat tata letak gambar fleksibel
- Mengatur max-width pada gambar agar tidak melebihi lebar layar
- Menyesuaikan ukuran teks dan margin menggunakan media queries






