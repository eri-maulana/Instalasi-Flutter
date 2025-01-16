Cara menginstall framework / SDK Flutter tanpa Android Studio dengan mudah 100% work.

Pada langkah-langkah ini saya menggunakan windows 10.

Saya yakin buat kalian yang memiliki spesifikasi laptop/komputer kurang bagus pasti merasakan betapa beratnya menggunakan android studio. Pastikan temen-temen terkoneksi internet ya, karena kita membutuhkan resource dari repository online.

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
2. Jalankan sdkmanager “platform-tools”
3. Jalankan sdkmanager “platforms;android-30”
4. Jalankan sdkmanager “build-tools;30.0.0”
5. Jalankan sdkmanager --licenses
6. Jalankan flutter doctor --android-licenses
7. Jalankan flutter doctor
8. Selesai

Link instalasi :
Flutter: https://flutter.dev/docs/development/...
Command Line Tools: https://developer.android.com/studio
Open JDK: https://adoptopenjdk.net/
