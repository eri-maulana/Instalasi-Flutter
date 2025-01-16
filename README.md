Cara menginstall framework / SDK Flutter tanpa Android Studio.

Pada langkah-langkah ini saya menggunakan windows 10.
Pastikan untuk terkoneksi internet, karena kita membutuhkan resource dari repository online.

Instalasi
1. Download SDK Flutter
2. Download Command Line Tools
3. Install Open JDK

Konfigurasi
1. Buat folder Android di partisi c:/
2. Buat folder sdk di dalam folder Android
3. Buat folder cmdline-tools/latest didalam folder sdk
4. Ekstrak SDK Flutter ke folder Android
5. Ekstrak Command Line Tools ke dalam folder latest

Setting flutter
1. Set environtment variable
    atau bisa langsung memasukan 3 perintah berikut di command prompt agar lebih mudah : 
    a. jalankan setx ANDROID_HOME C:\Android 
    b. jalankan setx C:\Android\flutter\bin
    c. jalankan setx C:\Android\sdk\cmdline-tools\latest\bin

2. Jalankan sdkmanager “platform-tools”
3. Jalankan sdkmanager “platforms;android-30”
4. Jalankan sdkmanager “build-tools;30.0.0”
5. Jalankan sdkmanager --licenses
6. Jalankan flutter doctor --android-licenses
7. Jalankan flutter doctor
8. Selesai

Link instalasi : 

Flutter : https://docs.flutter.dev/release/archive

Command Line Tools : https://developer.android.com/studio?hl=id (buka di halaman paling bawah dengan judul "Command line tools only")

Open JDK : https://adoptopenjdk.net/
