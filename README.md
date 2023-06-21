# Heating-Load-Cooling-Load-Prediction
Memprediksi *Heating Load* serta *Cooling Load* pada Suatu Bangunan dengan Delapan Parameter Bentuk Bangunan.

Final Project Aljabar Linear Lanjut 2022.

Kelompok 3:
1. Gemilang Bagas Ramadhani (2006535205)
2. Imam Azka Ramadhan (2006577504)
3. Muhammad Raihan Azhari (2006468320)
4. Zana Niswah Awahita (2006577593)

## Penjelasan tentang dataset
Dataset yang kami gunakan sendiri dihasilkan dari simulasi analisis energi dari 12 model dasar dari bangunan yang berbeda menggunakan Autodesk Ecotect Analysis. 12 bangunan tersebut berbeda dalam beberapa parameter, yaitu:

*   Relative compactness (X1)
*   Surface area (X2)
*   Wall area (X3)
*   Roof area (X4)
*   Overall height (X5)
*   Orientation (X6)
*   Glazing area (X7)
*   Glazing area Distribution (X8)

lalu, parameter tersebut akan menentukan nilai dari heating load (Y1) dan cooling load (Y2)

12 model dasar tersebut memiliki memiliki beberapa parameter yang statis, yaitu relative compactness, surface area, wall area dan roof area. sedangkan untuk parameter yang bervariasi adalah overall height, orientation, glazing area dan glazing area distribution. parameter yang bervariasi tadi membuat dataset memiliki 768 model bangunan yang berbeda, dengan nilai heating load dan cooling load masing-masing.

Selanjutnya, data tersebut akan dicari korelasinya untuk mendesain bangunan agar nilai cooling load dan heating load-nya optimal yang menentukan seberapa layak huni suatu bangunan.
