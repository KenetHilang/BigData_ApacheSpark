# Big Data dan Data Lakehouse (A)

## Studi Kasus Apache Spark - Analisis Tren dan Volatilitas Harga Kripto 

### Anggota

| Nama   | NRP |
| -------- | ------- |
| Nathan Kho Pancras  | 5027231002    |
| Michael Kenneth Salim | 5027231002     |

## 📂 Deskripsi Kasus

> Sebuah perusahaan investasi ingin memahami pola dan volatilitas harga dari beberapa mata uang kripto utama untuk merancang strategi investasi yang lebih efektif. Mereka menyediakan data historis harga harian dari beberapa kripto, termasuk Bitcoin (BTC), Ethereum (ETH), dan masih banyak lagi.

> Dataset tersedia dalam format CSV dengan kolom: Date, Open, High, Low, Close, Volume, dan Market Cap.

## 📌 Tugas Mahasiswa

1. Preproses Data
    - Baca data dari file CSV menggunakan PySpark untuk BTC, ETH, DOGE, dan 2 kripto lainnya (bebas, total 5 crypto).
    - Pastikan kolom Date bertipe tanggal dan data diurutkan secara kronologis.

2. Analisis Tren Harga

    - Hitung rata-rata harga penutupan (Close) bulanan untuk setiap kripto.
    - Identifikasi bulan dengan rata-rata harga penutupan tertinggi dan terendah untuk setiap kripto.

3. Analisis Volatilitas

    - Hitung volatilitas harian sebagai selisih antara High dan Low.
    - Hitung rata-rata volatilitas bulanan untuk setiap kripto.
    - Identifikasi bulan dengan volatilitas tertinggi dan terendah untuk setiap kripto.
    - Hitung persentase kenaikan masing masing kripto setiap tahunnya

4. Perbandingan Antar Kripto

    - Bandingkan tren harga dan volatilitas antara 5 kripto yang dipilih.
    - Identifikasi kripto dengan tren kenaikan harga paling konsisten.
    - Identifikasi kripto dengan volatilitas tertinggi secara keseluruhan.

5. Interpretasi dan Rekomendasi

    - Berdasarkan analisis, berikan rekomendasi strategi investasi jangka pendek dan panjang untuk masing-masing kripto.