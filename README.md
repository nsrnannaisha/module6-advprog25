NPM : 2306275960  
Kelas : B**

## Reflection
### Commit 1 Reflection Notes
**Inside the `handle_connection` Method**  
Method `handle_connection` berfungsi untuk menangani setiap permintaan yang dikirim oleh _browser_ atau _client_ ke server. Saat _client_ terhubung ke alamat `127.0.0.1:7878`, permintaan akan dikirim dalam bentuk teks menggunakan protokol HTTP. Fungsi ini membaca permintaan tersebut baris demi baris dan menampilkannya di terminal. Informasi yang dibaca meliputi method permintaan (seperti GET), alamat yang diminta, dan data tambahan tentang _client_. Dengan mengetahui isi permintaan, server dapat memahami kebutuhan _client_ dan menyiapkan respons yang sesuai. Jadi, `handle_connection` menjadi langkah awal untuk memproses permintaan sebelum server merespons.

 