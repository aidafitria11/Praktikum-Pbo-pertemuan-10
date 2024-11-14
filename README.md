untuk membuat mdeo dalam kelas Account untuk mengubah PIN, yaitu: changePin()
code yang di Account : ![image](https://github.com/user-attachments/assets/24efb0c3-bd1b-4ca8-a786-bb48eb07f64b) 
code yang terdapat di ATM : ![image](https://github.com/user-attachments/assets/2dd9e5c4-35bc-439b-bb98-f3f1a0b99680)
PENJELASANNYA :
•	Verifikasi PIN lama
 Langkah ini memastikan PIN yang dimasukkan sesuai dengan yang tersimpan dalam sistem.
•	Minta nasabah memasukkan PIN baru dua kali
Langkah ini bertujuan untuk menghindari kesalahan ketik dengan meminta nasabah memasukkan PIN baru dua kali.
•	Validasi bahwa kedua input PIN baru cocok
 Memastikan kedua input PIN baru yang dimasukkan nasabah adalah sama.
•	Perbarui PIN jika validasi berhasil
Jika PIN baru cocok, sistem akan memperbarui data PIN dengan nilai baru yang telah diverifikasi.
a.	Modifikasi fitur penarikan sehingga nasabah harus menyisakan saldo minimal setelah penarikan dilakukan. Misal, saldo minial adalah Rp50,000-
b.	Langkah-langkah:
i.	Tentukan saldo minimal, tambahkan konstanta MINIMUM_BALANCE dalam kelas Account
ii.	Modifikasi methode execute() dalam kelas Withdrawal untuk memeriksa apakah saldo setelah penarikan tidak kuran dari saldo minimal
iii.	Jika saldo tidak mencukupi, tampilkan pesan kesalahan
Code yang di Account : ![image](https://github.com/user-attachments/assets/676839d2-e58b-49d7-868b-2c627abc1743)
Code yang di ATM : ![image](https://github.com/user-attachments/assets/944c5d69-f0b3-4101-baee-dd9f28394165)
PENJELASANNYA :
•	Tentukan saldo minimal
Buat konstanta MINIMUM_BALANCE dalam kelas Account untuk menyimpan saldo minimal, misalnya Rp50,000.
•	Modifikasi metode execute() dalam kelas Withdrawal
Pastikan saldo yang tersisa setelah penarikan dilakukan tetap di atas saldo minimal.
•	Tampilkan pesan kesalahan jika saldo tidak mencukupi
Jika saldo setelah penarikan kurang dari saldo minimal, maka sistem akan menampilkan pesan kesalahan kepada nasabah.





