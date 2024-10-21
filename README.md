# Pratikum3

## Membuat Repository

### Membuat akun github

pertama tama yang pasti anda harus membuat akun gituhub terlebih dahulu, buatlah akun pada github.com
apabila sudah membuat/memiliki akunnya silahkan login dan akan ada tampilan profil seperti ini:

![Screenshot 2024-10-21 211314](https://github.com/user-attachments/assets/6412b8c3-5c1a-426c-8858-b9c24b9d083c)

### Membuat File
setelah itu silahkan kembalik ke menu home dan nekan menu NEW:

![Screenshot 2024-10-21 223903](https://github.com/user-attachments/assets/b3581a21-9e37-4b88-a158-50fdaabe52ff)

setelah setelah di tekan silakhkan isi nama dari file repository dan pilih menu publik dari 2 menu tersebut,
lalu tekan Create Repository :

![Screenshot 2024-10-21 223950](https://github.com/user-attachments/assets/ea54c45e-4105-4fd0-830c-6b69e3dc3ba0)

### memasang git tools

kemudian anda harus download terlebih dahulu  Git Tool dengan melakuan percarian di chrome "Gistscm",
lalu tekan download for windows

![Screenshot 2024-10-21 193736](https://github.com/user-attachments/assets/8be342db-48bf-44b9-bc6a-2ee0cbff75fe)

lalu tekan click here to download

![Screenshot 2024-10-21 193835](https://github.com/user-attachments/assets/c776a991-e2e6-44c3-a05f-e4b100ddbdbf)

setelah itu kalian masuk ke proses penginstalan git tools yang sudah kalian download lalu klik next teruh hingga tampilannya berubah lalu tekan instal,
tunggu hingga proses penginstalan selesai hingga tampilannya seperti ini: lalu centang kedua pilihan tersebut.

![Screenshot 2024-10-21 195508](https://github.com/user-attachments/assets/3ff9c5d1-927c-41f0-a0d9-3c576a0768b5)

### mengoperasian Git Tools

setelah selesai melakukan penginstalan maka tampilannya akan seperti ini:

![Screenshot 2024-10-21 225324](https://github.com/user-attachments/assets/4a922cd7-da8f-4559-b358-eae3e41ae126)

Selanjutnya kalian masukan kode kode tersebut, kode tersebut yang berupa "pwd" adalah untuk memeriksa data file sebelum memulai ke langkah berikutnya,
selanjutnya kalian kembali ke dalam web github untuk mengcopy link repository yang sudah kalian buat, tekan kolom "Code" lalu salin code tersebut :

![Screenshot 2024-10-21 225854](https://github.com/user-attachments/assets/54b8c182-da66-421a-8b87-adac06163d75)

lalu kembali ke fit tools dan lanjutkan dengan code "git clone copy link yang tadi", lalu cari file README.md pada file Web1La1:

![Screenshot 2024-10-21 230508](https://github.com/user-attachments/assets/c71c9011-073d-43d0-bdfc-3fe26745162c)


lalu buka file README.md dengan vs code mkan tampolan dari README.md kalian akan seperti ini:

![vsc](https://github.com/user-attachments/assets/d6a92ae7-aef6-483d-a7cb-b1a53010975b)

lalu anda buat file baru:

![newfile](https://github.com/user-attachments/assets/be70b973-63d9-4e88-b7dc-8548f3fd59ac)

lalu diganti menjadi Python:

![py](https://github.com/user-attachments/assets/528a8424-f8d1-467e-b85d-1384d58d6437)

dan save sesuai dengan keinginan anda:

![Screenshot 2024-10-21 231243](https://github.com/user-attachments/assets/18d79ffd-39ed-48aa-993e-8c3457bacaaf)

## Membuat flowchart untuk menghitung 3 bilangan untuk menetukan bilangan terbesar

Pertama tama yang pasti anda harus membuat flowchatr terlebih dahulu seperti gambar di bawah :

![Flowchart](https://github.com/user-attachments/assets/28009564-4db4-4c4f-8a4d-8184d8cda659)

### Langkah langkah dalam flowchart

1. Mulai: Titik awal proses.

2. Input Bilangan: Minta pengguna untuk memasukkan tiga bilangan (misalnya A, B, C).

3. Bandingkan A dan B:

Jika A > B, lanjut ke langkah berikutnya.
Jika B >= A, lanjut ke langkah 5.

4. Bandingkan A dan C:

Jika A > C, maka A adalah yang terbesar.
Jika C >= A, maka C adalah yang terbesar.
Setelah itu, output hasil dan selesai.

5. Bandingkan B dan C:

Jika B > C, maka B adalah yang terbesar.
Jika C >= B, maka C adalah yang terbesar.
Setelah itu, output hasil dan selesai.

4. Output Hasil: Tampilkan bilangan yang terbesar.

7. Selesai: Titik akhir proses.

Flowchart untuk menghitung tiga bilangan dan menentukan bilangan terbesar biasanya terdiri dari beberapa langkah yang sistematis. Berikut adalah penjelasan mengenai proses tersebut:

1. Inisialisasi: Proses dimulai dengan mendefinisikan tiga bilangan yang akan dibandingkan, misalnya A, B, dan C. Input untuk bilangan ini dapat dilakukan secara manual atau melalui sistem.

2. Perbandingan Pertama: Langkah selanjutnya adalah membandingkan bilangan A dan B.

Jika A lebih besar daripada B, maka A adalah kandidat terbesar saat ini.
Jika B lebih besar atau sama dengan A, maka B menjadi kandidat terbesar.

3. Perbandingan Kedua: Setelah menentukan kandidat terbesar antara A dan B, langkah berikutnya adalah membandingkan kandidat tersebut dengan bilangan C.

Jika kandidat (A atau B) lebih besar daripada C, maka kandidat tersebut tetap sebagai bilangan terbesar.
Jika C lebih besar daripada kandidat, maka C menjadi bilangan terbesar.

4. Output: Setelah semua perbandingan selesai, hasil akhirnya adalah bilangan yang terpilih sebagai terbesar di antara ketiga bilangan tersebut. Proses ini diakhiri dengan menampilkan hasil kepada pengguna.

### Program phyton untuk mengitung 3 bilangan untuk menentukan bilangan terbesar

di sini saya memiliki program untuk menghitung 3 bilangan untuk menentukan bilangan terbesar,
di contoh saya menggunakan bilangan A yang saya isi dengan 20 dan B dengan 40 Dan C dengan 50, di bawah ini adalah contoh :

![vscode1](https://github.com/user-attachments/assets/7bf963c4-dc41-4fcc-aa06-942018686fa2)

dan di bawah inilah penejelasan daro program tersebut :

1. Input Bilangan:

- a = int(input("Masukkan bilangan A: ")): Meminta pengguna untuk memasukkan bilangan A dan mengonversinya menjadi tipe data int.

- b dan c: Dikerjakan dengan cara yang sama untuk bilangan B dan C.

2. Menentukan Bilangan Terbesar:

- Struktur Kondisional: Menggunakan if, elif, dan else untuk membandingkan ketiga bilangan.

- if a >= b and a >= c:: Mengecek apakah A lebih besar atau sama dengan B dan C. Jika ya, A adalah yang terbesar.

- elif b >= a and b >= c:: Jika kondisi sebelumnya tidak terpenuhi, memeriksa apakah B lebih besar atau sama dengan A dan C. Jika ya, B adalah yang terbesar.

- else:: Jika tidak ada kondisi di atas yang terpenuhi, maka C adalah yang terbesar.

3. Output Hasil:

4. print("Bilangan terbesar adalah:", terbesar): Menampilkan bilangan terbesar yang telah ditentukan di langkah sebelumnya.

### Cara Kerja Program

- Program ini meminta pengguna untuk memasukkan tiga bilangan.

- Dengan menggunakan logika perbandingan, program menentukan bilangan terbesar di antara ketiga bilangan tersebut.

- Hasilnya kemudian ditampilkan kepada pengguna.

### Contoh Penggunaan

Jika pengguna memasukkan:

A = 20
B = 40
C = 50

maka output yang di keluarkan adalah 

Bilangan Terbesar adalah: 50

### Selesai
