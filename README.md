# 🗺️ Analisis Klasterisasi Kepadatan Penduduk Kabupaten Muara Enim menggunakan DBSCAN

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)  
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange)  
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Deskripsi
Proyek ini merupakan implementasi dari penelitian berjudul **"Analisis Klasterisasi Kepadatan Penduduk Kabupaten Muara Enim Menggunakan Algoritma DBSCAN"** yang dipublikasikan pada **Prosiding Seminar Nasional Sains Data 2024**.  
Tujuan utama proyek adalah melakukan klasterisasi kepadatan penduduk dengan algoritma **DBSCAN** serta mengevaluasi hasilnya menggunakan metrik **Silhouette Score**, **Davies–Bouldin Index**, dan **Dunn Index**.

👉 [Baca Artikel Asli](https://prosiding-senada.upnjatim.ac.id/index.php/senada/article/view/393)  
👉 [DOI: 10.33005/senada.v4i1.393](https://doi.org/10.33005/senada.v4i1.393)

---

## 👨‍💻 Penulis
- Rafi Fadhlillah  
- Balqis Dwian Fitri Zamzami  
- Ghozi Alvin Karim  
- Anasthashya Rachman  
- Khalda Luthfi Azzira  
- Febri Dwi Irawati  
- Rizki Dimas Permana  
- Rizty Maulida Badri  

(Institut Teknologi Sumatera)

---

## 🎯 Tujuan
1. Menentukan parameter optimal DBSCAN (`epsilon` dan `minPts`).
2. Mengelompokkan kecamatan di Muara Enim berdasarkan kepadatan penduduk.
3. Mengevaluasi kualitas clustering dengan Silhouette Score, DBI, dan Dunn Index.
4. Mengidentifikasi pola kepadatan penduduk berdasarkan lokasi geografis.

---

## ⚙️ Instalasi
Clone repository ini lalu install dependensi:

```bash
git clone https://github.com/username/muara-enim-dbscan.git
cd muara-enim-dbscan
pip install -r requirements.txt
```


---

## 📊 Hasil Penelitian

- **Parameter Optimal**:  
  - `epsilon = 0.23`  
  - `minPts = 5`

- **Evaluasi Klaster**:  
  - Silhouette Score = **0.475289**  
  - Davies–Bouldin Index = **0.634530**  
  - Dunn Index = **0.9982**

- **Kategori Wilayah**:
  - **Cluster Rendah**: Gelumbang, Lembak, Sungai Rotan, Muara Belida, Kelekar, Belida Darat (~93.18 jiwa/km²)  
  - **Cluster Sedang**: Wilayah dekat ibu kota kabupaten (~132.70 jiwa/km²)  
  - **Noise/Outlier**: Semende Darat Laut, Semende Darat Ulu, Semende Darat Tengah, Tanjung Agung, Panang Enim (~52.89 jiwa/km²)  

- **Insight Penting**:  
  Kepadatan penduduk dipengaruhi kedekatan dengan ibu kota kabupaten.
  
---

## 🔮 Rekomendasi Pengembangan
- Bandingkan DBSCAN dengan algoritma lain (K-Means, HDBSCAN, OPTICS).  
- Optimasi parameter DBSCAN dengan heuristic (misalnya k-dist plot).  
- Tambahkan fitur demografis lain (GDP per kapita, fasilitas pendidikan/kesehatan).  
- Kembangkan visualisasi interaktif dengan **Plotly** atau **Folium**.  

---

## 📚 Referensi
- Fadhlillah, R., Zamzami, B. D. F., Karim, G. A., Rachman, A., Azzira, K. L., Irawati, F. D., Permana, R. D., & Badri, R. M. (2024).  
  *Analisis Klasterisasi Kepadatan Penduduk Kabupaten Muara Enim Menggunakan Algoritma DBSCAN*.  
  PROSIDING SEMINAR NASIONAL SAINS DATA, 4(1), 982–992.  
  DOI: [10.33005/senada.v4i1.393](https://doi.org/10.33005/senada.v4i1.393)

---

## 📜 Lisensi
Proyek ini menggunakan lisensi **MIT License** – silakan gunakan, modifikasi, dan distribusikan dengan bebas.

---

## 🙌 Acknowledgement
Terima kasih kepada **BPS Kabupaten Muara Enim** sebagai sumber data dan **Institut Teknologi Sumatera** atas dukungan dalam penelitian ini serta UPN Veteran Jawa Timur yang telah memberikan kesempatan untuk bergabung di SENADA 2024.
