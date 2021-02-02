# Disclaimer
Project ini masih tahap pengembangan dan prototipe. Kami menggunakan sumber daya seadanya agar Smart Cleaner ini bisa beroperasi sesuai yang direncanakan terlebih dahulu.

Ukuran asli akan lebih besar daripada ukuran saat ini.

# Contents of this Repository
Repo ini berisi berkas dan progress Project Smart Cleaner yang saya kerjakan bersama kelompok saya di KSM Teknik Energi.

# What is Smart Cleaner?
Smart Cleaner yang kami kerjakan dibuat dan dikembangkan untuk membantu kegiatan kita sehari-hari dalam membersihkan rumah.

# What Can This Smart Cleaner Do?
1. Smart Cleaner diharapkan bisa memnyedot debu (vacuum)
2. Smart Cleaner diharapkan bisa mengepel lantai
3. Smart Cleaner diharapkan bisa memotong rumput di halaman rumah

# Requirements
1. Arduino UNO
2. [Arduino IDE](https://www.arduino.cc/en/software)
3. 4x DC Motor
4. 1x DC Booster
5. 1x L293D Motor Shield Driver / 2x L298N Motor Shield Driver
6. 1x Dust Sensor GP2Y1010AU0F
7. Power Source (Power Bank, Battery)
8. 1x Ultrasonic Sensor (additional requirement)

# Installation
1. Sumber tegangan 5V dihubungkan dengan DC Booster, lalu output dari DC Booster dihubungkan ke terminal External Power yang ada di L293D.
2. Atur output dari DC Booster menjadi 7-12V. Usahakan lebih dari 5V supaya DC Motor bisa berputar dalam kecepatan maksimal.
3. Upload kode Arduino yang telah dibuat.

# Why is This Project Delayed?
Karena pandemi COVID-19 kami terpaksa menghentikan project ini.

# Development Progress
1. Keempat DC Motor sudah bisa beroperasi bersamaan pada kecepatan maksimum

# Improvements
1. Setelah kami membaca datasheet dari Dust Sensor, kami mengalami kesulitan dalam mengaplikasikannya ke Project kami. Dust/Debu harus masuk ke tengah lingkaran yang ada di modul supaya bisa terdeteksi oleh modul. Karena itu, kami membuat improvisasi yaitu mengganti Dust Sensor dengan Ultrasonic Sensor.

# To Do
1. Memasang Ultrasonic Sensor untuk menghindari Smart Cleaner menabrak dinding atau objek lain yang ada di depannya.
2. Memasang panel surya sebagai pengisi baterai.

# Notes
1. Dalam video dokumentasi, saya ada kesalahan. Yang dimaksud Smoke Detector adalah Dust Sensor.
2. Kode program Arduino akan diunggah kalau Project ini sudah lebih dari 50% layak dipraktekan.

# Documentations
[Lihat di Google Drive](https://drive.google.com/drive/folders/1CO8K7rmB4_CI0fVGQtGMxk1W0MKN9mfa?usp=sharing)
