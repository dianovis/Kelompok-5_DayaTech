# Kelompok-5_DayaTech
## Nama Anggota
    1.	Dian Novitasari (21050974006)
    2.	Adib Bagus Subarkah (21050974039)
    3.	Yurie Enggarnisa (21050974050)
    4.	Adinda Amelia Putri (21050974056)

# Dayatech
## Deskripsi
Implementasi cloud computing nextcloud dengan proxmox menggunakan virtual mesin untuk perkantoran yang bernama “Dayatech” merupakan website dari situs nextcloud yang menggunakan penyimpanan cloud secara local yang dapat membantu dalam mempermudah pekerjaan para pekerja pada sebuah perkantoran yang di desain secara userfriendly pada website dari situs nextcloud daya ini memiliki beberapa fitur yang pertama adalah para pekerja dapat saling mengirim pesan, dan semua berkas contohnya seerti dokumen, foto, video, music, dan dapat mebuat grub untuk sebuah grub tertentu yang dapat mengakses semua berkas yang di upload ke dalam grub tersebut. Dayatech juga dapat menandai berkas yang di favoritkan.

## Tujuan dan Fungsi
1. Menghemat penyimpanan data perusahaan ke dalam cloud computing proxmox.
2. Memudahkan penggunanya untuk menjalankan program tanpa harus menginstall terlebih dahulu dan memudahkan pengguna untuk mengakses data dan informasi melalui internet.

# Proxmox
## fitur-fitur proxmox
Dapat menginputkan Template NextCLoud dengan cara create CT Templates
## ![image](https://github.com/dianovis/Kelompok-5_DayaTech/assets/116280719/5d7b1a2e-ae56-4876-bca2-6fe991dea09b)

# Langkah-langkah install Proxmox di VirtualBox
1. download virtual box dari internet https://www.virtualbox.org/wiki/Downloads
2. install virtual box pada komputer 
3. download file proxmox VE dari internet https://www.proxmox.com/en/downloads
4. Buka virtual box dan buat virtual machin (VM) baru
5. Atur nama, lokasi folder, dan masukkan iso proxmox VE yang sudah didownload serta pilih tipe version OS
![Screenshot (142)](https://github.com/dianovis/Kelompok-5_DayaTech/assets/107270053/f62fdd2c-cb0d-4242-98bd-a57280d28e24)
6. Konfigurasi memory, procecor,virtual hard disk, cpu core, dan lain lain kemudian finish
![Screenshot (143)](https://github.com/dianovis/Kelompok-5_DayaTech/assets/107270053/9a4030fc-755b-4f64-9b0c-3c2a8e58374f)
![Screenshot (144)](https://github.com/dianovis/Kelompok-5_DayaTech/assets/107270053/4428167c-5d20-4cba-9d3c-3b201157ce8a)
7. Buka setting dan ubah dibagian network pada adapter 1 menjadi "Host Only Adapter", klik advance dan centang allow all
8. pada adapter 2 pilih "Bridge Adapter", kemudian advance dan centang allow all, kemudian apply
![Screenshot (145)](https://github.com/dianovis/Kelompok-5_DayaTech/assets/107270053/a7696073-72b8-4465-9a8a-09acf4fd666e)
9. Jalankan Virtual Machine nya
10. Install proxmox dengan mengatur beberapa konfigurasi seperti region, username, pass, hostname, serta ip address
![Screenshot (146)](https://github.com/dianovis/Kelompok-5_DayaTech/assets/107270053/d96593b9-1388-44ef-a190-e15f93e81278)
![Screenshot (147)](https://github.com/dianovis/Kelompok-5_DayaTech/assets/107270053/0b6ae93b-054c-4235-aaca-b41c8ba9175b)
![Screenshot (148)](https://github.com/dianovis/Kelompok-5_DayaTech/assets/107270053/61b5f39a-a4ba-4135-a96e-3a4a307b09c8)
11. Tunggu instalasi selesai, setelah selesai kembali ke virtual box dan remove file iso pada VM di bagian settting -> storage kemudian apply
![Screenshot (149)](https://github.com/dianovis/Kelompok-5_DayaTech/assets/107270053/e8f83636-7ab7-45ee-b61b-d7a2f61bf968)
![Screenshot (150)](https://github.com/dianovis/Kelompok-5_DayaTech/assets/107270053/5a07a3b7-b6c0-41dd-9bf3-e46cf32ad070)
![Screenshot (151)](https://github.com/dianovis/Kelompok-5_DayaTech/assets/107270053/7b2c8b0d-c5df-4dde-acb5-cff511ba1516)
12. Restart VM dan tunggu sampai selesai
13. Setelah selesai lakukan login dengan username root dan password yang telah dibuat sebelumnya
![Screenshot (155)](https://github.com/dianovis/Kelompok-5_DayaTech/assets/107270053/9a362339-3e06-448b-aba6-e1990494bc83)
14. Buka proxmox di web browser dengan mengetikkan ip dan port yang ada di bagian paling atas setelah login proxmox berhasil
15. Login dengan menggunakan username "root" dan password
![Screenshot (153)](https://github.com/dianovis/Kelompok-5_DayaTech/assets/107270053/b1b2f902-54e3-428f-a162-b5a3d52597e0)
16. Proxmox siap digunakan
![Screenshot (154)](https://github.com/dianovis/Kelompok-5_DayaTech/assets/107270053/25f79666-fcf1-466b-9d9d-e60baf6ca785)



# NextCloud
## fitur-fitur next cloud
1. Menambahkan User dan dan password bagi user tersebut
## <img width="960" alt="image" src="https://github.com/dianovis/Kelompok-5_DayaTech/assets/116280719/483642cd-686d-41f9-a8c9-b85e64ac2142">
2. Dapat membuat grup
## <img width="956" alt="image" src="https://github.com/dianovis/Kelompok-5_DayaTech/assets/116280719/4fc26a63-d203-484f-9b96-7debe579ba12">
3. Dapat mengirim berkas berupa
   * 3.1 Dokumen
   ## <img width="959" alt="image" src="https://github.com/dianovis/Kelompok-5_DayaTech/assets/116280719/96aa38df-9afd-4afd-a76b-fd7192321186">
   * 3.2 Foto
   ## <img width="958" alt="image" src="https://github.com/dianovis/Kelompok-5_DayaTech/assets/116280719/c681bc80-d94d-4ee3-b8c8-f69417b0ae35">
   * 3.3 Video
   ## <img width="960" alt="image" src="https://github.com/dianovis/Kelompok-5_DayaTech/assets/116280719/68110094-8ce1-43b8-bd8b-220146acc20b">
   * 3.4 Musik
   ## <img width="959" alt="image" src="https://github.com/dianovis/Kelompok-5_DayaTech/assets/116280719/acb303cd-774f-42c0-ae42-9379bbb8e239">
4. Menambahkan berkas favorit
   ## <img width="956" alt="image" src="https://github.com/dianovis/Kelompok-5_DayaTech/assets/116280719/8ae05c02-874e-4d21-9633-490a7c2953bb">
## Langkah-langkah instal next cloud
1. Uploud CT Template
## ![image](https://github.com/dianovis/Kelompok-5_DayaTech/assets/116284533/292b9069-0f82-4299-9aa3-5de6a72ac03e)
2. Create CT
## ![image](https://github.com/dianovis/Kelompok-5_DayaTech/assets/116284533/b75e6a2d-044a-478d-976c-b41b88d29196)
3. Setting pada general
## ![image](https://github.com/dianovis/Kelompok-5_DayaTech/assets/116284533/b31f707c-068b-431f-a875-15a208606b88)
4. Setting pada Tamplate
## ![image](https://github.com/dianovis/Kelompok-5_DayaTech/assets/116284533/57b82575-2678-4d16-a74c-10de912c9d74)
5. Setting Disk
## ![image](https://github.com/dianovis/Kelompok-5_DayaTech/assets/116284533/e6673ae2-2723-4480-97a3-6a28c6456b60)
6. Setting CPU
## ![image](https://github.com/dianovis/Kelompok-5_DayaTech/assets/116284533/732cfe3d-30dd-435f-bbd1-260b52e877a0)
7. Setting Memory
## ![image](https://github.com/dianovis/Kelompok-5_DayaTech/assets/116284533/bac2cc13-bfd0-4826-8ebf-03b5e2e9dccd)
8. Setting Network
## ![image](https://github.com/dianovis/Kelompok-5_DayaTech/assets/116284533/df41b0a4-829f-4a4d-a3a8-4daf0f0ea73d)
9. Setting DNS
## ![image](https://github.com/dianovis/Kelompok-5_DayaTech/assets/116284533/6011df1a-41dc-4be3-9106-161d081d82e0)
10. Confirm
## ![image](https://github.com/dianovis/Kelompok-5_DayaTech/assets/116284533/f13cba07-e58b-4c43-85ac-4afe8e0e6f1e)
11. Tunggu hingga selesai (task ok)
## ![image](https://github.com/dianovis/Kelompok-5_DayaTech/assets/116284533/6446e5a8-8bc6-460d-b989-0b454b4a994e)
12. running nextcloud pada console yang sudah terpasang
## ![image](https://github.com/dianovis/Kelompok-5_DayaTech/assets/116284533/8cf14e6b-08db-425d-a9d1-732ddef775ca)
13. Buat Password baru untuk nextcloud
## ![image](https://github.com/dianovis/Kelompok-5_DayaTech/assets/116284533/a711916b-1520-48eb-a1da-36b4b959112f)
14. ulangi masukkan Password baru untuk nextcloud
## ![image](https://github.com/dianovis/Kelompok-5_DayaTech/assets/116284533/7e6b6028-8199-4c3d-8926-599c9b8118ae)
15. Membuat domain
## ![image](https://github.com/dianovis/Kelompok-5_DayaTech/assets/116284533/e9b21818-346b-45c8-a1f3-78570f4dea05)
16. selanjutnya pilih skip
## ![image](https://github.com/dianovis/Kelompok-5_DayaTech/assets/116284533/5421b2a8-a58e-42b2-a0c3-9fbeff21f669)
17. Kalau sudah selesai akan muncul seperti berikut
## ![image](https://github.com/dianovis/Kelompok-5_DayaTech/assets/116284533/0d8a9c03-ddcc-4aff-a2cf-e8fd4e3671ce)


