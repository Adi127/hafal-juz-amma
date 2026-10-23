# Hafal Juz Amma

Aplikasi web (PWA) untuk menghafal Juz 30: putar murottal per ayat dengan pengulangan, rekam dan bandingkan bacaan, tandai ayat yang sudah hafal, dan ikuti jadwal muraja'ah.

- Pola pengulangan: per ayat, rentang, dan rantai
- Enam pilihan qari, audio diputar dari everyayah.com (butuh internet)
- Progres hafalan tersimpan di browser perangkat masing-masing, dengan kode cadangan untuk pindah perangkat
- Halaman, teks, dan font tetap terbuka tanpa internet setelah dipasang

## Mengubah isi

Setiap kali `index.html` diganti, naikkan angka versi `CACHE` di `sw.js` (v1 jadi v2). Kalau tidak, perangkat yang sudah memasang aplikasi bisa terus menampilkan versi lama.

## Sumber data

Teks Arab, transliterasi, dan terjemahan Indonesia dari paket npm `quran-json`. Audio dari everyayah.com. Ketentuan penggunaan audio perlu dicek sebelum dibagikan secara luas.
