# Eksplorasi Dataset _Coffee Shop_

Hi, ini adalah _repository_ yang memuat salah satu proyek dataku, yakni melakukan eksplorasi data pada dataset bisnis _coffee shop_. Dalam prosesnya, ditemukan beberapa fakta-fakta unik dan menarik mengenai bisnis _coffee shop_ tersebut, yang bisa dilihat dalam notebook yang disediakan.

**Blog post:** https://www.feliciasantoso.me/blog/2022/notebook-baru-exploring-coffee-shop-dataset

**NEW - Sekarang ada [PPT](https://drive.google.com/file/d/1RbyNvvdmwFp4Jj9T1dIhexfhZIxkb6QN/view?usp=sharing) dan [dashboard Power BI](/dashboard) juga!**

## Background

### Problem

Sebuah _coffee shop chain_ fiktif yang terdiri dari 3 outlet ingin menganalisis data yang mereka punya. Secara singkat, data yang telah dikoleksi adalah data pelanggan, transaksi, serta _inventory_ produk mereka. 

Dalam analisis ini, aku bertujuan untuk melakukan beberapa hal sebagai berikut:

- Melakukan *profiling* pelanggan untuk mendukung strategi produk di setiap outlet

- Memberikan _product recommendation_ agar bisa meningkatkan *revenue*

- Mengoptimalisasi stok atau mengurangi stok produk agar tidak banyak yang terbuang

Berkenaan dengan poin tiga, aku juga menyelidiki berapa jumlah dan mengapa outlet-outlet _coffee shop_ ini memiliki banyak *pastry* yang terbuang karena tidak terjual setiap harinya.

### Data

Berikut ini data-data yang tersedia/digunakan dalam analisis _case_ ini:

| Nama Tabel       | Dimensi                 | Deskripsi Singkat                                                                                            |
| ---------------- | ----------------------- | ------------------------------------------------------------------------------------------------------------ |
| Receipts         | 49,894 baris x 14 kolom | Data transaksi utama yang berisi produk terjual beserta kuantitas dan harganya.                              |
| Products         | 88 baris x 12 kolom     | Data mengenai semua produk yang dijual oleh _chain coffee shop_ ini.                                         |
| Pastry Inventory | 307 baris x 7 kolom     | Data perhitungan stok _pastry_ yang dibuat, dijual, dan terbuang oleh tiap outlet _coffee shop_ setiap hari. |
| Customers        | 2,246 baris x 9 kolom   | Data informasi dan demografis pelanggan _coffee shop_ yang memiliki kartu _membership_.                      |
| Generations      | 70 baris x 2 kolom      | Data tahun lahir berapa yang dianggap masuk generasi tertentu (ex: _Baby Boomers_).                          |

Data diambil dari data _assignment_ salah satu kelas data yang aku ikuti, dimana (dari hasil penelusuran) kemungkinan besar data tersebut berasal dari [sumber ini](https://www.kaggle.com/datasets/ylchang/coffee-shop-sample-data-1113).

## Metode

Data dianalisis melalui teknik eksplorasi data, dimana detail-detail dari dataset _coffee shop_ ini dieksplorasi sesuai dengan objektif yang ada melalui statistika dan visualisasi. Objektif dipecah menjadi pertanyaan-pertanyaan eksplorasi yang lebih spesifik, dimana setiap pertanyaan kemudian dicari jawabannya dengan perhitungan dan visualisasi dari data yang tersedia. 

**Alat & Teknologi:** Analisis dilakukan dalam _Jupyter Notebook_ (tersedia dalam _repository_ ini) menggunakan bahasa Python, serta _library_ standar analisis data di Python seperti `pandas`, `matplotlib`, maupun `seaborn`.

## How to Navigate Repository

Untuk membuka notebook, klik folder **Notebook** pada tampilan utama Github, lalu pilih file notebook yang ingin Anda lihat. File notebook memiliki nama file berakhiran `.ipynb`, dan nama file notebooknya adalah `Exploring Coffee Shop Dataset.ipynb` untuk kasus eksplorasi data kali ini.

Setelah Anda klik file notebook yang sesuai, _preview_ notebook akan langsung terbuka di browser Anda (termasuk jika Anda menggunakan browser _mobile_!) 🎉

![Contoh Preview Notebook](https://user-images.githubusercontent.com/47961812/183531580-8355ccf2-1b40-4ddc-b19a-bc73a0bddc14.png)

_Catatan:_ Apabila Anda khawatir harus membaca kode Python untuk memahami notebooknya, tenang saja karena notebook telah berisi banyak _comment_ serta visualisasi yang bisa dibaca. Misalnya, jika Anda perhatikan pada _screenshot_ di atas, kalimat yang bertulisan tebal telah disediakan sebagai kesimpulan dari hasil kode yang ditulis di bawahnya. Jadi, Anda tidak harus menjadi ahli Python untuk bisa mengikuti dan memahami analisisnya 😃

## Acknowledgment

Eksplorasi data ini dibuat untuk proyek _capstone_ kelas _Basic Analytics for Business People_ Narasio Data, lalu diedit serta diupdate sebelum ditampilkan di sini. Terima kasih untuk Mbak Dyantika sebagai mentorku selama kelas dan tim trainer Narasio Data untuk kelasnya yang menarik, dan teman saya Nicholas C.W. sebagai teman diskusi dan inspirasi untuk bagian rekomendasi bisnisnya!
