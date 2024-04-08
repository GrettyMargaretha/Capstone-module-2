# Capstone-module-2
AirBnB Listing - Bangkok

# 1. Latar Belakang

AIR BnB adalah sebuah perusahaan yang berfokus pada layanan daring penyewaan properti yang memungkinkan pengguna mendaftarkan atau menyewa properti untuk digunakan sementara (dalam jangka waktu pendek). Harga sewanya ditetapkan oleh pemilik properti. Airbnb menerima sebagian tarif jasa pembukuan dari tamu dan tuan rumah.

AirBnB Cabng Bangkok - Thailand, telah merekrut seorang Data Scientist untuk menganalisis masalah yang ada pada aplikasi online mereka melalui data listing Bangkok. Informasi ini akan dipergunakan oleh CMO (Chief Marketing Officer) untuk meningkatkan kualitas dan peringkat (review) aplikasi, mampu melihat permasalahan dalam penggunaan aplikasi, dan merancang strategi pemasaran yang akan meningkatkan daya tarik pengguna (calon penyewa) untuk melilih berbagai jenis properti dalam aplikasi AirBnB di Bangkok. 

### 1.1. Pernyataan Masalah
Perusahaan ingin mengetahui **faktor-faktor apa saja yang bisa diperbaiki di aplikasi AirBnB untuk meningkatkan kenyamanan atau kepuasan pengalaman calon penyewa properti di AirBnB kedepannya**. Informasi ini akan membantu perusahaan untuk meningkatkan kenyamanan pengalaman penyewa dalammenggunakan aplikasi AirBnB, dengan begitu dapat meningkatkan peringkat (rating) aplikasi itu sendiri. 

Sebagai seorang *data scientist*, kita akan mencoba menjawab pertanyaan berikut:

**Apa hal-hal yang dapat dilakukan untuk meningkatkan kepuasan pelanggan dalam penggunaan aplikasi AirBnB di Bangkok?**

- Following question: Tipe ruangan/properti apa yang paling banyak terlibat dalam faktor-faktor tersebut?


### 1.2. Data
Untuk menjawab pertanyaan di atas, kita akan menganalisa data AirBnB Listings Bangkok yang sudah dikumpulkan. Dataset dapat diakses [di sini](https://drive.google.com/file/d/1Kagt-IMGruvyBV3tH6HYa721JK-TN-56/view?usp=drive_link). 

Dataset ini berisi informasi terkait nama dan tipe ruangan yang disewakan, geografis, ID penyewa, dan lainnya. Ada 17 kolom di dalam dataset AirBnB Listing Bangkok, yaitu:  

 * Unnamed: Nomor urut data
 * id: nomor identitas listing AirBnB 
 * name: Nama listing / properti
 * host_id: nomor identitas pengguna atau penyewa  
 * host_name: nama penyewa properti 
 * neighbourhood: Wilayah tersebut di-geocode menggunakan lintang dan bujur terhadap lingkungan sebagaimana yang ditentukan oleh shapefiles digital terbuka atau publik. 
 * latitude: proyeksi latitude
 * longitude: proyeksi longitude
 * room_type: jenis ruangan yang disewakan, seperti: Entire home/apartment, private room, shared room, hotel  
 * price: harga penyewaan properti per malam
 * minimum_nights: minimum penyewaan properti (satuan: per malam)
 * number_of_reviews: jumlah review yang didapat properti tersebut
 * last_review: terakhir kali properti tersebut diberi review
 * reviews_per_month: jumlah review yang dimiliki property tersebut dalam satu bulan
 * calculated_host_listings_count: Jumlah penyewaan yang dimiliki oleh pemilik dalam perolehan data saat ini di geografi kota/wilayah.
 * availability_365: Ketersediaan_x. Kalender menentukan ketersediaan daftar x hari ke depan. Perlu diperhatikan bahwa sebuah daftar dapat tersedia karena telah dipesan oleh tamu atau diblokir oleh tuan rumah.
 * number_of_reviews_ltm: Jumlah ulasan yang dimiliki oleh properti tersebut (dalam 12 bulan terakhir).


# 2. Pemahaman Data dan Cleaning
Sebelum masuk ke dalam analisis, kita perlu mengenal dataset kita lebih jauh dalam tahapan *data understanding*. Dari proses ini, kita akan tahu anomali-anomali apa saja yang terdapat di dalam dataset kita dan perlu ditangani dalam tahapan *data cleaning*. Setiap penangan anomali yang dilakukan, akan disertai dengan justifikasi langkah yang diambil, baik secara *domain knowledge* maupun secara statistik.

# 3. Analisis (detail dapat dilihat pada file jupiter notebook - Capstone Module 2.ipynb)

# 4. Kesimpulan (detail dapat dilihat pada file jupiter notebook - Capstone Module 2.ipynb)

# 5. Rekomendasi (detail dapat dilihat pada file jupiter notebook - Capstone Module 2.ipynb)
