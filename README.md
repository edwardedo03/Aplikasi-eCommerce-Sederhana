# Aplikasi-eCommerce-Sederhana
UAS Object Oriented Programming Semester 3

Kelompok:
Edward Antonio Herlambang Hutauruk
Gabriella Lavigne Pink
Joel Oktavianus

Untuk memastikan program dapat dijalankan dengan lancar, terdapat satu penyesuaian kecil pada source code yang perlu dilakukan, khususnya terkait pemanggilan file gambar (resource). Adapun langkah-langkah yang perlu dilakukan adalah sebagai berikut:
1. Buka direktori Other Sources → src/main/resources → images.
2. Pilih file gambar logobaru-removebg-preview.png, kemudian klik kanan dan pilih Properties.
3. Salin alamat (path) lengkap dari file tersebut melalui menu Copy Address.
4. Setelah itu, buka Source Packages → View → Login.java, lalu masuk ke bagian Source Code.
5. Pada baris pemanggilan fungsi pengaturan gambar, silakan ganti alamat file gambar dengan path yang telah disalin sebelumnya, misalnya: "C:\\Users\\joelo\\uas_oop\\Ecommerce Final\\Ecommerce\\src\\main\\resources\\images\\logobaru-removebg-preview.png", jLabel17);
Penyesuaian ini diperlukan agar sistem dapat menemukan resource gambar dengan benar pada saat program dijalankan.
