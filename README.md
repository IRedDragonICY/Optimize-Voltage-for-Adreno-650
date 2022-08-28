
# Optimize-Voltage-for-Adreno-650
[![Github All Releases](https://img.shields.io/github/downloads/IRedDragonICY/Optimize-Voltage-for-Adreno-650/total.svg)]()

# Compatible Devices
For Kona chipsets (Locked):
- SD865
- SD865+
- SD870 (recommendation)

Tested Phone:
- Poco F3/Redmi K40/Mi 11x

# How to use
Import configuration using "Konabess Modification".

Don't forget to always backup vendor_boot.img before using this configuration!!!

# How to Calculate Voltage
Formula
(KonaBess Number) x 2.5 + 200 = Voltage (mV)

# Voltage Comparison of Qualcomm Adreno 650 Stock with Optimize Adreno 650
Stock Adreno 650

| Clock (HZ)  | KonaBess Voltage | Real Voltage (V) | bus-freq-ddr7 | bus-min-ddr7 | bus-max-ddr7 | bus-freq-ddr8 | bus-min-ddr8 | bus-max-ddr8 | acd-level |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| 670000000 | 320-NOM-L1  | 1,05  | 11 | 11 | 11 | 11 | 11 | 11 | 0x802b5ffd |
| 587000000 | 256-NOM | 0,89  | 11 | 11 | 11 | 11 | 11 | 11 | 0x802b5ffd |
| 525000000 | 224-SVS-L2 | 0,81 | 9 | 9 | 11 | 8 | 8 | 11 | 0x802b5ffd |
| 490000000 | 192-SVS-L1 | 0,73 | 9 | 6 | 9 | 8 | 7 | 9 | 0x802b5ffd |
| 441600000 | 144-SVS-L0 | 0,61 | 9 | 6 | 9 | 8 | 7 | 9 | 0x802b5ffd |
| 400000000 | 128-SVS  | 0,57 | 7 | 6 | 9 | 8 | 6 | 9 | 0x802b5ffd |
| 305000000 | 64-LOW-SVS | 0,41 | 3 | 2 | 9 | 3 | 2 | 9 | 0x802b5ffd |

Optimized Adreno 650 ([v1.0 beta](https://github.com/IRedDragonICY/Optimize-Voltage-for-Adreno-650/releases/tag/Beta))
| Clock (HZ)  | Konabess Voltage | Real Voltage | bus-freq-ddr7 | bus-min-ddr7 | bus-max-ddr7 | bus-freq-ddr8 | bus-min-ddr8 | bus-max-ddr8 | acd-level |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| 682978000 | 225 | 0,8125 | 11 | 1 | 11 | 11 | 1 | 11 | 0x802b5ffd |
| 654000000 | 209 | 0,7725 | 11 | 1 | 11 | 11 | 1 | 11 | 0x802b5ffd |
| 635000000 | 193 | 0,7325 | 11 | 1 | 11 | 11 | 1 | 11 | 0x802b5ffd |
| 621000000 | 129 | 0,5725 | 11 | 1 | 11 | 11 | 1 | 11 | 0x802b5ffd |
| 514900000 | 65 | 0,4125 | 5 | 1 | 6 | 5 | 1 | 6 | 0x802b5ffd |
| 443890000 | 1 | 0,2525 | 1 | 1 | 5 | 1 | 1 | 5 | 0x802b5ffd |

# Bugs
If there are force closed or graphical issues, please report in the  [issues](https://github.com/IRedDragonICY/Optimize-Voltage-for-Adreno-650/issues/new).

P.S. Karena ini silicon lottery, ada beberapa chipset yang mengalami permasalahan di atas.

# Thanks to
* **[@libxzr](https://github.com/libxzr)** for KonaBess App.
* **@hmm** to Modify Konabess Application open granulated voltage.
* **I** tested myself for 24 hours with Genshin Impact and Apex Legends.

.




