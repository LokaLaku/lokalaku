# Kebijakan Keamanan (Security Policy)

Kami menjaga keamanan proyek LokaLaku Trip dengan serius. Kami menghargai bantuan dari komunitas dan peneliti keamanan untuk melaporkan kerentanan secara bertanggung jawab. Semua laporan akan kami tinjau dan tanggapi sesegera mungkin.

## Versi yang Didukung

Karena ini adalah website statis yang terus diperbarui, kami hanya memberikan dukungan keamanan untuk versi terbaru yang ada di cabang `main`.

| Versi   | Didukung          |
| ------- | ----------------- |
| `main`  | :white_check_mark: |

## 🛡️ Melaporkan Kerentanan

**Tolong jangan melaporkan kerentanan keamanan melalui Isu (Issues) publik di GitHub.**

Jika Anda menemukan masalah keamanan, silakan laporkan secara pribadi melalui email ke:

**`kontak.lokalaku@email.com`**

_[Harap ganti alamat email di atas dengan alamat email pribadi yang ingin Anda gunakan untuk menerima laporan keamanan]_

Harap sertakan informasi sebanyak mungkin dalam laporan Anda agar kami dapat mereproduksi dan memvalidasi masalah tersebut.

### Informasi yang Disertakan

* Deskripsi detail tentang kerentanan yang ditemukan.
* Langkah-langkah yang jelas untuk mereproduksi kerentanan tersebut.
* Dampak potensial dari kerentanan tersebut.
* Saran perbaikan atau mitigasi (jika Anda memilikinya).

## Komitmen Kami

Setelah menerima laporan kerentanan, kami akan berusaha untuk:

1.  Mengakui penerimaan laporan Anda sesegera mungkin (biasanya dalam 48 jam).
2.  Mengkonfirmasi keberadaan kerentanan dan memberikan perkiraan waktu untuk perbaikan.
3.  Memberi tahu Anda ketika perbaikan telah dirilis.
4.  Memberikan kredit atau ucapan terima kasih kepada pelapor di catatan rilis (jika Anda setuju).

## Ruang Lingkup

Kebijakan ini berlaku untuk kode yang ada di dalam repositori ini.

### Termasuk dalam Ruang Lingkup:

* Kerentanan *Cross-Site Scripting* (XSS).
* Penggunaan pustaka/library pihak ketiga (misalnya, jQuery, Bootstrap) yang memiliki kerentanan yang diketahui.
* Masalah *"Mixed Content"* (memuat aset HTTP di halaman HTTPS).

### Tidak Termasuk dalam Ruang Lingkup:

* Kerentanan pada layanan pihak ketiga yang kami gunakan (misalnya, Formspree, Vercel, Google Fonts). Masalah ini harus dilaporkan langsung ke penyedia layanan tersebut.
* Laporan Spam atau Phishing yang tidak terkait langsung dengan kode di repositori ini.
* Saran praktik terbaik (misalnya, konfigurasi header HTTP) yang tidak menunjukkan adanya kerentanan aktif.

Terima kasih telah membantu menjaga keamanan LokaLaku Trip.
