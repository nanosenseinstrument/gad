# Covid-19 | Ai-Detection

## 1.1 Latar Belakang

Pemanfaatan kemajuan teknologi sensor yang dikombinasikan dengan sistem piranti lunak kecerdasan buatan atau *artificial intelligence* (AI) menjadikan harapan akan hadirnya alat deteksi cepat dan akurat untuk berbagai bidang aplikasi. Alat deteksi yang dimaksud adalah hidung elektronik atau *electronic nose*. Prinsip kerja dari *electronic nose* adalah dengan meniru cara kerja indera penciuman manusia. Oleh sebab itu, sifat dari alat ini antara lain adalah (a) harus dilatih mengenali sampel yang valid sebelum digunakan untuk aplikasi deteksi, (b) hasil deteksinya bersifat kualitatif dan (c) cepat. Untuk dapat mengingat, alat ini dilengkapi dengan AI yang sesuai dan telah dioptimasi. 

Secara umum, aplikasi *electronic nose* sangat luas, seperti di bidang Pertanian (yaitu, perlindungan tanaman, penyimpanan daging, makanan laut dan produk ikan, stres hewan, dan otentikasi herbal), bidang Makanan dan Kosmetik (yaitu, otentikasi halal, kontaminasi makanan, karakteristik bau, kualitas penilaian kontrol, dan aditif wewangian), dan bidang penyalahgunaan Narkoba (yaitu, tes cepat untuk ganja, tes cepat untuk prekursor obat, dan tes obat urin). Selain itu, *electronic nose* dapat diaplikasikan dalam bidang kesehatan, seperti deteksi TBC melalui nafas, deteksi pneumonia, terutama dalam bidang diagnostik cepat suatu penyakit. Dalam bidang medis, senyawa mudah menguap atau *volatile organic compound* (VOC) yang diemisikan melalui nafas pasien dan dalam berbagai kondisi terbukti dapat digunakan sebagai indikasi suatu penyakit tertentu. 

*Volatile organic compound* (VOC) yang diemisikan melalui nafas pasien telah diteliti sebagai marker biologis (*biomarker*) untuk diagnosis dari penyakit kanker paru dan penyakit inflamasi saluran nafas lainnya. Hal ini dikaitkan dengan proses/reaksi biokimia yang menghasilkan suatu pola/ *breath pattern* di level molekuler  yang berbeda antara pasien dengan penyakit paru/penyakit pernafasan dengan orang sehat. Penelitian oleh Chen *et al* pada tahun 2020, menunjukkan adanya perubahan karakteristik protein serta metabolit dan senyawa kimia dari pasien yang terinfeksi SARS-CoV 2 dibandingkan orang sehat. Hal ini dapat dianalisis dari VOC yang diemisikan melalui nafas pasien (*breath-borne* VOC *biomarkers*). Oleh karena itu, pada sistem ini terdapat kombinasi antara *electronic nose* yang bertugas untuk mendeteksi senyawa VOC pada rentang yang luas berupa data-data respon sensor dengan perangkat lunak AI yang bertugas membaca data-data respon sensor ke dalam pola-pola tertentu. Pada sistem GeNose C19-S ini, perangkat lunak AI inilah yang berfungsi sebagai pengklasifikasi pola-pola dari data respon sensor ke dalam label diagnostik berdasarkan data medis pasien yang dicurigai terinfeksi SARS-CoV 2 dan yang negatif SARs-CoV 2. 

Agar menghasilkan diagnosis (skrining) yang tepat maka perangkat lunak AI ini dilatih mengenali pola sampel nafas pasien berdasar label tertentu yang diberikan oleh tenaga medis. Untuk itu, perangkat lunak AI versi pertama ini telah dilatih untuk mengenali pola respon nafas pasien SARS-COV 2 dan pasien sehat dari data respon sensor *electronic nose* sehingga bisa digunakan untuk melakukan diagnosis apakah seseorang terpapar SARS-COV 2 atau tidak.

## 1.2 Informasi Produk 

GeNose, Gadjah Mada *Electronic Nose*, adalah alat pengindera elektronik cerdas yang terdiri atas tiga bagian utama yakni sistem larik sensor, sistem akuisisi data termasuk sistem aliran udara, dan sistem pengenal pola berbasis AI (*machine learning* dan *deep learning*). Seperti *electronic nose* pada umumnya, GeNose dikhususkan sebagai alat untuk mendeteksi, membedakan, dan mengklasifikasi sampel berdasarkan bau atau aromanya. GeNose menggunakan sepuluh sensor gas berbahan *metal oxide semiconductor* (MOS). Perangkat GeNose secara umum merupakan alat deteksi aroma dengan larik sensor gas untuk mendeteksi/mengukur aroma sampel, seperti fungsi dari spektroskop FTIR yang mendeteksi interaksi sampel dengan gelombang *infrared* (IR) menggunakan sensor IR. 

 

Khususnya, GeNose versi C19-S atau GeNose C19-S merupakan alat skrining infeksi Sars-Cov2 melalui hembusan nafas pasien Covid-19. GeNose C19-S merupakan perangkat GeNose yang dikombinasikan dengan *software* Ai yang terlatih untuk membedakan sampel nafas positif covid-19 atau negatif covid-19 dari data keluaran GeNose. Keunggulan GeNose C19-S adalah pengujian yang akurat, cepat, persiapan sederhana, analisis mudah, dan pengoperasian mudah.

## 1.3 Tujuan Pembuatan

Tujuan pembuatan GeNose C19-S adalah menyediakan alat skrining cepat, akurat dan non-invasif yang dikombinasikan dengan AI untuk mengklasifikasi yang dilanjutkan dengan prediksi pola data dari nafas subyek terkonfirmasi positif (berdasarkan hasil swab/PCR) dengan nafas subyek sebagai kontrol (terkonfirmasi negatif dari pengujian PCR).

## Release

### 1.3.2 (22 Februari 2021)

- Improve detection

### 1.3.1 (15 Februari 2021)

- Cek Lingkungan otomatis
- Improve print report
- Improve management template
- Bug fixed

### 1.3.0 (13 Februari 2021)

- Improve UI
- minor bug fixed

### 1.2.9 (10 Februari 2021)

- Improve Scan folder 
- Improve PUBLIC mode 
- Improve UI
- PUBLIC: Predict LOW with default
- minor bug fixed

### 1.2.4 (4 Februari 2021)

- Edit/Backup/Restore template
- minor bug fixed

### 1.2.0 (1 Februari 2021)

- Add public transportation mode (Experiment)
- Ai versi 103 build 0
- Qrcode template report

### 1.1.7 (30 Januari 2021)

- bug fixed some device not working for second analysis.

### 1.1.5 (26 Januari 2021)

- improve dialog form
- minor bug fixed
- rewrite version ai

### 1.1.4 (25 Januari 2021)

- add ID di dialog form
- improve cleaning tool
- improve template
- improve positive warning
- update prediction class
- improve UI
- minor bug fixed

### 1.1.0 (19 Januari 2021)

- add hospital mode
- optimize UI and menu
- many bug fixed

### 1.0.1+build.0 (15 Januari 2021)

- add hospital mode
- bug fixed current cycle if change device
- inform saved folder before analyze
- bug fixed configuration files.
- versioning ai in generated report
- add generated file report menu

### 1.0.0+build.10 (12 Januari 2021)

- bug fixed probability report

### 1.0.0+build.9 (9 Januari 2021)

- bug fixed report on screening mode

### 1.0.0+build.8 (7 Januari 2021)

- bug fix (report manual)

### 1.0.0+build.7 (7 Januari 2021)

- rev. terminate
- add admin (setting)

### 1.0.0+build.5 (6 Januari 2021)

- optimize source code

### 1.0.0+build.4 (5 Januari 2021)

- add report
- must install requirement.txt

### 1.0.0+build.3 (4 Januari 2021)

- bug fixed update patcher, **must fresh install**

### 1.0.0+build.2 (3 Januari 2021)

- add update patcher
- edit core (add percentage, edit HIGH prob.)
- add saved folder data collection

## 1.0.0+build.1

- release version (1 Januari 2021)

### 1.0.0-pre.1+build.4

- force close when not using en-US language format.

### 1.0.0-pre.1+build.7

- add view - shift signals
- add action Valve ON
- Update model Ai

### 1.0.0-pre.1+build.9

- update lv2. rfe+rf v.2.0

### 1.0.0-pre.1+build.10

- add version information

### 1.0.0-pre.1+build.11

- ver eref01





