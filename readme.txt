Instalasi requirements:
pip install -r requirements.txt

Instalasi keras-contrib:
1. cd keras-contrib
2. python setup.py install

Training model GAN:
1. Lakukan augmentasi data dengan menjalankan "Data Augmentation.ipynb" untuk memperbanyak jumlah data training. Hasil dari augmentasi data akan disimpan dalam folder "Dataset".
2. Buka file "ContextualGAN.ipynb" dan jalankan baris kode yang terdapat pada notebook tersebut untuk memulai training.
3. Model hasil training akan tersimpan pada folder "Models".
4. Buka file "Testing.ipynb" untuk melakukan inference pada data uji dengan model yang telah dilatih.
5. Hasil inference akan disimpan dalam folder "Generated Images".
6. Buka file "Compute SSIM and L2-norm.ipynb" untuk menghitung performasi sistem dengan menggunakan SSIM dan L2-norm.
7. Untuk melakukan inference dengan gambar masukan sketsa tunggal, dapat menggunakan file "Predict Image.ipynb".