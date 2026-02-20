1. Konfigurasi (JS vs CSS)

V3 (tailwind.config.js): Kamu harus mengatur warna, font, dan tema di dalam file JavaScript. Ini mengharuskan Tailwind membaca file JS tersebut sebelum men-generate CSS-nya.
V4 (CSS-First & @theme): Sekarang konfigurasi dilakukan langsung di dalam file CSS utama menggunakan direktori @theme. Jadi, variabel CSS kamu adalah konfigurasinya. Kamu tidak perlu lagi bolak-balik antara file .js dan .css.

2. Performa dan Kecepatan

V3 (Lebih Berat): Menggunakan banyak dependencies (seperti PostCSS) yang membuat proses build membutuhkan waktu lebih lama, terutama pada proyek besar.
V4 (Lebih Cepat & Ringan): Versi 4 dibangun menggunakan engine baru bernama Oxide. Engine ini ditulis ulang menggunakan bahasa pemrograman Rust yang sangat cepat. Hasilnya? Proses kompilasi bisa berkali-kali lipat lebih cepat dan ukuran paketnya lebih kecil."# ppwl_3_2026" 
