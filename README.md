
# Financial Data Challange

## Description
Challenge ini dibuat dalam lingkup kerjasama PT. Sharing Vision Indonesia dengan BRI (PT Bank Rakyat Indonesia, Tbk) dengan tujuan:
* Membuka kesempatan untuk peserta dari seluruh Indonesia, dari Sabang sampai Merauke untuk merasakan Challenge terhadap real financial use case, pengalaman-pengalaman dalam lingkungan BRI.
* Membuka peluang peserta untuk mendapatkan kesempatan bekerja di BRI. Challenge ini dapat membantu BRI/Sharing Vision untuk melihat peserta yang berpotensi untuk ikut menjadi Team Big Data di lingkungan BRI/Sharing Vision.
* Membuka peluang peserta yang ingin learning by doing.

## Use Case
Dalam kompetisi ini, kasus yang peserta hadapi adalah churn. Churn adalah suatu istilah dimana nasabah meninggalkan perusahaan. Jika dalam dunia perbankan, nasabah tersebut pada periode tertentu memutuskan untuk tidak lagi menjadi nasabah di suatu bank dan mungkin kemudian menjadi nasabah di bank lain. Peserta akan diminta untuk membuat model machine learning untuk klasifikasi yang dapat membedakan antara nasabah yang tergolong churn dan yang tidak churn. 

Pekerjaan yang peserta lakukan harus memenuhi langkah-langkah berikut, antara lain:
1. Exploratory data analysis (EDA)
2. Feature Engineering
3. Modeling
4. Evaluation
5. Prediction Output

## Data

Data terdiri atas dua dataset, yaitu:
* [fin_data_challenge_train.csv](findata_challenge_train.csv): 100.000 baris dan 126 kolom (125 kolom fitur dan 1 kolom target 'y’)
* [fin_data_challenge_test.csv](findata_challenge_test.csv): 25.000 baris dan 125 kolom (tanpa kolom target 'y’)

**Deskripsi Kolom**<br />
Data Nasabah: <br />
x0-x124 (125 kolom) : Merupakan data nasabah yang telah dinormalisasi dan dirahasiakan nama kolomnya.

Variabel target: <br />
y - Apakah nasabah akan churn? (1 :iya,0 :tidak)

Note :<br />
Terdapat beberapa _Missing Value_ pada data.

## Evaluation
Evaluasi dilakukan dengan mengukur performa model yang dilakukan oleh peserta, berdasarkan performance AUC. 
File yang dikirimkan memiliki format sebagai berikut:
1. Coding script dalam bentuk ‘nama_lengkap-submission.ipynb’
2. Nama file output (hasil prediksi terhadap data test): 'nama_lengkap-submission.csv' <br /> Kolom: 'Id' dan 'Predicted'. <br />Mohon perhatikan bahwa nama file dan nama kolom bersifat case sensitive.

<img src="submission.jpg" align="center" width="600" />

## Rules

- Satu akun per perserta. Tidak ada penggabungan peserta dalam kompetisi ini. 
- Batasan/larangan dalam kompetisi ini adalah sebagai berikut:
    * Peserta dilarang untuk melakukan code sharing
    * Peserta dilarang untuk meminta atau mendapatkan bantuan dari pihak lain.
    * Peserta dilarang melakukan pelabelan manual

**Jadwal:**<br />
10 Feb 2022		: Webinar Roadmap to Smart Banking Mindset Through AI-ML<br />
14 Feb – 11 Maret 2022	: Pelaksanaan Lomba<br />
14 Mar – 18 Mar 2022	: Penilaian<br />
25 Mar 2022		: Pengumuman Pemenang

