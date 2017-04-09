# TUGAS WEB SERVICE 2 MEFI FRINKAZELA NIKICA / 1154073 / D4 TI 2A

Dalam tugas Web Service 2 ini merupakan tugas yang membuat file XSD dimana lebih banyak praktek dari sebelumnya, dalam tugas ini ada 2 file yaitu file XML dan XSD. File XML digunakan untuk membuat struktur awal beberapa data dan File XSD merupakan design yang menentukan type data untuk setiap element XML.

Langkah-langkah untuk membuat file XSD :

1.Buatlah project baru di aplikasi Eclipse dengan memilih menu File->New->Project->Plug-in Development->Plug-in Project

2.Isi nama project misalnya tamu_hotel(sesuaikan dengan nama project anda) ->Next->Finish

3.Pada package explorer pilih tamu_hotel->lalu src

4.pada src klik kanan pilih new->other->folder XML-> XML file-> beri nama kamar.XML(sesuaikan dengan nama project anda)->finish

5.setelah file xml berhasil di buat isilah data atau project yang sesuai dengan apa yang anda buat.

6.setelah selesai membuat file dan mengisi data project lalu klik kanan pada file xml yang di buat tadi ->create definition

7.pilih Format :-XML Schema Encoding :-UTP-8 Width :-80

8.lalu beri nama kamar.xsd(sesuaikan dengan nama Project yang anda buat)->finish

9.setelah semua sudah terbentuk lalu klik kanan pada file xsd->generate->XML File->lalu buat nama file tersebut sesuaikan dengan nama project anda

10.lalu klik file yang baru saja di buat tersebut dan copy data yang terdapat pada file tersebut seperti(xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:noNamespaceSchemaLocation="kamar.xsd")

11.lalu paste di file xml di bawah perintah :xml version="1.0" encoding="UTF-8"?>

12.lalu save hasil yang sudah di buat tersebut dan uji coba apakah file tersebut sudah terkoneksi atau tidak dengan cara di file kamar.xml klik kanan->validate

13.sesudah berhasil kita akan membuat agar data email yang terdapat di file XML menggunakan tanda (@ dan .)

14.masuk ke file XSD lalu pilih email lalu di bawah terdapat properties->constraints->patterns->add

15.masukkan di current regular expression:masukkan (@ dan .)->finish

16.lalu klik kanan pada file xml->validate kalau berhasil anda sudah membuat file XSD dan pattern di file XSD

Demikianlah langkah-langkah cara pengerjaan file xsd dan pattern pada XSD.
