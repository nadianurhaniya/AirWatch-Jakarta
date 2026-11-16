# AirWatch Jakarta

Dashboard pemantauan kualitas udara (ISPU) DKI Jakarta berbasis web, dibuat untuk tugas Visualisasi Data, Departemen Informatika, Universitas Diponegoro.

**Dashboard:** https://nadianurhaniya.github.io/AirWatch-Jakarta/
**Dataset bersih (Zenodo):** [isi link Zenodo]

## Tujuan
Dashboard dirancang secara *goal-driven* untuk membantu pemerintah daerah (pengelola pemantauan kualitas udara) menjawab tiga Critical Business Questions (CBQ):

| CBQ | Pertanyaan | KPI |
|---|---|---|
| 1 | Stasiun mana yang memiliki ISPU tertinggi? | Rata-rata ISPU, ISPU maksimum, peringkat stasiun |
| 2 | Seberapa sering udara berada di kategori Tidak Sehat ke Atas (ISPU > 100)? | Jumlah pengamatan, persentase, jumlah hari per stasiun |
| 3 | Bagaimana perubahan ISPU dari bulan ke bulan? | Rata-rata bulanan, perubahan absolut dan persen, jumlah periode naik, perbandingan bulan sama antartahun |

## Tata Letak (3 Zona)
1. **Zona 1, Ringkasan:** filter periode dan stasiun, tiga scorecard.
2. **Zona 2, Tren:** rata-rata ISPU bulanan dan perubahan terhadap bulan sebelumnya.
3. **Zona 3, Perbandingan:** perbandingan stasiun, jumlah hari ISPU > 100, dan perbandingan 2024 vs 2025.

Fitur interaktif: filter periode, filter stasiun, toggle poin/persen, dan tooltip pada setiap grafik.

## Data
- **Sumber:** Satu Data Jakarta, data ISPU DKI Jakarta
- **Periode:** 1 Januari 2024 – 30 November 2025
- **Cakupan:** 5 stasiun pemantauan, 3.480 observasi valid setelah pembersihan
- **Kategori ISPU:** mengacu pada Permen LHK No. P.14/2020 (Baik 0–50, Sedang 51–100, Tidak Sehat 101–200, Sangat Tidak Sehat 201–300, Berbahaya > 300)

## Cara Menjalankan
Dashboard berupa satu file `index.html`.
1. Unduh `index.html`.
2. Buka dengan browser (Chrome, Edge, atau Firefox). Perlu koneksi internet untuk memuat pustaka grafik.

Atau buka langsung melalui tautan dashboard di atas.

## Teknologi
HTML, CSS, dan JavaScript. [isi pustaka grafik yang dipakai, mis. Plotly.js]

## Tim (Kelompok 9)
- Khanza Qaila
- Nadia Azura Nurhaniya
- Olivia Oktaviani
- Adelia Clearesta

**Dosen pengampu:** Dinar Mutiara Kusumo Nugraheni, S.T., M.InfoTech.(Comp)., Ph.D.

## Sitasi Data
[isi sitasi Zenodo setelah dataset dipublikasikan]
