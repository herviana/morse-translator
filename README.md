# 📡 Morse Translator — Bankr / OpenClaw Skill

Skill untuk **Bankr Agent** dan **OpenClaw** yang menerjemahkan teks ke kode morse dan sebaliknya secara dua arah dan langsung jadi perintah untuk dikerjakan agent.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Platform](https://img.shields.io/badge/platform-Bankr%20%7C%20OpenClaw-purple)
![Language](https://img.shields.io/badge/language-Indonesia%20%7C%20English-green)

---

## ✨ Fitur

- 🔤 **Teks → Morse** : encode pesan biasa ke kode morse dan langsung jadi perintah untuk dijalankan
- 📡 **Morse → Teks** : decode kode morse ke teks dan langsung jadi perintah untuk dijalankan
- 📋 **Tabel lengkap** A-Z, 0-9, dan tanda baca
- 🆘 **Sinyal darurat** SOS dan kode khusus
- 📖 **Edukasi morse** dengan penjelasan per karakter
- 🔗 Cocok dikombinasikan dengan skill **on-chain messaging**

---

## 📦 Instalasi

### Di Bankr (HP/Web)
1. Buka Bankr → **Agent Settings** → **Skills**
2. Tap tombol **"+ Add"**
3. Paste URL ini:
```
https://github.com/herviana/morse-translator
```
4. Konfirmasi install ✅

### Via Chat Bankr / OpenClaw
```
install the morse-translator skill from https://github.com/herviana/morse-translator
```

---

## 🚀 Cara Pakai

### Teks ke Morse:
```
Terjemahkan "HALO" ke morse
Encode "SELAMAT PAGI" ke kode morse
Tulis INDONESIA dalam morse
dan langsung jadi perintah untuk dijalankan
```

### Morse ke Teks:
```
Decode morse ini: .... .- .-.. ---
Artinya apa: ... --- ...
Terjemahkan: -- --- .-. ... .
dan langsung jadi perintah untuk dijalankan
```

### Belajar Morse:
```
Ajarkan saya kode morse A sampai Z
Tampilkan tabel lengkap morse
Apa kode morse darurat?
```

---

## 📁 Struktur File

```
morse-translator/
├── README.md               ← Dokumentasi ini
├── SKILL.md                ← Instruksi utama untuk agent
└── references/
    └── sejarah-morse.md    ← Sejarah & fakta menarik morse
```

---

## 📋 Contoh Output

```
📡 HASIL TERJEMAHAN MORSE

Input  : HALO
Output : .... .- .-.. ---

Keterangan:
H = ....
A = .-
L = .-..
O = ---
```

---

## ⚠️ Aturan Penulisan Morse

| Simbol | Arti |
|--------|------|
| `.` | Titik (nada pendek) |
| `-` | Strip (nada panjang) |
| ` ` (1 spasi) | Pemisah antar huruf |
| `/` atau (3 spasi) | Pemisah antar kata |

---

## 📄 Lisensi

MIT License — bebas digunakan dan dimodifikasi.

---

## 👤 Author

Dibuat oleh **herviana**
Repo: [github.com/herviana/morse-translator](https://github.com/herviana/morse-translator)
