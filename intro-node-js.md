1. Mohon jelaskan apa itu Node.js? Apa perbedannya dengan JavaScript?
   - **Node.js merupakan kode pemograman yang dipublikasikan secara umum _(Open Source)_. Dijalankan pada sistem operasi windows, linux, MacOS _(Cross Platform)_. Dapat digunakan back-end yang berjalan menggunakan _V8 Engine_ dan mengeksekusi kode JavaScript di luar browser web. Node.js memungkinkan pengembang menggunakan JavaScript untuk menulis _command line tools_ dan untuk menghasilkan konten halaman web dinamis sebelum halaman dikirim ke browser web pengguna _(server-side scripting)_.**
   - **Perbedaan Node.js dengan JavaScript yaitu terletak pada proses eksekusinya yakni saat mengerjakan JavaScript kita hanya bisa menggunakan browser untuk menampilkan hasil eksekusinya. Sedangkan, dengan menggunakan Node.js kita dapat menjalankan javascript di server side menggunakan terminal command line menggunakan perintah “node”.**
2. Mohon jelaskan arsitektur dari Node.js?
   - **Node.js menggunakan arsitektur _“Single Threaded Event Loop”_ untuk menangani beberapa client secara bersamaan. Model pemrosesan Node.js didasarkan pada model _event-based_ JavaScript dan mekanisme _callback_ JavaScript (menjalankan perintah yang paling baru dibuat terlebih dahulu).**
3. Apa perbedaan antara Built-in Module, External Module, dan Custom Module pada Node.js?
   - **Built-in Module : module yang dimuat secara otomatis ketika proses node.js dimulai.untuk menggunakannya hanya perlu mengimpornya menggunakan _require_**
   - **External Module : Module yang diimplementasikan oleh orang-orang komunitas node.js untuk memecahkan banyak masalah pengkodean umum tanpa menulis ulang kode yang sama untuk setiap aplikasi.Untuk menggunakannya harus menginstal basis kode nya terlebih dahulu pada NPM menggunakan perintan _npm install module-name_ lalu jika sudah diinstal tinggal diimport menggunakan fungsi require juga**
   - **Custom Module : membuat module kita sendiri dan untuk bisa menggunakannya dalam aplikasi kita hanya perlu mengimpornya.**
4. Sebutkan salah satu contoh dari Built-in Module, External Module, dan Custom Module pada Node.js?
   - **Built-in Module : http, url, querystring, path, fs, crypto, net, dns. os**
   - **External Module : bower, csv, debug, gulp, lodash, mongoose, mongodb**
   - **Custom Module : arithmetic operations like addition, multiplication, subtraction, and division.**
