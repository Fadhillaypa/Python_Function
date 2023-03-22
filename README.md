# Python_Function
PENJELASAN

Fungsi hitung_fpb(a, b) digunakan untuk menghitung FPB dari dua bilangan a dan b dengan menggunakan algoritma Euclidean. Fungsi tersebut memeriksa apakah bilangan b sudah mencapai nol. Jika iya, maka fungsi mengembalikan bilangan a sebagai hasil FPB. Jika belum, maka fungsi memanggil dirinya sendiri dengan argumen b dan sisa hasil bagi a dan b, yaitu a % b.

Fungsi hitung_kpk(a, b) digunakan untuk menghitung KPK dari dua bilangan a dan b. Fungsi tersebut menginisialisasi variabel kpk dengan nilai maksimum antara a dan b. Kemudian, fungsi menggunakan sebuah loop untuk mengecek apakah kpk adalah kelipatan dari a dan b. Jika ya, maka fungsi mengembalikan kpk sebagai hasil KPK. Jika tidak, maka fungsi menambahkan nilai kpk sebesar 1 dan memulai loop kembali.

Selanjutnya, program utama meminta pengguna untuk memilih opsi hitung FPB atau KPK, atau keluar dari program. Jika pengguna memilih opsi hitung FPB atau KPK, program meminta pengguna untuk memasukkan dua bilangan. Program kemudian menggunakan fungsi yang sesuai untuk menghitung FPB atau KPK dari dua bilangan tersebut, dan mengeluarkan hasilnya ke layar. Jika pengguna memilih opsi keluar, program keluar dari loop utama dan menampilkan pesan terima kasih. Jika pengguna memilih opsi lain, program menampilkan pesan bahwa pilihan tidak valid dan meminta pengguna untuk memilih lagi.
