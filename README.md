# UAS_OCR
M.Hafizh Khairullah_4222201006_Computer Vision

OCR Plat Nomor Kendaraan dengan Visual Language Model (VLM)

Program ini menggunakan model multimodal seperti LLaVA atau BakLLaVA melalui LMStudio untuk mengenali teks dari gambar plat nomor kendaraan. Hasil prediksi akan disimpan dan dibandingkan dengan ground truth untuk menghitung Character Error Rate (CER).
using
- LMStudio (https://lmstudio.ai/)
- Model multimodal terpasang di LMStudio (google/gemma-3-4b)
- LMStudio berjalan dengan REST API aktif di (http://127.0.0.1:1234)

Menjalankan Program
Pastikan LMStudio sedang berjalan, dan model multimodal seperti LLaVA sudah aktif dan bisa membaca gambar.

Jalankan program:
ocrVLM.ipynb

Output yang dihasilkan:
1. Prediksi hasil OCR per gambar
2. Nilai CER (Character Error Rate)
3. File output (misalnya: results.csv) berisi nama file, ground truth, prediksi, dan nilai CER per gambar

Output Program:
Rata-rata CER:  0.3715



