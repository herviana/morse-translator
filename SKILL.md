---
name: morse-translator
description: >
  Terjemahkan teks ke kode morse atau kode morse ke teks biasa.
  Gunakan skill ini ketika user ingin encode pesan ke morse,
  decode kode morse ke teks, belajar morse, atau memainkan
  bunyi morse. Trigger pada kata kunci seperti "morse", "kode morse",
  "terjemahkan ke morse", "decode morse", ".. ..", "---", "titik strip".
metadata:
  version: "1.0.0"
  author: "herviana"
  emoji: "📡"
---

# Morse Translator 📡

Skill untuk menerjemahkan **teks ke kode morse** atau **kode morse ke teks** secara dua arah.

---

## Cara Pakai

### Teks → Morse
```
"Terjemahkan 'HALO' ke morse"
"Encode pesan 'SELAMAT PAGI' ke kode morse"
"Tulis INDONESIA dalam morse"
```

### Morse → Teks
```
"Decode morse ini: .... .- .-.. ---"
"Artinya apa: ... --- ..."
"Terjemahkan kode morse: -- --- .-. ... ."
```

### Lainnya:
```
"Ajarkan saya kode morse huruf A sampai Z"
"Apa kode morse darurat?"
"Tampilkan tabel lengkap kode morse"
```

---

## Tabel Kode Morse Lengkap

### Huruf
| Huruf | Morse   | Huruf | Morse   |
|-------|---------|-------|---------|
| A     | .-      | N     | -.      |
| B     | -...    | O     | ---     |
| C     | -.-.    | P     | .--.    |
| D     | -..     | Q     | --.-    |
| E     | .       | R     | .-.     |
| F     | ..-.    | S     | ...     |
| G     | --.     | T     | -       |
| H     | ....    | U     | ..-     |
| I     | ..      | V     | ...-    |
| J     | .---    | W     | .--     |
| K     | -.-     | X     | -..-    |
| L     | .-..    | Y     | -.--    |
| M     | --      | Z     | --..    |

### Angka
| Angka | Morse   | Angka | Morse   |
|-------|---------|-------|---------|
| 0     | -----   | 5     | .....   |
| 1     | .----   | 6     | -....   |
| 2     | ..---   | 7     | --...   |
| 3     | ...--   | 8     | ---..   |
| 4     | ....-   | 9     | ----.   |

### Tanda Baca & Simbol Penting
| Simbol | Morse        |
|--------|--------------|
| .      | .-.-.-       |
| ,      | --..--       |
| ?      | ..--..       |
| !      | -.-.--       |
| /      | -..-.        |
| @      | .--.-.       |
| SOS    | ...---...    |

---

## Format Output

Saat menerjemahkan, gunakan format ini:

### Teks ke Morse:
```
📡 HASIL TERJEMAHAN MORSE

Input  : HALO
Output : .... .- .-.. ---

Keterangan:
H = ....
A = .-
L = .-..
O = ---

(spasi antar huruf = 1 spasi)
(spasi antar kata = / )
```

### Morse ke Teks:
```
📡 HASIL DECODE MORSE

Input  : .... .- .-.. ---
Output : HALO

Keterangan:
.... = H
.-   = A
.-.. = L
---  = O
```

---

## Aturan Penulisan Morse

- **Titik** = `.` (nada pendek)
- **Strip** = `-` (nada panjang)
- **Spasi 1x** = pemisah antar huruf
- **Spasi 3x** atau `/` = pemisah antar kata
- **SOS** = `... --- ...` (sinyal darurat universal)

---

## Referensi Tambahan

Lihat `references/sejarah-morse.md` untuk sejarah dan fakta menarik kode morse.
