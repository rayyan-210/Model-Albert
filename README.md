# 🧠 ABSA Model Using ALBERT — Sentiment Analysis for Bukalapak Reviews

Repository ini berisi proyek pembuatan model **Aspect-Based Sentiment Analysis (ABSA)** menggunakan **ALBERT (A Lite BERT)**. Model ini dilatih menggunakan dataset ulasan konsumen dari platform **Bukalapak**, dengan tujuan mengklasifikasikan sentimen berdasarkan aspek tertentu dalam teks.

---

## 📂 Dataset

Dataset yang digunakan sudah tersedia di dalam repository, terdiri dari:

| File | Deskripsi | Proporsi |
|------|-----------|----------|
| `train_70.csv` | Data pelatihan model | 70% |
| `test_30.csv` | Data pengujian model | 30% |

Format dataset mengikuti struktur:

| Column | Deskripsi |
|--------|-----------|
| `text` | Ulasan dari pengguna Bukalapak |
| `aspect` | Aspek yang ingin dianalisis |
| `label` | Sentimen (Positive, Negative, Neutral) |

---

## 🧩 Model

Model yang digunakan adalah:

ALBERT-base

**Kenapa ALBERT?**

- Lebih ringan dibanding BERT
- Akurasi tinggi pada tugas NLP Bahasa Indonesia setelah fine-tuning
- Lebih efisien dalam memori dan waktu training

---

## 🚀 Training Workflow

Seluruh pipeline dapat dijalankan dari file berikut:
Albert.ipynb

Isi utama notebook mencakup:

- Import data
- Preprocessing & tokenization
- Fine-tuning ALBERT
- Evaluasi performa model menggunakan:
  - Accuracy
  - Precision, Recall, F1-Score
  - Confusion Matrix

---

## 📈 Hasil Model

> **(Update angka setelah evaluasi final)**

| Metric | Score |
|--------|-------|
| Accuracy |  0.92  |
| Precision | — |
| Recall | — |
| F1-Score | — |

---

## 🏁 Cara Menjalankan

### 1️⃣ Clone repository

```bash
git clone https://github.com/rayyan-210/Model-Albert.git



