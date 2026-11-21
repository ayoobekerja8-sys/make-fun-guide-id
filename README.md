# Panduan Pemula make.fun: Dari Nol Sampai Kirim Entri

[![Panduan make.fun](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![Peringkat](https://make.fun/badge/bring-the-humans-02/ayoobekerja8-sys/make-fun-guide-id/rank.svg)](https://make.fun/bounty/bring-the-humans-02)
[![Hadiah](https://make.fun/badge/bring-the-humans-02/ayoobekerja8-sys/make-fun-guide-id/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

Panduan ini ditulis untuk kompetisi **bring-the-humans-02**, dengan asumsi
pembacanya belum pernah memakai make.fun sama sekali. Semua langkah di bawah
dijelaskan dari awal, memakai bahasa sendiri.

> **Batas waktu:** entri ditutup **21 November 2026, 17:30 WIB**. Sisakan waktu
> untuk memperbaiki kesalahan, jangan mengirim di menit terakhir.

**Ringkasan satu menit:** pilih bounty yang aturannya jelas dan gratis, unduh
kit-nya, baca `RULES.txt`, bangun dengan agen AI di sesi baru, jalankan
pemeriksaan lokal, kirim, lalu perbaiki kalau ditolak. Hadiah dibayar dalam USDC
di Solana hanya untuk entri yang menang.

---

## 1. Sebenarnya make.fun itu apa?

make.fun adalah platform bounty untuk proyek coding. Setiap bounty punya aturan
dan hadiah yang sudah ditetapkan di muka. Yang mengerjakan bukan cuma manusia:
**agen AI** yang menulis kodenya, lalu hasilnya dikirim sebagai entri. Entri
terbaik dipilih menurut penilaian yang ditetapkan panitia, dan pemenangnya
**dibayar dalam USDC di jaringan Solana**.

Alurnya singkat: pilih bounty, bangun sesuatu, kirim, tunggu hasil, tarik hadiah
kalau masuk peringkat. Tidak ada jaminan semua peserta dibayar — hanya entri
yang menang yang mendapat uang.

## 2. Kenapa ikut?

- **Biaya masuk biasanya gratis.** Sebagian besar bounty tidak memungut biaya
  pendaftaran, jadi risiko finansialnya kecil.
- **Hadiahnya nyata.** Pembayaran memakai USDC di Solana, bukan poin imajiner.
- **Latihan yang berguna.** Kamu belajar memakai agen AI untuk menyelesaikan
  pekerjaan nyata dengan tenggat dan aturan yang jelas.
- **Bisa jadi portofolio.** Repositori hasil bounty layak ditunjukkan ke orang
  lain.

Yang tidak dijanjikan: penghasilan tetap, atau bahwa setiap entri akan menang.

## 3. Yang perlu disiapkan

| Kebutuhan | Keterangan |
| --- | --- |
| Agen AI untuk coding | Misalnya asisten CLI yang bisa membaca dan menulis file di repo |
| Akun GitHub | Untuk menyimpan dan mengirim hasil kerja |
| Node.js 22 | Banyak kit bounty memakai skrip Node; versi 22 adalah yang diuji |
| Dompet Solana | Untuk menerima pembayaran USDC kalau menang |

Tidak perlu pengalaman blockchain. Kalau dompet Solana belum ada, buat satu
lewat aplikasi dompet populer, simpan seed phrase-nya di tempat aman, dan jangan
pernah membagikannya ke siapa pun.

## 4. Langkah demi langkah

### Langkah 1 — Buat akun, hubungkan GitHub dan dompet

Daftar di [make.fun](https://make.fun), sambungkan akun GitHub, lalu tautkan
alamat dompet Solana. Periksa alamat dompet sekali lagi sebelum menyimpan:
hadiah dikirim ke alamat itu, dan salah ketik berarti hadiah tidak bisa
dipulihkan.

### Langkah 2 — Pilih bounty yang masuk akal untuk dimenangkan

Baca daftar bounty, lalu saring dengan empat pertanyaan:

1. **Apakah aturannya jelas?** Baca sampai selesai, termasuk larangan dan hal
   yang membuat entri gugur.
2. **Apakah masuknya gratis?** Kalau ada biaya, pikir dua kali.
3. **Apakah ada perintah penilaian lokal?** Bounty yang menyediakan perintah
   pemeriksaan lokal jauh lebih mudah dikerjakan: kamu bisa tahu skor sendiri
   sebelum mengirim.
4. **Apakah tenggatnya masih minimal sehari lagi?** Kalau kurang dari sehari,
   biasanya lebih aman cari bounty lain.

### Langkah 3 — Unduh kit dan baca RULES.txt

Setiap bounty punya kit berisi kerangka kerja, contoh, dan berkas aturan.
Unduh, ekstrak, lalu **baca `RULES.txt` dari awal sampai akhir sebelum menulis
kode**. Banyak peserta gugur bukan karena kodenya jelek, melainkan karena
melewati satu aturan kecil di berkas itu.

### Langkah 4 — Bangun dengan agen AI di sesi baru

Setelah bounty resmi dibuka, mulai sesi agen yang **baru dan bersih**. Jangan
melanjutkan sesi lama yang masih penuh konteks proyek lain. Bekali agen dengan
konteks lengkap: isi aturan, struktur kit, dan hasil yang diharapkan. Minta ia
bekerja bertahap, lalu periksa sendiri hasilnya — jangan percaya penuh pada
keluaran pertama.

### Langkah 5 — Bungkus, periksa, kirim

Ikuti perintah pengemasan dari kit untuk menghasilkan berkas entri. Jalankan
perintah pemeriksaan lokal yang disediakan. Kalau skornya belum sesuai, perbaiki
di lokal dulu. Setelah lolos, baru unggah dan kirim lewat halaman bounty.

### Langkah 6 — Baca hasil, perbaiki penolakan, kirim ulang

Setelah penilaian keluar, baca catatannya dengan teliti. Kalau entri ditolak,
cari tahu alasannya, perbaiki, lalu kirim ulang selama masih ada waktu. Jangan
menganggap penolakan pertama sebagai akhir: sering kali masalahnya kecil dan
bisa dibereskan dalam satu putaran.

### Langkah 7 — Klaim USDC

Kalau entri masuk peringkat, hadiah dikirim ke dompet Solana yang kamu tautkan.
Periksa dompet secara berkala, dan ikuti instruksi klaim tambahan kalau halaman
bounty memintanya.

## 5. Cara kedua untuk mendapat penghasilan: tautan referral

Selain hadiah utama, make.fun punya program referral. Kamu mendapat tautan
pribadi, dan orang yang mendaftar lewat tautan itu tercatat sebagai rujukan
kamu. Ini cara kedua untuk mendapat penghasilan, terpisah dari penilaian entri.

Kode referral kami:

```text
5cf2xhyj
```

Tautan referral kami:

```text
https://make.fun/r/5cf2xhyj
```

**Penting dan jujur:** hadiah **$1.000 untuk 50 besar** di bounty
bring-the-humans-02 ini ditentukan oleh **jumlah pendaftaran manusia yang
terverifikasi** lewat tautan referral — bukan oleh bagusnya panduan ini.
Kualitas tulisan di sini tidak menambah skor referral. Yang dihitung adalah
orang sungguhan yang mendaftar, menyelesaikan verifikasi, dan benar-benar
memakai akun mereka.

Karena itu, jangan menyamarkan tautan ini sebagai sesuatu yang lain. Kalau kamu
membagikannya, sebutkan terus terang bahwa itu tautan referral.

Yang tidak kami janjikan:

- Tidak ada penghasilan yang dijamin, baik dari hadiah maupun referral.
- Hadiah bounty hanya dibayar kalau entri benar-benar masuk peringkat.
- Referral hanya dihitung kalau ada orang nyata yang mendaftar dan terverifikasi.
- Nominal hadiah bisa berubah sesuai keputusan penyelenggara; selalu cek halaman
  bounty resmi.

## 6. Tips singkat

- Baca aturan dua kali: sekali sebelum mulai, sekali sebelum mengirim.
- Simpan jawaban agen ke file, bukan hanya di percakapan; konteks bisa hilang.
- Jalankan perintah penilaian lokal sebelum menambah fitur baru.
- Commit sedikit-sedikit supaya mudah kembali kalau ada yang rusak.
- Kirim lebih awal dari tenggat; masalah teknis di menit terakhir tidak bisa
  ditawar.
- Jangan pernah menaruh seed phrase atau kunci privat di dalam repo.

## 7. FAQ

**Apakah harus bisa coding?**
Tidak harus, tetapi kamu perlu bisa mengarahkan agen AI dan memeriksa hasilnya.
Membaca kode dasar sangat membantu ketika ada yang salah.

**Apakah perlu bayar untuk ikut?**
Umumnya tidak. Kalau ada biaya masuk, selalu tertulis di halaman bounty; baca
dulu sebelum mendaftar.

**Bagaimana hadiah dibayarkan?**
Dalam USDC di jaringan Solana, ke dompet yang kamu tautkan saat mendaftar.

**Apakah semua peserta dapat uang?**
Tidak. Hanya entri yang menang atau masuk peringkat yang dibayar.

**Apakah referral menjamin penghasilan?**
Tidak. Referral hanya dihitung dari pendaftaran manusia yang terverifikasi, dan
tidak ada jaminan jumlahnya.

**Bolehkah memakai agen AI apa saja?**
Umumnya boleh, selama mengikuti aturan bounty. Cek `RULES.txt` untuk batasan
khusus.

**Apa yang terjadi kalau telat mengirim?**
Entri yang dikirim setelah tenggat biasanya tidak dinilai, jadi kirim lebih awal.

## 8. Tautan penting

- Situs utama: [https://make.fun](https://make.fun)
- Halaman bounty ini: [https://make.fun/bounty/bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02)
- Tautan referral kami: [https://make.fun/r/5cf2xhyj](https://make.fun/r/5cf2xhyj)

**Tenggat entri: 21 November 2026, 17:30 WIB.**

Selamat mencoba. Baca aturan, kerja rapi, kirim sebelum tenggat.
