# Logistic-Regression-and-CIELAB-For-Classification-Serviks-Cancer

Klasifikasi Risiko Kanker Serviks Berdasarkan Citra Medis Menggunakan Logistic Regression & Ruang Warna CIELAB
Proyek ini bertujuan untuk mengidentifikasi tingkat risiko Cervical Intraepithelial Neoplasia (CIN) melalui ekstraksi fitur warna pada citra medis. Metode ini memanfaatkan transformasi ruang warna CIELAB untuk menangkap informasi kromatik yang lebih akurat dibandingkan ruang warna RGB standar.

📋 Ikhtisar Proyek
Model dilatih untuk mengklasifikasikan citra ke dalam tiga kategori risk berdasarkan karakteristik visualnya (milky, opaque, transparent):

CIN 3 (High Risk) - Kategori: Milky

CIN 2 (Moderate Risk) - Kategori: Opaque

CIN 1 / Normal (Low Risk) - Kategori: Transparent

🛠️ Metodologi & Fitur Teknis
Preprocessing Citra: Transformasi dari format BGR/RGB ke ruang warna CIELAB (L* untuk luminans, a* dan b* untuk dimensi warna lawan).

Ekstraksi Fitur: Menggunakan statistik deskriptif dari kanal warna, termasuk:

Mean (Rata-rata)

Standard Deviation (Standar Deviasi)

Skewness & Kurtosis

Shannon Entropy (untuk mengukur kompleksitas tekstur/warna)

Pemodelan: Implementasi algoritma Logistic Regression dengan Standard Scaling melalui Pipeline Scikit-learn.

Evaluasi: Analisis performa menggunakan Accuracy, Recall, Confusion Matrix, dan Classification Report.

🚀 Teknologi yang Digunakan
Bahasa: Python

Library Utama: * Analisis Data: Pandas, NumPy, SciPy

Pengolahan Citra: OpenCV (cv2), Scikit-image, PIL

Visualisasi: Matplotlib, Seaborn

Machine Learning: Scikit-learn

Contributor
@gracyanurmalasinurat
