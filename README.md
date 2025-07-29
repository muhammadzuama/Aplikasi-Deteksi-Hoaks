

# 📱 Hoaks Detection Using Text and Link

Aplikasi **Hoaks Detection Using Text and Link** dikembangkan menggunakan **Flutter**, yang memanfaatkan **model klasifikasi teks berbasis TensorFlow** untuk mengidentifikasi apakah sebuah **berita teks atau tautan** mengandung **informasi hoaks**. Proyek ini bertujuan untuk membantu pengguna menyaring dan mengenali berita palsu secara otomatis demi meningkatkan literasi digital.

---

## 🚀 Fitur Utama

* 🧠 **Deteksi Hoaks Otomatis**
  Menggunakan model deep learning berbasis TensorFlow untuk mendeteksi konten hoaks dari input teks atau tautan berita.

* 💬 **Analisis Percakapan**
  Simulasi percakapan antara pengguna dan sistem untuk memeriksa keabsahan berita.

* 📊 **Klasifikasi Hoaks / Valid**
  Konten yang dimasukkan pengguna akan diklasifikasi sebagai **Hoaks** atau **Valid** berdasarkan prediksi model.

* 📱 **Optimasi Android**
  Aplikasi dikembangkan dengan Flutter dan sepenuhnya dioptimalkan untuk perangkat Android.

---

## 🛠 Teknologi yang Digunakan

| Teknologi           | Deskripsi                                                        |
| ------------------- | ---------------------------------------------------------------- |
| **Flutter**         | Framework UI cross-platform                                      |
| **Dart**            | Bahasa pemrograman utama aplikasi                                |
| **Provider / Bloc** | (Opsional) Untuk manajemen state                                 |
| **TensorFlow**      | Framework machine learning untuk model klasifikasi teks dan link |
| **Flask**           | Untuk untuk mengembangkan model manjadi API                      |
| **Android SDK**     | Untuk membangun dan menjalankan aplikasi Android                 |

---

## 📦 Instalasi & Menjalankan Aplikasi

### 1. Clone Proyek

```bash
git clonehttps://github.com/muhammadzuama/Aplikasi-Deteksi-Hoaks.git
cd hoaksdetectionapp
```

### 2. Cek JDK & Flutter

```bash
java -version     # Pastikan menggunakan JDK 17
flutter doctor    # Cek apakah environment Flutter telah siap
```

### 3. Install Dependency

```bash
flutter pub get
```

### 4. Jalankan Aplikasi

```bash
flutter run
```

> ⚠️ Pastikan emulator Android aktif atau perangkat Android sudah terhubung.

---

## 🤖 Tentang Model Deteksi Hoaks

* Model dikembangkan menggunakan **TensorFlow** dan dilatih pada dataset berita palsu dan berita asli.
* Model mampu menganalisis **teks berita** dan/atau **tautan berita** untuk mengidentifikasi potensi hoaks.
* Setelah pelatihan, model dikonversi ke format **TensorFlow Lite (TFLite)** agar dapat dijalankan langsung di perangkat Android.

---

## 🧪 Contoh Kasus Penggunaan

| Input Pengguna                                                                                                | Deteksi   |
| ------------------------------------------------------------------------------------------------------------- | --------- |
| “[https://newsbohong.com/virus-menular-lewat-internet”](https://newsbohong.com/virus-menular-lewat-internet”) | **Hoaks** |
| “Pemerintah resmikan program vaksinasi nasional”                                                              | **Valid** |
| “Klik link ini untuk klaim hadiah dari WHO”                                                                   | **Hoaks** |

---
