# UTS - PAM - RA | 120140003
## Nama Aplikasi : Todolist
## Deskripsi Aplikasi
Aplikasi ini dibangun dengan react native dan expo.
Aplikasi ini memiliki fitur menambahkan note, menghapus note, 
menampilkan status bar dan mengatur kecerahan layar. 
Fitur menampilkan status bar dan mengatur kecerahan layar tersebut dibuat dengan
menggunakan API dari expo.


## Package yang Digunakan (Expo)

* expo-brightness

* expo-status-bar


## Cara Menginstall Aplikasi dalam Mode Pengembangan
### Prerequisite:
* expo-cli
* eas-cli

jika belum teinstall Jalankan
```bash
  npm i -g expo-cli eas-cli
```

### Langkah Menjalankan Aplikasi pada Development Mode

1. Clone repo ini
    ```bash
    git clone https://github.com/Ardhito120140003/Todolist.git
    ```

2. Masuk ke dalam direktori proyek
    ```bash
    cd Todolist
    ```

3. Install dependencies
    ```bash
    npm install
    ```

4. Ketikkan 
    ```bash
    eas login
    ```
   dan login menggunakan akun expo

5. Ketikkan
    ```bash
    eas build --profile development --platform android
    ```
   untuk memulai build development

6. Setelah build selesai, setelah itu download aplikasi melalui link
   yang muncul setelah melakukan build

7. Install Aplikasi yang sudah didownload 

8. Buka aplikasi, dan login menggunakan akun expo

9. Pada terminal, ketikkan
    ```bash
    npx expo start --dev-client
    ```
   untuk memulai development server

11. Pada aplikasi, Pilih Development Server "Todolist - .....", jika tidak muncul silahkan scan QR code yang diberikan pada terminal

12. Tunggu proses buindling aplikasi selesai

13. Izinkan aplikasi untuk melakukan perubahan terhadap sistem pada tab brightness

14. Aplikasi sudah dapat dipakai dalam tahap development mode
