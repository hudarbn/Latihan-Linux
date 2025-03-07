# Linux Fun Project
1. Mengunduh program dan membuat folder, kemudian masuk kedalamnya
```
sudo apt install wget unzip xxd && mkdir artists_who_can_sing && cd artists_who_can_sing
```
2. Mendownload file zip menggunakan wget
```
wget https://drive.usercontent.google.com/u/0/uc?id=1lV1HVmPTY_BOAK6ToXymRu7V5eVfR0ut&export=download -O tutorials.zip
```
3. Unzip atau extract file ke dalam folder lain
```
unzip tutorials.zip -d singing_tutorials
```
4. Masuk ke dalam folder dan menampilkan list
```
cd singing_tutorials && ls && ls -a
```
5. Filter file dan pipe hasilnya di suatu direktori
```
find .*_opera_*_NBAYoungboy* | grep -rIh "FLAG{.*}" | head -n 1 > ../flag.txt
```
6. Mundur ke direktori sebelumnya dan download file baru
```
cd .. && wget https://files.catbox.moe/9l4qu8 -O plsrunmeiamnotmalwarefr
```
7.Buat izin untuk permission dan jalankan program
```
chmod +x plsrunmeiamnotmalwarefr && ./plsrunmeiamnotmalwarefr
```
8. Melihat proses program yang sedang berjalan
```
ps aux
```
9. Membuat program dan mengecek kembali proses program yang sedang berjalan
```
touch ransom.moolah && ps aux
```
10. Mematikan proses program dan memastikan program sudah mati
```
kill -9 <PID> && ps aux
```
