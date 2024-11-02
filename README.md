# CTF Steganografi

![](https://github.com/fixploit03/CTF_STEGANOGRAFI/blob/main/maung.jpg)

> Repo ini untuk belajar steganografi.

## Instruksi

1. **Kloning repo CTF_STEGANOGRAFI**:
   ```
   git clone https://github.com/fixploit03/CTF_STEGANOGRAFI/
   ```

2. **Pindah ke folder CTF_STEGANOGRAFI**:
   ```
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

5. **Jalankan CrackStego**:
    Eksekusi CrackStego dan ikuti instruksi yang muncul.

6. **Upload Flag**:
    Jika flag ditemukan, silakan fork repo ini dan unggah file flag yang berhasil ditemukan ke dalam folder flag dengan format `flag_[username_github].txt`.

**Selamat Mencoba**
