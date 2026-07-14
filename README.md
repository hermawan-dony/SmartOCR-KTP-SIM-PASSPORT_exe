# 🌟 INDONESIAN DOCUMENT OCR ENGINE (e-KTP, PASSPORT, SIM A/B/C) 🌟
### Full AI Cloud Auto-detect & Offline Mode. Ready for PowerBuilder & Legacy App integration.

Halaman ini menyediakan rilis berkas executable (`smartocr.exe` dan `smartocr_server.exe`) untuk demo pemrosesan dokumen KTP, Passport, dan SIM Indonesia. 

---

## 📢 HUBUNGI KAMI UNTUK SOURCE CODE & INTEGRASI
Jika Anda membutuhkan **Source Code Lengkap (C# CLI, Portable PWA Server, & PowerBuilder Object .srw/.srd)**, **Secret Code Cloud AI**, serta **Bantuan Integrasi Penuh** ke sistem aplikasi Anda, silakan hubungi:

### 🟢 WhatsApp: **[0851-7172-1782](https://wa.me/6285171721782)**
*Siap membantu integrasi ke PowerBuilder, Delphi, FoxPro, VB6, PHP, ASP.NET, Java, dll.*

---

## 1. `smartocr.exe` (CLI Utility)
Utilitas Command Line Interface (CLI) yang sangat ringan untuk mengekstrak data terstruktur dari dokumen Indonesia. Mudah dipanggil dari aplikasi desktop apa pun (PowerBuilder, Delphi, dll.).

### Cara Penggunaan:
```cmd
smartocr.exe "C:\path\to\document.jpg" [secret_code]
```

* **Mode Offline (Default)**: Berjalan 100% lokal tanpa koneksi internet menggunakan Windows OCR Engine.
* **Mode Cloud AI**: Menggunakan AI tingkat tinggi untuk ekstraksi data dengan akurasi 100% dan mengembalikan hasil dalam format terstruktur dipisahkan oleh karakter pipa (`|`).

### Format Hasil OCR (Mode Cloud AI):
* **KTP (17 Kolom):**
  `KTP|Provinsi|KabupatenKota|NIK|Nama|TempatLahir|TanggalLahir|JenisKelamin|Alamat|RtRw|KelDesa|Kecamatan|Agama|StatusPerkawinan|Pekerjaan|Kewarganegaraan|BerlakuHingga`
* **PASSPORT (15 Kolom):**
  `PASSPORT|NoPaspor|NamaLengkap|Jenis|KodeNegara|Kewarganegaraan|TanggalLahir|JenisKelamin|TempatLahir|TanggalPengeluaran|TanggalHabisBerlaku|NoReg|KantorPengeluar|MRZ1|MRZ2`
* **SIM (12 Kolom):**
  `SIM|GolonganSIM|NoSIM|Nama|TempatLahir|TanggalLahir|JenisKelamin|Alamat|Pekerjaan|KabupatenKota|PoldaPenerbit|BerlakuHingga`

---

## 2. `smartocr_server.exe` (Portable PWA Server)
Aplikasi WinForms mandiri yang berfungsi sebagai Web Server lokal. Server ini menyediakan **PWA Mobile Web App** sehingga operator/sales Anda dapat memotret dokumen menggunakan kamera smartphone Android/iOS, lalu mengunggahnya secara langsung ke folder PC Windows Anda melalui jaringan Wi-Fi lokal.

### Fitur Utama:
* **Tanpa Setup**: Tidak perlu IIS, Apache, Nginx, maupun Database.
* **Auto QR Code**: Scan QR Code di layar server menggunakan HP untuk membuka Web App kamera instan.
* **Kamera & Auto Crop**: Antarmuka kamera seluler ter-embed pemotong gambar (crop) otomatis.

---

### Gambar Contoh Uji Coba (Dapat Diunduh di Folder demo-pb):
*(Catatan: Gambar contoh Paspor dan SIM yang digunakan untuk pengujian ini bersumber dari mesin pencari publik seperti Google Images. Karena dokumen-dokumen tersebut dapat diakses secara publik di internet, dokumen tersebut tidak memerlukan sensor privasi khusus).*

- **KTP Sample**:
  ![KTP Sample](demo-pb/demo-ktp.jpg)

- **Passport Sample**:
  ![Passport Sample](demo-pb/demo-pass.jpg)

- **SIM Sample**:
  ![SIM Sample](demo-pb/demo-sim.jpg)

---

### Hasil Screenshoot Server & Mobile PWA Interface:
- **Desktop Server Interface**:
  ![Desktop Server](demo-pb/svr1.jpeg)

- **Mobile PWA Interface**:
  ![Mobile PWA](demo-pb/svr2.jpeg)

---

### 💼 Dapatkan Layanan Profesional Kami:
1. Full Source Code Project (C# & PowerBuilder).
2. Kustomisasi jenis dokumen lain sesuai kebutuhan bisnis Anda.
4. **Hubungi WhatsApp: [0851-7172-1782](https://wa.me/6285171721782)**
