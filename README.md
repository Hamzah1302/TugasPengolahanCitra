Program 1
Fungsi Utama:

Program ini dimulai dengan memuat citra dari path yang diberikan dan memeriksa keberadaan citra tersebut. Jika tidak ditemukan, akan mengeluarkan pesan kesalahan.
Setelah citra berhasil dimuat, program memvisualisasikan masing-masing channel RGB (Red, Green, Blue) dengan menampilkan channel dalam format citra terpisah.
Fungsi-fungsi:

load_image: Memuat citra dan mengubahnya dari format BGR ke RGB. Juga menangani kesalahan jika citra tidak ditemukan.
visualize_rgb_channels: Memisahkan citra menjadi channel R, G, dan B, dan menampilkan channel-channel ini bersama citra asli dalam satu plot.
Visualisasi:

Citra asli dan masing-masing channel ditampilkan dalam subplot, dengan format yang jelas dan terorganisir.
Program 2
Fungsi Utama:

Program ini memuat citra dan mengubahnya dari format BGR ke RGB, lalu membagi citra menjadi channel R, G, dan B.
Kemudian, program menerapkan dua metode pemetaan: pemetaan uniform dan pemetaan logarithmic untuk masing-masing channel.
Fungsi-fungsi:

uniform_mapping: Menormalkan intensitas channel antara 0 dan 255.
logarithmic_mapping: Menerapkan pemetaan logarithmic pada channel, yang berguna untuk memperbaiki kontras dalam citra.
plot_channel: Digunakan untuk memplot channel-channel citra dalam subplot.
Visualisasi:

Setiap channel (original, uniform, logarithmic) ditampilkan dalam subplot terpisah, memberikan gambaran yang jelas tentang perbedaan antara channel asli dan hasil pemetaan.
Kesimpulan
Tujuan dan Kegunaan:

Kedua program memiliki tujuan yang berbeda: Program 1 fokus pada pemisahan dan visualisasi channel RGB, sedangkan Program 2 tidak hanya memisahkan dan memvisualisasikan channel tetapi juga menerapkan teknik pemrosesan citra untuk meningkatkan kontras.
Fungsi dan Modularitas:

Keduanya menggunakan fungsi untuk modularitas, tetapi Program 1 lebih sederhana dan fokus pada visualisasi, sedangkan Program 2 lebih kompleks dengan penerapan teknik pemrosesan citra yang lebih mendalam.
Pentingnya Teknik Pemetaan:

Program 2 menunjukkan pentingnya teknik pemetaan seperti uniform dan logarithmic dalam pengolahan citra untuk meningkatkan kualitas visual citra.
