
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

## 📂 Struktur Project

```
📁 BitTycoon-Proxy/
├── main.py                ← Script utama automasi mining
├── token.txt              ← Token akun BitTycoon (1 per baris)
├── proxies.txt            ← Daftar proxy (opsional)
├── code-reff.txt          ← Kode referal (opsional)
├── requirements.txt       ← Daftar dependencies Python
```

---

## 🔧 Instalasi

### Di PC / VPS:
```bash
git clone https://github.com/MendhozaJimkhakho/App-BitTycoon-mining.git
cd App-BitTycoon-mining/BitTycoon-Proxy
pip install -r requirements.txt
```

### Di Termux (Android):
```bash
pkg update && pkg install python git -y
git clone https://github.com/MendhozaJimkhakho/App-BitTycoon-mining.git
cd App-BitTycoon-mining/BitTycoon-Proxy
pip install -r requirements.txt
```

---

## 🧾 Format File

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

### `code-reff.txt` (opsional)
Isi kode referral kamu agar akun mining otomatis terdaftar dengan referral:
```text
code reff kamu
```

---

## ▶️ Cara Menjalankan

### Mode normal (tanpa proxy):
```bash
python main.py
```

### Mode dengan proxy:
```bash
python main.py --use-proxy
```

### Jalankan loop terus-menerus:
```bash
python main.py --loop
```

### Kombinasi semua:
```bash
python main.py --use-proxy --loop
```

---

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
