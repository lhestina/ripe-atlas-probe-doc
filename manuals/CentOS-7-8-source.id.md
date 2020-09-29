Versi CentOS bisa digunakan untuk x86_64 (amd64). Perlu diketahui bahwa skrip instalasi dan startup ini dengan asumsi anda menggunakan `systemd`.

1. Untuk membuat dan menginstal paket software, silahkan ikuti petunjuk khusus CentOS yang terdapat di file 
   [INSTALL.rst](https://github.com/RIPE-NCC/ripe-atlas-software-probe/blob/master/INSTALL.rst)
   .

2. Setelah menginstal software probe ini, SSH Key pair baru akan terbuat, ini akan digunakan untuk menghubungkan probe ke infrastruktur RIPE Atlas. Public key ini juga diperlukan untuk [mendaftarkan probe](/apply/swprobe/) tersebut.
   Public key ini bisa ditemukan di `/var/atlas-probe/etc/probe_key.pub`.
