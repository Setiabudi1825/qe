11. Iterable data struktur

General purpose implementations
Tujuan umum impelementasi adalah implementasi yang paling umum digunakan dirancang untuk penggunaan sehari-hari.

Iterable di pekerkenalkan untuk dapat digunakan dalam loop foreach. kelas yang mengimplementasikan antarmuka iterable dapat diulangi.
Antarmuka iterable memiliki satu metode iterator.

Iterator adalah kelas yang mengelola iterasi diatas iterable. itu mempertahankan keadaan dimana kita berada dalam iterasi saat ini, dan tahu apa elemen berikutnya dan bagaimana mendapatkannya.