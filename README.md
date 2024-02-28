# Membuat Bootable Flashdisk Windows dengan Rufus
1. Download Windows : https://www.microsoft.com/software-download/windows11
2. Download Rufus : https://rufus.ie/id/
3. Instal rufus dan jalankan
4. Pasang flashdisk ke PC. Rufus akan mendeteksi flashdisk secara otomatis dan menampilkan namanya di dalam kolom “Device” beserta kapasitas penyimpanannya
5. Atur konfigurasi Rufus seperti yang diuraikan berikut ini:
  - Klik tombol “SELECT”, lalu cari dan klik dua kali pada file ISO Windows 11 untuk memasukkannya ke Rufus.
  - Pada bagian “Partition Scheme” pilih GPT.
  - Pada bagian “Target system” pilih UEFI (non CSM).
  - Pada bagian “Volume label”, opsi ini berfungsi untuk memberi nama pada flashdisk. Rufus sudah memberi nama secara otomatis, tapi anda juga bisa merubahnya dengan nama lain.
  - Pada bagian “File system”, pilih NTFS.
  - Pada bagian “Cluster size”, biarkan seperti apa adanya.
6. Klik tombol “Start”, Setelah Rufus selesai membuat bootable flashdisk Windows 11, klik tombol Close untuk keluar dari Rufus.
7. Restart PC dan saat booting pertama tekan F2/F9 tergantung PC untuk ke BIOS.
8. Agar laptop anda booting pertama kali dari flashdisk, maka anda perlu menempatkan Removable Devices/Nama Flasdisk ke urutan pertama. Caranya cukup mudah yaitu dengan memilih Removable Devices/Nama Flasdisk kemudian menggesernya menggunakan tombol +/- sampai urutannya di posisi teratas.
9. Untuk menyimpan setting yang telah anda lakukan, pindah ke tab Exit, pilih Exit Saving Changes kemudian pilih Yes. Atau anda bisa langsung menekan tombol F10, kemudian pilih Yes.
10. Ikuti step by step > Instal > pilih advance > Partisi/Data C > Oke.
11. Selesai.
