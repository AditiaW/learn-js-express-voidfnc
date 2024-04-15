
# Deskripsi
Repository ini berisi implementasi CRUD REST API dengan menggunakan Layered Architecture, ExpressJS, Prisma, dan PostgreSQL.

## Fitur-fitur CRUD:
- findProducts: Temukan produk-produk
- findProductById: Temukan produk berdasarkan ID
- insertProductById: Sisipkan produk baru
- deleteProductById: Hapus produk berdasarkan ID
- editProductById: Edit informasi produk berdasarkan ID

## Referensi
Video tutorial yang digunakan sebagai referensi dapat ditemukan di [YouTube: VoidFnc](https://www.youtube.com/watch?v=5YUTB3WGxWs).

## Cara untuk clone
1. Clone repository ini dengan menjalankan perintah berikut di terminal:
```
git clone https://github.com/AditiaW/learn-js-express-voidfnc.git
```
2. Masuk ke direktori repository:
```
cd learn-js-express-voidfnc
```
4. Install semua dependensi dengan menjalankan perintah:
```
npm i
```
5. Siapkan database Anda.
6. Ganti nama file `.env.example` menjadi `.env` dan isi dengan URL database Anda.
7. Sinkronkan model basis data dengan menjalankan perintah:
```
npx prisma db push
```
8. Jalankan Prisma Studio untuk mengelola data dengan perintah:
```
npx prisma studio
```
9. Jalankan server API dengan perintah:
```
node .
```
10. Untuk melihat route API, Anda bisa melihatnya di `src/index.js`.

Semoga bermanfaat!





