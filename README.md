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


4. penjelasan Skema basis data, relasi, trigger dan view

Database

Database yang saya buat ada ecommerce lalu saya gunakan untuk presentasi hari ini, lalu memulai membuat table terdiri dari table customers, orders, products. Serta orders_items.

![Database](https://github.com/wigunaputra/UAS-Basis-Data-Lanjutan/assets/114755182/1374105a-0c3a-4483-89eb-ab26b5ef9f83)

Tabel Customers, orders, products, order_items

Customers

Dalam hal ini saya membuat table customers terlebih dahulu yang berisikan tentang id customer, nama, email serta alamat customer

![Database](https://github.com/wigunaputra/UAS-Basis-Data-Lanjutan/assets/114755182/b537b59c-edaa-43d4-95e6-9514b57ce05b)

Order

Dalam hal ini saya membuat table customers terlebih dahulu yang berisikan tentang order_id, customer_id foreign key, order_date, total_amount

![Order](https://github.com/wigunaputra/UAS-Basis-Data-Lanjutan/assets/114755182/684c47bc-04fb-4bb9-b350-285a61ab3331)

products

Dalam hal ini saya membuat table customers terlebih dahulu yang berisikan tentang product_id, nama, price, deskripsi


![Products](https://github.com/wigunaputra/UAS-Basis-Data-Lanjutan/assets/114755182/348ee067-c801-4a5b-bd1d-4b7c3956a3a9)

Tabel Order items

Dalam hal ini saya membuat table customers terlebih dahulu yang berisikan tentang order_item_id,order_id foreign, product_id foreign, quantity.

![Order item](https://github.com/wigunaputra/UAS-Basis-Data-Lanjutan/assets/114755182/effaafb2-1b81-4750-a159-edf5c9865697)

Insert Data setiap tabel

![Customer Insert](https://github.com/wigunaputra/UAS-Basis-Data-Lanjutan/assets/114755182/df2c9e1c-f203-4fe1-8c70-64a9a09f6b13)

![Insert order](https://github.com/wigunaputra/UAS-Basis-Data-Lanjutan/assets/114755182/f74221e9-a6ec-4356-b959-98293855d856)

![Insert order item](https://github.com/wigunaputra/UAS-Basis-Data-Lanjutan/assets/114755182/8e162ecf-f71a-4754-a764-e7e12d2ebfd2)

![insert Products](https://github.com/wigunaputra/UAS-Basis-Data-Lanjutan/assets/114755182/904506b2-54f7-42f9-8bcc-d18edd68a177)

view 

disini berguna untuk menampilkan sedikit saja untuk menggabungkan hasilnya contoh dari customer id dan nama bisa kita cari berapa dia total spent membeli products

![View](https://github.com/wigunaputra/UAS-Basis-Data-Lanjutan/assets/114755182/3958042f-2883-4c40-8d81-1acaf4cd9b5d)

Trigger

mekanisme dalam basis data yang secara otomatis menjalankan aksi tertentu ketika ada peristiwa spesifik terjadi, seperti INSERT pada tabel.Otomatisasi Proses: Mengotomatiskan tugas rutin, seperti memperbarui data atau memvalidasi input.

![Trigger](https://github.com/wigunaputra/UAS-Basis-Data-Lanjutan/assets/114755182/2708bce8-45fe-4d5e-80c1-9752e5e6ca4e)

Agregat SUM

Agregat ini saya menggunakan SUM untuk menampilkan total order bisa dikatakn untuk customer yang membeli product ini  dengan itu saya menggunakan quarry dibawah ini

![Agregat](https://github.com/wigunaputra/UAS-Basis-Data-Lanjutan/assets/114755182/fd4b69f4-4cce-49b3-b331-0e65f37a0289)

Index

Kegunaan:
Meningkatkan Performa: Membuat indeks pada kolom customer_id di tabel Orders untuk mempercepat pencarian data.
Optimasi Database: Indeks ini membuat query yang mencari berdasarkan customer_id lebih cepat, karena mengurangi jumlah data yang harus dipindai.

![Index](https://github.com/wigunaputra/UAS-Basis-Data-Lanjutan/assets/114755182/49cc2918-cfd4-4d0d-b5a7-4a1ba1e9c53d)

Relasi terdiri dari Left join dan Inner Join

1. Left join

   Menggabungkan Tabel: Menggabungkan dua tabel dan mengembalikan semua baris dari tabel kiri (Customers), meskipun tidak ada kecocokan di tabel kanan (Orders).

![Left join](https://github.com/wigunaputra/UAS-Basis-Data-Lanjutan/assets/114755182/11641811-063a-4a40-be0a-0b8a91850b90)

2. Inner Join

   Menggabungkan Tabel: Menggabungkan dua tabel dan hanya mengembalikan baris yang memiliki kecocokan di kedua tabel (Customers dan Orders).
   Menampilkan Data yang Sesuai: Hanya menampilkan pelanggan yang memiliki pesanan.

   ![Inner Join](https://github.com/wigunaputra/UAS-Basis-Data-Lanjutan/assets/114755182/eece8346-32f5-4df0-b47b-315e0c11ad23)

3. Subquary

   Quarry ini kegunaannnya Memfilter baris yang tidak memenuhi kriteria tertentu. Mengimpor data secara selektif dari tabel lain. Menemukan nilai maksimum atau
   minimum dalam situasi tertentu.

   ![Subquarry](https://github.com/wigunaputra/UAS-Basis-Data-Lanjutan/assets/114755182/aaf4a4a8-b71b-4b4b-bdaa-9ec8f799c63c)

4. Having
   
   Kegunaan quarry ini agar kita bisa menampilkan siapa yang memspent uang lebih dari 50 dan hasilnya dari customer id 1 dan 3

   ![Having](https://github.com/wigunaputra/UAS-Basis-Data-Lanjutan/assets/114755182/224538bf-fb77-4d5d-b6b3-e7fbef8afdeb)


6. Wildcard

   untuk menemukan beberapa item dengan data yang serupa, tetapi tidak identik semisal saya ketik ‘%john%’ maka hasilnya seperti ini

   ![Wildcard](https://github.com/wigunaputra/UAS-Basis-Data-Lanjutan/assets/114755182/7cad90c0-1cab-468b-82a4-1ae4462e6ea9)





