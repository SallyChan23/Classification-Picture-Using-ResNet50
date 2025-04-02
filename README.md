# Image Classification using CNN + RestNet50
Proyek ini bertujuan untuk melakukan klasifikasi gambar pemandangan (seperti forest, mountain, sea, dll) menggunakan 
model CNN berbasis Transfer Learning dengan ResNet50. Model dilatih pada dataset Intel Image Classification yang terdiri dari 6 kelas, 
dan berhasil mencapai akurasi testing sebesar 93.33% dan Training di sekitar 95%.

# Model yang digunakan 
* Arsitektur: Sequential CNN + Pretrained ResNet50
* Preprocessing: Resize ke 224x224, Normalisasi pixel
* Callbacks: EarlyStopping, ReduceLROnPlateau, ModelCheckpoint
* Export Format: SavedModel (untuk inference)

# Evaluasi
* Train Accuracy: 95%
* Validation Accuracy: Stabil di angka 93%
* Test Accuracy: 93.33%
* Inference bekerja akurat pada gambar baru

# Contoh Hasil Akhir:
![image](https://github.com/user-attachments/assets/a8e778b0-e215-4763-a638-0f10a7539956)
