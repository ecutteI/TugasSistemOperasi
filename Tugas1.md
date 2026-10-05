# TUGAS 1 SISTEM OPERASI
 
**Nama** : Fadel Mahmud Athallah
 
**NIM** : 09011282530073
 
**Mata Kuliah** : Sistem Operasi
 
---
 
## 1. Proses instalasi Linux Ubuntu
 
- **1.1.** Buka website Ubuntu (https://ubuntu.com/download) dan mendownload Ubuntu versi desktopnya.
- **1.2.** Mencolok USB Drive
- **1.3.** Mendownload Rufus (https://rufus.ie/en/) dan memasukkan file Ubuntu yang di download tadi ke dalam USB Drive, Rufus berguna untuk membuat Bootable USB.
- **1.4.** Menonaktifkan Bitlocker (kalau ada, di aku bitlocker tidak ada).
- **1.5.** Membuat Partisi untuk Ubuntu (aku menaruh cuma sekitar 30an GB)
- **1.6.** Merestart Laptop sambil memencet tombol Shift untuk membuka Boot Menu, Saat diminta “Choose an Option” pencet “Use a Device” lalu pencet nama USB Drive yang dipakai.
- **1.7.** Terbuka GNU Grub lalu memilih “Try or Intall Ubuntu”.
- **1.8.** Saat terbuka ubuntu laptop ku bertemu dengan masalah, yaitu belum mematikan Rapid Storage Technology (RST), jadi aku membuka BIOS dan menggantikan SATA Mode-nya dari “Intel with RST” menjadi “AHCI”.
- **1.9.** Saat memboot dengan Ubuntu lagi, masalah sudah terselesaikan.
- **1.10.** Ubuntu sudah terinstal.

## 2. Analisislah pada gambar kenapa saat instalasi perlu dipilih “/” pada opsi Mount Point?
“/” Pada mouse point memberi tahu Ubuntu partisi tersebut akan menjadi partisi root, tempat seluruh sistem operasi akan diinstal.

## 3. Berikan penjelasan tentang ext4, ext3, swap, ntfs, fat32, btrfs!
 
### 3.1. Ext4 (Fourth Extended Filesystem)
 
Filesystem default Linux/Ubuntu. Cepat, stabil dan punya journaling (mencatat perubahan agar data aman saat terjadi crash). Cocok untuk pertisi root “/”.
 
### 3.2. Ext3 (Third Extented Filesystem)
 
Pendahulu Ext4, sudah usang, performa lambat dan jarang dipakai lagi
 
### 3.3. Swap
 
RAM cadangan yang ada di disk. Dipakai saat RAM penuh atau untuk hibernasi
 
### 3.4. NFTS
 
Filesystem default Windows. Bisa dibaca/ditulis di linux, tapi tidak bisa jadi partisi root Linux.
 
### 3.5. FAT32
 
Filesystem universal (bisa dipakai oleh hampir semua OS/perangkat), tapi limit ukuran file maks 4GB. Biasa dipakai untuk partisi EFI atau flashdisk
 
### 3.6. Btrfs
 
Filesystem modern dengan fitur snapshot (bisa rollback sistem) dan copy-on-write (lebih aman dari korupsi data). Lebih canggih dari Ext4, dipakai sebagai default di beberapa distro seperti openSUSE.
