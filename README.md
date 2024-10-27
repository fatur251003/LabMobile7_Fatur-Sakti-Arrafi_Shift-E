Nama: Fatur Sakti Arrafi<br>
NIM : H1D022041<br>
Praktikum Pemob Shift E<br>


<h1>ScreenShot</h1>

![alt text](https://github.com/fatur251003/LabMobile7_Fatur-Sakti-Arrafi_Shift-E/blob/main/images/Screenshot%202024-10-27%20180640.png)<br>
![alt text](https://github.com/fatur251003/LabMobile7_Fatur-Sakti-Arrafi_Shift-E/blob/main/images/Screenshot%202024-10-27%20202232.png)<br>


<h1>Cara untuk Menambahkan Komponen di halaman Ionic</h1>

1. Buka Project Ionic menggunakan Visual Code
2. Buka file folder.page.html di dalam folder src/app/folder/
3. Tambahkan Component pada folder.page.html dengan mengetikan kode berikut:
   
   "<ion-content>
  <ion-card>
    <img src = assets/images/marseler.jpg alt="Kang parkir pesawat""/>
    <ion-card-header>
      <ion-card-title><h1>Marsheller</h1></ion-card-title>
      <ion-card-subtitle>Marsheller merupakan petugas yang memiliki peran untuk mengarahkan Pesawat menuju tempat parkir yang benar</ion-card-subtitle>
    </ion-card-header>
    
  <ion-card-content>
      Ini adalah komponen card. ditambahkan oleh <b>Fatur Sakti Arrafi</b> dengan NIM <b>H1D022041</b>
    </ion-card-content>
  </ion-card>
</ion-content>

<ion-content>
  <ion-card>
    <img 'src=assets/images/pushtruck.jpg' alt="Pushback Car" />
    <ion-card-header>
      <ion-card-title><h1>Pushback Car</h1></ion-card-title>
      <ion-card-subtitle>Pushback Car merupakan kendaraan yang digunakan untuk mendorong mundur pesawat dari Apron menuju Taxiway</ion-card-subtitle>
    </ion-card-header>
  
<ion-card-content>
      Ini adalah komponen card. ditambahkan oleh <b>Fatur Sakti Arrafi</b> dengan NIM <b>H1D022041</b>
    </ion-card-content>
  </ion-card>
</ion-content>"

4. Jalankan Aplikasi dengan mengetikan iconic serve pada terminal

<h1>Penjelasan Komponen</h1>
<li>
  <ul>
    <ion-card>: Komponen utama untuk card.
    <ion-card-header>: Bagian header card, di mana kita bisa meletakkan judul dan subjudul.
    <ion-card-title>: Menentukan judul dari card.
    <ion-card-subtitle>: Menentukan subjudul dari card.
    <ion-card-content>: Bagian isi/konten card.
  </ul>
</li>
