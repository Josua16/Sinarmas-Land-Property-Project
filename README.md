# Sinarmas-Land-Property-Project

# Tujuan Project
Melakukan Clustering untuk Credit Risk Segmentation dan Melakukan Analisis terhadap Credit Ris Segmentation

# Background
Pada project ini dilakukan credit risk segmentation mengunakan model clustering atau model unsupervised learning. Credit risk merupakan suatu risiko kerugian yang disebabkan oleh ketidak mampuan dari debitur atas kewajiban pembayaran utangnya baik utang pokok maupun bunganya ataupun keduanya. 

sebagai contoh Bank Sinarmas memberikan kredit perumahan kepada debitur perorangan.  Saat memberikan kredit tersebut, bank memiliki risiko bahwa sebagian atau seluruh debitur perorangan tersebut akan gagal membayar bunga ataupun pokok kredit yang diterimanya. Risiko kredit timbul dari adanya kemungkinan bahwa kredit yang diberikan oleh bank, atau obligasi yang dibeli, tidak dapat dibayarkan kembali. Risiko kredit juga timbul dari tidak dipenuhinya berbagai bentuk kewajiban pihak lain kepada bank, seperti kegagalan memenuhi kewajiban pembayaran dalam kontrak derivatif. Untuk sebagian bank, risiko kredit merupakan risiko terbesar yang dihadapi. Pada umumnya, marjin yang diperhitungkan untuk mengantisipasi risiko kredit hanyalah merupakan bagian kecil dari total kredit yang diberikan bank dan oleh karenanya kerugian pada kredit dapat menghancurkan modal bank dalam waktu singkat.

Bank menggunakan sejumlah teknik dan kebijakan dalam mengelola risiko kredit untuk meminimalkan kemungkinan terjadinya atau dampak dari kerugian kredit (dikenal dengan mitigasi risiko kredit). Teknik dan kebijakan tersebut adalah:
1. model pemeringkatan (grading model) untuk kredit perorangan
2. manajemen portofolio kredit
3. sekuritisasi
4. agunan
5. pengawasan arus kas
6. manajemen pemulihan (recovery management).

Pada project ini akan dilakukan pembuatan model credit risk segementation untuk memberikan grade atau label kepada customer sehingga pihak perusahan dapat menolak permintaan kredit customer untuk customer yang diberikan label bad risk. Dengan demikian, pihak perusahaan tidak mengalami kerugian atau dapat mengurangi jumlah customer yang tidak dapat membayar cicilan atau tagihan kredit. Dengan kata lain, Kredit yang diberikan bank setiap saat dapat menjadi bermasalah, namun kemungkinannya menjadi kecil jika bank menerapkan kebijakan pemberian kredit yang sehat.  Langkah pertama adalah menciptakan model pemeringkatan kredit sebagai sarana untuk menetapkan kemungkinan terjadinya gagal bayar (default).  Dalam hal ini bank melakukan kalibrasi risiko yang pada gilirannya akan memungkinkan bank untuk menetapkan suatu probabilitas tertentu untuk setiap kejadian yang tidak diinginkan (yang dikenal dengan probability of default/PD).  Cara ini memungkinkan bank untuk memastikan bahwa portofolio kredit bank tidak terkonsentrasi pada kredit berkualitas buruk yang memiliki kemungkinan gagal bayar yang tinggi.

# Library
library yang digunakan dalam project ini, yaitu:
1. pandas versi 1.4.2
2. numpy versi 1.21.5
3. scikit learn versi 1.1.2
4. feature engine packages versi 1.4.1

# Feature Engineering
Pada project dilakukan beberapa feature engineering seperti:
1. Feature scalling mengunakan metode minmax scaller
2. Feature encoding mengunakan metode ordinal encoder
3. Data Visualization mengunakan Matplotlib

# Model
kmeans_new = KMeans(n_clusters=2, init='random', n_init=1, random_state=42)
