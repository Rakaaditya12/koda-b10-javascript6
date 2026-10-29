# Javascript6

## Mencari 20 built-in method dan 5 built-in function

## built-in method

- toUpperCase => merubah teks menjadi huruf besar.
  toUpperCase digunakan di dalam tipe data string untuk memperbesar sebuah teks, contoh misalnya jika membuat
  sebuah variabel yang bertipe data string "raka aditya", ketika menggunakan method toUpperCase(), maka output
  akan menghasilkan "RAKA ADITYA" yang sebelumnya "raka aditya".

- toLowerCase => merubah teks menjadi huruf kecil. toLowerCase digunakan di dalam tipe data string untuk memperkecil sebuah teks, contoh misalnya sebuah variabel.
  sebelumnya terdapat berisi huruf besar atau hanya ada beberapa huruf besar. contoh misalnya terdapat teks berisi
  "Jakarta, PASAR Baru", ketika menggunakan method toLowerCase(), maka output akan menghasilkan "jakarta, pasar baru"
  yang sebelumnya "JAKARTA, PASAR BARU".

- trim => untuk menghapus spasi di awal dan akhir teks. trim digunakan di dalam tipe data string untuk menghapus spasi yang berada di dalam awal / akhir teks.
  ketika membuat sebuah variabel yang di dalamnya bertipe data string, lalu isi string nya "rabu ",
  nah di dalam teks rabu tersebut terdapat spasi setelah kata rabu, maka tersebut akan beroutput
  ( rabu ), tapi jika menggunakan trim akan beroutput (rabu) yang dimana spasi tesebut sudah dihapus dengan menggunakan method trim.

- replace => mengganti bagian teks. replace digunakan di dalam tipe data string untuk mengganti bagian teks yang sudah kita buat. contoh
  ketika kita membuat variabel yang berisi string "saya suka bola", lalu
  kita menggunakan teks.replace("saya suka bola", "saya suka berenang"), maka
  output yang tadinya "saya suka bola" menjadi "saya suka berenang". cara pakainya
  di index awal nya itu untuk teks lama yang sudah kita buat, dan di index 1 untuk
  membuat sebuah teks baru agar teks yang lama berubah.

- includes string => memeriksa apakah teks berada di dalam variabel tersebut atau tidak. dalam includes (method string) digunakan untuk memeriksa apakah teks tersebut ada atau tidak di dalam string tersebut.
  jika kita menginput selain teks yang ada di dalam string tersebut, maka akan mengoutput false. contoh kita menginput
  belajar.includes("z", "x"), maka akan menghasilkan nilai false karena huruf tersebut tidak ada di dalam string.
  tapi ketika kita menginputkan belajar.includes("h", "i"), maka akan menghasilkan nilai true karena di dalam
  variabel tersebut terdapat teks h, yang di mana teks h ada di dalam kata hari dan bahasa, dan i berada di dalam kata indonesia.

- slice => mengambil sebagian teks. slice termasuk method string yang digunakan untuk mengambil sebagian teks yang berada di dalam variabel.
  disini saya membuat variabel bertipe data string: "javascript adalah bahasa pemograman". jadi ketika
  saya menggunakan javascript.slice(0, 10), maka output yang keluar akan hanya javascript nya saja,
  karena maksud dari slice(0, 10) => 0 yang berarti menghitung index awal (huruf awal), dan 10 adalah akhir dari index (huruf akhir).

- split => memecah teks menjadi array. split termasuk method string yang digunakan untuk memecah teks menjadi array.
  jika sebelumnya output string nya "saya mau pergi", ketika menggunakan kata.spit(" ") maka akan menjadi ["saya", "mau", "pergi"].

- push => menambah sebuah elemen di akhir array. push merupakan method array yang digunakan untuk menambah sebuah elemen di akhir array.
  contoh ketika menggunakan fruits.push(), maka nilai array yang sebelumnnya ["melon", "jeruk", "apel"] menjadi ["melon", "jeruk", "apel", "durian"].

- pop => menghapus sebuah elemen di akhir array. pop merupakan method array yang digunakan untuk menghapus sebuah elemen di akhir array.
  contoh ketika menggunakan colors.pop(), maka nilai array yang sebelumnya ["biru", "merah", "putih", "hitam"] menjadi ["biru", "merah", "putih"].

- shift => menhapus sebuah elemen di awal array. shift merupakan method array yang digunakan untuk menghapus sebuah elemen di awal array.
  Ketika menggunakan firstNumber.shift(), maka yang sebelumnya isi array [20, 22, 24] menjadi [22, 24].

- unshift => menambah sebuah elemen di awal array. unshift merupakan method array yang digunakan untuk menambah sebuah elemen di awal array.
  Jadi ketika misalkan saya membuat array yang berisi [30, 34, 38] dan saya gunakan unsfhit(20), maka 20 akan ditambahkan ke dalam arraynya.

- includes array => memeriksa apakah elemen tersedia. ketika menggunakan includes di array, isi includes tersebut harus sesuai dengan elemen yang tersedia di dalam arraynya.
  jika kita input di dalam includes nya selain elemen yang ada di dalam, maka akan mengoutputkan false, dan begitu pun sebaliknya.

- indexOf array => mencari indeks elemen di dalam array. jadi ketika menggunakan indexOf dan memasukkan angka yang dimana angka tersebut merupakan angka yang berada di dalam array nya
  indexOf(24), maka output nya akan memunculkan 0 karena angka 24 berada di index 0.

- join => menggabungkan elemen array menjadi teks. join untuk menggabungkan si elemen array jadi teks. jadi ketika menggunakan pergi.join(),
  yang sebelumnya elemen array ini ["saya", "mau", "pergi"]
  berubah menjadi teks biasa (saya - mau - pergi).

- reverse => membalikkan urutan elemen. reverse digunakan untuk membalikkan urutan array.
  jadi yang tadinya ["saya", "mau", "pulang"] menjadi ["pulang", "mau", "saya"].

- map => membuat array baru dari hasil pemrosesan elemen. map untuk membuat array baru dari hasil pemrosesan elemen.
  contoh jika membuat array [20, 25, 30], penggunaan nya seperti di bawah:
  maps.map((items) => items _ 2), ketika items _ 2 maka akan terjadi perkalian dimana items berasal
  dari variabel maps bertipe data array yang isinya [20, 25, 30] dan dikalikan dengan 2, dan hasilnya
  menjadi [40, 50, 60], 40 hasil dari (20 _ 2), 50 hasil dari (25 _ 2), dan 60 hasil dari (30 \* 2).

- filter => membuat array baru dari elemen yang memenuhi kondisi. filter digunakan untuk membuat elemen baru yang memenuhi kondisinya. contoh ketika membuat sebuah variabel
  bertipe data array filters = [23, 25, 29, 35], ketika menggunakan filters.filter((item) => item > 25),
  pada bagian item > 25 itu membandingkan apakah item lebih besar dari 25, karena di variabel filters nya
  berisi [23, 25, 29, 35], maka output dari pembanding item > 25 jadi [29, 35], karena 23 dan 25 tidak lebih
  besar dari 25. jadi hasil output nya adalah [29, 35].

- length => menghitung jumlah karakter, bisa menghitung pada tipe data string dan juga array. length digunakan untuk menghitung jumlah karakter di dalam tipe data string dan array di bawah.
  pada contoh bagian array di bawah, char.length merupakan cara untuk menghitung ada berapa karakter
  yang berada di dalam array tersebut. di dalam array tersebut berisi ["one", "two", "three", "four"], jadi jika kita
  gunakan method length, maka akan menghasilkan nilai 4 karena karakter tersebut dihitung mulai dari
  one, lalu ke two, lalu three, dan terakhir four. pada contoh bagian string sama seperti halnya di bagian contoh
  bagian array, hanya saja berbeda di bagian array dimulai dari index 0 (one), itu menunjukkan karakter 1 dan seterusnya,
  bagian string nya dimulai dari teks h dan pada bagian spasi nya juga termasuk sebagai karakter.

- concat => menggabungkan nilai yang terpisah menjadi satu nilai. concat digunakan untuk menggabungkan nilai yang terpisah menjadi satu nilai.
  contoh concat pada tipe data string, membuat variabel pertama namaDepan = "raka"
  dan variabel kedua namaBelakang = "aditya". ketika ingin menggabungkan variabel pertama
  dan variabel kedua menggunakan concat, maka jalankan seperti perintah di bawah, yaitu
  namaDepan.concat(" ", namaBelakang). untuk string yang berada di dalam concat (concat(" ")),
  itu berguna untuk memberikan spasi agar kedua isi variabel tidak berdempetan dan ada space nya.
  contoh concat pada tipe data array, menggabungkan variabel pertama dan variabel kedua.
  ketika menggunakan concat seperti arrayPertama.concat(arrayKedua), maka output nya akan menghasilkan
  ['nama', 'alamat', 'hobi', 'makanan', 'musik', 'favorit'], jika tidak menggunakan concat, maka kedua
  variabel tersebut harus mengoutput masing-masing dari nama variabel.

- sort => mengurutkan elemen sesuai dengan huruf awal, bisa juga dengan angka dengan angka paling terkecil ke terbesar. sort digunakan untuk mengurutkan elemen mulai dari huruf yang paling awal (a), dan angka yang paling terkecil.
  contoh di bawah mengurutkan makanan, ketika makanan.sort() maka hasil output nya bukan ["rendang", "nasi goreng", "pecel lele", "ayam goreng"],
  tapi menjadi ['ayam goreng', 'nasi goreng', 'pecel lele', 'rendang']. kenapa ayam goreng menjadi elemen paling awal ?
  karena huruf awal nya adalah a, jadi otomatis elemen tersebut akan berpindah ke posisi pertama.
  contoh lagi di bawah mengurutkan angka dari paling terkecil, array yang berisi elemen angka itu [37, 36, 39, 30, 1, 2],
  ketika menggunakan method nilai.sort() akan beroutput [1, 2, 30, 36, 37, 39]. kenapa angka 1 dan 2 berpindah ke tempat
  index 0 (untuk angka 1), dan index 1 (untuk angka 2)? karena angka 1 dan 2 merupakan angka yang paling terkecil di dalam
  variabel tersebut.

## built-in function

- prompt => untuk meminta input dari pengguna (user).
  prompt digunakan untuk meminta input dari pengguna. contoh seperti di bawah,
  membuat let input = prompt("masukkan nama") dan const namaSaya = "raka". ketika di browser,
  akan ada muncul seperti --> masukkan nama, lalu ada pilihan ok & cancel. disitu lah kita diperintahkan
  untuk menginput data yang sudah kita buat. contoh saya membuat variabel namaSaya = "raka", ketika browser
  meminta input masukkan nama, maka saya akan menginput raka, karena di bawah saya memakai pengkondisian,
  jika saya menginput raka, maka hasil nya akan selesai (break), dan menampilkan pesan dari alert di bawah.

- alert => menampilkan pesan pop up di browser. alert digunakan untuk menampilkan pesan pop up di browser, perintah di bawah, ketika saya menggunakan
  perintah alert("hellow semua"), maka di browser akan ada muncul pesan yang bertuliskan hellow semua.

- parseInt => mengubah nilai menjadi bilangan bulat. parseInt digunakan untuk mengubah sebuah nilai / angka menjadi bilangan bulat. contoh di bawah
  saya mendeklarasikan variabel yang berisi tipe data number. variabel tersebut berisi 30.3 (bilangan desimal).
  ketika saya menggunakan parseInt(angka), maka output nya hanya akan mengambil 30 saja, karena akan otomatis
  diubah menjadi bilangan bulat dari parseInt tersebut.

- parseFloat => mengubah nilai menjadi bilangan desimal. parseFloat digunakan untuk mengubah sebuah nilai / angka menjadi bilangan desimal. contoh di bawah
  saya mendeklarasikan variabel yang berisi tipe data number. variabel tersebut berisi 30.3 (bilangan desimal).
  ketika saya menggunakan parseFloat(angka), maka akan beroutput 50.8, nilai akan bernilai bilangan desimal.
  tidak memakai parseFloat juga hasilnya akan samma bernilai 50.8, karena nilai di dalam variabel tersebut
  memang sudah bernilai bilangan desimal. beda hal nya dengan ketika merubah bilangan desimal ke bilangan bulat,
  seperti contoh parseInt di atas.

- isNaN => memeriksa nilai apakah termasuk NaN. isNaN digunakan untuk memeriksa apakah si nilai tersebut termasuk NaN (Not a Number) atau bukan.
  contoh di bawah saya memakai kondisi if untuk memastikan apakah variabel nan itu NaN atau bukan.
  dan ketika saya jalankan ternyata benar, itu merupakan NaN (Not a Number) karena memang variabel
  nan isinya bernilai tipe data string.
