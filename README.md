# master_plan

A new Flutter project.

## Getting Started

# Tugas Praktikum 1: Dasar State dengan Model-View

1. Selesaikan langkah-langkah praktikum tersebut, lalu dokumentasikan berupa GIF hasil akhir praktikum beserta penjelasannya di file README.md! Jika Anda menemukan ada yang error atau tidak berjalan dengan baik, silakan diperbaiki.

2. Jelaskan maksud dari langkah 4 pada praktikum tersebut! Mengapa dilakukan demikian?

- File data_layer.dart dibuat dengan tujuan mempermudah pengelolaan dan penggunaan kode dalam proyek. Dengan menggabungkan impor dari plan.dart dan task.dart dalam satu tempat, kita dapat mengatur kode lebih efisien. Penggunaan file ini membuat impor menjadi lebih sederhana, hanya memerlukan satu impor untuk mengakses semua fitur yang terkait dengan lapisan data. Selain itu, file ini juga berfungsi sebagai titik abstraksi tingkat tinggi, menyediakan akses mudah ke berbagai fitur lapisan data terkait. Dengan demikian, pengelolaan dependensi di seluruh proyek menjadi lebih teratur, dan struktur modular proyek dapat diintegrasikan dengan lebih baik.

3. Mengapa perlu variabel plan di langkah 6 pada praktikum tersebut? Mengapa dibuat konstanta ?

- Pada langkah 6, variabel plan dideklarasikan sebagai konstanta (const Plan()), mungkin digunakan untuk menyimpan objek dari kelas Plan. Penggunaan const Plan() memberikan nilai awal yang tetap pada saat pembuatan objek, memastikan bahwa plan memiliki nilai awal yang konsisten setiap kali objek _PlanScreenState dibuat. Pendeklarasian plan sebagai konstanta juga dapat memberikan optimasi kinerja, karena objek yang dideklarasikan sebagai konstanta dibuat pada saat kompilasi. Selain itu, penggunaan konstanta ini dapat membantu mencegah perubahan nilai plan yang tidak diinginkan dan meningkatkan kejelasan kode.

4. Lakukan capture hasil dari Langkah 9 berupa GIF, kemudian jelaskan apa yang telah Anda buat!

- Gambar
![Screenshot hasil langkah 9](img/Hasil%20langkah%209.png)

5. Apa kegunaan method pada Langkah 11 dan 13 dalam lifecyle state ?

- Langkah 11 menggunakan method initState untuk menginisialisasi objek scrollController dan mengelola scrolling di dalam widget. Fungsi dari kode tersebut adalah menjadikan antarmuka pengguna lebih responsif dengan memindahkan focus dari elemen yang berfokus saat scrolling. Pada Langkah 13, method dispose digunakan untuk membersihkan sumber daya yang digunakan oleh widget ketika widget dihancurkan. Dalam hal ini, scrollController.dispose() membebaskan sumber daya terkait dengan objek scrollController, menghindari kebocoran memori atau masalah kinerja. Dengan menggunakan dispose pada saat yang tepat, Flutter memastikan bahwa sumber daya yang digunakan oleh widget dibersihkan dengan benar, sesuai dengan siklus hidup aplikasi, dan meningkatkan efisiensi penggunaan sumber daya.

6. Kumpulkan laporan praktikum Anda berupa link commit atau repository GitHub ke spreadsheet yang telah disediakan!

# Tugas Praktikum 2: InheritedWidget


This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
