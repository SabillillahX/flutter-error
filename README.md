# flutter-error 
ketika flutter doctor tidak bisa digunakan karena git tidak mengidentifikasi folder diwhite list
1. ekstrak flutter ke C:/
2. **FIX GIT PERMISSION**  
   Masukkan folder C:/flutter ke whitelist git:
   ```bash
   git config --global --add safe.directory C:/flutter
   ```
3. tambahkan path flutter ke environment variabel
   ```bash
   C:/flutter/bin
   ```
   * setelah step 3 kalo mau coba langsung flutter doctor gapapa tapi nanti error
4. hapus folder flutter di direktory C:/
5. ekstrak kembali ke folder C:/
6. install dependencies flutter
   ```bash
   flutter doctor
   ```
