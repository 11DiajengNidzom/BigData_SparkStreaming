## Diajeng Nidzom Yoesharnilillah
## TI3B - 06

## Soal BigData
1. Silakan selesaikan praktikum tersebut sesuai langkah-langkah sebelumnya, lalu laporkan hasilnya berupa link repository GitHub dengan nama spark-streaming disertai dengan screenshot hasilnya.
2. Jelaskan perbedaan spark streaming dengan metode stateless dan stateful stream processing ?
->Stateless Stream Processing: Stateless stream processing berarti setiap baris data dalam aliran diolah secara independen tanpa mempertahankan atau menggunakan status sebelumnya. 
->Stateful Stream Processing: Stateful stream processing berarti status (state) dari aliran data dipertahankan dan digunakan dalam pengolahan berikutnya.
3. Jelaskan masing-masing maksud kode berikut sesuai nomor kodenya pada laporan praktikum Anda!

## Menjelaskan Kodenya
-> sys.argv: adalah sebuah list dalam modul sys pada bahasa pemrograman Python. List ini berisi argumen baris perintah yang diberikan saat menjalankan skrip Python dari baris perintah atau terminal.
->StreamingContext: adalah entitas utama yang digunakan untuk mengonfigurasi dan mengendalikan proses streaming data dalam Spark Streaming.
->sc: SparkContext untuk berinteraksi dengan kluster Spark.
->sys.stderr: adalah objek file standar error dalam modul sys pada bahasa pemrograman Python.
->lambda line: fungsi anonim dengan satu parameter line.
->awaitTermination: adalah metode dalam StreamingContext di Apache Spark yang digunakan untuk menunggu hingga streaming job selesai atau dihentikan secara manual.
->socketTextStream: adalah sebuah metode dalam modul pyspark.streaming di Apache Spark yang digunakan untuk membuat DStream (Distributed Stream) yang membaca data dari socket TCP.
->reduceByKey: adalah sebuah operasi pada DStream (Distributed Stream) dalam modul pyspark.streaming di Apache Spark yang digunakan untuk menggabungkan nilai-nilai yang memiliki kunci yang sama dalam setiap batch dari DStream.
->nc, lk: utilitas netcat untuk membuka koneksi dan mengirim/menerima data melalui jaringan.
->master: argumen untuk menentukan alamat URL atau mode eksekusi kluster Spark.
->spark-submit: adalah sebuah perintah yang digunakan untuk menyerahkan (submit).
->flatMap: Membagi setiap elemen dalam RDD menjadi beberapa elemen dalam bentuk yang berbeda.
->ssc.checkpoint: adalah metode dalam StreamingContext di Apache Spark yang digunakan untuk mengatur titik kontrol.

  