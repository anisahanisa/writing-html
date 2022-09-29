# writing-html
HTML

(Hyper Text Markup Language)

HTML adalah suatu bahasa yang menggunakan tanda tanda tertentu (tag) untuk nyatakan kode kode yang harus ditafsirkan oleh browser agar halaman tersebut dapat ditampilkan secara benar. Dan di garis bawahi bahwa HTML bukan lah suatu bahasa pemograman artinya HTML tidak bisa dinamis mengolah data.

Beberapa tools tools pendukung atau memudahkan dan menambah produktifitas kita sebagai perogrammer yaitu browser dan code editor untuk code editor banyak sekali yang bisa gunakan antara lain notepad++, visual studio code, sublime text, atom dan lain-lain.

Untuk saat ini kita menggunakan visual studio code untuk tools pendukung kita dalam menjalankan HTML. Aku kan menjelaskan dasar dasar html, html bisa menuliskan tanpa structure dan kita bisa tetap menjalankan nya tetapi untuk menjalankannya dengan baik sebaiknya kita perlu html structure

Html structure

Html tersusun sebagai kesatuan dari sebuah tingkatan (family tree relationship) saat sebuah element berada di dalam element lain, makan di sebut child element. Element yang berada diatas element lain disebut juga parent element.

Html anatomy, html element itu didefinisikan dengan opening tag, content dan closing tag

Html attribute adalah properties dari sebuah html element semua html element memiliki attribute

Html comment

Programmer bisa disebut handal jika kode yang dibuat dapat dengan mudah dimengerti oleh sesame programmer didalam team.

Yang pertama buka file expoler kalian lalu tentuin dimana tempat yang mau kalian gunakan contohnya aku (d/skilvul/02-html) lalu kita check ke git bash terlebih dahulu kalau benar tinggal kasih command code . berfungsi memberitahu buat membuka code dalam alamat yang udah di tuju.

Selanjutnya buka vscodenya temen temen lalu kita tambahkan lampiran yang benema index.html supaya memberi tahu bahwa file tersebut Namanya index.html bukan yang lain lain.

Didalam vscode ada nih teman temannya shortcutnya buat structure dasarnya yaitu kita hanya menggunakan tanda ! dan sudah muncul pilihan seperti ini tinggal enter deh.

Nah sekarang tag \<title\>nya kita udah nih jadi belajar html dan \<h1\> kita tambahkan tulisan halloo dan jangan lupa langsung kita save

Selanjutnya kita lihat nih asilnya bagaiamana, caranya simple banget yang pertama kalian buka file expoler dan kalian buka file yang settingan awalnya lalu tinggal klik 2 kali atau dengan cara selanjutnya yaitu dari vscode yang menggunakan live server caranya klik kanan file index.html lalu ada opsi open with live server dan itu akan langsung otomatis ke buka dan mengikuti perubahan dalam codingan yang kita buat

Selanjutnya aku mau ganti \<h1\> hello I'am anisah dan aku mau kasih gambar nih \<img src="" alt=""\> sebelum itu aku mau siapin gambarnya terlebih dahlu kalau bisa save nya ditempat folder yang sama jadi\<img src="nama gambar yang kita buat" alt="me" width = "200"\> dan tampilannya jadi seperti ini.

Selanjutnya kita membuat link pakai engker jadi \<a href=""\>alamat yang dituju\</a\> , tapia da cara cepet nya dan terlihat rapi kita menggunakan tag \<ul\> jadi kita buat \<li\> dan dalemnya ada engker.

Aku punya tips untuk mempermudah kita gunakan seperti ini jadi ul\>li lalu dikalikan dengan kalian butuhkan tapi kita mau nih habis ini ditambah engker juga contohnya ul\>li\*3\>a nah tapi kita mau ditambahin bisa banget nih buat class atau id kalau class kita pakai "." Sedangkan id "#" jadi contohnya ul."nama classnya"\>li\*3\>a dan ul#(nama idnya)\>li\*3\>a

Nah sekarang bagaimana sih caranya kita membuat coment dalam vscode untuk kita bikin catetan catetan gitu caranya adalah block bagian code yang diingin lalau ctrl+/

Selanjutnya bagaimana sih caranya kita membuat \<ol\>order list menggunakan a, b, c atau 1, 2, 3? Caranya adalah ol\>li\*3 nah akan muncul seperti ini

\<ol type="tinggal tentuin mau A, a, 1, I"\>

\<li\>\</li\>

\<li\>\</li\>

\<li\>\</li\>

\</ol\>

Setelah itu kita mau ngasih git init nih di terminal nya yang pertama bagian pojok kanan ini kita udah pakai bash bukan powe shell, setelah itu tinggal jalanin perintah git init dan ada perubahan yang kelacak, berhasil akan ada tan U artinya untrack setelah itu kita kasih git add . setelah itu kita kasih git commit -m "add profile" selesai kalau ada perubahan nanti kita kasih git add . dan git commit -m lagi.

Selanjutnya kita mau nih kodingan kita di bungkus dengan  semantic HTML  cara nya \<section id= "profile"\> \</section\> nah kemudian kodingannya kita masukin deh kedalam \<section\> nah setelah itu kita rapihin dehh kodinganya dengan cara ctrl+shift+p

Setelah itu kita git add . lagi dan git commit -m "move all element to section profile"

Selanjutnya kita mau membuat \<form\> dengan \<h2\>judul kontak me dan di dalam \<form\> ada \<label\> nama dan email setalah itu \<input\> untuk nama menjadi text dan email \<input\> menjadi email, setelah itu kita tambahkan \<button\> send. Setelah itu kita bungkus lagi dengan semantic html \<section\> dengan id contact me dan selanjutnya kita rapihin lagi deh kodingannya.

Setelah itu kita git add . lagi dan git commit -m " add contact me"

Setelah itu kita hubungkan di github pertama buka githubnya lalu kita klik new repository selanjutnya memberikan Namanya dan pilih public creat kita sambungkan local ke internet dengan menggunakan git remote dan setelah itu menggunakan git push -u enter setelah itu kita refresh githubnya

.
