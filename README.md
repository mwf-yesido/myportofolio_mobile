# myportofolio_mobile

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Learn Flutter](https://docs.flutter.dev/get-started/learn-flutter)
- [Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Flutter learning resources](https://docs.flutter.dev/reference/learning-resources)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

### Tugas 7

1. Widget tree adalah struktur dari sebuah aplikasi flutter dimana parent merupakan container yang diisi oleh child widget-nya
2. MyHomePage sebagai container utama yang memuat beberapa children berbentuk InfoCard dan ItemCard, InfoCard yang memuat satuan kartu sebuah text informasi, dan ItemCard yang memuat satuan cartu interaktif
3. MaterialApp adalah widget yang memiliki/membungkus beberapa widget yang biasa digunakan dalam aplikasi berbasis Material Design. MaterialApp biasa digunakan sebagai root widget dikarenakan ia dapat mengatur top-level navigasi dari aplikasi.
4. Stateless tidak akan berubah setelah dirender, sedangkan Statefull bisa memiliki perubahan saat state berubah (Content bisa dirubah).
5. BuildContext menyimpan objects yang bisa di-pass kepada method lain. Dalam method build(), BuildContext bisa digunakan untuk mendapatkan objek inherited misalnya dengan Theme.of(context).
6. Hot reload adalah aksi yang menyimpan perubahan kode dan meng-update/re-build widget tree, menyimpan state dari program. Hot restart akan menyimpan perubahan kode, kemudian memulai ulang aplikasi Flutter. Kita bisa menggunakan hot reload untuk memeriksa perubahan design dengan cepat. Namun, kita tidak bisa mengandalkannya saat ingin menguji perubahan state.