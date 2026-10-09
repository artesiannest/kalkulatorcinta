# Love.exe — Kalkulator Cinta Nostalgia
Dapur Kreatif. Game browser ringan, responsif, tanpa database atau proses build.

## Upload lewat browser
1. Ekstrak ZIP ini terlebih dahulu. Jangan unggah ZIP-nya sebagai website.
2. Buka https://github.com/new dan buat repository bernama kalkulator-cinta. Pilih Public, aktifkan Add a README, lalu Create repository.
3. Klik Add file > Upload files. Unggah index.html, README.md, dan .nojekyll dari hasil ekstrak langsung ke root repository (bukan di dalam folder tambahan). Jika .nojekyll tidak terlihat, index.html dan README.md sudah cukup untuk game ini.
4. Klik Commit changes untuk menyimpan di branch main.
5. Buka Settings > Pages. Di Build and deployment, pilih Source: Deploy from a branch.
6. Pilih branch main dan folder /(root), lalu Save.
7. Tunggu proses selesai. Alamat akan ditampilkan di Settings > Pages: https://USERNAME.github.io/kalkulator-cinta/

## Menjalankan lokal
Klik dua kali index.html untuk bermain. Fitur share/clipboard paling baik digunakan melalui HTTPS setelah diterbitkan.

## Isi
- index.html: seluruh tampilan, CSS, dan logika game.
- .nojekyll: menandai website statis.
- README.md: panduan ini.

Dua nama yang sama menghasilkan persentase yang sama, termasuk saat urutannya ditukar. Persentase memakai hash nama untuk hiburan; bukan analisis hubungan nyata. Riwayat lima pasangan disimpan di browser perangkat pengguna. Tidak ada nama yang dikirim ke server oleh game. Font Google menggunakan koneksi internet, dengan font cadangan jika offline.

Dokumentasi resmi: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
