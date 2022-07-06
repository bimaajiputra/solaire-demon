Ini sy lampirkan struktur database LOS yang nanti akan dimodifikasi dan disesuaikan dengan project AKM

Penjelasan:
1. MST_DEBITUR: menampung filed2 debitur yang nanti akan dipecah menjadi debitur perosnal dan debitur perusahaan
2. DEB_PERSONAL: menampung detail dari data MST_DEBITUR
3. PRO_PENGAJUAN: merupakan table inti menyimpan data pengajuan kredit dan mendapatkan no_pengajuan
4. FAS_KREDIT: merupakan table inti menyimpan data untuk meregistrasikan data kreditnya nanti akan mendapatkan no_fas
5. PENGHASILAN_TETAP: menampung detail dari penghasilan Tetap dari debitur apabila table FAS_KREDIT terisi penghasilan tetap
6. PENGHASILAN_TIDAK_TETAP: menampung detail dari penghasilan Tidak Tetap dari debitur apabila table FAS_KREDIT terisi penghasilan tetap
7. PRO_BERKAS: merupakan table inti menyimpan dan meregistrasikan data bekas
8. BERKAS_DETAIL: detail berkas yang akan disimpan
9. PRO_AGUNAN: merupakan table inti meregistrasikan data agunan, no_pengajuan, dan no_fasilitas
10. MST_AGUNAN: merupakan data master agunan
11. AGUNAN_TANAH: adalah salah satu contoh data agunan tanah 
12. AGUNAN_OTHER Dst..
13. MPAK_ANALISA: nanti filed dimodifikasi disesuaikan permintaan analisa online jadi table ini merupakan table untuk menghitung dan menganalisa pengajuan kredit tersebut apa tidak
