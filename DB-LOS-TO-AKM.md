Ini sy lampirkan struktur database LOS yang nanti akan dimodifikasi dan disesuaikan dengan project AKM

Penjelasan:
----------
MST_DEBITUR: menampung filed2 debitur yang nanti akan dipecah menjadi debitur perosnal dan debitur perusahaan
DEB_PERSONAL: menampung detail dari data MST_DEBITUR
PRO_PENGAJUAN: merupakan table inti menyimpan data pengajuan kredit dan mendapatkan no_pengajuan
FAS_KREDIT: merupakan table inti menyimpan data untuk meregistrasikan data kreditnya nanti akan mendapatkan no_fas
PENGHASILAN_TETAP: menampung detail dari penghasilan tetap dari debitur apabila table FAS_KREDIT terisi penghasilan tetap
PENGHASILAN_TIDAK_TETAP: menampung detail dari penghasilan tidak etap dari debitur apabila table FAS_KREDIT terisi penghasilan tetap
----------
PRO_BERKAS: merupakan table inti menyimpan dan meregistrasikan data bekas
BERKAS_DETAIL: detail berkas yang akan disimpan
----------
PRO_AGUNAN: merupakan table inti meregistrasikan data agunan, no_pengajuan, dan no_fasilitas
MST_AGUNAN: merupakan data master agunan
AGUNAN_TANAH: adalah salah satu contoh data agunan tanah
Dst..
----------
MPAK_ANALISA: nanti filed dimodifikasi disesuaikan permintaan analisa online jadi table ini merupakan table untuk menghitung dan menganalisa pengajuan kredit tersebut apa tidak
