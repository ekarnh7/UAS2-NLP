# UAS2-NLP-Analisis Sentimen Ulasan Aplikasi Pintu di Play Store Menggunakan Metode Naive Beyes

![logo](Src/logo.png)


```bash 
Disusun Oleh Kelompok 2: 
1. Eka Risti Nailah Heruawan (7A PSTI)
2. Tresna Ramadhian Setya WG (7B PSTI)
```

# Background

Saat ini aplikasi yang berkaitan dengan jual/beli dan investasi aset digital sangat digemari oleh masyarakat. Salah satu aplikasi jual/beli dan investasi yang dikenal di Indonesia adalah aplikasi PINTU. Berdasarkan halaman berita suara.com (https://www.suara.com/bisnis/2021/12/10/060455/aplikasi-aset-crypto-pintu-telah-diunduh-2-juta-kali), saat ini aplikasi PINTU telah diunduh hingga 2 juta kali dengan pengguna aktif mencapai lebih dari 700 ribu. Untuk mengetahui feedback dari masyarakat mengenai aplikasi PINTU, pada project UAS 2 ini kami akan melakukan analisis sentimen aplikasi PINTU. 



# Dataset

Kami menggunakan dataset PINTU yang ada pada playstore dengan menggunakan teknik scraping, dimana scraping merupakan proses mengumpulkan informasi dari internet, pada studi kasus ini kami mengambil data tersebut dari playstore.Dataset yang digunakan sebanyak 1000 data, karena dataset pada playstore telah memiliki rating 1-5, oleh karena itu kami memberikan label pada setiap feedback/ulasan seperti berikut :
1. Bernilai NEGATIF, jika rating yang diberikan 1,2 atau 3
2. Bernilai POSITIF, jika rating yang diberikan 4 atau 5



# Struktur Projek

Berikut merupakan struktur projek :
1. File Readme\
   Berisi keterangan baik mengenai background, dataset, struktur projek, metrik, evaluasi, dan bagaimana cara menjalankan projek
2. File Requirements\
   Berisi library yang digunakan
4. Folder Data\
   Berisi dataset yang mentah atau dataset yang telah difilter berdasarkan varibael yang akan digubakan
3. Folder Parameter\
   Berisi keterangan mengenai lokasi path secara detail
4. Folder Src\
   Berisi file noteboks dan jenis file lainnya
5. Folder Output\
   Berisi hasil dataset yang sudah bersih
6. Folder Model\
   Berisi hasil dari training model 

  
  
# Metrik 

Kami menggunakan beberapa metrik yaitu accuracy, precission, recall, dan f1. Berdasarkan hasil dari confusion metrix dataset aplikasi PINTU memiliki jumlah False Negatif (FN) = 2, sedangkan False Positif (FP) = 184, sehingga antara jumlah FN dan FP tidak mendekati oleh karena itu kami memilih metrix F1 sebagai acuan.



# Evaluasi
```bash
Kami membagi dataset menjadi dua bagian yaitu :
1. 70%, untuk data training
2. 30%, untuk data testing
```

# Cara Menjalankan Projek 

```bash
Hasil analisis sentimen aplikasi PINTU
Path = ("src/analisis_sentimen.ipynb")
```
