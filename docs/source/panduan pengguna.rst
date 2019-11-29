.. Sistem Informasi Reformasi Birokrasi documentation master file, created by
   sphinx-quickstart on Fri Nov 29 06:21:38 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. _Panduan_Pengguna:

Panduan Pengguna
=================================================

Berikut panduan penggunanaan SIREBI berdasarlan peran masing-masing


Admin
=================================================
	
Secara default, SIREBI mempunyai satu akun pengguna yang perannya sebagai Admin. Selanjutnya Admin dapat membuat akun untuk pengguna-pengguna lainnya sesuai dengan peran yang diinginkan.

**1. Pembuatan Akun Pengguna**

Pembuatan akun pengguna hanya dapat dilakukan oleh pengguna dengan peran atau hak akses sebagai Admin. Berikut langkah-langkah pembuatan akun pengguna.	

 1.	Admin melakukan proses otentikasi melalui halaman Login.

 	
	.. figure:: images/login.png
	   :width: 600
	   :alt: gambar 1. halaman login


  2.	Jika kombinasi nama pengguna dan password sesuai, Admin akan secara otomatis diarahkan ke halaman Dashboard.
  3.	Pilih menu Kelola Pengguna.
  4.	Lalu pada pojok kanan atas, pilih atau tekan tombol Tambah Pengguna. Selanjutnya secara otomatis Admin akan diarahkan ke halaman tambah pengguna.
  5.	Pada halaman tambah pengguna, isikan semua detail pengguna sesuai dengan kolom isian yang ada.
  6.	Pada kolom Role Pengguna, pilih peran pengguna sesuai dengan peran yang diinginkan.
  7.	Tekan simpan.
  8.  Jika data isian telah sesuai, sistem akan memberikan informasi bahwa data berhasil disimpan, dan Admin akan secara otomatis diarahkan ke halaman daftar pengguna yang sudah dibuat.
  9.  Jika data isian tidak sesuai, sistem akan memberikan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.

   2.	Melihat detail akun pengguna


 

2. Organisasi Kemahasiswaan
	
	:code:`Organisasi Kemahasiswaan` mempunyai peran untuk dapat mengajukan usulan perizinan kegiatan dan perizinan tempat. Selain itu, Organisasi Kemahasiswaan juga dapat memonitor jalannya proses perizinan yang telah diajukan. Seperti halnya melihat status pengajuan usulan kegiatan, apakah disetujui, ditolak atau masih meunggu proses pertimbangan dari pihak berwenang.


3. Wakil Dekan Bidang Kemahasiswaan
	
	Pengguna dengan peran sebagai :code:`Wakil Dekan Bidang Kemahasiswaan` mempunyai hak khusus untuk meninjau usulan perizinan kegiatan yang dilakukan oleh Organisasi kemahasiswaan. Selanjutnya, :code:`Wakil Dekan Bidang Kemahasiswaan` dapat mengambil keputusan untuk menyetujui ataupun menolak usulan perizinan kegiatan tersebut.


4. Wakil Dekan Bidang Umum dan Keuangan

	Pengguna dengan peran sebagai :code:`Wakil Dekan Bidang Umum dan Keuangan` mempunyai hak khusus untuk meninjau usulan perizinan tempat yang dilakukan oleh Organisasi kemahasiswaan. Selanjutnya, :code:`Wakil Dekan Bidang Umum dan Keuangan` dapat mengambil keputusan untuk menyetujui ataupun menolak usulan perizinan tempat tersebut.

5. Kepala Bagian Tata Usaha

	:code:`Kepala bagian Tata Usaha` mempunyai peran dan hak akses untuk memonitor jalannya proses perizinan yang dilakukan oleh Organisasi Kemahasiswaan. Selanjutnya, apabila perizinan kegiatan atau perizinan tempat disetujui oleh Wakil Dekan Bidang Kemahasiswaan dan Wakil Dekan Bidang Umum dan Keuangan, :code:`Kepala bagian Tata Usaha` akan menyiapkan surat persetujuan untuk perizinan tersebut.

6. Kasubag Akademik

	:code:`Kasubag Akademik` mempunyai hak akses untuk melakukan rekapitulasi terhadap semua proses perizinan yang sedang berjalan, sebagai bentuk kontrol dan tanggung jawab serta laporan bagi Fakultas.