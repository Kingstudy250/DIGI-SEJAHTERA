# DIGI-SEJAHTERA — Source Code Prototipe Front-End

Paket ini berisi source code prototipe front-end DIGI-SEJAHTERA yang dikirimkan untuk penyusunan lampiran esai.

## Isi paket

- `index.html` — dokumen utama yang memuat struktur HTML, CSS tertanam, konfigurasi Tailwind CSS, serta JavaScript untuk interaksi prototipe.
- `assets/digi-sejahtera-logo.png` — aset logo yang dipotong dari tangkapan layar dashboard yang disediakan.
- `assets/ibu-sari-wulandari.png` — aset avatar ilustratif yang dipotong dari tangkapan layar dashboard yang disediakan.
- `assets/ASSETS_NOTE.txt` — keterangan mengenai aset gambar.

## Cara menjalankan

1. Ekstrak ZIP ini ke sebuah folder.
2. Buka folder tersebut di komputer.
3. Jalankan server lokal dari folder proyek, misalnya dengan Python:

   ```bash
   python3 -m http.server 8000
   ```

4. Buka `http://localhost:8000` melalui browser.

Prototipe menggunakan pustaka eksternal melalui CDN (Tailwind CSS, Google Fonts, dan Chart.js), sehingga koneksi internet diperlukan agar seluruh gaya, tipografi, dan grafik dapat dimuat dengan benar.

## Cakupan dan batasan prototipe

Prototipe ini memperlihatkan antarmuka dan interaksi front-end, antara lain navigasi ant halaman, modal, notifikasi, simulasi unggah portofolio, penandaan penyelesaian modul, pencarian riwayat transaksi, pembaruan preferensi profil pada tampilan, interaksi diagram Hexahelix, serta grafik perkembangan.

Sebagian data bersifat ilustratif. Simulasi unggah dokumen hanya menambahkan nama berkas ke tampilan browser dan tidak mengirim berkas ke server. Perubahan pengaturan juga hanya diperlihatkan pada tampilan saat itu. Paket ini tidak mencakup backend, database, autentikasi, pemrosesan pembayaran, integrasi blockchain atau smart contract, maupun model machine learning yang berjalan secara aktual.

## Catatan aset dan berkas proyek

File HTML yang diberikan merujuk pada dua gambar di folder `assets`. Karena berkas gambar asli dari proyek Figma tidak disertakan sebagai file terpisah, gambar yang tersedia di paket ini merupakan potongan dari tangkapan layar dashboard. Untuk hasil paling tajam, ganti keduanya dengan aset asli dari proyek Figma menggunakan nama file yang sama.

Tangkapan layar Figma juga memperlihatkan `package.json` dan `vite.config.ts`, tetapi isi kedua berkas tersebut tidak disertakan dalam file source code yang dibagikan. Oleh karena itu, berkas tersebut tidak dibuat ulang atau ditebak dalam paket ini. File HTML dapat dijalankan sebagai prototipe mandiri dengan server lokal seperti petunjuk di atas.
