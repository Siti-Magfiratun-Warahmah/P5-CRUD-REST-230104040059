Laporan Praktikum P5: Membangun RESTful CRUD

Repositori ini berisi hasil dari Praktikum ke-5 mata kuliah Web Service Engineering. Proyek ini berfokus pada implementasi API RESTful sederhana untuk operasi CRUD (Create, Read, Update, Delete) menggunakan Node.js dan Express.js.

Identitas Mahasiswa
Nama : SITI MAGFIRATUN WARAHMAH 
NIM : 230104040059 Kelas : 
TI23B Dosen : Muhayat, M.IT 

Deskripsi Proyek
Proyek ini adalah sebuah server API sederhana yang dibuat dengan Express.js  untuk mengelola data produk. API ini mengikuti prinsip RESTful dan menggunakan metode HTTP (GET, POST, PUT, DELETE) yang sesuai dengan operasinya.

Data produk untuk sementara disimpan dalam sebuah array di dalam file src/data/products.data.js.

Teknologi yang Digunakan
- Node.js (v18+) 
- Express.js 
- Nodemon (sebagai dev dependency) 
- Postman / Thunder Client (untuk pengujian API) 

Tabel Endpoint API
Server berjalan pada http://localhost:3000 (diasumsikan dari screenshot ). Berikut adalah daftar endpoint yang telah diimplementasikan:
1. Method: GET Endpoint: /api/products Deskripsi: Mengambil semua data produk. Status Sukses: 200 OK 
2. Method: GET Endpoint: /api/products/:id Deskripsi: Mengambil data produk spesifik berdasarkan ID. Status Sukses: 200 OK Status Gagal: 404 Not Found 
3. Method: POST Endpoint: /api/products Deskripsi: Menambah data produk baru. Status Sukses: 201 Created 
4. Method: PUT Endpoint: /api/products/:id Deskripsi: Memperbarui data produk berdasarkan ID. Status Sukses: 200 OK Status Gagal: 404 Not Found 
5. Method: DELETE Endpoint: /api/products/:id Deskripsi: Menghapus data produk berdasarkan ID. Status Sukses: 200 OK Status Gagal: 404 Not Found 

Cara Menjalankan Proyek
1. Clone repositori ini: git clone https://github.com/Siti-Magfiratun-Warahmah/WSE-P5-CRUD-REST-230104040059 
2. Instal dependencies: npm install 
3. Instal Nodemon (jika belum): npm install nodemon --save-dev 
4. Jalankan server (mode development): npm run dev 
5. Uji Endpoint: Gunakan Postman atau Thunder Client untuk menguji endpoint di atas.
