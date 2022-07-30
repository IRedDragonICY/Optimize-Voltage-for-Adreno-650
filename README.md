# Optimize-Voltage-for-Adreno-650

# Kompatibel
Untuk chipset Kona (Locked):
- SD865
- SD865+
- SD870 (rekomendasi)

Tested Phone:
- Poco F3/Redmi K40/Mi 11x

# Tata Cara Penggunaan
Import konfigurasi menggunakan "Modifikasi Konabess".

Jangan lupa selalu backup vendor_boot.img sebelum menggunakan konfigurasi ini!!!

# Cara Menghitung Voltase
Rumus
(Bilangan KonaBess) x 2.5 + 200 = Voltase (mV)

# Perbandingan Voltase Adreno 650 Stock Qualcomm dengan Optimize Adreno 650

Stock Adreno 650

| Clock (HZ)  | KonaBess Voltage | Real Voltage (V) | bus-freq-ddr7 | bus-min-ddr7 | bus-max-ddr7 | bus-freq-ddr8 | bus-min-ddr8 | bus-max-ddr8 | acd-level |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| 670000000 | 320-NOM-L1  | 1,05  |
| 587000000 | 256-NOM | 0,89  |
| 525000000 | 224-SVS-L2 | 0,81  |
| 490000000 | 192-SVS-L1 | 0,73 |
| 441600000 | 144-SVS-L0 | 0,61 |
| 400000000 | 128-SVS  | 0,57 |
| 305000000 | 64-LOW-SVS | 0,41 |

Adreno 650 yang telah di optimisasi (v1.0 beta)
| Clock (HZ)  | Konabess Voltage | Real Voltage | bus-freq-ddr7 | bus-min-ddr7 | bus-max-ddr7 | bus-freq-ddr8 | bus-min-ddr8 | bus-max-ddr8 | acd-level |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| 682978000 | 225 | 0,8125 |
| 654000000 | 209 | 0,7725 |
| 635000000 | 193 | 0,7325 |
| 621000000 | 129 | 0,5725 |
| 514900000 | 65 | 0,4125 |
| 443890000 | 1 | 0,2525 |

# Bug
Jika ada force closed atau graphical issues, silahkan report di tab [issues](https://github.com/IRedDragonICY/Optimize-Voltage-for-Adreno-650/issues/new).

P.S. Karena ini silicon lottery, ada beberapa chipset yang mengalami permasalahan di atas.

# Thanks to
* **[@libxzr](https://github.com/libxzr)** untuk Aplikasi Konabess
* **@hmm** untuk Memodifikasi Aplikasi Konabess membuka granulated voltage
* **Saya** sendiri mengetest selama 24 Jam dengan Genshin Impact dan Apex Legends





