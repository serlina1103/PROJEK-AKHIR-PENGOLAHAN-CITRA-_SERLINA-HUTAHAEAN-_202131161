
#Deteksi Buah 
Beberapa teori dan teknik yang berkaitan dengan perubahan citra dengan objek buah. Berikut adalah beberapa teori yang relevan:

1).Segmentasi Citra: Teori segmentasi citra digunakan untuk memisahkan objek buah dari latar belakangnya. Tujuannya adalah untuk mengidentifikasi dan memisahkan wilayah yang berbeda dalam citra, termasuk objek buah. Metode segmentasi yang umum digunakan meliputi segmentasi berbasis warna, segmentasi berbasis tekstur, dan segmentasi berbasis tepi.Teori segmentasi citra berkaitan dengan teknik untuk memisahkan objek dari latar belakang dalam citra. Dalam pengolahan citra buah, segmentasi citra penting untuk mengidentifikasi dan memisahkan objek buah dari latar belakangnya. Terdapat beberapa metode segmentasi yang sering digunakan:

Segmentasi Berbasis Warna: Metode ini memanfaatkan perbedaan warna antara objek buah dan latar belakang. Dalam hal ini, model warna digunakan untuk menentukan rentang nilai warna yang mewakili objek buah. Misalnya, jika buah yang akan di-segmentasi adalah apel merah, maka rentang warna merah dapat digunakan untuk mengisolasi buah apel dari latar belakangnya.

Segmentasi Berbasis Tekstur: Metode ini mengandalkan perbedaan pola tekstur antara objek buah dan latar belakang. Karakteristik tekstur seperti kehalusan atau kasar dapat digunakan untuk memisahkan objek buah. Misalnya, kulit jeruk memiliki pola tekstur yang khas, yang dapat dibedakan dari latar belakang lainnya.

Segmentasi Berbasis Tepi: Metode ini berfokus pada deteksi tepi atau kontur objek buah. Tepi objek buah cenderung memiliki perbedaan intensitas yang signifikan dengan latar belakang. Dengan mendeteksi tepi, objek buah dapat dipisahkan dari latar belakang dengan memperhatikan perbedaan intensitas.

2).Ekstraksi Fitur: Ekstraksi fitur adalah proses untuk mengidentifikasi fitur penting atau karakteristik dari objek buah dalam citra. Fitur-fitur ini dapat mencakup bentuk, tekstur, warna, atau kombinasi dari semuanya. Dalam pengolahan citra, metode seperti transformasi Fourier, deskriptor tekstur (misalnya GLCM atau LBP), dan deteksi tepi (misalnya Canny atau Sobel) dapat digunakan untuk ekstraksi fitur objek buah.
 Teori ekstraksi fitur terkait dengan identifikasi fitur penting atau karakteristik dari objek buah dalam citra. Terdapat berbagai metode yang digunakan untuk ekstraksi fitur dalam pengolahan citra buah:

Transformasi Fourier: Metode ini mentransformasikan citra buah dari domain spasial ke domain frekuensi. Dalam domain frekuensi, fitur-fitur penting seperti frekuensi dominan atau energi spektral dapat diekstraksi. Misalnya, karakteristik tekstur seperti frekuensi spasial tinggi dapat menunjukkan keberadaan detail atau pola halus pada kulit buah.

Deskriptor Tekstur: Metode deskriptor tekstur, seperti Gray-Level Co-occurrence Matrix (GLCM) atau Local Binary Patterns (LBP), digunakan untuk menggambarkan pola tekstur dalam citra buah. Deskriptor GLCM menghitung distribusi relatif dari pasangan intensitas piksel dalam citra, sementara LBP menggambarkan pola biner lokal pada citra.

Deteksi Tepi: Metode deteksi tepi seperti operator Canny atau Sobel digunakan untuk menemukan tepi objek buah. Tepi menandakan perubahan tajam dalam intensitas citra dan sering menjadi fitur penting dalam pengolahan citra buah.
3).Klasifikasi Objek: Setelah fitur-fitur objek buah diekstraksi, langkah selanjutnya adalah mengklasifikasikan objek berdasarkan fitur-fitur tersebut. Terdapat berbagai metode klasifikasi yang dapat digunakan, termasuk klasifikasi berbasis aturan, klasifikasi berbasis statistik, dan klasifikasi berbasis pembelajaran mesin seperti SVM (Support Vector Machines), Naive Bayes, atau Jaringan Saraf Tiruan (Neural Networks).
Teori klasifikasi objek berkaitan dengan pengelompokan atau pengklasifikasian objek berdasarkan fitur-fitur yang telah diekstraksi sebelumnya. Pada pengolahan citra buah, tujuannya adalah mengklasifikasikan jenis buah berdasarkan fitur-fitur tersebut. Terdapat berbagai metode klasifikasi yang dapat digunakan:

Klasifikasi Berbasis Aturan: Metode ini menggunakan aturan atau kriteria tertentu untuk mengklasifikasikan objek buah. Misalnya, jika ukuran buah berada dalam rentang tertentu, maka dapat diklasifikasikan sebagai buah jenis A, sedangkan jika berada dalam rentang yang berbeda, maka diklasifikasikan sebagai buah jenis B.

Klasifikasi Berbasis Statistik: Metode ini menggunakan probabilitas dan statistik untuk mengklasifikasikan objek buah. Misalnya, dengan menggunakan pendekatan Naive Bayes, diperhitungkan probabilitas fitur-fitur yang diamati dalam citra untuk memprediksi jenis buah yang mungkin.

Klasifikasi Berbasis Pembelajaran Mesin: Metode ini melibatkan penggunaan algoritma pembelajaran mesin seperti Support Vector Machines (SVM) atau Neural Networks (Jaringan Saraf Tiruan). Dalam pendekatan ini, model pembelajaran mesin dilatih menggunakan data pelatihan yang berisi contoh-contoh citra buah dan label yang sesuai. Model ini kemudian digunakan untuk mengklasifikasikan jenis buah berdasarkan fitur-fitur yang diamati pada citra

4).Pengenalan Pola: Teori pengenalan pola dapat digunakan untuk mengenali atau mengklasifikasikan jenis buah berdasarkan citra yang diberikan. Metode seperti pengenalan pola berbasis statistik atau pengenalan pola berbasis pembelajaran mesin dapat digunakan untuk membangun model yang dapat mengenali dan mengklasifikasikan jenis buah.
pengolahan citra buah dapat melibatkan kombinasi dari berbagai teori dan teknik di atas, tergantung pada kompleksitas tugas dan kebutuhan aplikasi tertentu.
Teori pengenalan pola berkaitan dengan pengenalan atau klasifikasi objek berdasarkan pola-pola yang terdapat dalam citra. Pada pengolahan citra buah, tujuannya adalah mengenali dan mengklasifikasikan jenis buah berdasarkan citra yang diberikan. Terdapat berbagai metode pengenalan pola yang dapat digunakan:

Pengenalan Pola Berbasis Statistik: Metode ini menggunakan statistik dan probabilitas untuk mengenali pola dalam citra buah. Misalnya, dengan menggunakan analisis komponen utama (Principal Component Analysis, PCA), dimensi fitur-fitur yang diamati dalam citra dapat direduksi untuk mengidentifikasi pola yang signifikan dalam data.

Pengenalan Pola Berbasis Pembelajaran Mesin: Metode ini melibatkan penggunaan algoritma pembelajaran mesin untuk membangun model pengenalan pola. Contohnya adalah Jaringan Saraf Tiruan (Neural Networks) yang dapat dilatih menggunakan data pelatihan untuk mengenali pola pada citra buah dan mengklasifikasikannya ke dalam jenis yang tepat.

Pengenalan Pola Berbasis Jaringan Syaraf Tiruan (Convolutional Neural Networks, CNN): Metode ini khusus digunakan untuk pengenalan objek dalam citra. CNN memiliki kemampuan untuk mengekstraksi fitur secara otomatis 

Deteksi buah dalam pengolahan citra adalah proses mengidentifikasi keberadaan dan lokasi buah dalam citra. Tujuannya adalah untuk secara otomatis menemukan dan menandai objek buah dalam citra yang kompleks dengan variasi ukuran, bentuk, dan warna.

Berikut adalah beberapa metode umum yang digunakan dalam deteksi buah dalam pengolahan citra:

1.Deteksi berbasis warna: Metode ini mengandalkan perbedaan warna buah dengan latar belakang untuk mendeteksi buah. Warna buah yang khas diidentifikasi dengan menggunakan model warna seperti RGB atau HSV, dan ditemukan melalui pemrosesan citra dengan batasan warna yang ditentukan.
Deteksi berbasis warna menggunakan perbedaan warna antara buah dan latar belakang dalam citra untuk mendeteksi buah. Metode ini melibatkan penggunaan model warna seperti RGB (Red, Green, Blue) atau HSV (Hue, Saturation, Value) untuk mengidentifikasi rentang nilai warna yang mewakili buah yang ingin dideteksi. Langkah-langkah deteksi berbasis warna mencakup:

Konversi citra ke model warna yang sesuai.
Pemilihan atau definisi rentang nilai warna yang mencirikan buah tersebut.
Pemrosesan citra untuk menemukan piksel yang termasuk dalam rentang warna yang ditentukan.
Menerapkan teknik pengelompokan atau pemisahan objek berdasarkan kriteria warna yang telah ditentukan.

2.Deteksi berbasis tekstur: Metode ini mengandalkan perbedaan pola tekstur antara buah dan latar belakang untuk mendeteksi buah. Pada tahap ini, fitur-fitur tekstur seperti GLCM (Gray-Level Co-occurrence Matrix) atau LBP (Local Binary Patterns) dapat diekstraksi untuk membedakan tekstur buah dari latar belakang.

Deteksi berbasis tekstur menggunakan perbedaan pola tekstur antara buah dan latar belakang dalam citra untuk mendeteksi buah. Metode ini melibatkan ekstraksi fitur tekstur seperti GLCM (Gray-Level Co-occurrence Matrix) atau LBP (Local Binary Patterns) dari citra untuk menggambarkan pola tekstur dalam buah. Langkah-langkah deteksi berbasis tekstur mencakup:

Ekstraksi fitur tekstur seperti GLCM atau LBP dari citra buah.
Pemrosesan fitur-fitur tekstur untuk membedakan pola tekstur buah dari latar belakang.
Penerapan metode pengelompokan atau pengklasifikasian untuk memisahkan objek buah dari latar belakang berdasarkan fitur-fitur tekstur yang diekstraksi.

3.Deteksi berbasis bentuk: Metode ini berfokus pada deteksi buah berdasarkan karakteristik bentuknya. Fitur bentuk seperti lingkaran, elips, atau persegi panjang dapat digunakan untuk mendeteksi buah dalam citra. Misalnya, algoritma deteksi kontur dapat digunakan untuk mengidentifikasi bentuk-bentuk ini dalam citra dan memfilternya untuk mendapatkan buah yang diinginkan.
Deteksi berbasis bentuk fokus pada deteksi buah berdasarkan karakteristik bentuknya. Metode ini menggunakan fitur-fitur bentuk seperti lingkaran, elips, atau persegi panjang untuk mendeteksi buah dalam citra. Langkah-langkah deteksi berbasis bentuk mencakup:

Deteksi kontur dalam citra untuk mengidentifikasi kontur objek.
Ekstraksi fitur-fitur bentuk dari kontur, seperti kebulatan (roundness), rasio aspek (aspect ratio), atau perimeter (keliling).
Pemrosesan fitur-fitur bentuk untuk memfilter dan mengidentifikasi bentuk-bentuk yang sesuai dengan buah yang ingin dideteksi.
Penerapan metode pengelompokan atau pengklasifikasian untuk memisahkan buah dari objek lain berdasarkan fitur-fitur bentuk yang diekstraksi.


4.Deteksi berbasis pemrosesan skala multi: Metode ini melibatkan penggunaan teknik pemrosesan skala multi, seperti piramida citra atau transformasi Laplacian, untuk mendeteksi buah dalam berbagai ukuran dan skala. Dengan memeriksa citra pada berbagai skala, kemungkinan deteksi yang lebih baik untuk buah-buah yang berbeda dapat dicapai.

5.Deteksi berbasis pemrosesan spasial: Metode ini melibatkan analisis spasial dan perbandingan piksel di sekitar wilayah yang dicurigai. Misalnya, algoritma deteksi tepi seperti Canny atau Sobel dapat digunakan untuk menemukan tepi objek buah dan mengekstraksi fitur-fitur spasial yang relevan untuk mendeteksi buah dengan akurasi yang lebih baik.

Penting untuk dicatat bahwa penggunaan metode deteksi buah yang tepat tergantung pada sifat unik buah yang ingin dideteksi, kompleksitas latar belakang, dan tujuan aplikasi pengolahan citra yang spesifik.

langkah langkah mengerjakan projek akhir : 
1.Foto 3 buah , karena saya diruangan yang tidak terlalu terang maka saya menggunakan bantuan dari flash handphone 
2.membuat nama gambara dengan nama "buahku.jpg" dibaca menggunakan cv2.imread() dan disimpan dalam variabael 'image'
3.kemudian menggunakan kode hsv_img = cv2.cvtColor(img, cv2.COLOR_BGR2HSV) untuk mengubah ruang warna citra dari BGR (Blue-Green-Red) ke HSV (Hue-Saturation-Value).
4.kemudaian menggunakan np.array untuk membuat array NumPy dari objek Python seperti list atau tuple.
5.kemudian cv2.inrange digunakan untuk pemroresan citra
6.imshow untuk memanggil agar gambar nya keluar 

JURNAL : https://ejournal.unp.ac.id/index.php/voteknika/article/view/114251/0