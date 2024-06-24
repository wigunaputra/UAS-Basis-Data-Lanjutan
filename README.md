# UAS-Basis-Data-Lanjutan
# Deskripsi Project

## Pengumpulan UAS Basis Data Lanjutan

## Entity Relationships Diagram

![ERD ](https://github.com/wigunaputra/UAS-Basis-Data-Lanjutan/assets/114755182/ec694191-296e-46fc-8b69-6690356298f6)

1. Deskripsi Project berisikan
   
  -Database digunakan adalah ecommere

  Lalu didalamnya ada tabel
  
  Tabel costumers
  
  Tabel products
  
  Tabel orders
  
  Tabel order_item

3. Mekanisme database
   
   dalam database ini berisikan 4 tabel dimana terdapat yaitu customers, products, orders, order_item dimana seorang customers mem order product, lalu didalam
   order terdapat beberapa order item lalu untuk order setiap item ada 1 product masing masing


4. penjelasan trigger dan view
   
view 

disini berguna untuk menampilkan sedikit saja untuk menggabungkan hasilnya contoh dari customer id dan nama bisa kita cari berapa dia total spent membeli products

![View](https://github.com/wigunaputra/UAS-Basis-Data-Lanjutan/assets/114755182/3958042f-2883-4c40-8d81-1acaf4cd9b5d)

Trigger

mekanisme dalam basis data yang secara otomatis menjalankan aksi tertentu ketika ada peristiwa spesifik terjadi, seperti INSERT pada tabel.Otomatisasi Proses: Mengotomatiskan tugas rutin, seperti memperbarui data atau memvalidasi input.

![Trigger](https://github.com/wigunaputra/UAS-Basis-Data-Lanjutan/assets/114755182/2708bce8-45fe-4d5e-80c1-9752e5e6ca4e)

Relasi terdiri dari Left join dan Inner Join

1. Left join

   Menggabungkan Tabel: Menggabungkan dua tabel dan mengembalikan semua baris dari tabel kiri (Customers), meskipun tidak ada kecocokan di tabel kanan (Orders).

![Left join](https://github.com/wigunaputra/UAS-Basis-Data-Lanjutan/assets/114755182/11641811-063a-4a40-be0a-0b8a91850b90)

2. Inner Join

   Menggabungkan Tabel: Menggabungkan dua tabel dan hanya mengembalikan baris yang memiliki kecocokan di kedua tabel (Customers dan Orders).
   Menampilkan Data yang Sesuai: Hanya menampilkan pelanggan yang memiliki pesanan.

   ![Inner Join](https://github.com/wigunaputra/UAS-Basis-Data-Lanjutan/assets/114755182/eece8346-32f5-4df0-b47b-315e0c11ad23)




