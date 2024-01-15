# Ryzentosh

EFI ini sudah di coba di MacOs Catalina, BigSur, Monterey dan Ventura, untuk catalina bug di **Ethernet**, dan saya masih kesulitan install menggunakan **Hackintool**, file Kext **RealtekRTL8111** sudah saya masukan di EFI jika masih bug coba ganti dengan Kext yang sesuai dengan Ethernet yang anda gunakan. 

Namun jika spek PC yang anda gunakan sama, bisa langsung anda gunakan EFI ini. 

Untuk dapat membaca **Disk NTFS** bisa install **Paragon** namun ini berbayar, saya masih mencari cara untuk bisa **Read-Write NTFS**.

## Spesifikasi PC
- Ryzen 7 5700x
- Asus Prime B550M
- DDR4 32GB, 2x16GB 3200 Mhz
- Radeon RX 570 4GB 

## Bahan
- File Raw MacOS di [Olarila][Olarila]
- Bootable menggunakan [Balena Ecther][Balena]
- File [Build][Dortania]
- Dokumentasi [Dortania][Docs]
- Writeable NTFS [Paragon][Paragon]
- Bahan Tambahan ada di folder **penginstalan**

> Harap backup data dan gunakan Disk Kosong atau buat 1 partisi khusus untuk MacOS

[Paragon]:https://www.paragon-software.com/home/ntfs-mac/
[Docs]:https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html
[Dortania]:https://dortania.github.io/builds/
[Olarila]:https://www.olarila.com/topic/6278-olarila-vanilla-images-macos-installer
[Balena]:https://etcher.balena.io/
