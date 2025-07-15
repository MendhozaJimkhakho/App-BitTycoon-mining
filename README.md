# App-BitTycoon-mining Auto Reff


# Bot Otomatis Bit-Tycoon

Skrip ini adalah bot sederhana untuk melakukan otomatisasi tugas-tugas pada platform Bit-Tycoon, seperti pendaftaran, memasukkan kode referral, dan menyelesaikan tugas harian.

**Disclaimer:** Harap gunakan skrip ini dengan bijak. Segala risiko yang timbul dari penggunaan skrip ini menjadi tanggung jawab pengguna sepenuhnya.

---

## ## Fitur
-   Otomatisasi pendaftaran akun baru.
-   Input kode referral secara otomatis dari file `code-reff.txt`.
-   Menyelesaikan tugas harian (Daily Contract & Ads).
-   Dapat berjalan tanpa henti untuk membuat banyak akun.

---

## ## Cara Instalasi dan Menjalankan

Ikuti panduan di bawah ini sesuai dengan sistem operasi yang Anda gunakan.

### ### 🖥️ Untuk Pengguna Windows

**1. Persiapan Awal**

Anda harus menginstal Python dan Git terlebih dahulu jika belum ada di PC Anda.

-   **Install Python:** Unduh dari [python.org](https://www.python.org/downloads/). **Penting:** Saat instalasi, pastikan Anda mencentang kotak "Add Python to PATH".
-   **Install Git:** Unduh dari [git-scm.com](https://git-scm.com/download/win).

**2. Instalasi Skrip**

Buka **Command Prompt** atau **PowerShell** dan jalankan perintah berikut satu per satu.

```bash
# Pindah ke direktori yang Anda inginkan (misal: Desktop)
cd Desktop

# Clone repositori dari GitHub (ganti dengan URL repo Anda)
git clone https://github.com/MendhozaJimkhakho/App-BitTycoon-mining

# Masuk ke direktori hasil clone
cd App-BitTycoon-mining

# Install semua pustaka yang dibutuhkan
pip install -r requirements.txt

### 📱 Untuk Pengguna Termux

pkg update && pkg upgrade -y

# Install git dan python jika belum ada
pkg install git python -y

# Clone repositori dari GitHub (ganti dengan URL repo Anda)
git clone https://github.com/MendhozaJimkhakho/App-BitTycoon-mining

# Masuk ke direktori hasil clone
cd App-BitTycoon-mining

# Install dependensi yang diperlukan untuk kompilasi 'cryptography'
pkg install clang python-dev libffi-dev openssl-dev -y

# Install semua pustaka Python yang dibutuhkan dari requirements.txt
pip install -r requirements.txt
