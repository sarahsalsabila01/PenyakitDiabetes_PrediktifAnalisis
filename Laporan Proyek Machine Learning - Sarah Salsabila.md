# Laporan Proyek Machine Learning - Sarah Salsabila
 
## domain Proyek
Pada tugas Prediktif Analisis ini saya menggunakan domain Kesehatan .
Untuk lebih spesifik saya menggunakan domain Kesehatan mengenai Diabetes pada wanita .
![Diabetes](https://www.domino206lounge.com/wp-content/uploads/2020/03/403-1210x642.jpg)
-   Diabetes merupakan penyakit gangguan metabolik yang ditandai dengan kenaikan gula darah akibat penurunan sekresi insulin oleh sel beta pankreas atau penurunan fungsi insulin .
    Berdasarkan Kementrian Kesehatan ,Indonesia memilki jumlah pengidap diabetes sebanyak 10 juta atau 6,9% . Menurut data tahun 2015 , Kasus diabetes yang terdeteksi di dunia berdasarkan gender pada pria sebanyak 215,2 juta dan pada wanita sebanyak 199,5 juta . 
    Berdasarkan IDF ATLAS edisi ke-7 pada tahun 2015 , Indonesia menempati Posisi ke -7 sebagai 10 negara dengan jumlah orang dewasa yang terkena diabetes . 
    Berdasarkan 10 penyebab kematian utama dengan sistem sample registrasion Indonesia pada tahun 2014 , diabetes menempati posisi ke -4 sebagai penyebab kematian terbanyak dengan persentase 6,7%.
-   Alasan dibalik pemilihan domain adalah karena berdasarkan penelitian, Diabetes menjadi penyebab penyakit jantung yang sering ditemukan pada wanita daripada pria .
    Berdasarkan Hasil Riset Kesehatan Dasar pada tahun 2013 , proporsi diabetes pada wanita cenderung lebih tinggi yaitu (7,7%) dibandingkan dengan pria yang hanya (5,6%) . Selanjutnya berdasarkan Riskesdas 2013 dari sebanyak 6,9% orang yang memiliki diabetes , 69,5% diantaranya tidak terdiagnosis . 
    Diabetes merupakan penyebab utama kematian no.9 pada wanita ditingkat global,menyebabkan 2,1 juta kematian setiap tahunnya. Saat ini terdapat lebih dari 199 juta wanita hidup dengan diabetes dan diproyeksikan akan meningkat menjadi 313 juta pada tahun 2040. Dan menurut riset , Wanita yang mengidap Diabetes memiliki potensi kesulitan yang lebih besar pada proses kehamilan serta wanita yang memiliki diabetes dapat berdampak buruk terhadap kehamilannya . 
    Oleh sebab itu Masalah ini harus segera ditindak guna membantu mengurangi tingkat diabetes pada wanita di Indonesia .
-   Untuk Informasi lebih lanjut mengenai Diabetes pada wanita , berikut terdapat beberapa Jurnal yang relevan serta Riset mengenai Diabetes pada wanita .
    - [Wanita dan Diabetes oleh Kementerian Kesehatan Republik Indonesia](http://p2ptm.kemkes.go.id/uploads/VHcrbkVobjRzUDN3UCs4eUJ0dVBndz09/2017/11/Dr_HM_Subuh_MPPM_Woman_Diabetes.pdf)
    - [GAMBARAN KARAKTERISTIK DAN FAKTOR-FAKTOR YANG BERHUBUNGAN DENGAN KEJADIAN DIABETES MELITUS TIPE 2PADA WANITA](https://ejournal3.undip.ac.id/index.php/jkm/article/view/11772/11427)
    - [ANALISIS FAKTOR risiko PENYEBAB TERJADINYADIABETESMELITUS TIPE 2 PADA WANITA USIA PRODUKTIFDIPUSKESMASWAWONASA](https://ejournal.unsrat.ac.id/index.php/ebiomedik/article/view/4554/4082)
 
## Business Understanding
Berdasarkan pemaparan pada domain proyek mengenai Diabetes pada wanita . Sebagai wanita saya memiliki keinginan untuk mengenal lebih dalam mengenai diabetes, Dengan tujuan untuk membantu wanita agar dapat melakukan pencegahan terhadap penyakit Diabetes , seperti sebuah pepatah yang mengatakan bahwa
> Tak Kenal maka Tak Sayang 
> -unknown
 
Juga saya pernah mendengar istilah ,
 
> Dalam menghadapi musuh , tak ada yang lebih mengena daripada senjata kasih sayang
> -Cut Nyak Dien
 
 
Dan yang terakhir 
 
![Quotes](https://jagokata.com/images/upload/margaret-thatcher-butuh-pengorbanan-lebih-dalam-mengenal-musuh-karena.jpg)
 
Istilah serta pepatah tersebut mengajarkan kita untuk melakukan sebuah pengorbanan. Pada kasus ini, dengan cara mengenal lebih dalam apa itu diabetes , apa saja penyebab diabetes, bagaimana ciri - ciri diabetes .
Sehingga kita dapat melakukan upaya pencegahan sebagai bukti bahwa kita menyayangi diri kita sendiri dan agar terhindar dari penyakit diabetes, berdasarkan faktor - faktor diabetes nantinya .
 
### Problem Statements
Berdasarkan fakta bahwa Diabetes merupakan salah satu penyebab kematian tertinggi dan banyaknya kasus di mana para pengidap diabetes tidak terdeteksi sebelumnya .Serta berdasarkan Riset di mana Wanita memiliki potensi yang lebih tinggi terkena penyakit Diabetes dibandingkan pria. Membuat saya berpikir ,
 
    1. Apa saja Faktor yang berpengaruh terhadap penyakit Diabetes?
    2. Faktor mana yang menyebabkan kemungkinan tertinggi seseorang memiliki penyakit Diabetes ?
    3. Apa saja ciri - ciri seseorang yang mengidap penyakit Diabetes ?
    4. Apakah ada suatu cara untuk mengetahui seseorang terkena Diabetes atau tidak ?
    
### Goals
Untuk  menjawab pertanyaan tersebut, saya mencoba membuat predictive analisis dengan tujuan atau goals sebagai berikut:
- Mengetahui faktor apa saja yang memiliki korelasi dengan pengidap Diabetes
- Mengetahui fitur atau faktor yang memiliki korelasi paling tinggi dengan Pasien yang mengidap Diabetes.
- Mengetahui ciri - ciri seseorang  yang mengidap penyakit diabates 
- Membuat model machine learning yang dapat memprediksi seseorang apakah mengidap diabetes dengan seakurat mungkin berdasarkan fitur-fitur yang ada.
 
### Solution statements
Untuk mencapai tujuan serta dapat menyelesaikan permasalahan pada problem statement , yaitu melakukan prediksi untuk mengetahui seorang wanita mengidap Diabetes atau tidak . di mana ini merupakan permasalahan klasifikasi . 
Saya menggunakan beberapa metode ,Diantaranya 
1. Untuk mengetahui Faktor yang berpengaruh pada seorang pasien Diabetes , saya akan menggunakan Diagram Persebaran Data . di mana dari diagram ini kita dapat memperoleh informasi menegenai persebaran data pada setiap variabel .
2. Selanjutnya melakukan Correlation Matrix pada fitur numerik, dari correlation matrix ini kita dapat melihat korelasi setiap variable yang ditampilkan dengan perbedaan gradien warna . di mana makin dekat nilai dengan angka 1 maka variabel tersebut memiliki korelasi yang tinggi , sebaliknya jika variabel menujukan angka makin dekat dengan 0 maka variabel tersebut memiliki korelasi yang rendah dengan variable tertentu
3. Melakukan perbandingan dalam membaca data dengan menggunakan beberapa diagram.
 
    - Diagram Bar , untuk melihat seperti apakah korelasi antara "Hasil" dengan setiap Variabel.
    - Diagram Box , untuk mendapatkan informasi lebih jelas terkait rentang korelasi antara "Hasil" dengan setiap variabel.
    - Melakukan pengurutan nilai variable dengan menggunakan fungsi data.corr , serta nilai akan diururtkan secara ascending false
    - Melakukan perbandingan korelasi setiap variable berdasarkan nilai rata-rata variabel tersebut.
    -  Untuk mengembangkan model machine learning, di sini saya menggunakan 4 algoritma.
      1.  K-Nearest Neighbor
      2.  Random Forest
      3.  Boosting Algorithm
      4.  Support Vector Machine
 
 
di mana Pada urutan 1-3 nanti, akan dilakukan evaluasi performa masing-masing algoritma dan menentukan algoritma mana yang dapat memberikan prediksi terbaik (nilai paling mendekati).
 
Pada algoritma ke -4 ,Saya melakukan evaluasi dengan menggunakan sistem nilai akurasi , untuk  memastikan apakah model SVM dapat menghasilkan nilai akurasi yang tinggi ketika memprediksi dataset .
 
## Data Understanding
Data yang digunakan untuk proyek ini adalah sebuah data yang berasal dari National Institute of Diabetes dan Digestive dan Kidney Diseases . di mana data berisikan pasien wanita pima India yang memiliki diabetes dan tidak .
Untuk dataset, saya mengambil dari Kaggle , berikut link Dataset 
> [Pima Indians Diabetes Database](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
 
### Data Loading
Untuk mempermudah dalam proses memahami data , saya melakukan proses loading data terlebih dahulu . 
1. Melakukan mounted drive ( untuk menghubungkan google colab dengan drive , karena saya menyimpan dataset pada file drive )
2. Melakukan impor library yang dibutuhkan . Untuk membaca file dataset pima Indian, saya mengimpor library pandas . karena dataset dengan nama diabetes.csv akan dibaca menggunakan fungsi read_csv() yang ada pada library pandas .
 `diabetes = pd.read_csv('/content/drive/MyDrive/Colab Notebooks/dataset/diabetes.csv')`
 
3. Memanggil dataframe dengan fungsi head() untuk membaca tabel data ,default dari fungsi head() akan menampilkan 5 baris data pada saat fungsi dieksekusi (di sini saya menamai dataframe dengan diabetes)
 `diabetes.head()`

    ![Diabetes read  &head](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/Membaca%26melihat%20Diabetes.jpg)
 
4. Selajutnya saya melihat nama kolom dan berupaya untuk mengubah nama dari beberapa kolom agar dapat memudahkan saya ketika mengolah data . untuk mengganti nama kolom dapat menggunakan fungsi rename().
 `diabetes = diabetes.rename(columns={'Pregnancies':'Kehamilan','Age':'Umur','Outcome':'Hasil','DiabetesPedigreeFunction':'PediFunction'})
diabetes.head()`
 
    ![mengubah kolom](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/2.Gantikolom.jpg)
 
5. Selanjutnya mencari informasi tentang dataset mengenai jumlah baris data,kolom data ,serta tipe data . saya menggunakan fungsi shape dan info()
6. Berikutnya memeriksa dataset untuk melihat apakah data memiliki nilai duplikat dengan menggunakan fungsi `diabetes.duplicated().sum()`. setelah itu melihat apakah data memiliki nilai null dengan fungsi isnull() . terakhir kita dapat mengetahui informasi lebih lanjut mengenai data dengan menggunakan fungsi describe()
 
    ![shape , info dan duplikat](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/3.Jumlahdata%2Cduplikat%2Cinfo.jpg)
 
    ![isnull dan describe](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/4.Isnulldandescribe.jpg)
 
Berdasarkan langkah - langkah di atas dapat diambil Informasi sebagai Berikut :
- Dataset memiliki 9 buah variabel .diantaranya, 
    - Pregnancies(Kehamilan) : Untuk menghitung berapa kali pasien pernah mengandung.
    - Glucose(glukosa) : Konsentrasi glukosa dalam rentang waktu 2 jam berdasarkan tes toleransi oral glukosa.
    - Blood Pressure(Tekanan Darah) : Tekanan darah diastolik (mm Hg).
    - Skin Thickness (Ketebalan Kulit) : Ketebalan kulit bagian trisep (mm).
    - Insulin : Tingkat insulin 2 jam insulin serum dalam satuan mu U/ml).
    - BMI : indeks massa tubuh (kg/m^2).
    - DiabetesPedigreeFunction : Indikator riwayat diabetes dalam keluarga
    - Age(Umur) : Usia wanita suku Indian pima (tahun).
    - Outcome(Hasil) : Kategori ,di mana 1 mempresentasikan nilai true (diabetes) dan 0 yang mempresentasikan nilai false (tidak memiliki diabetes).
- Dataset memiliki 768 baris dengan 9 Kolom.
- Terdapat 9 variabel , di mana 2 dari 9 variabel memiliki tipe float (BMI dan PediFunction) sedangkan sisanya memiliki tipe int.
- Tidak ada nilai yang berduplikat.
- Tidak ada nilai yang null.
- Jumlah tertinggi dari Kehamilan adalah sebanyak 17 kali , dan yang terendah adalah 0 ( tidak pernah mengalami kehamilan).
- glukosa memiliki nilai terendah 0 dengan nilai maksimal 199.
- Insulin memiliki nilai terendah 0 dengan nilai maksimal 846.
- Ketebalan Kulit dan BMI keduanya memiliki nilai terendah 0 .
- Tekanan darah memiliki nilai terendah 0 .
- Jangkauan umur yang ada pada pasien wanita adalah 21 tahun sampai 81 tahun.
 
Berdasarkan informasi di atas , terdapat beberapa informasi yang janggal . yaitu nilai terendah pada beberapa variabel seperti (BMI,Blood Pressure,Insulin ,Skin thickness). 
Nilai 0 pada beberapa variabel tersebut tidak memungkinkan . karena ,
1. Jika BMI seseorang 0 . maka dia tidak memiliki massa sama sekali .
2. Apabila tekanan darah 0 , aliran darah dalam tubuh tidak akan mengalir .
3. Tidak mungkin insulin dan ketebalan kulit memiliki nilai 0 .
Informasi janggal tersebut akan dipelajari lebih lanjut pada tahap exploratory data . guna mengambil tindakan apakah data akan di drop atau data dapat diganti dengan nilai yang lain .

### Eksploratory Data
Pada tahap ini saya mencoba mencari tahu apakah tedapat Outliers pada data, variabel mana saja yang memiliki korelasi antar variable , melihat persebaran data pada tiap variable  serta jenis variabel apa saja yang ada pada dataset .
 
Sebelum melakukan analisis korelasi pada data , saya berusaha melihat persebaran data dan outliers pada data dengan menggunakan plot atau grafik.
 
![outliers](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/5.outliers.jpg)
    "Outliers pada variabel glukosa dan BloodPressure"
 
Setelah melihat grafik outliers secara keseluruhan . saya mendapatkan bahwa nilai 0 pada beberapa variable menjadi sebuah outliers pada dataset. Oleh sebab itu saya memilih untuk mengubah nilai 0 pada beberapa data variable dengan menggunakan nilai mean . sebab jika dilakukan drop secara menyeluruh maka dataset akan memiliki jumlah data yang terlalu sedikit (di bawah 500).
![mean](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/6.ganti%20mean.jpg)
![tanpa 0](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/7.tanpa0.jpg)
 
setelah melakukan perubahan pada nilai 0 ,saya melihat kembali persebaran data pada outliers. lalu memilih untuk melakukan drop pada outliers yang berada di q1 dan q3 .
 
![drop](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/8.dropoutliers.jpg)
 
Berdasarkan hasil pengamatan pada dataset , diabetes ini memiliki 8 numerical features dan 1 categorical features , yaitu "hasil" atau "outcome".dikarenakan variable hasil , memiliki nilai 1 atau 0 . di mana biner tersebut mempresentasikan apakah pasien wanita tersebut positif diabetes(1) atau negatif (0).
Selanjutnya untuk melihat persebaran data pada categorical feature ,saya menggunakan diagram sebagai visualisasi untuk melihat keseluruhan sampling data pada categorical features .
 
![Categorical](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/9.kategorical%20feature.jpg)
 
Untuk numerical features saya menggunakan correlation matrix dan juga fungsi paiplot untuk melihat apakah ada korelasi antar variable 
 
![correlation matrix](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/10.correlation.jpg)
 
![pairplot](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/11.pairplot.jpg)
 
Dari hasil eksekusi tersebut di dapatkan Informasi sebagai berikut :
- Dikarenakan drop outliers , dataset yang sekarang sudah tidak memiliki nilai 0 , kecuali pada variable kehamilan (karena 0 pada variabel ini dapat mempresentasikan tidak pernah mengandung). 
- Jumlah keseluruhan data menjadi berkurang dari 768 baris menjadi 619 baris .
- Pada categorical features, Jumlah keseluruhan sample adalah 619 . Jumlah sample dengan nilai 0 (false) terdapat 426 dan nilai 1(true) terdapat 193 .
Berdasarkan hal ini dapat disimpulkan bahwa ,rasio perbandingan data adalah 60:30 dan data dapat dinyatakan kurang seimbang.
- Pada correlation matriks di dapatkan informasi seperti berikut :
    - Kehamilan dan Umur memiliki korelasi yang cukup berpengaruh.
    - Ketebalan kulit dan BMI juga memiliki korelasi.
    - glukosa memiliki korelasi dengan pasien wanita yang memiliki diabetes.
- Lalu pada paiplot didapatkan informasi sebagai berikut :
    - Kehamilan dan Umur memiliki korelasi yang tinggi
    - glukosa dan insulin memiliki korelasi.
    - Umur dan Blood Pressure(tekanan darah) memiliki korelasi
    - SkinThickness dan BMI memiliki korelasi

Guna mengetahui variable apa saja yang memiliki potensi paling tinggi berkorelasi dengan diabetes ,saya melakukan perbandingan menggunakan beberapa diagram :
    1. Diagram Bar ,guna melihat korelasi antara "Hasil" dengan setiap Variabel.
    ![bardiagram](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/12.hamildiabnetes.jpg)
    2. Diagram Box ,guna mendapatkan informasi lebih jelas terkait rentang nilai korelasi antara "Hasil" dengan setiap variabel.
    ![boxdiagram](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/13.hamil%20diabetes%20box.jpg)
    3. Melakukan pengurutan nilai variable dengan menggunakan fungsi data.corr , serta nilai akan diururtkan secara ascending false . (untuk mengetahui nilai mana yang memiliki tingkat korelasi tertinggi sampai ke terendah)
    4. Melakukan perbandingan korelasi setiap variable berdasarkan nilai rata-rata variabel tersebut.
     ![false dan mean](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/korelasi.jpg)
    
    
Dari proses perbandingan tersebut didapatkan informasi sebagai berikut :
- Semua Variabel memiliki korelasi terhadap kemungkinan mengidap diabetes .
- Pasien diabetes biasa ditemui pada pasien yang memiliki glukosa di atas 120
- Kelebihan berat badan juga memiliki pengaruh cukup besar dalam kemungkinan memiliki diabetes , wanita yang memiliki BMI lebih dari 30 memiliki kemungkinan yang besar terkena diabetes (seseorang yang mengalami obesitas memiliki peluang lebih besar terkena diabetes).
- Seseorang yang memiliki umur lebih dari 28 tahun memiliki kemungkinan terkena diabetes yang tinggi .
- Pasien yang memiliki diabetes dapat mencapai insulin dengan level lebih dari 125 bahkan lebih dari 150 .
- glukosa menjadi salah satu penyebab diabetes tertinggi . dilihat dari hasil persentase dan penyampaian diagram di atas .
- Pasien yang telah beberapa kali Hamil memiliki risiko diabetes yang cukup tinggi .
 
Jika di ukur berdasarkan Peringkat ,Variabel penyebab diabetes pada wanita adalah :
1. Glucose
2. BMI
3. Umur
4. Kehamilan
 
 
## Data Preparation
Pada tahap ini ,saya melakukan pembagian data menjadi data training dan data tes .Untuk membagi data saya menggunakan train_test_split dari sklearn library . Data saya bagi dengan rasio 80:20, sehingga test_size bernilai 0.2 .
Setelah itu ,saya melakukan pemeriksaan jumlah sample pada setiap data menggunakan fungsi len ,untuk memastikan apakah data sudah terbagi dengan benar.
 
 ![bagidata](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/14.bagi%20data.jpg)
 
Tahap selanjutnya saya melakukan standardisasi ,di mana proses ini dapat membantu membuat fitur data menjadi bentuk yang lebih mudah diolah oleh algoritma .
 
 ![standardisasi](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/15.standardisasi%20latih.jpg)
 
Guna mengindari kebocoran data pada data uji ,standardisasi yang dilakukan pada tahap ini hanya dilakukan pada data uji .Untuk data tes akan dilakukan nanti pada tahap evaluasi.
 
 ![meanstd](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/16.mean0st1.jpg)
 
Proses standarscaler dapat membuat mean menjadi 0 dan Standar deviasi menjadi 1.
 
 
## Modeling
Untuk mencapai salah satu tujuan yaitu mencari tahu model mana yang dapat memberikan Hasil prediksi terbaik ,di sini saya menggunakan 4 buah algoritma .
1. K-Nearest Neighbor
2. Random Forest
3. Boosting Algorithm
4. Support Vector Machine
 
di mana tahap 1-3 nanti , saya akan mengevaluasi performa masing-masing algoritma dan menentukan algoritma mana yang dapat memberikan hasil prediksi terbaik .Dengan pendekatan model yang memiliki nilai paling mendekati dengan nilai asli .
 
Pada algoritma ke -4 ,saya melakukan evaluasi dengan menggunakan sistem nilai akurasi ,untuk  memastikan apakah model SVM dapat menghasilkan nilai akurasi yang tinggi ketika memprediksi dataset.
 
Hal yang pertama kali saya lakukan pada tahap ini adalah membuat dataframe untuk analisis model 
 
 ![dataframe](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/18.frame%20model.jpg)
 
Selanjutnya membuat kode guna melakukan pelatihan dengan KNN.
- Impor library yang dibutuhkan
- Saya menggunakan k = 10 tetangga dan metric Euclidean untuk mengukur jarak antara titik.
- Data yang di pakai sekarang adalah data latih .
 
 ![knn](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/19.knn.jpg)
 
Berikutnya membuat Kode untuk pelatihan dengan Random Forest.
- Melakukan impor library yang dibutuhkan
- Model prediksi menggunakan max_depth = 16 , random_state = 55 , estimasi 50 .
 
 ![rf](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/20.randomforest.jpg)
 
Berikutnya membuat kode untuk model Prediksi Boosting.
 
 ![boosting](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/21.boosting.jpg)
 
## Evaluation
Pada tahap ini ,saya melakukan scaling pada data uji ,seperti yang diberitahukan pada saat standardisasi , bahwa data uji akan dilakukan standardisasi pada tahap evaluasi guna menghindari kebocoran data pada data latih .
 
 ![standardisasi tes](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/22.standardisasi%20test.jpg)
 
Melakukan evaluasi model dengan metrik MSE
 
 ![eval MSE](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/23.evalusi.jpg)
 
  ![Mean eval](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/24.prediksi%20mean.jpg)

Evaluasi dengan model 1 - 3 telah selesai dieksekusi.

Selanjutnya , Saya akan coba menggunakan SVM untuk melihat skor akurasi pada prediksi berdasarkan model SVM .
 
1. Saya membuat dataframe baru ( memiliki data yang sama seperti dataset diabetes ) alasannya,guna menghindari adanya kesalahan data yang dapat memengaruhi data utama.
2. Membuat deklarasi S dan r di mana nilai variabel serupa dengan deklarasi X dan y pada data diabetes .
3. Lalu melakukan standardisasi pada data uji dan mengubahnya ke dalam bentuk array menggunakan fungsi fit.transform.
4. Hasil dari standardisasi ,saya deklarasikan menjadi P.
5. Membagi dataset menjadi training dan tes dengan parameter yang sama seperti dataset diabetes yaitu test_size 0.2 dan random_state 2
 
 ![svm1](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/svm%201.jpg)
 
 ![svm2](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/svm2.jpg)
 
 ![svm3](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/svm%203.jpg)
 
 ![svmlatih](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/svm%20train.jpg)
 
  ![svmtest](https://raw.githubusercontent.com/sarahsalsabila01/Image_S1MLTerapan/main/svm%20test.jpg)
 
Setelah seluruh prediksi dieksekusi didapatkan kesimpulan informasi sebagai berikut :
- Untuk diagram bar mse terlihat model yang memiliki error terkecil untuk data tes adalah model boosting, tetapi saat dilakukan predict terlihat bahwa prediksi KNN lebih mendekati nilai asli . 
ketidak sinkronan ini cukup dapat diterima, dikarenakan dataset yang dipakai memiliki sampel kurang besar. sehingga mengalami kemungkinan ketidak sinkronan seperti ini. Akan tetapi guna beruapaya mencari model yang memiliki prediksi terbaik. di sini saya mencoba menggunakan parameter lain yaitu dengan menggunakan perhitungan rata - rata ketiga nilai mse pada data tes .Di dapatkan hasil rata-rata 0.00015632166666666668 . di mana hasil rata-rata mendekati nilai mse pada model KNN yaitu 0.000157419 . 
 
Oleh sebab itu ,ditarik kesimpulan bahwa model KNN adalah solusi terbaik guna memprediksi dataset diabetes di antara kedua model lainnya.
 
- Untuk model SVM ,dari hasil eksekusi didapatkan nilai akurasi pada data latih sebesar 0.79 .dan saat data tes melakukan predict didapatkan nilai akurasi 0.8 . Dari sini , selain KNN menurut saya SVM  dapat digunakan sebagai salah satu metode guna memprediksi diabetes , karena memiliki nilai akurasi yang cukup tinggi

Sekian Laporan saya mengenai proyek kali ini . berdasarkan proses selama pengerjaan ke - 4 pertanyaan pada problem statement telah terjawab .
 
Notebook dapat diakses pada link berikut 
[Diabetes_MLT_Sarah](https://colab.research.google.com/drive/1mJ3nx2JBSInlpZuae4z8q5nx2op1Px7Z?usp=sharing)

Github refrensi gambar dapat diakses pada link berikut
[githubimage](https://github.com/sarahsalsabila01/Image_S1MLTerapan)