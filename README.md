# INDATHON_BPS

# Identitas Diri

Nama : Febriyeni Susi

Satuan Kerja : BPS Provinsi Maluku (Kabupaten Buru)

# Penggunaan Data:
1. Penumpang MRT
2. Penumpang LRT
3. Armada Transjakarta
4. Perjalanan Moda MRT
5. Perjalanan Moda LRT
6. Jumlah Penumpang Keberangkatan Pesawat Domestik
7. Jumlah Penumpang Keberangkatan Pesawat Luar Negeri
8. Curah Hujan
9. Lags, Triwulan, Bulan, Tahun

# Prerequisites
xgb.XGBRegressor()

Python and Jupyter Notebook

library and package :
* pandas == 2.1.4
* numpy == 1.26.4
* matplotlib == 3.7.2
* seaborn == 0.13.0
* datetime == 5.0
* sklearn
* xgboost == 2.0.2

# Pembagian Data Training dan Testing

train = df.loc[df.index < '31-01-2023']

test = df.loc[df.index >= '31-01-2023']
