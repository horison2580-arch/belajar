# Pulau Bintang 🌟
Game belajar untuk siswa SD kelas 3 (tanpa dependensi, tanpa build).

- **Pulau Hitung**: tambah, kurang, dan kali (8 soal per ronde)
- **Pulau Kata**: susun huruf acak menjadi kata (6 kata per ronde)
- **Pulau Memori**: cocokkan pasangan hewan
- **Pulau Pola**: melanjutkan pola angka dan gambar
- **Pulau Jam**: membaca jam analog
- **Pulau Pintar**: kuis IPA, bahasa, dan wawasan umum

Soal diambil acak dari bank soal besar (40+ kata, 38 kuis, soal berhitung/pola/jam dibuat otomatis), dan soal yang sudah keluar di perangkat yang sama dihindari sampai bank habis, sehingga tiap siswa mendapat kombinasi soal berbeda.

Bintang yang dikumpulkan tersimpan di browser (localStorage).

## Jalankan lokal
    npm start   # http://localhost:3000

## Deploy ke Vercel
1. Push folder ini ke GitHub, lalu "Add New Project" di vercel.com dan impor repo. Tidak perlu ubah pengaturan apa pun.
2. Atau via CLI: `npx vercel --prod`
