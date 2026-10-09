RODAKAS — APLIKASI KEUANGAN DRIVER SHOPEEFOOD

CARA DEPLOY AGAR BISA DI-INSTALL
1. Ekstrak ZIP ini ke sebuah folder.
2. Unggah SEMUA isi folder (index.html, manifest.json, sw.js, folder icons) ke satu project GitHub/Vercel. Jangan hanya unggah index.html.
3. Deploy sebagai situs statis. Tidak memerlukan build command; output/root directory adalah folder tempat index.html berada.
4. Buka URL HTTPS hasil deploy dari HP atau laptop.
5. Android/Chrome: tekan tombol “Install aplikasi” jika tersedia, atau menu browser > Install app / Tambahkan ke layar utama.
6. iPhone/iPad: buka URL di Safari > Bagikan > Add to Home Screen.
7. Laptop Chrome/Edge: tekan ikon install di address bar atau menu browser > Install RodaKas.

CATATAN PENTING
- PWA harus dibuka dari HTTPS (misalnya Vercel) atau localhost. Membuka index.html langsung sebagai file tidak mengaktifkan instalasi/offline service worker.
- Setelah pertama kali dibuka online, aplikasi dapat membuka app shell secara offline. Untuk pembaruan, buka kembali saat online.
- Data transaksi disimpan di penyimpanan lokal browser/perangkat. Tidak otomatis sinkron antar HP dan laptop; gunakan menu Cadangkan JSON dan Pulihkan JSON untuk memindahkan data.
- Jangan hapus data browser tanpa membuat cadangan JSON.
- Aplikasi ini bukan aplikasi resmi ShopeeFood dan tidak mengambil data otomatis dari akun driver.
