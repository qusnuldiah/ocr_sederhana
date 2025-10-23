# ocr_sederhana

A new Flutter project.

## Tampilan Output
1. Layar Utama (HomeScreen): Pengguna melihat AppBar bertuliskan "Menu Utama" dan satu ListTile dengan ikon kamera bertuliskan "Mulai Pindai Teks Baru".
   <img width="536" height="1201" alt="image" src="https://github.com/user-attachments/assets/7bdcbb2b-4b33-4cf4-b5d0-93dfb7f1de4d" />

2. Pindai (ScanScreen): Aplikasi pindah ke ScanScreen. Pengguna akan melihat layar loading baru (abu-abu gelap dengan indikator kuning) selama 1-2 detik selagi kamera bersiap.
   <img width="539" height="1208" alt="image" src="https://github.com/user-attachments/assets/8d7bac1d-47c3-475a-b340-4a9e55d0ff58" />

3. Layar Hasil (ResultScreen):
   - Setelah pemindaian berhasil, aplikasi pindah ke ResultScreen.
     <img width="529" height="1186" alt="image" src="https://github.com/user-attachments/assets/363d59ca-2e30-4d0d-906b-719419fdf954" />

   - Teks hasil OCR akan ditampilkan lengkap dengan format baris baru (tidak dalam satu baris panjang).
   - Di pojok kanan bawah, pengguna akan melihat dua tombol FAB bertumpuk vertikal:
     - Tombol atas: Ikon Icons.volume_up (untuk TTS).
     - Tombol bawah: Ikon Icons.home (untuk kembali).
       <img width="451" height="1011" alt="image" src="https://github.com/user-attachments/assets/5b4e06a2-2359-46e4-8838-a59ce69b8abc" />

4. Aksi Pengguna:
   - Jika menekan Tombol Volume: Ponsel akan mulai membacakan teks yang ada di layar dalam Bahasa Indonesia.
   - Jika menekan Tombol Home: Aplikasi akan langsung kembali ke HomeScreen (Langkah 1). Jika pengguna menekan tombol "kembali" (back) fisik pada ponsel mereka dari HomeScreen, aplikasi akan langsung tertutup (bukan kembali ke ResultScreen), karena navigasinya sudah dibersihkan.






