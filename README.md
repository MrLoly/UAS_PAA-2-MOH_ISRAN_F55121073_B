# UAS_PAA-2-MOH_ISRAN_F55121073_B
A. Analisis algoritma bubble sort dan insertion sort Fungsi Bubble Sort: Fungsi bubble_sort(arr) digunakan untuk mengurutkan array arr menggunakan algoritma Bubble Sort. Algoritma Bubble Sort bekerja dengan membandingkan setiap elemen secara berpasangan dan menukar posisi jika ditemukan elemen yang lebih besar. Fungsi ini mengembalikan waktu eksekusi pengurutan.

Fungsi insertion_sort(arr) digunakan untuk mengurutkan array arr menggunakan algoritma Insertion Sort. Algoritma ini membagi array menjadi dua bagian, yaitu bagian yang sudah diurutkan dan bagian yang belum diurutkan. Kemudian, setiap elemen dari bagian belum diurutkan dimasukkan ke posisi yang tepat dalam bagian yang sudah diurutkan. Fungsi ini mengembalikan waktu eksekusi pengurutan.

Fungsi display_iterations(arr) digunakan untuk menampilkan 5 iterasi pertama dan 5 iterasi terakhir dari array arr.

Fungsi display_execution_time(execution_time) digunakan untuk menampilkan waktu komputasi pengurutan yang diberikan dalam parameter execution_time.

Fungsi display_before_after(arr, sorted_arr) digunakan untuk menampilkan array sebelum dan setelah pengurutan. Array awal arr dan array yang sudah diurutkan sorted_arr ditampilkan.

Fungsi analyze_algorithm() digunakan untuk menampilkan analisis algoritma pengurutan yang diimplementasikan. Fungsi ini menjelaskan Worst Case, Best Case, dan Average Case complexity dari Bubble Sort dan Insertion Sort.

Fungsi main() merupakan fungsi utama yang akan dijalankan saat program dijalankan. Fungsi ini mendefinisikan array arr yang akan diurutkan dan menampilkan pilihan algoritma pengurutan kepada pengguna. Pilihan yang tersedia adalah Bubble Sort, Insertion Sort, dan Analisis Algoritma. Jika pengguna memilih Bubble Sort atau Insertion Sort, array akan diurutkan menggunakan algoritma yang dipilih dan hasilnya akan ditampilkan. Jika pengguna memilih Analisis Algoritma, penjelasan mengenai kompleksitas waktu algoritma pengurutan akan ditampilkan. Jika pilihan tidak valid, pesan kesalahan akan ditampilkan.

Selain itu, kode program juga mencakup inisialisasi dan eksekusi fungsi main() jika file tersebut dieksekusi langsung. 


Pada program tersebut, terdapat pilihan algoritma pengurutan antara Bubble Sort dan Insertion Sort. Pengguna dapat memilih algoritma yang ingin digunakan dan array akan diurutkan sesuai pilihan tersebut. Hasil pengurutan beserta waktu eksekusi akan ditampilkan. Selain itu, terdapat fungsi untuk menampilkan iterasi pengurutan, analisis kompleksitas waktu, dan array sebelum dan setelah pengurutan.

Analisis algoritma TSP dan Dijkstra:
- Algoritma TSP menggunakan pendekatan rekursif dengan memoization untuk mencari jalur terpendek dalam TSP. Algoritma ini mencoba semua kemungkinan permutasi dari vertex yang dikunjungi dan mencari jalur terpendek. Fungsi tsp_algorithm digunakan untuk implementasi algoritma ini.
- Algoritma Dijkstra digunakan untuk mencari jalur terpendek dalam graf. Algoritma ini bekerja dengan memperbarui jarak terpendek ke setiap vertex yang belum dikunjungi secara iteratif. Fungsi dijkstra_algorithm digunakan untuk implementasi algoritma ini.

Program juga mencakup fungsi get_graph_from_user() yang meminta input pengguna untuk informasi graf, seperti jumlah vertex dan matriks adjacency.

Fungsi main() merupakan fungsi utama program yang menampilkan informasi pembuat, meminta pilihan algoritma dari pengguna, dan menjalankan algoritma yang dipilih sesuai input pengguna. Hasil pencarian jalur terpendek atau jarak terpendek beserta waktu komputasi akan ditampilkan. Program juga memiliki mekanisme untuk keluar dari program jika pengguna memilih opsi keluar atau menampilkan pesan kesalahan jika pilihan tidak valid.

Program ini memberikan pengguna kemudahan dalam memilih algoritma pengurutan dan menemukan jalur terpendek dalam TSP atau jarak terpendek dalam graf menggunakan algoritma Dijkstra.
