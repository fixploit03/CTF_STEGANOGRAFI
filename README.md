# CTF Steganografi

> Repo ini untuk belajar steganografi.

## Instruksi

1. **Unduh gambar**:  
   Unduh gambar [maung.jpg]() dan simpan di direktori proyek Anda.

2. **Instal alat yang diperlukan**:  
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

3. **Buat wordlist**:  
   Gunakan Crunch untuk membuat wordlist:  
   ```bash
   crunch 4 4 0123456789 > wordlist.txt
   ```

4. **Jalankan CrackStego**:
    Eksekusi CrackStego dan ikuti instruksi yang muncul.

5. **Upload Flag**:
    Jika flag ditemukan, silakan fork repo ini dan unggah file flag yang berhasil ditemukan ke dalam folder flag dengan format `flag_[username_github].txt`.

**Selamat Mencoba**
