# CTF Steganografi

![](https://github.com/fixploit03/CTF_STEGANOGRAFI/blob/main/maung.jpg)

> Repositori ini ditujukan untuk belajar steganografi.

## Instruksi untuk menyelesaikan CTF

1. **Kloning repositori CTF_STEGANOGRAFI**:
   ```bash
   git clone https://github.com/fixploit03/CTF_STEGANOGRAFI/
   ```

2. **Pindah ke folder CTF_STEGANOGRAFI**:
   ```bash
   cd CTF_STEGANOGRAFI
   ```

3. **Instal alat yang diperlukan**:  
   Pastikan Anda memiliki alat berikut di sistem Anda:
   - **Steghide**:  
     ```bash
     sudo apt-get install steghide
     ```
   - **Crunch**:  
     ```bash
     sudo apt-get install crunch
     ```
   - **CrackStego**:  
     Instal dari [sini](https://github.com/fixploit03/CrackStego).

4. **Buat wordlist**:  
   Gunakan Crunch untuk membuat wordlist:  
   ```bash
   crunch 4 4 0123456789 > wordlist.txt
   ```

5. **Temukan Flag**:  
   Eksekusi CrackStego dan ikuti instruksi yang muncul untuk menemukan flag yang tersembunyi dalam file gambar [maung.jpg](https://github.com/fixploit03/CTF_STEGANOGRAFI/blob/main/maung.jpg).

6. **Unggah Flag**:  
   Jika flag ditemukan, silakan fork repositori ini dan unggah file flag yang berhasil ditemukan ke dalam folder `flag` dengan format `flag_[username_github].txt`.

**Selamat Mencoba!**
