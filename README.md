# ResponsiTccl
Saya Membuat aplikasi web untuk menampilkan profil pribadi

Dockerfile 

Dockerfile merupakan skrip yang berisi atau terdiri dari serangkaian perintah, intruksi (argumen) yang akan dieksekusi secara otomatisasi dan berurutan untuk membangun sebuah image. Jadi akan mempermudah kita untuk tidak selalu mengetikkan perintah setiap kali kita akan menjalankan container.


Sebelum kita masuk dockerfile langkah pertama yang kita lakukan ialah membuat directory dengan menggunakan perintah mkdir ResponsiTccl, kemudian untuk masuk kedalam directory menggunakan perintah cd ResponsiTccl,

langkah kedua yaitu membuat image dengan menggunakan perintah sudo docker build -t dengan menggunakan nama responsidaus


dan untuk langakah ketiga dengan menggunakan perintah sudo docker run -p 80:80 --name responsidaus-1 responsidaus berfungsi untuk menjalankan images responsidaus didalam localhost dengan port 80 yang namanya responsidaus-1.

