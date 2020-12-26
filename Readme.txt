Ide:
Menggunakan Algoritma Luhn Sebagai Penerapan Dalam Kehidupan Sehari-hari
Contoh Kasus: Terkadang Orang Menggunakan Visa Card dan saya pun terkadang memakainya.
Algoritma yang saya pakai menggunakan contoh nomor visa dummy.

Eksekusi:
Program sederhananya berjalan dengan baik.

/*Algoritma Luhn Kartu Kredit
Salah satu fungsi matematis komputasi yang bisa dipergunakan untuk memverifikasi keabsahan sebuah nomor kartu kredit adalah apa yang disebut dengan algoritma Luhn. Algoritma
ini adalah sebuah program logika cek digit kartu kredit yang dikembangkan oleh seorang ilmuan jenius perusahaan komputer IBM (International Business Machine) bernama Hans Peter Luhn. 
Sampai tulisan ini ditulis (tidak tahu kalau nanti), fungsi-fungsi dari algoritma ini masih berlaku untuk produk kartu kredit di berbagai negara termasuk di Indonesia. Anda bisa mencobanya sendiri
nanti terhadap nomor kartu kredit yang Anda miliki.

Pola Dart Dalam Regular Expression Check untuk kecocokan ekspresi dalam sebuah String:
RegExp exp = new RegExp(r"(\w+)");
Aturan yang Anda berikan sebenarnya tidak sepenuhnya memvalidasi nomor kartu kredit, mereka hanya memeriksa jumlah digit yang benar.
Perhatikan penggunaan string mentah (string yang diawali dengan r) pada contoh di atas. Gunakan string mentah untuk memperlakukan setiap karakter dalam string sebagai karakter literal.

Untuk menjelaskan ekspresi reguler yang Anda berikan:
^Berarti awal dari string dan $berarti akhir. Ini harus selalu digunakan untuk menambatkan ekspresi reguler Anda, kecuali jika Anda ingin mencocokkan pada substring dari string yang lebih besar.
[0-9]berarti sembarang digit (0 sampai 9 atau apapun di antaranya). Anda juga dapat menggunakan \duntuk ini (yang dapat dilakukan oleh salah satu contoh Anda yang lain). \dadalah karakter khusus 
yang berarti "sembarang digit". Ada beberapa karakter khusus lainnya seperti \syang berarti "sembarang karakter spasi".
{12} Berarti mengulangi huruf sebelumnya atau pola tanda kurung 12 kali (tidak lebih, tidak kurang).
(?:baru saja memulai pola tanda kurung. Perbedaan antara (?:dan (is yang (?:tidak menangkap pola untuk pengambilan nanti (menggunakan referensi kembali). Tak satu pun dari contoh-contoh ini 
menggunakan referensi balik jadi (?:tidak masalah (dan biasanya lebih efisien).
)mengakhiri pola tanda kurung. Pola tanda kurung hanya untuk menempatkan banyak huruf / pola ke dalam satu kelompok.*/

/*Notes:
Token	Artinya
^	Awal baris
$	Akhir baris
\b	Batas awal / akhir kata. Antara huruf/angka dan spasi*/