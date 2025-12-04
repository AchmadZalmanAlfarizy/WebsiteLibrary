# Frontend

Ini adalah proyek frontend yang dibangun menggunakan Vue.js 3.

## Deskripsi

Proyek ini merupakan bagian frontend dari aplikasi web. Dibangun dengan Vue.js 3, Vue Router untuk routing, dan Vuex untuk state management. Menggunakan Axios untuk HTTP request, Bootstrap untuk styling, dan Chart.js untuk visualisasi data.

## Fitur Utama

*   **Vue.js 3:** Framework JavaScript progresif untuk membangun antarmuka pengguna.
*   **Vue Router:** Router resmi untuk Vue.js, memungkinkan navigasi antar halaman.
*   **Vuex:** State management pattern + library untuk aplikasi Vue.js.
*   **Axios:** Promise based HTTP client untuk browser dan node.js.
*   **Bootstrap 5:** Framework CSS yang populer untuk pengembangan responsif, mobile-first.
*   **Chart.js:** Pustaka sederhana namun fleksibel untuk membuat grafik yang indah.

## Prasyarat

Sebelum menjalankan proyek ini, pastikan Anda telah menginstal:

*   **Node.js:** [https://nodejs.org/](https://nodejs.org/) (Versi terbaru disarankan)
*   **npm:** Biasanya terinstal bersamaan dengan Node.js.

## Instalasi

1. **Clone repository:**
    ```bash
    git clone <repository-url>
    ```
    Ganti `<repository-url>` dengan URL repositori Anda.

2. **Masuk ke direktori proyek:**
    ```bash
    cd frontend
    ```

3. **Install dependencies:**
    ```bash
    npm install
    ```

## Menjalankan Aplikasi

*   **Development Server:**
    ```bash
    npm run serve
    ```
    Perintah ini akan menjalankan development server. Buka browser Anda dan akses `http://localhost:8080/` (atau port yang ditentukan jika 8080 sudah dipakai). Aplikasi akan secara otomatis reload jika Anda mengubah file source.

*   **Production Build:**
    ```bash
    npm run build
    ```
    Perintah ini akan membuat build production di dalam folder `dist`. File-file di dalam folder `dist` sudah dioptimalkan dan siap untuk di-deploy ke server.
