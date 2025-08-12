# Roadmap Belajar Python & Data Science: 12 Minggu

Roadmap ini dirancang agar mudah diikuti dan langsung bisa disalin ke repositori GitHub Anda. Cocok untuk pemula yang ingin menguasai Python, Analisis Data, dan Machine Learning dengan praktik nyata dan portofolio.

---

## **Bulan 1: Fondasi Python yang Kokoh (Minggu 1 - 4)**

### **Minggu 1: Setup & Sintaks Dasar**
- **Tujuan:** Mengenal Python dan mempersiapkan lingkungan kerja.
- **Materi & Tugas:**
    - Apa itu Python, keunggulan, dan kegunaannya.
    - Instalasi Python & VS Code (atau editor pilihan).
    - **Penting:** Setup environment virtual (`venv`) sejak awal.
    - Tipe data dasar: `int`, `float`, `string`, `boolean`.
    - Variabel dan operasi aritmatika dasar.
    - Fungsi `input()` & `print()`.
    - Komentar dalam kode.
    - **Mini Task:** 
        - Program kalkulator sederhana.
        - Program biodata interaktif.

---

### **Minggu 2: Struktur Data & Kontrol Alur**
- **Tujuan:** Mengelola data dan mengontrol logika program.
- **Materi & Tugas:**
    - List & Tuple: perbedaan, indexing, slicing, metode dasar (`append`, `pop`, `len`).
    - Kontrol alur: `if`, `elif`, `else`.
    - Looping: `for` (dengan `range()` & list), `while`.
    - Pentingnya indentasi di Python.
    - **Mini Task:**
        - Program memisahkan angka genap & ganjil dari list.
        - Game tebak angka dengan `while`.

---

### **Minggu 3: Struktur Data Lanjutan & Fungsi**
- **Tujuan:** Memperdalam struktur data dan mulai menggunakan fungsi.
- **Materi & Tugas:**
    - Dictionary & Set: operasi dasar, kasus penggunaan.
    - List Comprehension.
    - Membuat & memanggil fungsi.
    - Parameter & return value.
    - Scope variabel (global vs local).
    - **Mini Task:**
        - Aplikasi daftar kontak sederhana (dictionary & fungsi).
        - Fungsi cek palindrom.

---

### **Minggu 4: Pengenalan OOP (Object-Oriented Programming)**
- **Tujuan:** Memahami dasar OOP dan cara membuat class.
- **Materi & Tugas:**
    - Apa itu OOP dan manfaatnya.
    - Membuat `class` dan `object`.
    - Konstruktor (`__init__`), atribut, dan method.
    - **Mini Task:**
        - `Class Kucing` dengan atribut (nama, warna) & method (mengeong, makan).
        - Buat beberapa objek dari class tersebut.

---

## **Bulan 2: Spesialisasi Analisis Data & Penguasaan OOP (Minggu 5 - 8)**

### **Minggu 5: OOP Lanjutan & Mini Proyek**
- **Tujuan:** Menguasai pilar OOP dan menerapkannya.
- **Materi & Tugas:**
    - Inheritance (pewarisan).
    - Encapsulation (penyembunyian detail, menggunakan `_`/`__`).
    - Polymorphism.
    - Metode khusus: `__str__`, `__repr__`.
    - **Proyek Mini OOP:**
        - Sistem perpustakaan (class `Buku` & `Perpustakaan`), atau
        - Sistem manajemen karyawan (`Karyawan` & `Departemen`).

---

### **Minggu 6: Pengenalan NumPy & Pandas**
- **Tujuan:** Bekerja dengan data numerik & tabular.
- **Materi & Tugas:**
    - NumPy: array, operasi vektor, indexing, slicing.
    - Pandas: `Series`, `DataFrame`.
    - Membaca data (CSV/Excel) ke DataFrame.
    - Seleksi data: `head()`, `tail()`, `info()`, `describe()`, `loc`, `iloc`.
    - **Mini Task:**
        - Load dataset (misal: Iris) ke Pandas dan eksplorasi dasar.

---

### **Minggu 7: Manipulasi & Pembersihan Data**
- **Tujuan:** Menguasai teknik inti analisis data.
- **Materi & Tugas:**
    - Filtering data, sorting.
    - Menangani missing values dan duplikat.
    - Agregasi (`groupby`).
    - **Mini Task:**
        - Bersihkan dataset Titanic: isi nilai usia kosong, hitung rata-rata tarif per kelas, filter penumpang yang selamat.

---

### **Minggu 8: Visualisasi Data & Analisis Sederhana**
- **Tujuan:** Mengkomunikasikan data dengan visualisasi.
- **Materi & Tugas:**
    - Dasar Matplotlib/Seaborn: line plot, bar chart, histogram, scatter.
    - Memberi judul & label.
    - Integrasi: import & bersihkan data, analisis, visualisasi.
    - **Mini Task:**
        - Analisis Titanic: bar chart jumlah penumpang per kelas, histogram usia, scatter usia vs tarif.

---

## **Bulan 3: Aplikasi, Integrasi, dan Portofolio (Minggu 9 - 12)**

### **Minggu 9: Dasar Machine Learning (Scikit-Learn)**
- **Tujuan:** Memahami workflow ML dan melatih model sederhana.
- **Materi & Tugas:**
    - Konsep supervised vs unsupervised.
    - Alur kerja ML: training, testing, evaluasi.
    - Pengenalan Scikit-Learn.
    - Model regresi linear & klasifikasi (logistic regression).
    - Overfitting.
    - **Penting:** Menyimpan model (`pickle`/`joblib`).
    - **Mini Task:**
        - Model klasifikasi pada dataset Iris.
        - Model regresi pada dataset harga rumah sederhana.

---

### **Minggu 10: Pengembangan Web & API dengan Flask**
- **Tujuan:** Membangun backend web & API.
- **Materi & Tugas:**
    - Apa itu web backend.
    - Setup Flask, routing (`@app.route`).
    - Menangani request & response.
    - Endpoint API sederhana (JSON).
    - Aksi CRUD lewat API.
    - **Mini Task:**
        - API To-Do List sederhana.

---

### **Minggu 11: Proyek Akhir - Integrasi AI & Web**
- **Tujuan:** Membangun aplikasi integrasi ML dan Web.
- **Materi & Tugas:**
    - Rancang arsitektur proyek (input web → model ML).
    - Aplikasi Flask yang memuat model ML (dari minggu 9).
    - Endpoint API menerima input, prediksi, dan kirim hasil prediksi (JSON).
    - **Fokus:** Fungsionalitas inti berjalan.

---

### **Minggu 12: Finalisasi Proyek & Portofolio**
- **Tujuan:** Memoles proyek akhir dan membangun portofolio.
- **Materi & Tugas:**
    - Refactor & review kode proyek.
    - Dokumentasi proyek: README.md yang informatif.
    - Bangun portofolio (GitHub yang rapi, proyek terdeskripsi baik).
    - Review seluruh materi.
    - Rancang langkah karier berikutnya.

---

> **Tips:**  
> - Konsisten latihan setiap minggu.
> - Dokumentasikan setiap proyek/praktik di GitHub.
> - Setelah menyelesaikan roadmap ini, lanjutkan dengan topik lanjutan seperti Deep Learning, Deployment, dan spesialisasi lain sesuai minat.
