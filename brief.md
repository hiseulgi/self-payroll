Fitur yang harus dikerjakan adalah sebagai berikut: 
1. Melakukan manage data jabatan berupa operasi CRUD (create, read, update, delete)
2. Melakukan manage data employee berupa operasi CRUD (Create, Read, Update, Delete)
3. Admin dapat melakukan topup balance perusahaan
4. Melakukan penarikan sallary dengan menyertakan employee ID dan secret ID, besaran salary berdasarkan jabatan yang dimiliki oleh tiap employee
5. Terdapat riwayat topup dan pengurangan balance perusahaan 


Untuk memudahkan dalam perancangan database silahkan menggunakan [rancangan database](https://drive.google.com/file/d/1N7R7u229GBKsmS3D_SfvJGGS36Q6kQi4/view?usp=sharing) yang telah disediakan, semua endpoint dan response harus sesuai dengan link dokumentasi yang ada pada [postman documenter](https://documenter.getpostman.com/view/4080490/2s83Ychhk4)


Web service kali ini dibuat dengan bahasa GO dan menggunakan database PostgreSQL, sangat disarakan untuk melakukan implementasi clean code sehingga mudahkan dalam pengembangan selanjutnya dan dapat mempermudah pekerjaan secara berkelompok. 


Jangan lupa untuk :
1. Menginstall PostGreSQL ke sistem operasi kalian melalui [link ini](https://www.postgresql.org/download/) 
2. Menginstall bahasa GoLang terbaru melalui [link ini](https://go.dev/doc/install) 
3. Menginstall code editor seperti Visual Studio Code. IntelliJ, atau code editor lainnya.


Hints
1. Gunakan GO versi terbaru atau lainnya
2. Sangat direkomendasikan melakukan implementasi [clean architecture](https://github.com/bxcodec/go-clean-arch)
3. Gunakan framework pendukung untuk membuat RestFull API, sangat direkomendasikan menggunakan [Echo](https://github.com/labstack/echo) 
4. Gunakan ORM untuk melakukan konseksi ke database, sangat direkomendasikan menggunakan [Gorm](https://gorm.io/)
5. Untuk terkoneksi dengan PostgreSQL dapat menggunakan menuju [dokumentasi](https://gorm.io/docs/connecting_to_the_database.html#PostgreSQL) 
6. Logging sangat berguna dalam pembuatan web service, kamu bisa menggunakan default logging dari Echo atau menggunakan [Logrus](https://github.com/sirupsen/logrus)
7. Gunakan RDBMS client unutuk mempermudah melihat data, sangat direkomendasikan menggunakan TablePlus 
8. Buat database sesuai dengan diagram yang telah disertakan, file diagram dapat di unduh melalui link [berikut ini](https://drive.google.com/file/d/1N7R7u229GBKsmS3D_SfvJGGS36Q6kQi4/view?usp=sharing)
9. Gunakan sumber daya yang telah di sediakan pada assignment ini seperti format pengerjaan dan study case se maksimal mungkin!
  

Format Submit :
1. Setelah kalian mengerjakan seluruh instruksi dengan benar, uploadseluruh environment dan folder yang kalian gunakan dalam bentuk .zip
2. Namakan file zip kalian dengan format nama : Task 5_BE_CI _[Nama Peserta] (contoh: Task 5_BE_CI _Vahiya Prananta)
3. Upload file zip pada tautan yang telah di sediakan di task 5 ini!
4. Lalu, unggah file notepad tersebut pada bagian "Unggah Hasil Pekerjaanmu"