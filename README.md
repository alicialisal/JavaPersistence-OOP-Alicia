# Java Persistence - OOP - Alicia
Ini merupakan proyek program sederhana dalam bahasa Java yang menunjukkan contoh penggunaan framework Hibernate untuk memanipulasi data dasar (CRUD) terhadap sebuah tabel database RDBMS, yaitu MySQL.
Program ini menggunakan fitur-fitur dasar Hibernate untuk memetakan sebuah objek Java ke dalam sebuah tabel database, serta untuk melakukan manipulasi data melalui objek Java ke tabel database.
Dalam contoh ini, kita ingin memasukkan data dalam database oop tabel students melalui inputan user dari terminal Java menggunakan framework hibernate.

### Cara Menjalankan Program:

1. Pastikan Java Development Kit (JDK) terinstal di komputer Anda.
2. Pastikan MySQL sudah terpasang dan berjalan di komputer Anda.
3. Buatlah sebuah database MySQL dengan nama "oop".
4. Buka file hibernate.cfg.xml di direktori src/main/resources dan sesuaikan konfigurasi koneksi database sesuai dengan pengaturan MySQL di komputer Anda.
5. Jalankan perintah "mvn clean install" di terminal untuk mengunduh dependensi dan membangun proyek Maven.
6. Jalankan proyek dengan menjalankan void main di class com.example.HibernateTest.

### Struktur Proyek:

- src/main/java/com/example: Direktori ini berisi kode sumber Java untuk aplikasi.
  - Students.java: Kelas entitas yang mewakili tabel Students dalam basis data.
  - HibernateTest.java: Kelas utama yang berisi logika untuk melakukan operasi CRUD menggunakan Hibernate.
  - HibernateUtils.java: Kelas utilitas untuk mendapatkan sesi Hibernate.
  - student.hbm.xml: File pemetaan Hibernate XML untuk kelas Students.
- src/main/resources:
  - hibernate.cfg.xml: File XML konfigurasi Hibernate yang mengatur koneksi database dan pemetaan kelas-kelas Java ke tabel dalam database.
- pom.xml: File XML konfigurasi Maven yang mendefinisikan proyek dan dependensi-dependensinya.

### Teknologi yang digunakan:

- Java
- MySQL
- Maven
- Hibernate'
