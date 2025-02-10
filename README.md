# Tugas-Sistem-Operasi
# Tutorial instal Virtualbox
Sebelum menginstal VirtualBox, pastikan laptop yang kamu pakai memenuhi persyaratan berikut:

Tutorial ini akan memandu kamu melalui langkah-langkah untuk menginstal VirtualBox di laptop. Ikuti langkah-langkah dengan hati-hati dan lihat tangkapan layar untuk pemahaman yang lebih baik.
# Persyaratan Sistem


Sebelum menginstal VirtualBox, pastikan laptop yang kamu pakai memenuhi persyaratan berikut:

•	Prosesor 64-bit dengan dukungan virtualisasi (Intel VT-x atau AMD-V diaktifkan di BIOS)

•	Minimal RAM 4GB (disarankan 8GB untuk performa lebih baik)

•	Minimal 10GB ruang kosong di hard disk

•	Sistem operasi Windows, macOS, atau Linux


# langkah pertama: download virtual box

**1. ketik virtual box lalu masuk**
ke situs resmi virtual box yang ada pada gambar
![Screenshot 2025-02-10 201306](https://github.com/user-attachments/assets/4986bcc5-3a52-4089-be5e-6c5dc9f2a91a)



__2. Lalu klik download__
![Screenshot 2025-02-10 201337](https://github.com/user-attachments/assets/1bc4a2a0-6221-4122-afa4-2cf69d88a3bd)



__3. Pilih versi sesuai dengan sistem operasi yang kamu gunakan (Windows, macOS, atau Linux).__
![Screenshot 2025-02-10 201449](https://github.com/user-attachments/assets/8afe1e5d-b629-47eb-b111-e09e4f334518)


# Langkah 2: Instal VirtualBox
# Untuk Windows:
__1. Cari file .exe yang telah diunduh dan klik dua kali untuk menjalankannya.__
![Screenshot 2025-02-10 201820](https://github.com/user-attachments/assets/e9793db1-0afd-4021-bec5-be3617ebf122)

__2. Ikuti panduan instalasi dan klik Next untuk melanjutkan.__

__3. Biarkan pengaturan default kecuali kamu memerlukan konfigurasi khusus.__

__4. Klik Install dan tunggu hingga proses selesai.__

__5. Klik Finish untuk menutup installer.__

# Untuk macOS:
Buka file .dmg yang telah diunduh.

Seret ikon VirtualBox ke dalam folder Applications.

Buka VirtualBox dari folder Applications.

Jika muncul peringatan, izinkan akses di System Preferences > Security & Privacy.

Untuk Linux (Ubuntu/Debian-based):

Buka terminal dan jalankan perintah berikut:

sudo apt update
sudo apt install virtualbox -y

Tunggu hingga instalasi selesai.

Verifikasi instalasi dengan menjalankan:

virtualbox

# Langkah 3: Instal VirtualBox Extension Pack (Opsional)
__1.	Kembali ke situs VirtualBox.__

__2.	Unduh Extension Pack yang sesuai dengan versi VirtualBox Anda.__

__3.	Buka VirtualBox dan masuk ke File > Preferences > Extensions.__

__4.	Klik Add New Package dan pilih Extension Pack yang telah diunduh.__

__5.	Klik Install dan setujui perjanjian lisensi.__

Nah sebelum kita membuat virtual machine nya kita di haruskan sudah mendownload file ISO sistem operasi, sebagai contoh:__ubuntu__


![Screenshot 2025-02-10 201926](https://github.com/user-attachments/assets/51958f26-7367-451b-aa85-a2dcb1f6ba63)



![Screenshot 2025-02-10 202006](https://github.com/user-attachments/assets/4156ace3-91d6-4cd5-97c0-f14ade157353)


![Screenshot 2025-02-10 202028](https://github.com/user-attachments/assets/4f29b52a-9612-4fae-818d-80d692ee55a0)





# Tutorial Setting Virtual Machine di VirtualBox
__Tutorial ini akan memandu kamu dalam mengatur Virtual Machine (VM) di VirtualBox setelah instalasi.__
# Langkah 1: Membuka VirtualBox dan Membuat Virtual Machine Baru
__1.	Buka VirtualBox.__

2.	Klik tombol New untuk membuat VM baru.

3.	Masukkan nama VM (contoh: "Ubuntu-Linux"), lalu pilih:

o	Type: Sistem operasi yang ingin diinstal (Windows, Linux, macOS, dll.)

o	Version: Pilih versi OS yang sesuai (contoh: Ubuntu 64-bit).

4.	Klik Next.


![Screenshot 2025-02-10 202255](https://github.com/user-attachments/assets/3e7013de-5823-4723-8274-928e19915938)

# Langkah 2: Mengatur Alokasi RAM
__1.	Tentukan jumlah RAM yang ingin dialokasikan ke VM.__

o	Minimal 2GB (2048MB) untuk Linux ringan.

o	Disarankan 4GB atau lebih untuk Windows dan Linux berat.

__2.	Klik Next.__
![Screenshot 2025-02-10 202406](https://github.com/user-attachments/assets/517ffcb2-344e-4d55-b24c-23c9c7633bbd)




# Langkah 3: Membuat Hard Disk Virtual
__1.	Pilih Create a virtual hard disk now lalu klik Create.__

__2.	Pilih format disk virtual:__

o	VDI (VirtualBox Disk Image) – Default, cocok untuk kebanyakan pengguna.

o	VHD atau VMDK jika ingin kompatibel dengan software lain.

__3.	Pilih metode alokasi ruang:__

o	Dynamically allocated (lebih fleksibel, hanya menggunakan ruang saat diperlukan).

o	Fixed size (lebih cepat, tapi langsung mengambil semua ruang yang dialokasikan).

__4.	Tentukan ukuran disk (disarankan minimal 20GB untuk Linux dan 50GB untuk Windows).__

__5.	Klik Create.__

# Langkah 4: Mengatur Konfigurasi Tambahan (Opsional)

Sebelum menjalankan VM, bisa dilakukan pengaturan tambahan:

__1.	Pilih VM yang sudah dibuat, lalu klik Settings.__

![Screenshot 2025-02-10 202700](https://github.com/user-attachments/assets/2cb0984a-3dc5-4863-a31f-0d9f81ddef44)




__2. Pada tab System, aktifkan Enable EFI (special OSes only) jika diperlukan.__

__3. Pada tab Display, atur Video Memory menjadi 128MB untuk performa grafis yang lebih baik.__

__4. Pada tab Storage, tambahkan file ISO sistem operasi yang ingin diinstal.__
![Screenshot 2025-02-10 202842](https://github.com/user-attachments/assets/cc44a712-ea48-473c-8625-39b75dd147d7)


![Screenshot 2025-02-10 203000](https://github.com/user-attachments/assets/cee15ccc-705f-4145-a156-39a1e9155094)

__5. Klik OK untuk menyimpan pengaturan.__

# Langkah 5: Menjalankan Virtual Machine
__1. Pilih VM yang sudah dikonfigurasi.__

__2. Klik Show untuk menjalankan mesin virtual.__
![Screenshot 2025-02-10 203038](https://github.com/user-attachments/assets/ed2b88dc-5c1d-48b1-8992-eda89429467f)


__3. Ikuti instruksi instalasi sistem operasi sesuai dengan OS yang dipilih.__
![WhatsApp Image 2025-02-10 at 21 22 42](https://github.com/user-attachments/assets/4e88b634-81a2-47c7-b175-4b63d304b200)


# Kesimpulan
# Kamu telah berhasil mengatur Virtual Machine di VirtualBox. Semoga langkah langkah nya membantu..
