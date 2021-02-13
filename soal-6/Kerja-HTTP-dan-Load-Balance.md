Bagaimana cara kerja HTTP dan Load Balance sebuah aplikasi? 

cara kerja **HTTP** dapat dijabarkan sebagai berikut :
Pertama-tama, komputer klien (HTTP klien) membuat sambungan, lalu mengirimkan permintaan dokumen ke web server.
HTTP server kemudian memproses permintaan klien, sementara itu, HTTP klien menunggu respon dari server tersebut.
Web server merespon permintaan dengan kode status data, lalu barulah menutup sambungan ketika telah selesai memproses permintaan.

Pada intinya, dalam kasus HTTP, client terlebih dahulu melakukan permintaan data kepada server, lalu kemudian server mengirimkan respon berupa file HTML yang ditampilkan dalam browser, ataupun data lainnya yang diminta oleh klien.
https://www.jagoanhosting.com/tutorial/glossary/http#:~:text=Secara%20singkat%2C%20cara%20kerja%20HTTP,menunggu%20respon%20dari%20server%20tersebut 

**Load Balancing** dirancang untuk mendistribusikan lalu lintas jaringan yang masuk secara efisien ke seluruh grup server backend, yang juga dikenal sebagai kumpulan server atau kumpulan server.
Dengan cara ini, Load Balancing melakukan fungsi berikut:
Mendistribusikan permintaan klien atau beban jaringan secara efisien di beberapa server
Memastikan ketersediaan dan keandalan tinggi dengan mengirimkan permintaan hanya ke server yang sedang online
Memberikan fleksibilitas untuk menambah atau mengurangi server sesuai permintaan
https://www.nginx.com/resources/glossary/load-balancing/