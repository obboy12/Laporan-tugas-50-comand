# Laporan-tugas-50-comand
# LAPORAN HASIL TUGAS
| Nama        | Abdullah Husin |
|--------------|------------|
| NIM        | 09030582327103 |
| Program Studi | Teknik Komputer |

# tugas!

--- 

---

### *1. Perintah Navigasi & Direktori*  
1. `pwd` → Menampilkan lokasi direktori saat ini  
2. `ls` → Menampilkan isi direktori  
3. `ls -l` → Menampilkan isi direktori dengan detail  
4. `ls -a` → Menampilkan file termasuk yang tersembunyi  
5. `cd [direktori]` → Berpindah direktori  
6. `cd ..` → Kembali ke direktori sebelumnya  
7. `cd /` → Berpindah ke root directory  
8. `cd ~` → Berpindah ke home directory  
9. `mkdir [nama_folder] `→ Membuat folder baru  
10. `rmdir [nama_folder]` → Menghapus folder kosong  

---

### *2. Manajemen File*  
11. `touch [nama_file]` → Membuat file kosong  
12. `cp [file1] [file2]` → Menyalin file  
13. `mv [file] [lokasi]` → Memindahkan atau mengganti nama file  
14. `rm [nama_file]` → Menghapus file  
15. `rm -r [nama_folder]` → Menghapus folder beserta isinya  
16. `cat [nama_file]` → Menampilkan isi file  
17. `more [nama_file]` → Menampilkan isi file satu layar penuh  
18. `less [nama_file]` → Menampilkan isi file dengan navigasi lebih fleksibel  
19. `head -n 10 [nama_file]` → Menampilkan 10 baris pertama file  
20. `tail -n 10 [nama_file]` → Menampilkan 10 baris terakhir file  

---

### *3. Manajemen User & Permission*  
21. `whoami` → Menampilkan user yang sedang login  
22. `id` → Menampilkan informasi user dan grup  
23. `who` → Menampilkan user yang sedang login ke sistem  
24. `chmod 755 [file]` → Mengubah permission file  
25. `chown [user]:[group] [file]` → Mengubah kepemilikan file  
26. `passwd` → Mengubah password user  
27. `adduser [nama_user]` → Menambahkan user baru  
28. `deluser [nama_user]` → Menghapus user  
29. `usermod -aG [group] [user]` → Menambahkan user ke grup tertentu  
30. `groups [user]` → Menampilkan grup yang dimiliki user  

---

### *4. Manajemen Proses*  
31. `ps aux` → Menampilkan daftar proses yang berjalan  
32. `top` → Menampilkan proses secara real-time  
33. `htop` → Alternatif top dengan tampilan interaktif (harus diinstal: sudo apt install htop)  
34. `kill [PID]` → Menghentikan proses berdasarkan PID  
35. `killall [nama_proses]` → Menghentikan semua proses dengan nama tertentu  
36. `pkill [nama_proses]` → Menghentikan proses berdasarkan nama  
37. `jobs` → Menampilkan daftar pekerjaan yang berjalan di background  
38. `fg [job_id]` → Membawa pekerjaan yang berjalan di background ke foreground  
39. `bg [job_id]` → Menjalankan pekerjaan di background  
40. `nice -n [prioritas] [perintah]` → Menjalankan proses dengan prioritas tertentu  

---

### *5. Manajemen Paket (APT - Advanced Package Tool)*  
41. `sudo apt update` → Memperbarui daftar paket  
42. `sudo apt upgrade` → Memperbarui semua paket  
43. `sudo apt install` [nama_paket] → Menginstal paket  
44. `sudo apt remove` [nama_paket] → Menghapus paket  
45. `dpkg -i [nama_paket.deb]` → Menginstal paket dari file .deb  

---

### *6. Jaringan & Internet*  
46. `ifconfig atau ip a` → Menampilkan konfigurasi jaringan  
47. `ping [alamat]` → Mengecek koneksi ke alamat tertentu  
48. `wget [url]` → Mengunduh file dari internet  
49. `curl [url]` → Mengambil data dari URL  
50. `netstat -tulnp` → Melihat port yang sedang digunakan  

---

