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

## *Perbedaan LP12 dan TMD*
Pada Tugas TMD kali ini, saya memutuskan untuk menggunakan konsep MVVM (Model-View-ViewModel) sebagai arsitektur utama. Pemilihan MVVM dilatarbelakangi karena saya ingin mencoba mengimplementasikan pola arsitektur MVVM,sedangkan untuk MVP saya sudah pernah mencoba mengimpelemntasikannya pada tugas LP sebelumnya dan juga saat Ujian Akhir Semester (UAS). Dengan menggunakan MVVM,saya berharap bahwa implementasi MVVM dalam TMD ini dapat meningkatkan pemahaman saya tentang pola arsitektur yang berbeda serta memperluas pemahaman saya tentang arsitektur ini.Untuk struktur file TMD saya sebagai berikut :
* Model : Di dalam folder ini, saya menempatkan kelas-kelas yang merepresentasikan objek-objek atau data yang digunakan dalam permainan.
  - Box.java -> Package model untuk mengakses kelas box 
  - DB.java -> Package model untuk mengakses basis data
  - GameInterface.java -> Package model untuk memberikan kerangka dasar bagi gameobject
  - GameObject.java -> Package model untuk mengakses GameObject (objek-objek di dalam game)
  - Player.java -> Package model untuk mengakses kelas player 
  - TableSCore.java -> Package model untuk mengakses table 
* View : Di folder ini, saya menempatkan semua file yang berkaitan dengan antarmuka pengguna atau UI. Ini termasuk tampilan menu utama dan tampilan display game.
  - Display.java -> Package view untuk menampilkan game dalam sebuah window.
  - Menu.java -> Package View untuk menampilkan menu utama
* Viewmodel :  Di dalam folder ini, saya menempatkan kelas-kelas yang bertanggung jawab untuk menghubungkan Model dengan View.
  - Controller.java -> Package ViewModel untuk pengontrol input keyboard dan mengakses kelas player.
  - Game.java -> Package ViewModel ini bertanggung jawab untuk mengatur logika permainan dan berinteraksi dengan kelas lain dalam aplikasi.
  - Handler.java -> Package ViewModel untuk mengelola objek game dalam permainan.
  - Music.java -> Package ViewModel untuk mengatur pemutaran musik
  - ProsesTabel.java -> Package ViewModel untuk mengakses dan memproses data pada tabel pemain
    
Maka, demikianlah penjelasan singkat mengenai penggunaan konsep MVVM (Model-View-ViewModel) dalam Tugas Masa Depan (TMD) saya ini. Jika terdapat kesalahan atau kekurangan dalam penjelasan saya, mohon maaf dan mohon untuk koreksiannya.Terima kasih atas perhatiannya.
