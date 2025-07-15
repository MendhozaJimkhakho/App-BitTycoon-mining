
# 🪙 BitTycoon Miner Automation (Proxy Ready)

Otomatisasi proses mining BitTycoon menggunakan banyak akun, proxy, dan referal otomatis.

> ⚠️ Gunakan dengan bijak! Tool ini dibuat untuk edukasi dan automasi. 
---

## ✨ Fitur

- ✅ Multi akun mining otomatis
- 🌐 Proxy support (HTTP/SOCKS) → gunakan `proxies.txt`
- 🔁 Auto loop mining (opsional)
- 💡 Dukungan referal otomatis dari `code-reff.txt`
- 📜 Log dan retry otomatis

---

## 🧾 Link Garapan : https://play.google.com/store/apps/details?id=com.gomining.tycoonlite&hl=id

## 📂 Struktur Project

```
📁 BitTycoon-Proxy/
├── pc.py                ← Script utama automasi mining
├── termux.py                ← Script utama automasi mining
├── proxies.txt            ← Daftar proxy (opsional)
├── code-reff.txt          ← Kode referal (opsional)
├── requirements.txt       ← Daftar dependencies Python
```

---

## 🔧 Instalasi

### Di PC / VPS:
```bash
git clone https://github.com/MendhozaJimkhakho/App-BitTycoon-mining.git
cd App-BitTycoon-mining/BitTycoon
```

### Di Termux (Android):
```bash
pkg update && pkg install python git -y
git clone https://github.com/MendhozaJimkhakho/App-BitTycoon-mining.git
cd App-BitTycoon-mining/BitTycoon
pip install -r requirements.txt
```

---

### `proxies.txt` (opsional)
Format:
```
http://user:password@ip:port
socks5://user:password@ip:port
```

Contoh dari file kamu:
```text
http://user:password@ip:port
```

### `code-reff.txt`
Isi kode referral kamu agar akun mining otomatis terdaftar dengan referral:
```text
code reff kamu
```

---

## ▶️ Cara Menjalankan

### Mode normal (tanpa proxy):
```bash
python pc.py --> untuk Khusus PC
python termux.py --> untuk Khusus TERMUX
```

## 📌 Tips

- Jangan gunakan akun utama untuk testing
- Gunakan proxy berbeda per akun untuk mencegah banned
- Jalankan di VPS atau Termux dengan `--loop` untuk auto mining 24/7

---

## 🙋 Kontak

Jika kamu punya pertanyaan atau ingin membeli akses lebih lanjut, hubungi:

📩 Telegram: [@agisalio](https://t.me/agisalio)
📣 Grup Diskusi: [t.me/airdrop888backup](https://t.me/airdrop888backup)

---
