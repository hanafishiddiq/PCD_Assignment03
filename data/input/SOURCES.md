# Sumber citra

## coins.png

- Koleksi contoh scikit-image, citra coins, ukuran asli 384 x 303 piksel.
- Sumber awal: Brooklyn Museum Collection. Dokumentasi scikit-image menyatakan tidak ada pembatasan hak cipta yang diketahui.
- Dokumentasi: https://scikit-image.org/docs/stable/api/skimage.data.html#skimage.data.coins
- Data dipakai tanpa resize, perubahan intensitas, atau penambahan derau.

## page.png

- Koleksi contoh scikit-image, citra page, ukuran asli 384 x 191 piksel.
- Dokumentasi: https://scikit-image.org/docs/stable/api/skimage.data.html#skimage.data.page
- Didistribusikan sebagai data contoh dalam proyek scikit-image. Lisensi proyek: https://github.com/scikit-image/scikit-image/blob/main/LICENSE.txt
- Data dipakai tanpa resize, perubahan intensitas, atau penambahan derau. Notebook tidak membutuhkan scikit-image.

## synthetic.png dan synthetic_mask.png

- Dibuat oleh fungsi make_synthetic pada PCD_Assignment03.ipynb.
- Ukuran 320 x 256 piksel; seed NumPy 31.
- Mask acuan ditentukan dari geometri sebelum intensitas diberi derau Gaussian sigma 7 dan impuls dengan probabilitas total 2.5%.
- Bukan anotasi hasil prediksi K-means atau hasil operasi morfologi.
- File disertakan agar dataset dapat dilihat tanpa menjalankan notebook. Saat dijalankan, notebook membuat ulang kedua file dengan parameter yang sama.
