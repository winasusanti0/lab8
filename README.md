# WINA SUSANTI - NIM 352310473
# Penjelasan Program

Program ini merupakan implementasi sederhana dari konsep pemrograman berorientasi objek menggunakan bahasa Python. Dalam program ini terdata informasi seperti nama, umur, NIM (Nomor Induk Mahasiswa), dan alamat.  berikut perintah pemogramannya : 

![perintah 1](https://github.com/user-attachments/assets/3487975b-a5ac-441d-b7a8-3005c6f637eb)
![perintah 2](https://github.com/user-attachments/assets/2fd94a71-68e0-4bf4-899b-005453e095f2)
![perintah 3](https://github.com/user-attachments/assets/b1e13158-8a45-44c8-a465-d6b0723db1b2)
![perintah 4](https://github.com/user-attachments/assets/8777bb86-7ec5-4890-9f11-7d1ed4fcb491)
![perintah 5](https://github.com/user-attachments/assets/0c87abd5-8400-45c0-8c25-971915e40e8b)


## Kelas `Person`

Kelas `Person` adalah kelas dasar yang menyimpan informasi umum tentang individu. Di dalam kelas ini, ada dua atribut utama: `nama` dan `umur`. Atribut `nama` adalah public, sehingga dapat diakses langsung dari luar kelas. Namun, untuk atribut `umur`, kita menggunakan private attribute, yang disimpan dengan awalan dua garis bawah (`__`). Ini dilakukan untuk melindungi data usia dari akses langsung dan untuk mencegah perubahan tidak terduga yang dapat menyebabkan kesalahan dalam logika program.

Kelas ini juga menyediakan metode getter dan setter untuk atribut `umur`. Metode getter memungkinkan pengguna untuk mengambil nilai dari atribut `umur`, sementara setter memungkinkan pengguna untuk menetapkan nilai baru. Namun, setter dilengkapi dengan validasi untuk memastikan bahwa umur yang diberikan tidak negatif. Jika nilai negatif diberikan, maka setter akan mengeluarkan pengecualian (exception) dengan pesan yang sesuai. Dengan cara ini, kita dapat menjaga konsistensi dan integritas data.

## Kelas `Mahasiswa`

Kelas `Mahasiswa` adalah turunan dari kelas `Person`. Ini berarti bahwa `Mahasiswa` mewarisi semua atribut dan metode yang ada di kelas `Person`. Namun, kelas ini juga menambahkan beberapa atribut dan metode baru yang spesifik untuk mahasiswa.

contoh Atributnya :
- **nim**: Atribut ini merupakan identifikasi unik untuk setiap mahasiswa.
- **alamat**: Atribut ini menyimpan informasi mengenai tempat tinggal mahasiswa.

contoh Metode:
- **set_alamat(alamat)**: Metode ini digunakan untuk mengatur alamat mahasiswa.
- **tampilkan_data()**: Metode ini menampilkan semua informasi yang relevan tentang mahasiswa, termasuk nama, NIM, alamat, dan umur.

## Kelas `Daftar Nilai Mahasiswa`

Kelas `DaftarNilaiMahasiswa` berfungsi sebagai koleksi untuk menyimpan data dari objek `Mahasiswa`. Kelas ini memiliki beberapa metode untuk mengelola data mahasiswa, termasuk menambah, menampilkan, menghapus, dan mengubah informasi mahasiswa.

contoh Atribut :
- **data_mahasiswa**: Ini adalah daftar (list) yang menyimpan semua objek mahasiswa yang telah ditambahkan.

contoh Metode :
- **tambah(mahasiswa)**: Metode ini digunakan untuk menambahkan objek mahasiswa baru ke dalam daftar.
- **tampilkan()**: Metode ini melakukan iterasi melalui semua mahasiswa dalam daftar dan mencetak informasi mereka dengan cara yang terstruktur.
- **hapus(nama)**: Metode ini memungkinkan pengguna untuk menghapus mahasiswa dari daftar berdasarkan nama.
- **ubah(nama, umur=None, alamat=None)**: Metode ini memungkinkan pengguna untuk memperbarui informasi mahasiswa, seperti umur dan alamat.


# Diagram alur : 

![diagram salsa](https://github.com/user-attachments/assets/6f9fb214-d407-4781-8898-ea656270ef96)

# flowchart : 

![flowchart](https://github.com/user-attachments/assets/b06c4fa7-84ed-47be-8bd7-57a40cce5b8e)
