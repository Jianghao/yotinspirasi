# yotinspirasi
Aplikasi yang akan Anda kerjakan nantinya adalah aplikasi berbasis Android, yang dibangun menggunakan React dan terhubung ke sisi backend menggunakan API. Maka dari itu, untuk memastikan Anda tidak mengalami kesulitan, maka kami akan memberikan beberapa instruksi untuk dikerjakan. Informasi Akses Login Username: JeanJTowne@dayrep.com Password: I2CYzMrNcH(oZ6afsU1ghbdY Informasi oAuth2 Client Consumer Key: 210673324 Consumer Secret: 02B6CD1019D61B700071FDD8587B7F46D52AEF4CE89A8F33129AEFBFFF81c89d Urutan pengerjaan: 1. Login. 2. Request Access Token. 3. Get Latest Articles. 4. Buat aplikasi Android menggunakan React untuk menampilkan artikel tersebut. Login URL Endpoint: https://dev.socialconnext.app/api/login Method: POST Parameters: - username : [Username] - password : [Password] Headers: - Content-Type : application/x-www-form-urlencoded Body: - CONSUMER_KEY : [Consumer Key] - CONSUMER_SECRET : [Consumer Secret] TODO: Dapatkan nilai dari session_id Request Access Token URL Endpoint: https://dev.socialconnext.app/api/request_token Method: POST Parameters: - scope : public,core,post Headers: - Content-Type : application/x-www-form-urlencoded - Cookie : PHPSESSID=[session_id] Gunakan nilai session_id yang Anda dapatkan dari tahap Login, contohnya: Cookie : PHPSESSID=etgo4eq3n00a8bovdfr2dlsr4j Body: - CONSUMER_KEY : [Consumer Key] - CONSUMER_SECRET : [Consumer Secret] TODO: Dapatkan Token Get Latest Articles URL Endpoint: https://dev.socialconnext.app/api/custom_service/?service=getlastposts Method: POST Headers: - Content-Type : application/x-www-form-urlencoded Body: - ACCESS_TOKEN : [Token] TODO: Dapatkan list artikel. Sampai sini, seharusnya Anda akan mendapatkan 10 artikel terbaru. Tampilkan 10 artikel tersebut dalam bentuk Android Apps, menggunakan React. Buatlah tampilan yang nyaman dilihat, dengan menampilkan judul, date, jumlah komentar, jumlah like, penulis, featured_image, dan 100 huruf pertama dari isi artikel