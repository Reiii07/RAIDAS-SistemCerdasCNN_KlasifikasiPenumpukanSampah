# RAIDAS – Sistem Cerdas Klasifikasi Penumpukan Sampah pada Drainase
# RAIDAS – Smart Drainage Waste Accumulation Classification

---

## 🇮🇩 Deskripsi

RAIDAS adalah proyek sistem cerdas yang bertujuan mengklasifikasikan tingkat
penumpukan sampah pada saluran drainase secara otomatis dari citra (gambar).
Penumpukan sampah di drainase merupakan salah satu penyebab utama tersumbatnya
aliran air dan banjir, sehingga deteksi dini sangat penting untuk membantu
pemantauan dan pengambilan keputusan.

Model dibangun menggunakan Convolutional Neural Network (CNN) dengan pendekatan
transfer learning memakai arsitektur MobileNetV2 yang sudah dilatih pada dataset
ImageNet. Model mengklasifikasikan gambar ke dalam 3 kelas:

- **Rendah**: penumpukan sampah sedikit atau aliran masih lancar
- **Sedang**: penumpukan sampah mulai mengganggu aliran
- **Tinggi**: penumpukan sampah banyak dan berpotensi menyumbat drainase

### Fitur Utama
- Klasifikasi tingkat penumpukan sampah menjadi 3 kelas
- Transfer learning dengan MobileNetV2 (ringan dan cocok untuk perangkat terbatas)
- Pemuatan dataset otomatis dari struktur folder per kelas
- Proses pelatihan lengkap dalam satu Jupyter Notebook

---

## 🇬🇧 Description

RAIDAS is a smart system project that automatically classifies the level of
waste accumulation in drainage channels from images. Waste buildup in drainage
is a major cause of blocked water flow and flooding, so early detection is
important to support monitoring and decision-making.

The model is built as a Convolutional Neural Network (CNN) using transfer
learning with the MobileNetV2 architecture, pre-trained on ImageNet. It
classifies images into 3 classes:

- **Low (rendah)**: little waste, water flow is still smooth
- **Medium (sedang)**: waste begins to disturb the flow
- **High (tinggi)**: heavy waste buildup with a risk of clogging the drainage

### Key Features
- Waste accumulation level classification into 3 classes
- Transfer learning with MobileNetV2 (lightweight, suitable for limited devices)
- Automatic dataset loading from class-based folder structure
- Complete training pipeline in a single Jupyter Notebook

---

## 📁 Struktur Folder / Folder Structure

```
RAIDAS-SistemCerdasCNN_KlasifikasiPenumpukanSampah/
├── dataset/
│   ├── train/        # rendah, sedang, tinggi
│   └── val/          # rendah, sedang, tinggi
├── notebook/
│   └── pelatihan_model.ipynb
├── README.md
└── requirements.txt
```


## 🛠️ Teknologi / Tech Stack

Python · TensorFlow · Keras · MobileNetV2 · Jupyter Notebook

## 🚀 Cara Menjalankan / How to Run

1. Clone repositori / Clone the repository
   ```bash
   git clone https://github.com/Reiii07/RAIDAS-SistemCerdasCNN_KlasifikasiPenumpukanSampah.git
   cd RAIDAS-SistemCerdasCNN_KlasifikasiPenumpukanSampah
   ```
2. Install dependensi / Install dependencies
   ```bash
   pip install -r requirements.txt
   ```
3. Buka dan jalankan / Open and run
   `notebook/pelatihan_model.ipynb`

## 📌 Catatan / Notes

- Dataset saat ini masih terbatas dan akan terus ditambah.
  / The dataset is still limited and will be expanded.
- Proyek ini merupakan bagian dari pengembangan sistem drainase cerdas.
  / This project is part of a smart drainage system development.