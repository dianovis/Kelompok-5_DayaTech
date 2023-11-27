# Kelompok-5_DayaTech

# Proxmox
## fitur-fitur proxmox
Dapat menginputkan Template NextCLoud dengan cara create CT Templates
## ![image](https://github.com/dianovis/Kelompok-5_DayaTech/assets/116280719/5d7b1a2e-ae56-4876-bca2-6fe991dea09b)


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
