<p align="center">
  <img src="https://img.shields.io/badge/Windows%2011-0078D4?style=for-the-badge&logo=windows-11&logoColor=white" />
  <img src="https://img.shields.io/badge/WSL-000000?style=for-the-badge&logo=windows-terminal&logoColor=white" />
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" />
  <img src="https://img.shields.io/badge/Debian-D70A53?style=for-the-badge&logo=debian&logoColor=white" />
</p>

#  Cara Install WSL di Windows 11

Repository ini berisi panduan *lengkap dan sederhana* untuk menginstall *WSL (Windows Subsystem for Linux)* di *Windows 11*.

---

##  Apa itu WSL?
*WSL (Windows Subsystem for Linux)* adalah fitur resmi dari Microsoft yang memungkinkan kamu menjalankan distribusi Linux langsung di dalam Windows tanpa perlu dual boot atau virtual machine yang berat.

---

## Screenshot
Berikut adalah tampilan *Windows Terminal* di laptop saya yang sudah berhasil menjalankan distro *Ubuntu* dan *Debian* secara bersamaan:


---<img width="1366" height="720" alt="Screenshot 2025-12-23 154001" src="https://github.com/user-attachments/assets/928ad487-ad14-47c0-a817-d123235c49d8" />


##  Langkah-Langkah Instalasi

### 1️ Buka Terminal sebagai Administrator
1.  Klik tombol *Start*.
2.  Cari *Terminal* atau *PowerShell*.
3.  Klik kanan dan pilih *Run as Administrator*.

### 2️ Jalankan Perintah Instalasi
Ketik perintah di bawah ini pada terminal lalu tekan *Enter*:
```powershell
wsl --install
