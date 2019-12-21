![image](https://user-images.githubusercontent.com/56400200/71306023-ed24ad00-240d-11ea-8a27-bd8471b8453d.png)


Di dalampraktikum 5 inimembahastentang program sederhana yang akanmenampilkandaftarnilaimahasiswamenggunakan Dictionary atau dict{}. Di bawahinimerupakankode-kode program yang digunakanbeserta output danpenjelasannya.

![image](https://user-images.githubusercontent.com/56400200/71305537-53a6cc80-2408-11ea-9859-de033692d0af.png)

•	Mendeklarasikan dictionary kosongdengannama dictionary data = {}

•	Menginputsalahsatu menu yang tersedia ((L)ihat, (T)ambah, (U)bah, (H)apus, (C )ari, (K)eluar) yang menggunakanperulangan While True

Menu "Tambah Data"

![image](https://user-images.githubusercontent.com/56400200/71305566-b5673680-2408-11ea-9859-034c7887823c.png)

Untuk menu "Tambah Data" :
•	Menggunakaninputan t danmenggunakankondisi if
•	Melanjutkanperintah di bawahnyayaitumenginput data (Nama, NIM, NilaiTugas, Nilai UTS, Nilai UAS).
•	Setelahitu, akanmengakses dictionary, nama sebagai key dan nama, NIM, tugas, uts, uas sebagai value.
•	Laluakanmencetak dictionary, setelah data diinput.

Menu "LihatNilai"

![image](https://user-images.githubusercontent.com/56400200/71305581-ecd5e300-2408-11ea-8568-5cc208316b0c.png)

Untukmenu"LihatNilai" :
•	Menggunakaninputan l danmenggunakankondisi elif
•	Menggunakankondisi if dan else
•	Untukkondisi if apabilasebelumnyasudahmelakukan input pada menu "Tambah Data" laluakanmencetak data dalambentuk list yang menggunakanperulangan for x in data.values():
•	Tetapi, jikasebelumnyatidakmelakukan input data, maka data tidakakandicetakatauditampilkandanakanmencetak TIDAK ADA DATA yang menggunakankondisi else.

Menu "Keluar"

![image](https://user-images.githubusercontent.com/56400200/71305614-38888c80-2409-11ea-999e-e1c730d9d1df.png)

Pada menu "Keluar" menggunakaninputan k danfungsipernyataan break, maka program akanberhentiataukeluar

Menu "Hapus Data"

![image](https://user-images.githubusercontent.com/56400200/71305644-aa60d600-2409-11ea-8f66-9d1c1c1570ab.png)

•	Menggunakaninputan h danmenggunakankondisi if dan else
•	Menginputnama
•	akanmenghapus data apabila data tersebutsudahdiakses.
•	Dan sebaliknya Untukkondisi if, kode yang digunakan if nama in data.keys(): dan del data[nama] yang, untukkondisi else, maka data tidakberhasildihapuskarena data tidaktersediaatautidakdiinput.

Menu "Ubah Data"

![image](https://user-images.githubusercontent.com/56400200/71305675-088db900-240a-11ea-84e2-35888350a0cd.png)

•	Menggunakaninputan u danmenggunakankondisi if else
•	Menginputnama
•	Kondisi if akanmenginput (NIM, NilaiTugas, Nilai UTS, Nilai UAS) yang akandiubahdan data berhasildiubah
•	Kondisi else apabila data belumdiakses, maka data tersebuttidakdapatdiubahatau data tidakada.

Menu "Cari Data"

![image](https://user-images.githubusercontent.com/56400200/71305701-45f24680-240a-11ea-8a65-0a9d94557720.png)

•	Menggunakaninputan c danmenggunakankondisi if else
•	Menginputnama
•	Apabila data tersebutsudahdiakses, makaakanmencetakdaftarnilaisesuaidengannama yang dicari
•	Sedangkan, jika data tersebuttidakada, makatidakakanmencetakdaftarnilai

Kondisi Else

![image](https://user-images.githubusercontent.com/56400200/71305729-923d8680-240a-11ea-957f-f67d35eba1d9.png)

Perintahuntukmemilihsalahsatu menu yang tersedia.

Contoh Output yang dihasilkan

![image](https://user-images.githubusercontent.com/56400200/71305765-01b37600-240b-11ea-9b5a-2e6c6dd8bab0.png)


