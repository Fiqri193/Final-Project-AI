# Final-Project-AI
Digunakan untuk menyelesaikan Final Project AI

Berikut ada dua jenis dataset daun yaitu data set daun jeruk nipis dan daun sirih.
di setiap daun terdapat 50 foto yang sudah di resize ke ukuran 1600x 1200 serta memiliki background putih guna memudahkan dalam mengenali gambar daun saat di program.
terdapat data Processing dengan mengambil dataset kemudian dijadikan edge, kontras, grey. lalu image classification melalui dua metode yaitu CNN & ANN.


## Folder, file, dan kegunaannya

-   static/
    -   uploads/ --> Berisi gambar yang diunggah untuk diprediksi.
-   templates/
    -   index.html --> Berisi template website.
-   app.py --> Berisi konfigurasi route dan proses prediksi model untuk API.
-   nipis_sirih_class_model.h5 --> Model Image Classification CNN yang sudah di-training.
-   requirements.txt --> Berisi daftar dependency/package Python yang diperlukan untuk menjalankan API dan model Image Classification CNN.

#

## Cara menjalankan API pada komputer Anda

1. Pastikan Anda sudah menginstall Anaconda.
2. Buka terminal/command prompt/power shell.
3. Buat virtual environment dengan\
   `conda create -n <nama-environment> python=3.9`
4. Aktifkan virtual environment dengan\
   `conda activate <nama-environment>`
5. Install semua dependency/package Python dengan\
   `pip install -r requirements.txt`
6. Jalankan API menggunakan perintah\
   `python app.py`

## Akses melalui Website

1. Anda akan diberikan URL untuk membuka website berupa `localhost:5000/` atau `127.0.0.1:5000/`.
2. Buka URL dengan browser, coba masukkan daun jeruk nipis atau sirih yang ingin di prediksi.
3. Anda akan diberikan prediksi bahwa pada gambar tersebut adalah daun jeruk nipis atau sirih pada halaman website.
