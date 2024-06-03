# Pendahuluan

Untuk mengoptimalkan biaya produksi, pabrik baja `Steelproof` memutuskan untuk mengurangi konsumsi energi pada tahap pemrosesan baja. Anda harus mengembangkan model yang dapat memprediksi suhu logam.

**Proses Pengolahan Baja**

Baja diproses dalam sendok baja yang memiliki kapasitas sekitar 100 ton. Agar sendok tahan terhadap suhu tinggi, bagian dalamnya dilapisi dengan bata tahan api. Baja cair dituang ke dalam sendok dan dipanaskan hingga mencapai suhu yang diinginkan menggunakan elektroda grafit yang terdapat pada penutupnya.

Belerang dihilangkan dari logam melalui proses desulfurisasi. Komposisi kimia baja dikoreksi (dengan menambahkan paduan berupa bongkahan logam dari bunker berisi material curah atau dengan bantuan penghantar kawat), dan sampel yang diperlukan diambil.

Sebelum elemen paduan dimasukkan, suhu baja diukur dan komposisi kimianya dianalisis. Suhu kemudian dinaikkan selama beberapa menit, elemen paduan ditambahkan, dan paduan itu sendiri dibersihkan dengan gas inert. Setelah itu, paduan diaduk dan suhunya diukur kembali. Siklus ini berulang hingga komposisi kimia yang diinginkan dan suhu cair optimal tercapai.

Baja cair kemudian dimurnikan atau dipindahkan ke mesin pengecoran kontinyu yang memadatkan baja menjadi lempengan.

**Tahapan Pengerjaan Data:**

1. Pemuatan Data
2. Pre-Processing Data
3. Exploratory Data Analysis (EDA)
4. Pembuatan Model
5. Test Data
6. Kesimpulan

**Dengan Assesment Criteria Berikut:**

1. Fitur target: Suhu Terukur Terakhir
2. Metrik: MAE
3. Kriteria Penilaian:
- MAE > 8.7 — 0 SP
- 7.6 < MAE ≤ 8.7 — 4 SP
- 6.8 < MAE ≤ 7.6 — 4.5 SP
- 6.3 < MAE ≤ 6.8 — 5 SP
- 6.0 < MAE ≤ 6.3 — 5.5 SP
- MAE ≤ 6.0 —  6 SP
