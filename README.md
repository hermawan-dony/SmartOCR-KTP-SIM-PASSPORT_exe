# 🌟 INDONESIAN DOCUMENT OCR ENGINE (e-KTP, PASSPORT, SIM A/B/C) 🌟
### Full AI Cloud Auto-detect & Offline Mode. Ready for PowerBuilder & Legacy App integration.

[Bahasa Indonesia](#bahasa-indonesia) | [English](#english)

---

## BAHASA INDONESIA

### 📢 HUBUNGI KAMI UNTUK SOURCE CODE & INTEGRASI
Jika Anda membutuhkan **Source Code Lengkap (C# CLI, Portable PWA Server, & PowerBuilder Object .srw/.srd)**, **Secret Code Cloud AI**, serta **Bantuan Integrasi Penuh** ke sistem aplikasi Anda, silakan hubungi:
* 🟢 **WhatsApp: [0851-7172-1782](https://wa.me/6285171721782)**
* *Siap membantu integrasi ke PowerBuilder, Delphi, FoxPro, VB6, PHP, ASP.NET, Java, dll.*

---

### 1. `smartocr.exe` (CLI Utility)
Utilitas Command Line Interface (CLI) yang sangat ringan untuk mengekstrak data terstruktur dari dokumen Indonesia. Mudah dipanggil dari aplikasi desktop apa pun (PowerBuilder, Delphi, dll.).

#### Cara Penggunaan:
```cmd
smartocr.exe "C:\path\to\document.jpg" [secret_code]
```
* **Mode Offline (Default)**: Berjalan 100% lokal tanpa koneksi internet menggunakan Windows OCR Engine.
* **Mode Cloud AI**: Menggunakan AI tingkat tinggi untuk ekstraksi data dengan akurasi 100% dan mengembalikan hasil dalam format terstruktur dipisahkan oleh karakter pipa (`|`).

#### Format Hasil OCR (Mode Cloud AI):
* **KTP (17 Kolom):** `KTP|Provinsi|KabupatenKota|NIK|Nama|TempatLahir|TanggalLahir|JenisKelamin|Alamat|RtRw|KelDesa|Kecamatan|Agama|StatusPerkawinan|Pekerjaan|Kewarganegaraan|BerlakuHingga`
* **PASSPORT (15 Kolom):** `PASSPORT|NoPaspor|NamaLengkap|Jenis|KodeNegara|Kewarganegaraan|TanggalLahir|JenisKelamin|TempatLahir|TanggalPengeluaran|TanggalHabisBerlaku|NoReg|KantorPengeluar|MRZ1|MRZ2`
* **SIM (12 Kolom):** `SIM|GolonganSIM|NoSIM|Nama|TempatLahir|TanggalLahir|JenisKelamin|Alamat|Pekerjaan|KabupatenKota|PoldaPenerbit|BerlakuHingga`

---

### 2. `smartocr_server.exe` (Server & Mobile PWA Interface)
Ini adalah alat bantu (utility tool) inovatif yang dirancang untuk mempermudah proses pengambilan gambar kartu identitas (KTP/SIM/Paspor) melalui kamera smartphone dan langsung mengirimkannya ke PC/Server Windows Anda untuk diproses oleh mesin OCR.

#### 💡 Masalah yang Diselesaikan:
Sebelum ada alat ini, operator di kantor cabang sering kali harus:
1. Memindai kartu identitas nasabah secara manual menggunakan mesin pemindai flatbed (flatbed scanner) konvensional yang memakan waktu lama.
2. Atau, mengambil foto menggunakan ponsel pribadi, lalu mengirimkannya lewat WhatsApp Web, mengunduhnya secara manual, baru memindahkannya ke sistem (proses tidak praktis & rawan kebocoran data privasi).

#### 🚀 Solusi & Keunggulan Alur Kerja Baru:
Dengan `smartocr_server.exe`, operator cukup memindai QR Code di layar PC untuk meluncurkan aplikasi web (PWA) di smartphone. Begitu foto dokumen diambil, berkas gambar secara instan masuk ke folder target di PC/Server melalui jaringan Wi-Fi lokal, tanpa perantara WhatsApp, tanpa kabel data, dan tanpa input manual!

#### Fitur Utama Server PWA:
* **Tanpa Setup**: Berjalan sebagai berkas executable mandiri (*standalone*), tidak memerlukan IIS, Apache, Nginx, atau database.
* **Port & Folder Kustom**: Atur port web server dan folder penyimpanan file hasil jepretan kamera langsung dari tampilan aplikasi (UI).
* **Auto-run Startup Windows**: Cukup centang opsi di aplikasi untuk menjalankannya secara otomatis setiap kali komputer Windows dinyalakan.
* **QR Code & Daftar IP**: Menghasilkan QR Code secara otomatis saat server berjalan. Cukup scan menggunakan smartphone untuk membuka aplikasi web instan.
* **Kompatibilitas PWA (Progressive Web App)**: Dapat diinstal langsung ke beranda (*home screen*) perangkat iOS dan Android sebagai aplikasi mandiri yang terintegrasi dengan kamera ponsel bawaan.

---

## ENGLISH

### 📢 CONTACT US FOR SOURCE CODE & INTEGRATION
If you need the **Complete Source Code (C# CLI, Portable PWA Server, & PowerBuilder Object .srw/.srd)**, **Cloud AI Secret Code**, or **Full Integration Assistance** into your legacy software, please contact:
* 🟢 **WhatsApp: [0851-7172-1782](https://wa.me/6285171721782)**
* *Ready to assist with integrations for PowerBuilder, Delphi, FoxPro, VB6, PHP, ASP.NET, Java, etc.*

---

### 1. `smartocr.exe` (CLI Utility)
A lightweight Command Line Interface (CLI) utility to extract structured data from Indonesian documents. It is designed to be easily invoked from any desktop development environment.

#### Usage:
```cmd
smartocr.exe "C:\path\to\document.jpg" [secret_code]
```
* **Offline Mode (Default)**: Runs 100% locally without an internet connection using the built-in Windows OCR Engine.
* **Cloud AI Mode**: Utilizes a highly accurate Cloud AI engine to parse documents with 100% accuracy, returning pipe-delimited (`|`) structured text.

#### OCR Output Format (Cloud AI Mode):
* **KTP (17 Columns):** `KTP|Province|City|NIK|Name|BirthPlace|BirthDate|Gender|Address|RtRw|Village|Subdistrict|Religion|MaritalStatus|Occupation|Nationality|ExpiryDate`
* **PASSPORT (15 Columns):** `PASSPORT|PassportNo|FullName|Type|CountryCode|Nationality|BirthDate|Gender|BirthPlace|IssueDate|ExpiryDate|RegNo|IssuingOffice|MRZ1|MRZ2`
* **SIM (12 Columns):** `SIM|Class|SIMNo|Name|BirthPlace|BirthDate|Gender|Address|Occupation|City|IssuingPolda|ExpiryDate`

---

### 2. `smartocr_server.exe` (Server & Mobile PWA Interface)
An innovative workflow tool designed to simplify capturing ID document photos (KTP/Passport/SIM) via smartphone camera and transferring them instantly to a target folder on your Windows PC/Server for OCR processing.

#### 💡 The Problem it Solves:
Traditionally, branch office operators had to:
1. Manually scan physical ID cards using slow, conventional flatbed scanners.
2. Or, snap a photo on a personal phone, send it through WhatsApp, manually download it on WhatsApp Web, and then copy it to the local system (a slow process that raises data privacy and leakage concerns).

#### 🚀 The Solution & New Workflow:
With `smartocr_server.exe`, operators scan a dynamic QR Code on the PC screen to open the Web App (PWA) on their smartphone. As soon as the document photo is captured, it is instantly uploaded directly to the target folder on the PC/Server via local Wi-Fi. No WhatsApp transfers, no USB cables, and no manual copying needed!

#### Key PWA Server Features:
* **Zero Configuration**: Runs as a standalone portable utility without IIS, Apache, Nginx, or databases.
* **Custom Port & Path**: Easily configure the HTTP listening port and the target image storage folder from the UI.
* **Windows Boot Autorun**: Run the server automatically on Windows startup by checking the built-in option.
* **QR Code & IP Autodetect**: Automatically displays connection QR Code on startup. Scan it on your mobile device to open the capture app immediately.
* **PWA Compatibility**: Can be installed to the home screen of iOS and Android devices, functioning as a native-like mobile camera capture application.

---

### 📷 Screenshots & Demo Assets

#### Gambar Contoh Uji Coba / Demo Test Images:
*(Catatan: Gambar contoh Paspor dan SIM yang digunakan untuk pengujian ini bersumber dari mesin pencari publik seperti Google Images. Karena dokumen-dokumen tersebut dapat diakses secara publik di internet, dokumen tersebut tidak memerlukan sensor privasi khusus).*
*(Note: The sample passport and driver's license images utilized for testing are sourced from public search engines like Google Images. Since these documents are publicly accessible on the internet, they do not require special privacy redaction).*

- **KTP Sample**:
  ![KTP Sample](demo-pb/demo-ktp.jpg)

- **Passport Sample**:
  ![Passport Sample](demo-pb/demo-pass.jpg)

- **SIM Sample**:
  ![SIM Sample](demo-pb/demo-sim.jpg)

---

#### Tampilan Server & Antarmuka Seluler / Server & Mobile UI:
- **Desktop Server Interface**:
  ![Desktop Server](demo-pb/svr1.jpeg)

- **Mobile PWA Interface**:
  ![Mobile PWA](demo-pb/svr2.jpeg)
