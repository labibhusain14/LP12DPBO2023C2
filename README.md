# LP12DPBO2023C2
## *Janji*
Saya Mohammad Labib Husain mengerjakan Latihan Praktikum 12 dalam mata kuliah Desain Pemrograman Berbasis Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.
## *Penjelasan*
Menurut saya dalam permainan ini, ada objek-objek yang ada di dalam permainan (player dan box.). Ini termasuk ke bagian Model dalam MVP.

Kemudian, ada tampilan yang menunjukkan grafik, tombol, dan elemen-elemen visual lainnya yang bisa dilihat oleh user. Ini adalah bagian View dalam MVP.

Selanjutnya, ada bagian yang menghubungkan antara Model dan View, yang mengatur bagaimana objek-objek dalam permainan berinteraksi dengan tampilan dan logika bisnisnya. Ini adalah bagian Presenter dalam MVP.

Penerapan MVP ini, memisahkan tugas-tugas agar lebih mudah dikelola dan dipahami. Model berisi logika bisnis dan data terkait, seperti bagaimana karakter bergerak, aturan permainan, dan skor. View menampilkan elemen-elemen visual dan menerima masukan dari pengguna. Presenter bertindak sebagai penghubung antara Model dan View. Jadi, saat pengguna berinteraksi dengan tampilan, Presenter akan mengambil input tersebut, memprosesnya menggunakan Model, dan mengupdate tampilan sesuai dengan hasilnya.

Keuntungan menggunakan konsep MVP ini adalah:

* Memisahkan tugas-tugas sehingga setiap bagian dapat fokus pada fungsinya masing-masing.
* Memudahkan pengujian karena Model dan Presenter dapat diuji secara terpisah.
* Memungkinkan perawatan dan perubahan kode yang lebih mudah karena komponen-komponen dapat diganti atau diperbarui tanpa mengganggu bagian lainnya.
* Dalam contoh Anda, file-file yang ada dalam folder "model" berisi komponen Model, file-file dalam folder "view" berisi komponen View, dan file "controller.java" dalam folder "presenter" bertindak sebagai Presenter yang menghubungkan Model dan View.
