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


 2.	Jika kombinasi nama pengguna dan  sesuai, Admin akan secara otomatis diarahkan ke halaman Dashboard.
 3.	Pilih menu :code:`Kelola Pengguna`.
 4.	Lalu pada pojok kanan atas, pilih atau tekan tombol :code:`Tambah Pengguna`. Selanjutnya secara otomatis Admin akan diarahkan ke halaman tambah pengguna.


  .. figure:: images/tambah-pengguna.png
     :width: 600
     :alt: gambar 2. Tambah pengguna


 5.	Pada halaman tambah pengguna, isikan semua detail pengguna sesuai dengan kolom isian yang ada.
 6.	Pada kolom peran pengguna, pilih peran pengguna sesuai dengan peran yang diinginkan.


  .. figure:: images/peran-pengguna.png
     :width: 600
     :alt: gambar 3. Peran Pengguna


 7.	Tekan tombol :code:`Simpan` untuk menyimpan data.
 8. Jika data isian telah sesuai, sistem akan memberikan informasi bahwa data berhasil disimpan, dan Admin akan secara otomatis diarahkan ke halaman daftar pengguna yang sudah dibuat. Sistem juga secara otomatis akan mengirimkan detail nama pengguna dan kata sandi ke alamat email dari pengguna yang baru saja dibuat. Detail nama pengguna dan kata sandi ini diperlukan oleh pengguna untuk proses otentikasi di halaman login ketika akan mengakses layanan SIREBI.
 9.  Jika data isian tidak sesuai, sistem akan memberikan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.

   
**2.	Melihat detail akun pengguna**

 1. Pada halaman daftar pengguna, klik tanda :code:`...` pada kolom opsi pada akun pengguna yang ingin dilihat detailnya.


  .. figure:: images/detail-pengguna.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Pilih :code:`Detail`. Sistem akan otomatis mengarahkan ke halaman detail pengguna sesuai dengan pengguna yang dipilih.


  .. figure:: images/detail-pengguna2.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


**2.  Memperbarui detail akun pengguna**

 1. Pada halaman daftar pengguna, klik tanda :code:`...` pada kolom opsi pada akun pengguna yang ingin diperbarui detailnya.


  .. figure:: images/detail-pengguna.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Pilih :code:`Edit`. Sistem akan otomatis mengarahkan ke halaman edit pengguna sesuai dengan pengguna yang dipilih.


  .. figure:: images/edit-pengguna.png
     :width: 600
     :alt: gambar 4. Edit Pengguna


**3.  Menghapus akun pengguna**

 1. Pada halaman daftar pengguna, klik tanda :code:`...` pada kolom opsi pada akun pengguna yang ingin diperbarui detailnya.


  .. figure:: images/detail-pengguna.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Pilih :code:`Hapus`. Sistem akan menampilkan jendela konfirmasi, apakah proses penghapusan akun akan diteruskan atau tidak. Pilih OK untuk mengkonfirmasi penghapusan akun. 


  .. figure:: images/hapus-pengguna.png
     :width: 600
     :alt: gambar 4. Hapus Pengguna



Organisasi Kemahasiswaan
=================================================

Untuk bisa mendapatkan akses dan menggunakan layanan SIREBI, pastikan bahwa akun Organisasi Kemahasiswaan sudah dibuat oleh Admin. Jika Admin sudah membuatkan akun untuk masing-masing Organisasi Kemahasiswaan, Organisasi Kemahasiswaan dapat mengecek pada pesan masuk di email masing-masing Organisasi Kemahasiswaan untuk mendapatkan detail nama pengguna dan kata sandi untuk proses login.


**1. Memperbarui detail akun**

 1. Lakukan proses otentikasi melalui halaman Login.
 2. Jika kombinasi nama pengguna dan kata sandi sesuai, Organisasi Kemahasiswaan akan secara otomatis diarahkan ke halaman Dashboard.
 3. Pilih menu :code:`Kelola Akun Saya`.

  
  .. figure:: images/kelola-akun-saya.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 4. Isikan data sesuai dengan kolom yang ingin diperbarui. Lalu tekan tombol :code:`Perbarui` untuk menyimpan data.
 5. Jika data yang dimasukkan valid, maka akan muncul pemberitahuan bahwa data berhasil diperbarui.


  .. figure:: images/update-berhasil.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 6. Jika data yang dimasukkan tidak valid, maka akan muncul pemberitahuan  pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui


**2. Mengajukan izin kegiatan**

 1. Pilih menu :code:`Izin Kegiatan`. Secara otomatis Organisasi Kemahasiswaan akan diarahkan ke halaman daftar Izin Kegiatan.

  
  .. figure:: images/form-kegiatan.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 2. Pilih/tekan tombol :code:`Ajukan Kegiatan Baru` pada pojok kanan atas.
 3. Lengkapi kolom isian pada form pengajuan izin kegiatan. Lampirkan file proposal kegiatan dalam bentuk :code:`PDF` atau :code:`docx`.
 4. Tekan tombol :code:`Ajukan` untuk memperoses usulan kegiatan.
 5. Jika data yang dimasukkan pada form isian valid, sistem akan memberikan pemberitahuan konfirmasi yang memberitahukan bahwa usulan kegiatan berhasil dikirimkan ke Wakil Dekan Bidang Kemahasiswaan untuk diproses. Selanjutnya sitem akan mengarahkan kita ke halaman daftar Izin Kegiatan yang telah dibuat.


  .. figure:: images/list-kegiatan.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 6. Jika data isian yang dimasukkan pada form isian tidak valid, sitem akan menampilkan pesan error. Ikuti petunjuk pada pesan error untuk mengatasi masalah yang ditemui.
 7. Status pengajuan usulan izin kegiatan dapat dilihat dalam Daftar Izin Kegiatan. Terdapat 3 status sesuai masing-masing kondisi yaitu menunggu, disetujui dan ditolak. 

  :code:`Menunggu` berarti pengajuan usulan izin kegiatan oleh Organisasi kemahasiswaan masih dalam tahap pertimbangan oleh pihak Wakil Dekan Bidang Kemahasiswaan.

  :code:`Disetujui` berarti pengajuan usulan izin kegiatan oleh Organisasi kemahasiswaan telah disetujui. Nantinya Organisasi Kemahasiswaan akan mendapatkan surat persetujuan yang dapat di unduh melalui SIREBI.

  :code:`Ditolak` berarti pengajuan usulan izin kegiatan oleh Organisasi kemahasiswaan tidak disetujui. Organisasi Kemahasiswaan dapat melihat alasan penolakan pada detail pengajuan usualan izin kegiatan. Selanjutnya jika diperlukan, Organisasi Kemahasiswaan dapat merevisi pengjuan usulan kegiatan untuk kembali diajukan ke Wakil Dekan Bidang Kemahasiswaan. 

 7. Organisasi Kemahasiswaan akan mendapatkan pemberitahuan untuk setiap perubahan status dari usulan izin kegiatan yang diajukan. Pemberitahuan dapat dilihat pada ikon lonceng di sisi kanan atas ataupun melalui email Organisasi kemahasiswaan.


**3. Melihat detail izin kegiatan**

 1. Pilih menu :code:`Izin Kegiatan`. Pada halaman daftar Izin Kegiatan, tekan tanda :code:`...` pada kolom opsi pada baris izin kegiatan yang ingin dilihat detailnya.


  .. figure:: images/kegiatan-dots.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 2. Sistem akan otomatis mengarahkan Organisasi Kemahasiswaan ke halaman detail izin kegiatan.


  .. figure:: images/detail-kegiatan.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 3. Tekan tombol kembali untuk kembali ke daftar izin kegiatan.
 4. Apabila ingin mengedit atau memperbarui data, silahkan tekan tombol :code:`Edit`.


**4. Memperbarui detail izin kegiatan**

 1. Pilih menu :code:`Izin Kegiatan`. Pada halaman daftar Izin Kegiatan, tekan tanda :code:`...` pada kolom opsi pada baris izin kegiatan yang ingin diperbarui detailnya.


  .. figure:: images/kegiatan-dots.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 2. Pilih :code:`Edit`, sistem akan otomatis mengarahkan Organisasi Kemahasiswaan ke halaman edit izin kegiatan.


  .. figure:: images/form-kegiatan.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 3. Isikan data pada kolom isian yang inging diperbarui.
 4. Tekan tombol :code:`Simpan` untuk menyimpan data.


**5. Membatalkan izin kegiatan**

 1. Pilih menu :code:`Izin Kegiatan`. Pada halaman daftar Izin Kegiatan, tekan tanda :code:`...` pada kolom opsi pada baris izin kegiatan yang ingin diperbarui detailnya.


  .. figure:: images/kegiatan-dots.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 2. Pilih :code:`Batalkan`, sistem akan otomatis menampilkan jendela konfirmasi pembatalan kegiatan.


  .. figure:: images/kegiatan-batal.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 4. Tekan tombol :code:`Ok` untuk mengonfirmasi pembatalan, tekan tombol :code:`Batal` untuk membatalkan proses pembatalan.


**6. Mengunduh surat persetujuan izin kegiatan**

 1. Pilih menu :code:`Izin Kegiatan`. Secara otomatis Organisasi Kemahasiswaan akan diarahkan ke halaman daftar Izin Kegiatan.
 2. Pada halaman daftar Izin Kegiatan, tekan tombol :code:`Detail` pada baris izin kegiatan yang sudah disetujui. Sistem akan otomatis mengarahkan Organisasi Kemahasiswaan ke halaman detail izin kegiatan.


  .. figure:: images/setuju-kegiatan.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 3. Tekan tombol :code:`Unduh Izin Kegiatan` untuk mengunduh surat persetujuan izin kegiatan.


  .. figure:: images/ok-kegiatan.png
     :width: 600
     :alt: gambar 5. Kelola Akun


**6. Mengajukan izin tempat**

 1. Pilih menu :code:`Izin Tempat`. Secara otomatis Organisasi Kemahasiswaan akan diarahkan ke halaman daftar Izin Tempat. Pilih/tekan tombol :code:`Ajukan Izin tempat` pada pojok kanan atas. Sistem akan menampilkan halaman isian Izin Tempat.

  
  .. figure:: images/tempat-list.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 3. Lengkapi kolom isian pada form pengajuan Izin Kegiatan. Lampirkan file :code:`Surat Izin Kegiatan` yang sudah didapat dari persetujuan Izin Kegiatan. Lampirkan dalam bentuk :code:`PDF` atau :code:`docx`.


  .. figure:: images/tempat-form.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 4. Tekan tombol :code:`Ajukan` untuk memperoses usulan kegiatan.
 5. Jika data yang dimasukkan pada form isian valid, sistem akan memberikan pemberitahuan konfirmasi yang memberitahukan bahwa usulan Izin Tempat berhasil dikirimkan ke Wakil Dekan Bidang Umum dan Keuangan untuk diproses. Selanjutnya sitem akan mengarahkan kita ke halaman daftar Izin Tempat yang telah dibuat.


  .. figure:: images/izin-tempat.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 6. Jika data isian yang dimasukkan pada form isian tidak valid, sitem akan menampilkan pesan error. Ikuti petunjuk pada pesan error untuk mengatasi masalah yang ditemui. 
 7. Status pengajuan usulan Izin Tempat dapat dilihat dalam Daftar Izin Tempat. Terdapat 3 status sesuai masing-masing kondisi yaitu menunggu, disetujui dan ditolak. 
 8. Organisasi Kemahasiswaan akan mendapatkan pemberitahuan untuk setiap perubahan status dari usulan Izin Tempat yang diajukan. Pemberitahuan dapat dilihat pada ikon lonceng di sisi kanan atas ataupun melalui email Organisasi kemahasiswaan.



Wakil Dekan Bidang Kemahasiswaan
=================================================
	
**1. Memperbarui detail akun**

 1. Lakukan proses otentikasi melalui halaman Login.
 2. Jika kombinasi nama pengguna dan kata sandi sesuai, Wakil Dekan Bidang Kemahasiswaan akan secara otomatis diarahkan ke halaman Dashboard.
 3. Pilih menu :code:`Kelola Akun Saya`.

  
  .. figure:: images/wadek1-pp.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 4. Isikan data sesuai dengan kolom yang ingin diperbarui. Lalu tekan Perbarui untuk menyimpan data.
 5. Jika data yang dimasukkan valid, maka akan muncul pemberitahuan bahwa data berhasil diperbarui.


  .. figure:: images/wadek1-ok.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 6. Jika data yang dimasukkan tidak valid, maka akan muncul pemberitahuan  pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui


**2. Menyetujui/Menolak usulan izin kegiatan**

 1. Pilih menu :code:`Izin Kegiatan`. Sistem akan menampilkan daftar pengajuan izin kegiatan yang sudah dibuat Organisasi Kemahasiswaan. Klik tombol :code:`Detail` pada usulan izin kegiatan yang ingin ditinjau.


  .. figure:: images/wadek-kegiatan.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 2. Sistem akan otomatis menampilkan halaman detail izin kegiatan.
 3. Unduh lampiran izin kegiatan dengan menekan tombol :code:`Unduh Lampiran` ,untuk meninjau proposal kegiatan yang diajukan oleh Organisasi kemahasiswaan.


  .. figure:: images/wadek-detail.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 4. Tekan tombol :code:`Setujui` untuk menyetujui usulan izin kegiatan. Sistem akan menampilkan jendela konfirmasi. Bila diperlukan, Wakil Dekan Bidang Kemahasiswaan dapat menambahkan catatan untuk kegiatan yang akan disetujui. Tekan tombol Setujui untuk mengonfirmasi persetujuan.


  .. figure:: images/setuju.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 5. Untuk menolak usulan izin kegiatan. Tekan tombol :code:`Tolak` pada halaman detail kegiatan. Sistem akan menampilkan jendela konfirmasi. Bila diperlukan, Wakil Dekan Bidang Kemahasiswaan dapat menambahkan catatan untuk kegiatan yang akan ditolak. Tekan tombol Ok untuk mengonfirmasi persetujuan.


  .. figure:: images/tolak.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 6. Izin kegiatan yang telah dikonfirmasi persetujuannya akan berubah statusnya dari menunggu menjadi ditolak atau disetujui.



Wakil Dekan Bidang Umum dan Keuangan
=================================================

**1. Memperbarui detail akun**

 1. Lakukan proses otentikasi melalui halaman Login.
 2. Jika kombinasi nama pengguna dan kata sandi sesuai, Wakil Dekan Bidang Umum dan Keuangan akan secara otomatis diarahkan ke halaman Dashboard.
 3. Pilih menu :code:`Kelola Akun Saya`.

  
  .. figure:: images/wadek-uk.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 4. Isikan data sesuai dengan kolom yang ingin diperbarui. Lalu tekan Perbarui untuk menyimpan data.
 5. Jika data yang dimasukkan valid, maka akan muncul pemberitahuan bahwa data berhasil diperbarui.


  .. figure:: images/wadek-uk2.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 6. Jika data yang dimasukkan tidak valid, maka akan muncul pemberitahuan  pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui


**2. Menyetujui/Menolak usulan izin tempat**

 1. Pilih menu :code:`Izin Tempat`.
 2. Klik tombol :code:`Detail` pada usulan izin tempat yang ingin ditinjau. Sistem akan otomatis menampilkan halaman detail izin tempat.


  .. figure:: images/wadek-izin-tempat.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 3. Unduh lampiran proposal izin kegiatan dengan menekan tombol :code:`Unduh Lampiran` ,untuk meninjau proposal kegiatan yang diajukan oleh Organisasi kemahasiswaan.
 4. Unduh lampiran persetujuan izin kegiatan dengan menekan tombol :code:`Unduh Lampiran` ,untuk meninjau surat persetujuan izin kegiatan yang telah disetujui oleh Wakil Dekan Bidang Kemahasiswaan.


  .. figure:: images/wadek-izin-detail.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 5. Tekan tombol :code:`Setujui` untuk menyetujui usulan izin tempat. Sistem akan menampilkan jendela konfirmasi. Bila diperlukan, Wakil Dekan Bidang Umum dan Keuangan dapat menambahkan catatan untuk usulan izin tempat yang akan disetujui. Tekan tombol Setujui untuk mengonfirmasi persetujuan.


  .. figure:: images/izin-setuju.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 6. Untuk menolak usulan izin tempat. Tekan tombol :code:`Tolak` pada halaman detail kegiatan. Sistem akan menampilkan jendela konfirmasi. Bila diperlukan, Wakil Dekan Bidang Umum dan Keuangan dapat menambahkan catatan untuk usulan izin tempat yang akan ditolak. Tekan tombol Ok untuk mengonfirmasi persetujuan.


  .. figure:: images/izin-batal.png
     :width: 600
     :alt: gambar 5. Kelola Akun


 7. Izin tempat yang telah dikonfirmasi persetujuannya akan berubah statusnya dari menunggu menjadi ditolak atau disetujui.


Kepala Bagian Tata Usaha
=================================================


	:code:`Kepala bagian Tata Usaha` mempunyai peran dan hak akses untuk memonitor jalannya proses perizinan yang dilakukan oleh Organisasi Kemahasiswaan. Selanjutnya, apabila perizinan kegiatan atau perizinan tempat disetujui oleh Wakil Dekan Bidang Kemahasiswaan dan Wakil Dekan Bidang Umum dan Keuangan, :code:`Kepala bagian Tata Usaha` akan menyiapkan surat persetujuan untuk perizinan tersebut.

Kasubag Akademik
=================================================

	:code:`Kasubag Akademik` mempunyai hak akses untuk melakukan rekapitulasi terhadap semua proses perizinan yang sedang berjalan, sebagai bentuk kontrol dan tanggung jawab serta laporan bagi Fakultas.