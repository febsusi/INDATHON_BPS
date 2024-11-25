# INDATHON_BPS

# Penggunaan Data:
1. Penumpang Transjakarta
2. Penumpang MRT
3. Penumpang LRT
4. Armada Transjakarta
5. Perjalanan Moda MRT
6. Perjalanan Moda LRT
7. Jumlah Penumpang Keberangkatan Pesawat Domestik
8. Jumlah Penumpang Keberangkatan Pesawat Luar Negeri
9. Curah Hujan
10. Lags, Triwulan, Bulan, Tahun

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

# Rata-Rata Execution Time
CPU Time 500mcs
Wall Time 97ms

