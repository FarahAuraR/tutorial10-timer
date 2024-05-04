## Reflection
###### 1.2. Understanding how it works.
![1.2](assets/images/1.2.png)
Setelah menjalankan cargo run, fungsi async akan berjalan di luar fungsi utama (main) yang memanggilnya. Maka dari itu, "hey hey" bisa keluar terlebih dahulu sebelum "howdy!" dan "done!" karena "hey hey" ada di luar fungsi async, sementara fungsi tersebut masih menunggu hasil dari future.