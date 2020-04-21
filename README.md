# Covid-19 Cases Dashboard

Pada dashboard covid-19 ini berisi _report_ kasus-kasus persebaran wabah covid-19 di seluruh dunia. Report data yang ditampilkan berupa kasus yang terkonfirmasi positif, kematian, dan kesembuhan dari pasien covid-19. _Update_ data terbaru pada tanggal 19 April 2020. Dashboard ini bisa diakses via desktop, namun layout lebih cocok jika ditampilkan via mobile.

### A. Sumber data dan _tools_

Sumber data yang digunakan berasal dari https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset#covid_19_data.csv. Terdapat beberapa file yang disajikan dalam sumber data. Diantaranya data utama, data pada level individu, dan data time series. Pada dashboard kali ini saya mengolah data yang berada pada data utama. Informasi yang terdapat pada data utama berupa tanggal observasi, negara dan provinsi yang terinfeksi, jumlah terkonfirmasi, kematian, dan kesembuhan pasien.

Sebelum mengolah pada dashboard, data utama terlebih dahulu saya olah di jupyter notebook. Pengolahan ini bertujuan untuk mempelajari isi data, mencari ada atau tidaknya data kosong (null), melihat tipe data di masing-masing kolom, dan mengubah sebagian susunan kolom untuk keperluan visualisasi dashboard.

_Tools_ yang saya gunakan dalam membuat dashboard ini adalah Google Data Studio. Beberapa fitur chart yang saya gunakan antara lain geomaps, scorecard, line chart, donut chart, dan tabel. Fungsi dari masing-masing fitur yang saya gunakan akan saya jelaskan di bawah ini.

### B. Penerapan fitur Google Data Studio

1. Geomaps: Fitur ini saya gunakan untuk melihat tingkat persebaran kasus terkonfirmasi covid-19 pada setiap negara di seluruh dunia, dilihat dari sebuah peta dunia.

    ![Geomaps](/images/Geomaps.PNG)

2. Scorecard: Digunakan untuk melihat rangkuman total kasus terkonfirmasi, kematian, dan kesembuhan dari pasien covid-19 di seluruh dunia.

    ![Scorecard](/images/Scorecard.PNG)

3. Line Chart: Fitur ini digunakan untuk melihat arah trend perkembangan total kasus terkonfirmasi pada setiap negara di dunia.

    ![Line Chart](/images/Line_Chart.PNG)

4. Donut Chart: Digunakan untuk melihat komposisi antara kesembuhan dan kemmatian dari kasus covid-19 di seluruh dunia.

    ![Donut Chart](/images/Donut_Chart.PNG)

5. Tabel: Fitur ini digunakan untuk melihat data detail pada setiap negara dan total seluruh dunia. Data yang ditampilkan adalah data terkonfirmasi, kematian, _fatality rate_, kesembuhan, dan _recovery rate_.

    ![Table](/images/Table.PNG)

Pada masing-masing chart, jika diklik pada satu data maka fitur yang lainnya juga akan ikut menampilkan data dari yang dipilih tersebut. Misalnya, jika diklik bagian Indonesia pada geomaps, maka fitur yang lainnya juga ikut hanya menampilkan data dari negara Indonesia saja.

### C. Akses

Untuk mengakses keseluruhan tampilan dashboard interaktif ini, Anda dapat mengaksesnya di https://bit.ly/muhadyan_covid19_dashboard

Sekian dan terima kasih😊