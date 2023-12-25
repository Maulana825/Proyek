# BIKE SHARING DASHBOARD ✨

Project Akhir Dicoding Belajar Analisis Data dengan Python
Dashboard dibuat pada google colaboratory


## Setup environment
```
conda create --name main-ds python=3.9
conda activate main-ds
pip install numpy pandas scipy matplotlib seaborn jupyter streamlit babel
```
List library yang diperlukan
```
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import streamlit as st
```

## Run steamlit app
```
streamlit run dashboard.py
```

Pertama melakukan install library streamlit dan upload app.py sebagai file yang ingin ditampilkan di dashboard (file app.py ada pada folder dashboard)
```
!pip install -q streamlit
```
![Cuplikan layar 2023-12-25 115141](https://github.com/Maulana825/Proyek/assets/126551424/fcdc8fe4-7caf-4057-8545-72374646a9ce)

Kedua mendapatkan public IP address, karena untuk mengakses situs web streamlit wajib konfirmasikan IP publik. Adapun cara yang dilakukan disini ada me-runing kode wget berikut:
![Cuplikan layar 2023-12-25 135357](https://github.com/Maulana825/Proyek/assets/126551424/b7ba4392-d6b5-4cdc-a626-6a086056e44b)

``
!wget -q -O - ipv4.icanhazip.com
``

Ketiga Copy kode IP yang sudah didapat dari langkah kedua

![Cuplikan layar 2023-12-25 115544](https://github.com/Maulana825/Proyek/assets/126551424/6c7d40b1-0170-4e76-aa9b-e6af2c17fe9a)


Ke-empat jalankan streamlit app.py dengan klik link dari output code

``
!streamlit run dashboard.py &>/content/logs.txt & npx localtunnel --port 8501 
``

![Cuplikan layar 2023-12-25 140833](https://github.com/Maulana825/Proyek/assets/126551424/2c9e29fe-f167-4859-bade-d4e40b46df30)

Ke-lima paste dan submit kode pada bagian ini untuk menampilkan dashboard

![Cuplikan layar 2023-12-25 115343](https://github.com/Maulana825/Proyek/assets/126551424/57c014f6-52d0-43a5-a4d6-525959bdba53)

Tampilan dashboard yang sudah dijalankan
![Cuplikan layar 2023-12-25 141105](https://github.com/Maulana825/Proyek/assets/126551424/e6d80f53-ee36-4554-a631-995825145786)
![Cuplikan layar 2023-12-25 141125](https://github.com/Maulana825/Proyek/assets/126551424/2176a3e8-7e1a-4873-8916-9c22a70e23da)
