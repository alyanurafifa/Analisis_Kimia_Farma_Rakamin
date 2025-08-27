# Analisis_Kimia_Farma_Rakamin
Berisi query untuk membuat tabel aggregasi dari tabel-tabel yang telah ada, yaitu kf_final_transaction, kf_inventory, kf_kantor_cabang, kf_product.
Hasil tabel analisa memuat kolom-kolom:
- transaction_id : kode id transaksi,
- date : tanggal transaksi dilakukan,
- branch_id : kode id cabang Kimia Farma,
- branch_name : nama cabang Kimia Farma,
- kota : kota cabang Kimia Farma,
- provinsi : provinsi cabang Kimia Farma,
- rating_cabang : penilaian konsumen terhadap cabang Kimia 
Farma
- customer_name : Nama customer yang melakukan 
transaksi,
- product_id : kode product obat,
- product_name : nama obat,
- actual_price : harga obat,
- discount_percentage : Persentase diskon yang diberikan 
pada obat,
- persentase_gross_laba : Persentase laba yang seharusnya 
diterima dari obat dengan ketentuan berikut:
 ■ Harga <= Rp 50.000 -> laba 10%
 ■ Harga > Rp 50.000 - 100.000 -> laba 15%
 ■ Harga > Rp 100.000 - 300.000 -> laba 20%
 ■ Harga > Rp 300.000 - 500.000 -> laba 25%
 ■ Harga > Rp 500.000 -> laba 30%,
- nett_sales : harga setelah diskon,
- nett_profit : keuntungan yang diperoleh Kimia Farma,
- rating_transaksi : penilaian konsumen terhadap transaksi 
yang dilakukan.
