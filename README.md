# Hotel-Booking-Demand
## __A. Latar Belakang Masalah__
Pembatalan pemesanan kamar hotel pada menit-menit terakhir meningkat dalam beberapa tahun terakhir. Banyak faktor yang dapat mempengaruhi pembatalan antara lain karena pelanggan sakit, perubahan jadwal meeting, perubahan jadwal liburan, kondisi cuaca yang buruk, dan berbagai macam faktor lainnya. Identifikasi yang dilakukan oleh [Chen dan Xie (2013)](https://drive.google.com/file/d/1yIRYqXT0pyztsBjNTc9Y68Y3g68KlSup/view?usp=sharing) dan [Chen, Schwartz, dan Vargas (2011)](https://daneshyari.com/article/preview/1010016.pdf), saat ini sebagian besar pelanggan melakukan pembatalan karena pelanggan ingin mendapatkan harga yang terbaik. Terkadang setelah melakukan pemesanan, pelanggan tetap melakukan pencarian lebih lanjut untuk product/service yang sama dengan yang sudah dipesan. Akibatnya, pelanggan akan melakukan pemesanan pada seluruh produk/jasa tersebut kemudian melakukan pembatalan pada saat-saat terakhir dan menyisakan satu yang terbaik. Hal ini merupakan dampak dari perkembangan teknologi digital yang memudahkan seseorang untuk melakukan pemesanan dan pembatalan kamar.

Karena mudahnya akses memesan dan membatalkan, hotel mengalami kerugian cukup signifikan. Sehingga, fenomena ini menjadi salah satu faktor yang digunakan oleh manajerial dalam membuat suatu kebijakan. Salah satunya adalah dengan menerapkan kebijakan yang cukup kaku. Selain itu, pihak manajerial juga menerapkan kebijakan seperti charge yang harus dibayarkan oleh pelanggan apabila melakukan pembatalan [(referensi)](https://pdfs.semanticscholar.org/f468/aaa140f7c1eb7aa37b9bca495ae76b82f654.pdf). Kebijakan yang diterapkan tersebut dapat membawa dampak negatif reputasi dan kinerja suatu hotel di masa mendatang karena pelanggan akan lebih memilih hotel yang dapat dilakukan pembatalan dengan kebijakan yang mudah dan tanpa terkena charge.

## __B. Goals__
Project ini menawarkan solusi atas masalah yang terjadi. Sebuah *machine learning* akand dibangun agar pemilik usaha khususnya pemilik hotel dapat melakukan prediksi apakah orang tersebut akan melakukan pembatalan ketika melakukan pemesanan kamar hotel atau tidak. Project ini akan menggunakan historical data yang sudah dikumpulkan dari beberapa pihak manajerial hotel yang ada di seluruh dunia ([sumber data](https://drive.google.com/file/d/12uB4vKhUUQj3brmQ4N7zfw8BwLYvfqzb/view?usp=sharing)). Sehingga, dengan adanya prediksi tersebut dapat diambil keputusan kebijakan oleh manajerial.

## __C. Limitasi Model__
Machine learning yang dibangun terbatas pada data yang diberikan. Oleh sebab itu, sangat memungkinkan terjadi perbedaan hasil dengan machine learning lain dengan model yang sama.

## __D. Model Algorithm__
- Logistic Regression, KNN, Decision Tree, Random Forest

## __E. Summary__
Berdasarkan hasil machine learning yang dibangun di atas, dapat disimpulkan antara lain:
1. Model machine learning yang digunakan yaitu Logistic Regression, Decision Tree, KNN, dan Random Forest
2. Evaluation metrics yang digunakan yaitu ROC AUC 
3. Hasil classification report dari model machine learning yang dibuat, dapat ditarik beberapa kesimpulan diantaranya :
  - model dapat meminimalkan tamu yang melakukan pembatalan namun dianggap tidak melakukan pembatalan (recall score). Dalam hal ini, model mampu memprediksi 94% tamu yang tidak melakukan pembatalan hotel dan 53% tamu yang melakukan pembatalan hotel. Maka terdapat 6% tamu yang melakukan pembatalan tapi dianggap tidak melakukan pembatalan
  - model dapat meminimalkan tamu yang tidak melakukan pembatalan namun dianggap melakukan pembatalan (precision score). Model mampu memprediksi 83% tamu yang melakukan pembatalan. 
