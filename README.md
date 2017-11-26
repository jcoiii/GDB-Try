# GDB-Try-
Mencoba GDB Debugging

Program C dibuat terlebih dahulu
![](/Screenshot%20from%202017-11-27%2007-41-48.png)

Program di Run dengan compiler GCC dan keluarkan sebuah output baru misalnya pada program saya "jo" lalu jalankan GDB dengan command 
pada gambar
![](/GCC%20%2BGDB.png)

Lalu Add Breakpoint pada Line yang diinginlkan, pada kasus ini saya meletakkan breakpoint pada Line 5 6 7.
![](/Breakpoint_.png)

Program di Run dengan menggunakan menggetikkan command "r"
![](/RUN.png)

Setelah di Run Program dicontinue ke breakpoint selanjutnya dengan command "c"
![](/CONT.png)

Jika Ingin melihat isi dari line break point ketik print
![](/PRINT.png)

Setelah itu program terus diberi command "c" pada GDB hingga akhir program
![](/AKHIR.png)

GDB akan mengeluarkan hasil akhir dari program yang saya buat
