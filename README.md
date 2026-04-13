# Tugas Pemrograman Web Dinamis

Repositori ini berisi implementasi antarmuka web interaktif menggunakan antarmuka halaman tunggal (*Single Page Application* sederhana) yang dibangun dengan HTML, CSS, dan Vanilla JavaScript. Proyek ini dibuat untuk memenuhi tugas pemrograman web.

**Muhammad Fathur Aziz**

## Fitur Utama

Proyek ini menggabungkan tiga tugas utama menjadi satu alur antarmuka yang dinamis:

1. **Form Registrasi Mahasiswa (Autocomplete & Validasi)**
   - Menggunakan tag `<datalist>` untuk fitur *autocomplete* pada input nama.
   - Dilengkapi dengan validasi JavaScript dasar untuk memastikan kolom input penting (Nama dan NIM) tidak dibiarkan kosong sebelum melanjutkan ke tahap berikutnya.

2. **Pencarian Kode Pos Indonesia (Cascading Dropdown)**
   - Fitur pencarian kode pos berbasis *dropdown* bertingkat (Provinsi ➔ Kota/Kabupaten ➔ Kecamatan).
   - *Dropdown* level berikutnya hanya akan aktif setelah *dropdown* sebelumnya dipilih, mencegah input data yang tidak valid.
   - Hasil pencarian kode pos akan ditampilkan secara dinamis di layar.

3. **Filter Produk Dinamis (Dropdown Dependent)**
   - Implementasi logika *dropdown* yang bergantung pada pilihan sebelumnya (Kategori Produk ➔ Merk).
   - Opsi merk secara otomatis menyesuaikan berdasarkan jenis produk yang dipilih oleh pengguna.

##  Yang Digunakan

* **HTML5:** Struktur dasar dan elemen form interaktif.
* **CSS3:** *Styling* antarmuka, *layouting* yang responsif, dan animasi transisi antar halaman.
* **Vanilla JavaScript (ES6):** Manipulasi DOM, validasi form, dan logika simulasi *database* menggunakan Objek JS untuk *cascading dropdown*.

Akses Web di: https://fathurdxs.github.io/Formulir_Mahasiswa/
