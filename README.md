# UTS-PCD-NISA

kesimpulan 
Kesalahan dalam beberapa kode telah berhasil diperbaiki, termasuk perubahan dari cv2.imshow menjadi cv2_imshow untuk sesuai dengan lingkungan Google Colab pada Kode1. 
Pada Kode4, kesalahan fungsi show() diganti dengan plt.show(), memungkinkan tampilan histogram yang benar saat menggunakan Matplotlib dengan array NumPy. 
Pada Kode6, penamaan variabel (dari histogr menjadi histogram) diperbaiki, dan penggunaan variabel pada plotting histogram disesuaikan, menjaga konsistensi dan fungsionalitas kode.
Kode7 mengalami koreksi pada variabel warna (dari d menjadi b, dan b menjadi g) agar sesuai dengan format warna BGR pada OpenCV. 
Pada Kode9, perbaikan seperti mendefinisikan variabel histogram sebelum plt.plot() dan mengganti plt() dengan plt.show() dilakukan, memungkinkan tampilan histogram dengan warna yang sesuai (b, g, r).

Dengan perbaikan ini, dapat disimpulkan bahwa histogram berfungsi sebagai alat visualisasi yang efektif untuk menganalisis distribusi intensitas piksel dalam gambar. Dengan menggunakan fungsi dan variabel yang tepat, serta penyesuaian warna yang sesuai, kode-kode tersebut sekarang dapat dijalankan dengan baik. Visualisasi histogram yang dihasilkan juga memberikan wawasan yang akurat dan informatif mengenai karakteristik gambar, memudahkan analisis dan pemahaman terhadap distribusi nilai piksel dalam gambar.
