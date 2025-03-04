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
6. 
