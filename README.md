# Lab2Web
Nama: Sartika Agustin
Nim: 312310174
Kelas: TI.23.A2
Matkul: Pemrograman Web 1

# PRAKTIKUM
# Membuat file dokumen HTML
Tampilan web sederhana ini dibuat menggunakan html.
![Screenshot (446)](https://github.com/user-attachments/assets/b85c34af-997d-494e-a5c6-19c9a4fc573f)
# Mendeklarasikan CSS internal
Dengan menambahkan CSS internal tampilan web jadi berubah, terdapat penambahan "border-bottom" sehingga memberikan border di bagian 
header dan pada bagian teks juga berubah, penulisan miring dan tebal dengan menggunakan css internal. Penulisan code css ini berada di dalam 
file dokumen. jika kita mendeklarasikan CSS Internal kita memberikan instruksi visual kepada browser tentang bagaimana elemen HTML harus ditampilkan di halaman web.
![Screenshot (447)](https://github.com/user-attachments/assets/336a9b2f-86bd-4505-a0bc-0b2c4559fae3)
# Menambahkan Inline CSS
Menambahkan style pada paragraf dengan menggunakan inline css/penulisan codenya berada di awal paragraf, sama seperti sebelumnya
penulisannya berada dalam satu file yang sama. Jika kita menambahkan inline CSS ke dalam elemen HTML, kita memberikan gaya langsung pada elemen tersebut, 
menggunakan atribut styledi dalam tag HTML.
![Screenshot (441)](https://github.com/user-attachments/assets/9e134931-111a-42c7-bec8-d8d4171c8940)
# Membuat CSS Eksternal
pertama buat file baru dengan nama "style_eksternal.css, lalu setelah itu isi, setelah di isi tambahkan
tag <link> pada file dokumen untuk memanggil style cssnya, sehingga tampilannya akan jadi seperti ini. CSS eksternal dapat digunakan ntuk mengelola gaya 
dalam satu file ringkasan dan menerapkannya ke beberapa halaman web sekaligus.
![Screenshot (442)](https://github.com/user-attachments/assets/28e82e26-4bfa-4947-855c-4c6598966af7)
# Menambahkan CSS Selector
Dengan menambahkan selector, kita dapat mengatur tampilan berbagai elemen di halaman web berdasarkan tipe elemen, kelas, ID, atribut, atau status tertentu.
setelah menambahkan CSS selector maka tampilannya akan seperti di bawah ini.
![Screenshot (444)](https://github.com/user-attachments/assets/c69fda2f-cfdd-4daa-bc50-b63cd58c0db7)
# Hasil Validasi CSS Eksternal
![image](https://github.com/user-attachments/assets/99c1816f-9232-4eed-87d3-1899b345ceee)



# PERTANYAAN DAN TUGAS
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 (...) dengan #intro h1 (...)? berikan penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! (<p id="paragraf-1" class="text-paragraf">)

# JAWABAN
1. Saya mengubah warna tampilan web dengan warna lain dan juga menambahkan satu bar bernama "CSS" dengan menambahkan tag "<link"
![Screenshot (450)](https://github.com/user-attachments/assets/5eff4e69-06b5-4e2c-acd1-81d7672362b7)
berikut tampilan file baru saat dibuka
![Screenshot (449)](https://github.com/user-attachments/assets/3e3caed8-1f48-408a-9845-759152248e6e)
2. Kedua elemen ini sama-sama digunakan untuk memberikan kepala dari elemen h1 dengan kelas 'intro'. tapi, perbedaannya adalah apakah di-deklarasikan melalui kelas atau melalui ID. kalau class kemungkinan untuk menggunakan deklarasi ini untuk lebih dari satu elemen melalui atribut 'class'. Sedangkan ID, memberikan satu dan hanya satu elemen untuk setiap ID. ID juga biasanya digunakan untuk membuat elemen lebih khusus.
3. yang akan ditampilkan adalah inline css, deklarasi ini akan diprioritaskan dibanding eksternal dan internal.
![Screenshot (441)](https://github.com/user-attachments/assets/9e134931-111a-42c7-bec8-d8d4171c8940)
4. Pada satu elemen HTML yang memiliki ID dan kelas yang masing-masing memiliki deklarasi CSS, deklarasi mana yang akan ditampilkan pada situs web itu tergantung pada urutan deklarasi    CSS. Deklarasi CSS yang ditampilkan pertama kali adalah yang akan diterapkan pada elemen tersebut. Jika deklarasi CSS yang pertama untuk elemen tersebut adalah berdasarkan kelas, maka deklarasi melalui kelas akan lebih tinggi prioritasnya daripada ID. Di contoh ini deklarasi ID lebih dulu:
![Screenshot (444)](https://github.com/user-attachments/assets/c69fda2f-cfdd-4daa-bc50-b63cd58c0db7)


