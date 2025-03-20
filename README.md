NPM : 2306275960  
Kelas : B**

## Reflection
### Commit 1 Reflection Notes
**Inside the `handle_connection` Method**  
Method `handle_connection` berfungsi untuk menangani setiap permintaan yang dikirim oleh _browser_ atau _client_ ke server. Saat _client_ terhubung ke alamat `127.0.0.1:7878`, permintaan akan dikirim dalam bentuk teks menggunakan protokol HTTP. Fungsi ini membaca permintaan tersebut baris demi baris dan menampilkannya di terminal. Informasi yang dibaca meliputi method permintaan (seperti GET), alamat yang diminta, dan data tambahan tentang _client_. Dengan mengetahui isi permintaan, server dapat memahami kebutuhan _client_ dan menyiapkan respons yang sesuai. Jadi, `handle_connection` menjadi langkah awal untuk memproses permintaan sebelum server merespons.

### Commit 2 Reflection Notes
**Modifications in the `handle_connection` Method**  
Setelah dimodifikasi, method `handle_connection` tidak hanya membaca permintaan dari client, tetapi juga memberikan respons balik ke _client_ dalam bentuk halaman HTML. Setelah permintaan dibaca, fungsi ini menyusun respons HTTP dengan status "200 OK" dan membaca isi _file_ `hello.html`, lalu mengirimkan isi _file_ tersebut sebagai respons ke _client_ melalui koneksi. Dengan perubahan ini, fungsi `handle_connection` tidak hanya berperan mencatat permintaan, tetapi juga menyajikan tampilan yang diminta.
![Commit 2 screen capture](assets/images/commit2.png)

 