# KISI-KISI UJIAN JAVASCRIPT SEMESTER GENAP 2023

## 1. Materi IF ELSE

Soal : 

2 orang mahasiswa yang bernama budi dan joko tidak mengetahui dimana kelas javascript dan
php ,buatkanlah program sederhana dengan menggunakan if else yang mana program tersebut bisa
mengetahui dimana kelas javascript dan php berada
kelas javascript berada di ruangan labor 103 mulai kelas jam 10:00 AM sedangkan kelas php berada di
ruangan labor 101 mulai kelas pada jam 01:00 PM
buatkan lah ruangan dan waktu mulai kelas tersebut menggunakan if,else if, dan else
jika ada seorang yang belum terdaftar di kelas maka output nya " mohon maaf anda belum mengambil kelas
kafe koding"

Output :

1. budi kelas javascript yang kamu ambil berada 
di ruangan labor 103 kelas di mulai pada jam 10:00 am
2. joko kelas php yang kamu ambil berada di ruangan 
labor 101 kelas di mulai pada jam 01:00 pm pagi
3. mohon maaf anda tidak mengambil kelas kafe koding

Code :
```
let mhs1='budi'
let mhs2='joko'
let waktuJS = ('10:00 am')
let waktuPHP = ('01:00 pm')
let ruanganJavaScript= 'labor 103'
var ruanganPHP='labor 101'
if(mhs1=='budi'){
console.log(mhs1+' kelas yang kamu ambil berada di '+ ruanganJavaScript+' kelas di mulai pukul '+waktuJS)
}else if(mhs2=='joko'){
console.log(mhs2+' kelas yang kamu ambil berada di '+ ruanganPHP+' kelas di mulai pukul '+waktuPHP)
}else{
console.log('mohon maaf anda belum terdaftar di kelas kafe koding')
}
```


## 2. Materi IF ELSE

Soal :

Sebuah kampus memiliki 10 buah kelas kelas,kelas 1-6 sedang di pakai,kelas yang ke 7 tidak di
pakai,sedangkan kelas ke 8 sedang di renovasi,kelas 9-10 tidak di pakai buatkanlah program sederhana
dengan menggunakan perulangan for dan percabangan if else

Output :

1. jika kelas yang ke 1-6 di pakai maka output 
nya kelas 1-6 sedang di pakai oleh mahasiswa
2. jika kelas 7,9,dan 10 tidak di pakai maka output nya 
kelas 7,9,10 sedang tidak di pakai
3.jika kelas 8 sedang di renovasi maka output nya kelas 
yang ke 8 sedang di renovasi



## 3. Materi FUNCTION

Soal:

Sebuah warung menjual kopi,gula dan minyak
harga:kopi=5000,gula=4000,minyak=6000
buatlah sebuah program sederhana dengan menggunakan function yang mana ketika user membeli kopi
dengan jumlah 2 bungkus maka output nya kamu membeli kopi 2 bungkus dengan harga 10.000
jika user membeli kopi 2 bungkus dan minyak 1 bungkus maka output nya kamu membeli kopi 2 bungkus dan
minyak 1 bungkus dengan total bayar 16.000

Clue:

nama=jml*harga

total=nama+nama+nama

Code :
```
function warung(kopi,gula,minyak){
var jumlahKopi
var jumlahGula
var jumlahMinyak
var harga
jumlahKopi=kopi*5000
jumlahGula=gula*4000
jumlahMinyak=minyak*6000
harga=jumlahKopi+jumlahGula+jumlahMinyak
return harga
}
console.log('anda membeli kopi 2 bungkus dan minyak 1 bungkus dengan total bayar Rp. '+warung(2,0,1))
```


## 4. Materi ARRAY

Soal :

Di dalam kafe koding terdapat 7 kelas
nama kelas 1.php
2. javascript
3. desain grafis
4. ui/ux
5. python
6. html . css
7. kotlin
Buatlah sebuah program sederhana array dan array bersarang yang mana di dalam kelas python terdapat 5
orang mahasiswa yang bernama budi,joko,ayu,dila,dan alex di kelas kotlin terdapat 3 orang mahasiswa yang
bernama suci,dona,dan satria
nah cari lah dimana letak dona berada dan kelas nya dimana menggunakan index array dan 2 buah array
bersarang

Output :

Mahasiswa kotlin yang bernama dona sedang sakit




# SOAL UJIAN JAVASCRIPT SEMESTER GENAP 2023
Mekanisme Tata Cara Ujian :
1. Ujian akan dilaksankana pada 17 juni  2023 
2. Setiap peserta dibolehkan mengerjakan 1 soal yang dipilih oleh mentor seminggu sebelum Ujian
3. Soal boleh dikerjakan di rumah, dan dikirimkan melaui github
4. Pada saat hari H ujian, Setiap peserta mempresentasikan soal yang didapatkan dengan baik (disclaimer saat presentasi peserta tidak boleh menyontek atau bertanya peserta lain)

## SOAL 1 

Buatlah sebuah funtion menghitung gaji karyawan
seorang karyawanbekerja di pt semen padang pegawai tersebut belum menerima gaji selama 6 tahun
hitunglah gaji karyawan tersebut
gaji perbulan = 2.500.000
tunjangan pertahun = 600.000
bonus yang di dapatkan mengerjakan proyek 1 proyek bonus nya 400.000 pegawai tersebut mngerjakan
proyek sebanyak 7x
hitunglah gaji karyawan tersebut

## SOAL 2

Di dalam kafe koding terdapat 7 kelas
nama kelas 1.php
2. javascript
3. desain grafis
4. ui/ux
5. python
6. html . css
7. kotlin
Buatlah sebuah program sederhana array dan array bersarang yang mana di dalam kelas python terdapat 5
orang mahasiswa yang bernama budi,joko,ayu,dila,dan alex di kelas kotlin terdapat 3 orang mahasiswa yang
bernama suci,dona,dan satria
nah cari lah dimana letak dona berada dan kelas nya dimana menggunakan index array dan 2 buah array
bersarang

Output :

Mahasiswa kotlin yang bernama dona sedang sakit


## SOAL 3

Sebuah kampus memiliki 10 buah kelas kelas,kelas 1-6 sedang di pakai,kelas yang ke 7 tidak di
pakai,sedangkan kelas ke 8 sedang di renovasi,kelas 9-10 tidak di pakai buatkanlah program sederhana
dengan menggunakan perulangan for dan percabangan if else

Output :

1. jika kelas yang ke 1-6 di pakai maka output 
nya kelas 1-6 sedang di pakai oleh mahasiswa
2. jika kelas 7,9,dan 10 tidak di pakai maka output nya 
kelas 7,9,10 sedang tidak di pakai
3.jika kelas 8 sedang di renovasi maka output nya kelas 
yang ke 8 sedang di renovasi




