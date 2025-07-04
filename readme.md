# 🤖 Asuma Multi Device - WhatsApp Bot Base

Bot WhatsApp Multi Device berbasis **type case**, mendukung:
- ✅ WhatsApp Biasa
- ✅ WhatsApp Bisnis

Dibuat menggunakan [@whiskeysockets/baileys](https://github.com/whiskeysockets/Baileys), cocok untuk pemula maupun developer berpengalaman. Stabil, ringan, dan mudah dikembangkan.

---

## 🚀 Fitur Utama
- 🟢 Multi-device support (WA & WA Business)
- ⚙️ Struktur type-case (tanpa command system ribet)
- 📂 Modular & mudah dikembangkan
- 💾 Auto save session (tanpa scan ulang)
- 🖼️ Auto detect media (image, video, audio, sticker)
- 🔘 Support Button, List, Template Message
- 📥 Banyak fitur: downloader, AI, tools, game, edukasi, dan lainnya

---

## 📦 Cara Install

### 1. Clone Repo
```bash
git clone https://github.com/ditss-dev/base.git
cd base
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Jalankan Bot
```bash
node index.js
```

> Akan muncul QR Code, scan menggunakan WA Biasa atau WA Bisnis

---

## 🗂️ Struktur Folder

```bash
├── message/
│   ├── case/            # Semua command ditulis dalam bentuk switch case
├── session/             # File sesi login WhatsApp
├── lib/                 # Fungsi bantu (helper)
├── config.js            # Konfigurasi bot
├── index.js             # File utama
└── package.json
```

---

## 🧩 Contoh Command

```js
case 'menu': {
  m.reply('Halo! Ini adalah menu utama bot.')
}
break
```

Tambahkan command baru di file case seperti contoh di atas.

---

## 🔧 Konfigurasi

Edit file `config.js` untuk:
- Nama bot & owner
- Prefix command
- Mode publik/self
- API Key eksternal

---

## 🧑‍💻 Developer
- Nama: Aditia Nugraha Putra
- Website: [https://www.ditss.cloud](https://www.ditss.cloud)
- WhatsApp: [wa.me](https://wa.me/6281513607731)
- GitHub: [github.com/ditss-dev](https://github.com/ditss-dev)

---

## ☕ Dukungan

Bot ini **gratis dan open-source**.  
Gunakan dengan bijak. Tidak dipungut biaya!

Donasi:  
📌 QRIS atau [Sociabuzz](https://sociabuzz.com/ditss)

---

## 📄 Lisensi

MIT License © 2025 Ditss
