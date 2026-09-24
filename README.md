# Python Regular Expressions (RegEx) Practice

Repositori ini berisi kumpulan studi kasus penerapan **Regular Expressions (RegEx)** menggunakan pustaka `re` di Python untuk pemrosesan teks, manipulasi data, dan ekstraksi informasi pada skenario E-Commerce & Logistik.

---

## Deskripsi Proyek

Notebook ini mendemonstrasikan **39+ teknik ekstrasi dan manipulasi teks** berbasis RegEx yang mencakup:

### 1. Ekstraksi Data Transaksi & Produk
* **ID Transaksi & SKU:** Mengambil format nomor faktur (`#INV-...`) dan kode SKU barang (`SKU: ...`).
* **Keuangan & Harga:** Ekstraksi nominal harga (`Rp ...`), persentase diskon (`%`), serta masking nomor kartu kredit demi keamanan[cite: 3].
* **Spesifikasi & Varian:** Parsing dimensi produk (`30x20x15 cm`), berat (`gr`/`kg`), warna/ukuran, serta atribut spesifikasi (`RAM`, `Storage`, `Baterai`)[cite: 3].

### 2. Pengolahan Data Logistik & Pengiriman
* **Nomor Resi & Ekspedisi:** Identifikasi nomor resi pengiriman (`JNE...`), nama kurir (`SiCepat REG`), dan lokasi rak gudang (`RAK-...`)[cite: 3].
* **Alamat & Kontak:** Ekstraksi kode pos 5 digit, sanitasi nomor telepon (`08...` / `+62...`), dan alamat email[cite: 3].

### 3. Pembersihan & Normalisasi Teks (Text Preprocessing)
* **Sanitasi Data:** Menghapus tag HTML (`<p>`, `<b>`), menghilangkan *multiple whitespace*, dan mengekstrak karakter emoji/unicode[cite: 3].
* **Normalisasi Chat:** Mengubah singkatan tidak baku (*slang text*) seperti `brg`, `sdh`, `smp`, `tq` menjadi kata baku[cite: 3].
* **Analisis Sentimen & Keamanan:** Filter kata kasar/spam, ekstraksi hashtag promosi, serta deteksi pola serangan *SQL Injection*[cite: 3].

---

## Library yang Digunakan

* `re` — Module bawaan Python untuk pengolahan RegEx (fungsi `re.findall()`, `re.sub()`, dll.)[cite: 3].

---

## Cara Menjalankan

1. Clone repositori ini:
   ```bash
   git clone [https://github.com/USERNAME_KAMU/NAMA_REPOSITORI.git](https://github.com/USERNAME_KAMU/NAMA_REPOSITORI.git)
