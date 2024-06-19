# Menghapus/ Membatalkan Commit Terakhir Sebelum di Push ke Github

**Membatalkan Commit Terakhir dan Menyimpan Perubahannya di Working Directory**
   
    git reset --soft HEAD~1
    

**Membatalkan Commit Terakhir dan Menghapus Perubahannya dari Working Directory**

    git reset --hard HEAD~1


**Membatalkan Commit Terakhir yang Sudah Dikirim ke Remote Repository**
Jika commit terakhir sudah di-push ke remote repository dan dibatalkan, maka langkah-langkahnya:

1. Reset commit terakhir secara lokal menggunakan salah satu dari metode di atas (--soft atau --hard).
2. Push perubahan tersebut ke remote repository dengan menambahkan opsi --force untuk memaksa push perubahan.

    Contoh:

       git reset --hard HEAD~1

   push

       git push origin <branch_name> --force

    atau

       git push -f origin branch_name
