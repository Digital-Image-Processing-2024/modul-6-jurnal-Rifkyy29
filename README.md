[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/174iODBg)

# Resume Finger Simulation Experiment - F1D022077

## Data Understanding

_Jelaskan mengenai data yang digunakan dalam project kalian, seperti jumlah data, jumlah kelas, serta bagaimana cara kalian mendapatkan data tersebut._
Data yang digunakan merupakan kumpulan jari dari semua praktikan. Jumlah data tersebut sebanyaj 2164 data, dengan 5 kelas yaitu : finger1,finger2,finger3,finger4,finger5.

## Data Preparation

### Image Augmentation

_Jelaskan kombinasi teknik augmentasi gambar apa saja yang kalian gunakan, serta berapa gambar yang dihasilkan dari 1 gambar asli._
teknik augmentasi yang saya gunakan adalah `resize_image`, `rotate_image`., `shift_image`, `zoom_image`, `flip_horizontal` dan `flip_vertical`. 1 gambar asli akan dirubah menjadi 3 gambar.

### Preprocessing

_Dari setiap percobaan yang telah kalian lakukan, jelaskan bagaimana cara kalian menemukan preprocessing yang paling tepat. Jelaskan alasan kalian menggunakan teknik tersebut dan berikan alasan mengapa preprocessing diperlukan._
preprocessing yang paling tepat mungkin pengurangan noise dan deteksi tepi. hal ini karena gambar pada dataset sifatnya random dari segi pencahayaan dan background, oleh karena itu dilakukan deteksi tepi agar dapat mengetahui data data yang serupa bentuknya.

### Feature Selection

_Jelaskan bagaimana kalian menemukan fitur yang paling tepat untuk digunakan. Jelaskan alasan kalian menggunakan fitur tersebut dan berikan alasan mengapa fitur tersebut diperlukan._
dengan menggunakan varian dan korelasi untuk menentukan data apa saja yang diambil dalam dataset dapat membuat proses pengolahan lebih cepat dan ringan. Hal ini karena dimensi dari dataset fitur GLCM berkutang dan fitur-fitur yang tidak memiliki korelasi tinggi dengan fitur lainnya menghilang.

## Modeling

_Jelaskan bagaimana kalian melakukan hyperparameter tuning pada model tersebut._

## Evaluation

_Jelaskan bagaimana peningkatan performa model dari metrics yang kalian gunakan pada berbagai percobaan yang telah kalian lakukan._

_Catatan:_

- _Tutorial mengenai penggunaan Markdown dapat dibaca [di sini](https://guides.github.com/features/mastering-markdown/)_
- _Kalian dapat melakukan copy untuk file `percobaan_n.ipynb` (ganti `n` dengan nomor percobaan) untuk setiap percobaan yang kalian lakukan._
