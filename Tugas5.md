# TUGAS 5 SISTEM OPERASI
 
**Nama** : Fadel Mahmud Athallah
 
**NIM** : 09011282530073
 
**Mata Kuliah** : Sistem Operasi
 
---
 
## 1. Lihat peralatan I/O, *character device*, yang ada di sistem komputer.
Menggunakan command ls -l /dev | grep "^c"
<br>
 <img width="626" height="1001" alt="image" src="https://github.com/user-attachments/assets/a1a30404-99ef-4a83-b9eb-106ead6e2f82" />

## 2. Buatlah sub direktori januari, februari dan maret sekaligus pada direktori latihan 5.
<img width="889" height="59" alt="image" src="https://github.com/user-attachments/assets/0947df36-f34a-4337-ab9c-a5c6e5bb2f93" />

## 3. Buatlah file dataku yang berisi nama, nim dan alamat anda pada sub direktori januari dan copy-kan file tersebut ke sub direktori februari dan maret.
<img width="934" height="133" alt="image" src="https://github.com/user-attachments/assets/af2f74a5-3e92-4ba3-84b3-acd94c4c9a16" />

## 4. Ubahlah ijin akses file dataku pada sub direktori januari sehingga *group* dan others dapat melakukan *write*.
<img width="689" height="43" alt="image" src="https://github.com/user-attachments/assets/eb9c8575-b890-4f2f-b2b6-5447eada9e45" />

## 5. Ubahlah ijin akses file dataku pada sub direktori februari sehingga user dapat melakukan baik *write*, *read* maupun *execute*, tetapi *group* dan *others* hanya bisa *read* dan *execute*.
<img width="773" height="39" alt="image" src="https://github.com/user-attachments/assets/2dbc2e84-8cc6-4588-bf43-49feaa78b055" />

## 6. Ubahlah ijin akses file dataku pada sub direktori maret sehingga semua dapat melakukan *write*, *read* dan *execute*.
<img width="778" height="43" alt="image" src="https://github.com/user-attachments/assets/8ed7216e-6199-4aa1-ab8f-aa514bf1ac2a" />

## 7. Hapuslah direktori maret.
<img width="778" height="43" alt="image" src="https://github.com/user-attachments/assets/98e2e565-1d37-43b9-ad35-b5ea26737e15" />

## 8. Ubahkan kepemilikan sub direktori februari sehingga *user* dan *group* hanya dapat melakukan *read*, dan cobalah untuk membuat direktori baru haha pada sub direktori februari.
<img width="779" height="61" alt="image" src="https://github.com/user-attachments/assets/783e355d-d035-4109-8546-bf29c9ba5bd1" />
<br>
*Permission Denied* karena membuat isi direktori membutuhkan izin write

## 9. Modifikasi umask dari file dataku pada sub direktori januari menjadi 027 dan berapakan nilai *default*-nya?
<img width="716" height="168" alt="image" src="https://github.com/user-attachments/assets/1a86330e-6ccc-4e1c-8849-889e7f179598" />

## 10. Buatlah link dari file dataku ke file dataku.ini dan file dataku.juga dan dengan perintah list perhatikan berapa link yang terjadi?
<img width="725" height="162" alt="image" src="https://github.com/user-attachments/assets/27bba9c0-9297-4e9b-bf4b-9b76d02db6af" />
<br> 
Ada 3 kali link terjadi
