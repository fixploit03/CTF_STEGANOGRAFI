# CTF Steganografi

![](https://github.com/fixploit03/CTF_STEGANOGRAFI/blob/main/maung.jpg)

> Repositori ini bertujuan untuk belajar steganografi.

## Instruksi untuk menyelesaikan CTF

1. **Kloning repositori CTF_STEGANOGRAFI**:
   ```bash
   git clone https://github.com/fixploit03/CTF_STEGANOGRAFI/
   ```

2. **Masuk ke folder CTF_STEGANOGRAFI**:
   ```bash
   cd CTF_STEGANOGRAFI
   ```

3. **Instal alat yang diperlukan**:  
   Pastikan Anda telah menginstal alat berikut di sistem Anda:
   - **Steghide**:  
     ```bash
     sudo apt-get install steghide
     ```
   - **Crunch**:  
     ```bash
     sudo apt-get install crunch
     ```
   - **CrackStego**:  
     Instal dari [tautan ini](https://github.com/fixploit03/CrackStego).

4. **Buat wordlist**:  
   Gunakan Crunch untuk membuat wordlist:  
   ```bash
   crunch 4 4 0123456789 > wordlist.txt
   ```

5. **Temukan Flag**:  
   Jalankan CrackStego dan ikuti instruksi yang muncul untuk menemukan Flag yang tersembunyi dalam file gambar [maung.jpg](https://github.com/fixploit03/CTF_STEGANOGRAFI/blob/main/maung.jpg).

6. **Unggah Flag**:  
   Jika flag ditemukan, silakan [fork](https://github.com/fixploit03/CTF_STEGANOGRAFI/forks) repositori ini dan unggah file flag yang berhasil ditemukan ke dalam folder `flag` dengan format `flag_[username_github].txt`, lalu buat pull request.

**Selamat mencoba!**
