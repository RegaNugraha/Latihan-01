#LATIHAN-01

LANGKAH-LANGKAH MEMBUAT REPOSITORY LOCAL DAN REPOSITORY PADA GITHUB, DAN MEMBUAT FILE RAEDME.md

YANG DIBUTUHKAN ANTARA LAIN ADALAH  :
*AKUN GITHUB - SOFTWARE GIT
  1. BUAT AKUN GITHUB DI https://github.com ISI DATA DIRI LALU KLIK SIGN UP PADA POJOK KANAN ATAS.
  ![2019-10-25 (7)](https://user-images.githubusercontent.com/56884391/67550646-34096580-f731-11e9-9036-7b4fb54a5c44.png)
  2. APA BILA SUDAH MEMPUNYAI AKUN GITHUB KLIK SIGN IN PADA POJOK KANAN ATAS.
  ![2019-10-25 (9)](https://user-images.githubusercontent.com/56884391/67551186-8303ca80-f732-11e9-98dd-9af184f15f73.png)
  3. UNTUK MEMBUAT SEPOSITORY ANDA KLIK TANDA + DI POJOK KANAN ATAS. SETELAH ITU KLIK NEW REPOSITORY. PERHATIKAN GAMBAR BERIKUT:
  ![2019-10-25 (10)](https://user-images.githubusercontent.com/56884391/67551455-2c4ac080-f733-11e9-9f12-622a49505f42.png)
  ![2019-10-25 (11)](https://user-images.githubusercontent.com/56884391/67557089-96b52e00-f73e-11e9-8cfb-6aebc2830ea7.png)
  ![2019-10-25 (12)](https://user-images.githubusercontent.com/56884391/67557326-16db9380-f73f-11e9-8196-2613aeedf2f8.png)
  4. SETELAH ANDA MEMBUAT REOPOSITORY. ANDA DOWNLOAD SOFTWARE GIT DI "git-scm.com" LALU ANDA INSTAL TERLEBIH DAHULU.
  5. SETELAH ANDA MENGINSTAL GIT. BUKA DOCUMENT DAN BUAT FOLDER, BARU ANDA KLIK KANAN PADA FOLDER LALU PILIH "GIT BASH HERE"
  SEPERTI GAMBAR DI BAWAH INI:
  ![1](https://user-images.githubusercontent.com/56884391/67551899-18ec2500-f734-11e9-9042-b0b2663e7b4c.png)
  6. LALU KONFIGURASI DENGAN MEMASUKAN PERINTAH "git config --global user.name "name.user"" DAN "git config --global user.email "user.email""
  ![2](https://user-images.githubusercontent.com/56884391/67552235-d7a84500-f734-11e9-8cf2-1fb56c3ddff5.png)
  7. SETELAH ITU BUAT DIREKTORI BARU DENGAN MENGGUNAKAN PERINTAH "mkdir latihan-01" dan "cd latihan-01"
  ![3](https://user-images.githubusercontent.com/56884391/67552391-34a3fb00-f735-11e9-9603-3e5ca0031f79.png)
  8. LALU JALANKAN PERINTAH "git init" UNTUK MEMBUAT FILE KOSONG BERFORMAT git.
  ![4](https://user-images.githubusercontent.com/56884391/67552634-a4b28100-f735-11e9-9f78-d45ffc7ecac7.png)
  9. LALU BUAT 1 FILE BERNAMA README.md DENGAN MEMASUKAN PERINTAH "echo "#Latihan-01" >> "README.md"" LALU KETIK PERINTAH "ls -1" UNTUK MELIHAT FILE
  ![5](https://user-images.githubusercontent.com/56884391/67552649-abd98f00-f735-11e9-8360-d55d5cdc5518.png)
  10. MENAMBAHKAN FILE README.md PADA REPOSITORY LOCAL DENGAN MENGGUNAKAN PERINTAH "git add" 
  ![6](https://user-images.githubusercontent.com/56884391/67552666-b6942400-f735-11e9-9033-2c4b5852d8ec.png)
  11. UNTUK MELIHAT STATUS FILE KETIK PERINTAH "git status"
  ![7](https://user-images.githubusercontent.com/56884391/67552671-ba27ab00-f735-11e9-8944-205939e9b10e.png)
  12. SETELAH ITU KETIK PERINTAH "git commit -m" "komentar saya" UNTUK MENYIMPAN PERUBAHAN YANG ADA KE DALAM FILE DATABASE REPOSITORY
  ![8](https://user-images.githubusercontent.com/56884391/67552698-c90e5d80-f735-11e9-9fb6-376ae38b3321.png)
  13. SELANJUTNYA ANDA MASUK LAGI KE WEBSITE GITHUB, LALU ANDA MASUK KE REPOSITORY YANG SEBELUMNYA ANDA BUAT. SETELAH ITU PADA BAGIAN QUICK SETUP TERDAPAT URL GITHUB KITA. URL INI NANTINYA AKAN DIGUNAKAN MENGGUNAKAN PERINTAH "git remote add origin [url]" DAN PERINTAH GITCLONE "git clone [url]"
  ![9](https://user-images.githubusercontent.com/56884391/67552699-c90e5d80-f735-11e9-88be-a6dca08c8fa5.png)
  14. LALU KETIKKAN PERINTAH "git remote add origin [url]" contoh "git remote add origin https://github.com/RegaNugraha/Latihan-01.git"
  ![10](https://user-images.githubusercontent.com/56884391/67552701-c90e5d80-f735-11e9-9aa1-73e8fb5ef523.png)
  15. UNTUK MENGIRIM PERUBAHAN LOCAL REPOSITORY KE SERVER GUNAKAN PERINTAH "git push-u origin"
  ![11](https://user-images.githubusercontent.com/56884391/67552702-c9a6f400-f735-11e9-97cc-83685ed74f76.png)
  16. TUNGGU BEBERAPA MENIT SAMPAI ADA KOLOM GITHUB LOGIN. LAU ANDA ISI KOLOM TERSEBUT, PERHATIKAN GAMBAR BERIKUT
  ![12](https://user-images.githubusercontent.com/56884391/67556663-c1eb4d80-f73d-11e9-905f-d4ce43193bf6.png)
  17. SETELAH ITU AKAN MUNCUL KOLOM OPEN SHH. LALU ANDA ISI KOLOM TERSEBUT. PERHATIKAN GAMBAR BERIKUT
  ![13](https://user-images.githubusercontent.com/56884391/67552706-ca3f8a80-f735-11e9-8e77-6c4dd9ae0bfb.png)
  18. SETELAH ITU APABILA ANDA INGIN MELAKUKAN CLONE REPOSITORY GUNAKAN PERINTAH "git clone [url]" CONTOH "git clone https://github.com/RegaNugraha/Latihan-01.git" PERHATIKAN GAMBAR BERIKUT
  ![16](https://user-images.githubusercontent.com/56884391/67556894-2d351f80-f73e-11e9-819f-8738d7d51a53.png)
  ![17](https://user-images.githubusercontent.com/56884391/67552722-cdd31180-f735-11e9-8697-f9650d5dc54f.png)
  ![17](https://user-images.githubusercontent.com/56884391/67552724-ce6ba800-f735-11e9-882c-e89b09237ec3.png)
