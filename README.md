
# WebGIS - Pemetaan Lokasi Gedung dan Infrastruktur ITERA

## Deskripsi

Proyek **WebGIS** ini dikembangkan untuk memetakan lokasi berbagai gedung dan infrastruktur yang ada di **Institut Teknologi Sumatera (ITERA)**. Aplikasi ini menggunakan **Leaflet.js** untuk membuat peta interaktif yang menampilkan berbagai **marker** untuk lokasi gedung, masjid, kantin, dan fasilitas kampus lainnya. Dengan menggunakan **OpenStreetMap** dan **Esri World Imagery** sebagai peta dasar, aplikasi ini memberikan tampilan peta yang mudah digunakan untuk menavigasi lokasi-lokasi penting di kampus.

Aplikasi ini dilengkapi dengan fitur-fitur seperti **MiniMap**, **Layer Control**, **deteksi lokasi pengguna**, dan **poligon** untuk menandai area tertentu.

## Fitur

- **Peta Interaktif**: Menampilkan peta interaktif dengan berbagai jenis **marker** untuk lokasi gedung dan infrastruktur di ITERA.
- **MiniMap**: Menambahkan **MiniMap** di sudut layar untuk melihat gambaran umum peta.
- **Layer Control**: Memungkinkan pengguna untuk memilih antara **OpenStreetMap** dan **Esri World Imagery** sebagai peta dasar.
- **Deteksi Lokasi Pengguna**: Fitur untuk mendeteksi lokasi pengguna dan menampilkan posisi mereka di peta.
- **Poligon dan Lingkaran**: Menandai area tertentu menggunakan **polygon** dan **circle**, seperti gedung atau bundaran.
- **Popup**: Memberikan informasi lebih lanjut tentang lokasi tertentu melalui popup yang muncul ketika marker atau area diklik.

## Teknologi yang Digunakan

- **Leaflet.js**: Pustaka JavaScript untuk membuat peta interaktif.
- **JavaScript**: Bahasa pemrograman utama untuk menambahkan fungsionalitas ke peta.
- **HTML5 & CSS3**: Untuk struktur dan styling halaman web.
- **OpenStreetMap**: Sebagai peta dasar sumber terbuka.
- **Esri World Imagery**: Sebagai alternatif peta dasar satelit.
- **Leaflet MiniMap**: Plugin untuk menambahkan MiniMap pada peta.
- **JavaScript Geolocation**: Untuk mendeteksi lokasi pengguna.

## Instalasi dan Pengaturan

Untuk menjalankan aplikasi WebGIS ini di mesin lokal Anda, ikuti langkah-langkah berikut:

### 1. Clone Repositori
Clone repositori ini ke komputer lokal Anda menggunakan Git:
```bash
git clone https://github.com/username/webgis-iteraproject.git
```

### 2. Buka File `index.html`
Setelah meng-clone repositori, buka file **`index.html`** di browser Anda untuk melihat aplikasi berfungsi. Anda bisa menggunakan **Live Server** di **Visual Studio Code** atau membuka file ini langsung di browser.

### 3. Menambahkan Marker atau Fitur Baru
Untuk menambahkan **marker** atau **overlay** baru, buka file **`script.js`** dan tambahkan kode berikut untuk menambahkan lokasi baru di peta:
```javascript
L.marker([latitude, longitude]).addTo(map).bindPopup('Nama Lokasi');
```

## Penggunaan

Aplikasi **WebGIS ITERA** ini digunakan untuk memetakan berbagai gedung dan infrastruktur penting di kampus ITERA. Pengguna dapat melakukan hal-hal berikut:

1. **Melihat Lokasi Gedung**: Pengguna dapat melihat berbagai gedung dan infrastruktur kampus ITERA yang ditandai dengan **marker** pada peta.
2. **Menjelajahi Peta**: Pengguna dapat memilih **peta dasar** yang ingin digunakan, baik itu **OpenStreetMap** atau **Esri World Imagery**.
3. **Melihat Area dengan Poligon dan Lingkaran**: Area tertentu seperti bangunan atau bundaran dapat dilihat dengan menggunakan **poligon** atau **lingkaran**.
4. **Deteksi Lokasi Pengguna**: Pengguna dapat melihat lokasi mereka sendiri di peta menggunakan fitur **deteksi lokasi**.

## Demo

Untuk melihat demo aplikasi, Anda bisa mengunjungi **[Demo WebGIS ITERA](https://username.github.io/webgis-iteraproject/)**.

## Kontribusi

Jika Anda ingin berkontribusi pada proyek ini, silakan ikuti langkah-langkah berikut:

1. **Fork repositori** ini ke akun GitHub Anda.
2. **Clone repositori fork** ke komputer lokal Anda:
   ```bash
   git clone https://github.com/username/webgis-iteraproject.git
   ```
3. **Buat branch baru**:
   ```bash
   git checkout -b fitur-baru
   ```
4. **Lakukan perubahan** dan **commit** perubahan:
   ```bash
   git add .
   git commit -m "Menambahkan fitur baru"
   ```
5. **Push perubahan** ke repositori fork:
   ```bash
   git push origin fitur-baru
   ```
6. **Buat Pull Request** ke repositori utama untuk penggabungan perubahan.

## Lisensi

Repositori ini dilisensikan di bawah **MIT License**. Silakan lihat file [LICENSE](LICENSE) untuk informasi lebih lanjut.

---

## Referensi

1. **Leaflet.js Documentation**: [https://leafletjs.com/](https://leafletjs.com/)
2. **Leaflet MiniMap Plugin**: [https://github.com/Norkart/Leaflet-MiniMap](https://github.com/Norkart/Leaflet-MiniMap)
3. **OpenStreetMap**: [https://www.openstreetmap.org/](https://www.openstreetmap.org/)
4. **Esri World Imagery**: [https://www.esri.com/en-us/arcgis/products/arcgis-online](https://www.esri.com/en-us/arcgis/products/arcgis-online)

## Contact

- **Nama**: M. Gilang Martiansyah M
- **Email**: mgilang.121450056@student.itera.ac.id
- **Github**: [github.com/username](https://github.com/username)

---

Terima kasih telah mengunjungi repositori ini! Jika Anda memiliki pertanyaan atau saran, silakan buka **issue** atau buat **pull request**.
