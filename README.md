Repository ini dibuat untuk tugas besar pemrograman mobile

Contributor untuk pembuatan aplikasi ini yaitu :

  1. Moch Inzhagi Hafiz (201810370311341)
  2. Bimo Gempar Buwono (201810370311345)
  3. Much Romadhoni (201810370311346)
  4. Nico Yogi Syahputra (201810370311364)

Aplikasi ini merupakan aplikasi yang berguna untuk membuat jadwal secara otomatis untuk mahasiswa. Pada awalnya aplikasi ini didesain khusus untuk mahasiswa UMM yang sedang mengikuti perkuliahan.

Fitur-fitur pada aplikasi ini yaitu :
  1. tambah kelas
  2. kelas saya
  3. jadwal saya
  4. tautan chat
  5. profil dan kontak dosen

Aplikasi ini didukung dengan cara login dan sign in menggunakan firebase, yang berarti user harus memiliki/membuat akun terlebih dahulu pada aplikasi ini, pada aplikasi ini juga menerapkan verifikasi dan authentikasi email, yang nantinya link verifikasi email akan langsung dikirm melalui email, dan juga user akan merasa tenang dengan adanya fitur ubah password yang developer buat untuk kaum pelupa password, nantinya user juga akan menerima email ganti password yang dikirim ke email user

pada fitur tambah kelas disini, pada fitur ini kami membaca/ me retrieve data yang sudah kami sediakan pada realtime database di firebase yang berisi mapel,jadwal, nama dosen dan lain-lain. awal nya jika user men click salah satu kelas pada fragment addkelas/tambah kelas ini maka nantinya kelas yang dipilih otomatis akan keisi atau berada pada fragment home, jadwal dan chat. namun kita belum bisa melakukan hal tersebut dan sudah melihat banyak referensi namun tetap tidak paham tentang bagaimana logic dari fitur tersebut yang digabungkan dengan realtime database yang ada

kemudian pada fitur yang lain seperti jadwal dan chat kita isi dengan data yang terdapat pada array langsung, bukan dari kelas yang sudah dipilih oleh user tadi pada fragment add kelas

pada menu home apabila kita mengklik salah satu mata pelajaran yang ada maka user akan langsung membuka profil dari dosen tersebut dan terdapat kontak dosen yang dapat di copy pada button yg ada

pada menu chat disini kami membuat fitur yang apabila user meng-clik salah satu mata pelajaran yang ada maka user akan langsung di arahkan ke tautan grup chat whatsapp mapel yang dipilih

kami menyadari bahwa jika kami bisa membuatnya dengan database yang bagus dan secara realtime (contoh firebase) yang berisi jadwal seluruh mata pelajaran dari berbagai jurusan dan semester yang ada dan berhasil melakukan fitur add kelas dengan baik maka aplikasi ini akan sangat berguna untuk mahasiswa umm
