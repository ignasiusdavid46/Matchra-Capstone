# 🎮 Panduan Penggunaan Aplikasi Matchra

Selamat datang di **Matchra**, sebuah platform rekomendasi game cerdas berbasis *Artificial Intelligence* (Machine Learning). Dokumen ini berisi panduan langkah demi langkah tentang cara menggunakan fitur-fitur di dalam aplikasi Matchra untuk menemukan game yang paling cocok untuk Anda.

---

## 1. Halaman Utama (Landing Page)
Saat pertama kali membuka website Matchra, Anda akan disambut oleh halaman utama.
- Anda dapat melihat rangkuman fungsi aplikasi di bagian *Hero Banner*.
- Di bawah banner utama, terdapat **Conveyor Game Marquee**, yaitu komidi putar dinamis yang menampilkan katalog berbagai macam game populer secara acak dari database kami.
- Anda bisa menekan tombol **Mulai Cari Game** atau **Panduan Pemula** untuk masuk ke dalam fitur utama rekomendasi AI.

---

## 2. Fitur: Time & Budget Recommender
Fitur ini cocok bagi Anda yang sudah tahu *genre* apa yang disuka, tetapi bingung mencari game yang durasi tamatnya (*playtime*) pas dengan kesibukan Anda dan harganya pas di kantong.

**Cara Penggunaan:**
1. Klik menu **Time & Budget** pada *sidebar* di sebelah kiri.
2. **Input Genre/Tema:** Ketikkan *genre*, tema, atau judul game referensi yang Anda sukai (misalnya: `"action rpg open world"`, `"zombie survival"`, atau `"mirip GTA V"`).
3. **Pilih Waktu Luang:** Pilih durasi permainan yang Anda inginkan (Tersedia opsi *Singkat*, *Menengah*, atau *Sangat Panjang* untuk game epik).
4. **Atur Budget:** Geser *slider* budget dari **Gratis** hingga **Game AAA** sesuai dana yang Anda siapkan.
5. Klik tombol **Cari Rekomendasi Game**.
6. Sistem AI Matchra akan memproses kata kunci Anda menggunakan metode *TF-IDF* dan *Latent Semantic Analysis (LSA)*, kemudian menampilkan 5 game dengan tingkat kecocokan (Similarity Score) tertinggi.

---

## 3. Fitur: Beginner Guide (Panduan Pemula)
Fitur ini dirancang khusus bagi pengguna yang baru pertama kali ingin mencoba bermain game dan bingung harus mulai dari mana.

**Cara Penggunaan:**
1. Klik menu **Beginner Guide** pada *sidebar* di sebelah kiri.
2. **Pilih Pengalaman:** Pilih salah satu pengalaman bermain yang Anda cari:
   - *Cerita Mendalam* (Fokus pada narasi).
   - *Gameplay Aksi* (Fokus pada adrenalin).
   - *Santai/Kasual* (Fokus untuk rileks).
3. **Pilih Platform:** Tentukan platform bermain yang Anda miliki (PC, PlayStation, Xbox, atau Switch).
4. **Pilih Intensitas:** Seberapa rumit game yang ingin Anda pelajari (Santai, Menengah, atau Menantang).
5. Klik tombol **Beri Rekomendasi**.
6. Matchra akan menerjemahkan pilihan Anda ke dalam atribut *gameplay* dan mencarikan game-game ramah pemula yang sesuai.

---

## 4. Membaca Hasil Rekomendasi
Setelah AI memproses *input* Anda, layar akan menampilkan kartu-kartu hasil pencarian. Pada setiap kartu game, Anda dapat melihat informasi:
- **Gambar Sampul Game** (Thumbnail).
- **Match Score:** Menunjukkan persentase kemiripan antara input Anda dengan deskripsi game tersebut (contoh: *Match: 85%*). Semakin tinggi, semakin relevan.
- **Genre & Tag:** Kategori utama game tersebut.
- **Harga (Price) & Playtime:** Estimasi harga game dan waktu yang dibutuhkan untuk menyelesaikannya.
- **Deskripsi Singkat:** Sinopsis atau ringkasan cerita dari game.

---

### Catatan Tambahan
- Jika Anda ingin kembali ke halaman utama (*Landing Page*), Anda dapat kapan saja mengeklik tombol **Home** dengan ikon rumah 🏠 yang berada di urutan paling atas pada menu *sidebar*.
- Pastikan koneksi internet Anda stabil, karena aplikasi menarik *thumbnail* game langsung dari *server* pihak ketiga.

Selamat mengeksplorasi dan menemukan game impian Anda di Matchra! 🚀
