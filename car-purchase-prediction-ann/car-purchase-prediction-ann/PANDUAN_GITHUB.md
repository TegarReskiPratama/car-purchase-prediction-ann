# Menambahkan proyek ke portofolio GitHub

## Pengaturan repository

- Nama: `car-purchase-prediction-ann`
- Description: `Car purchase amount prediction using TensorFlow/Keras ANN, with preprocessing, regression evaluation, and training visualization.`
- Visibility: Public jika ingin ditampilkan sebagai portofolio publik.
- Topics: `python`, `tensorflow`, `keras`, `machine-learning`, `regression`, `neural-network`, `data-science`, `portfolio`.

## Unggah melalui browser

1. Ekstrak ZIP proyek terlebih dahulu.
2. Buka https://github.com/new dan buat repository dengan nama di atas. Boleh centang Add a README file agar repository langsung memiliki halaman berkas.
3. Di repository, pilih **Add file → Upload files**.
4. Unggah isi folder `car-purchase-prediction-ann` ke root repository, termasuk folder `assets`; jangan hanya mengunggah ZIP. README dalam paket akan menggantikan README awal.
5. Tulis commit message `Add ANN car purchase prediction portfolio`, lalu pilih **Commit changes**.
6. Periksa README, grafik, dan pratinjau notebook. Tambahkan description/topics melalui bagian About dan pin repository di profil GitHub jika diperlukan.

README harus berada langsung di root repository agar pengantar proyek mudah ditemukan. Sertakan `.gitignore` saat unggah; di beberapa file manager berkas bertitik tidak terlihat.

## Sebelum menyebutnya eksperimen yang sudah direproduksi

Paket ini memuat hasil tersimpan dari notebook asal. CSV belum disertakan dan pelatihan belum dijalankan ulang saat penyiapan portofolio. Untuk membuktikan reproduksi, jalankan seluruh cell dengan CSV asli, pastikan tidak ada error, simpan hasil, dan catat versi dependensi. Lengkapi atribusi modul serta sumber dan lisensi dataset bila sudah diketahui.

Angka 99% harus disebut **proporsi prediksi dalam toleransi ±10%**, bukan akurasi klasifikasi. Gunakan R², MAE, dan RMSE sebagai metrik regresi utama.

Dokumentasi resmi unggah: https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
