Penjelasan setiap variable (Data Dictionary)

1. VendorID:	Kode ID yang menunjukkan vendor taksi.
   1 = Creative Mobile Technologies, LLC
   2 = VeriFone Inc.
2. lpep_pickup_datetime:	Tanggal dan waktu saat perjalanan taksi dimulai.
3. lpep_dropoff_datetime:	Tanggal dan waktu saat perjalanan taksi berakhir.
4. store_and_fwd_flag:	Menunjukkan apakah catatan perjalanan disimpan dalam memori kendaraan sebelum dikirim ke vendor. Y berarti "simpan dan lanjutkan", N berarti bukan perjalanan "simpan dan lanjutkan".
5. RatecodeID	Kode: tarif untuk perjalanan.
   1 = Tarif standar
   2 = JFK
   3 = Newark
   4 = Nassau atau Westchester
   5 = Tarif yang dinegosiasikan
   6 = Perjalanan kelompok.
6. PULocationID	ID lokasi penjemputan, yang sesuai dengan zona taksi di mana meteran (taximeter) diaktifkan.
7. DOLocationID	ID lokasi penurunan, yang sesuai dengan zona taksi di mana meteran (taximeter) dinonaktifkan.
8. passenger_count	Jumlah penumpang di dalam kendaraan.
9. trip_distance	Jarak perjalanan dalam mil.
10. fare_amount	Tarif yang diukur untuk perjalanan.
11. extra	Biaya tambahan. Saat ini, ini hanya mencakup biaya tambahan 0,5 dolar dan 1 dolar untuk jam sibuk dan larut malam.
12. mta_tax	Pajak MTA sebesar 0,50 dolar yang otomatis aktif berdasarkan tarif yang diukur yang digunakan.
13. tip_amount:	Jumlah tip. Bidang ini otomatis diisi untuk tip kartu kredit. Tip tunai tidak termasuk.
14. tolls_amount:	Jumlah total dari semua tol yang dibayar dalam perjalanan.
15. ehail_fee	Biaya: tambahan sebesar 1 dolar yang otomatis dikenakan untuk setiap perjalanan yang dipesan melalui platform ehail.
16. improvement_surcharge	Biaya tambahan sebesar 0,30 dolar yang dinilai pada awal perjalanan. Biaya tambahan ini mulai dikenakan pada tahun 2015.
17. total_amount	Jumlah total yang dikenakan kepada penumpang. Bidang ini mencakup tarif yang diukur, biaya tambahan, mta_tax, tip_amount, dan tolls_amount ditambah biaya tambahan ehail atau improvement_surcharge.
18. payment_type	Kode numerik yang menunjukkan metode pembayaran.
19. trip_type	Kode yang menunjukkan apakah perjalanan adalah dari sisi jalan atau dari pengiriman yang otomatis ditetapkan berdasarkan tarif yang diukur yang digunakan tetapi dapat diubah oleh pengemudi.
    1 = Street-hail
    2 = Dispatch
20. congestion_surcharge	Biaya kemacetan sebesar 2,75 dolar untuk perjalanan dengan taksi kuning dan hijau di Manhattan selatan dari 96th St. Biaya tambahan ini mulai dikenakan pada tahun 2019.

**Kesimpulan Umum**

Permintaan taksi lebih tinggi pada hari kerja dibandingkan weekend, dengan sore hari menjadi waktu yang paling sibuk. Manhattan mendominasi dalam hal volume perjalanan, dengan tarif perjalanan dalam kota menjadi pilihan utama pelanggan. Selain itu, tarif dan jarak perjalanan adalah faktor utama yang mempengaruhi besarnya tip yang diberikan oleh pelanggan.

**Rekomendasi**

a. Ketersediaan Taxi
1. Optimalkan jumlah taxi pada weekdays dan perbanyak armada taxi pada jam sibuk yaitu 15.00 s/d 18.00.
2. Untuk weekend permintaan meningkat pada pukul 11 s/d 20.00 dan jumlah permintaan cenderung lebih kecil daripada weekdays akan lebih optimal jika armada dikurangi
3. Pastikan ketersediaan taxi pada rute yang memiliki rata-rata fare amount tertinggi seperti West Side North, Upper Yorkville West, dan sebagainya.

b. Strategi Wilayah
1.Untuk PU Borough Manhattan dan Quees disarankan untuk membuka perjalanan yang lebih jauh minimal dengan trip distance 2.68 (angka ini didapat dari rata-rata trip distance Broklyn yang memiliki rata-rata trip tertinggi)
2. Berikan promo untuk wilayah-wilayah yang sepi permintaan seperti Bronx dan Staten Island

c. Strategi untuk Meningkatkan Demand dan Profit
1. Pertimbangkan untuk penyesuaian tarif berdasarkan permintaan. Misalnya, naikkan tarif sebesar 1-3% saat puncak permintaan di jam sibuk
2. Tawarkan promo atau diskon pada saat-saat permintaan rendah, misalnya pada tengah malam atau awal pagi, untuk menarik lebih banyak pelanggan.
3. Tawarkan perjalanan kelompok yang memiliki drop off yang berbeda dan sesuaikan tarif yang make sense bagi customer dan perusahaan

d. Peningkatan Kualitas Pelayanan
1. Menambah metode pembayaran yang memudahkan pelanggan seperti QRIS dan yang lainnya
2. Memberikan edukasi pada driver dalam melayanani dan mengajak pelanggan berkomunikasi agar tidak bosan di jalan
