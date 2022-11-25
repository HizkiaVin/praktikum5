# Latihan List
Code :
```python
#membuat list
data = [2,5,3,6,7]

#akses list
print("Menampilkan elemen ke-3:", data[3])
print("Nilai elemen ke-2 sampai ke -4 :", data[1:4])
print("Mengambil elemen terakhir :", data[-1])

#ubah element list
data[3] = 11
print("Ubah elemen 4 :", data)
data[3:5] = [76,29]
print("Ubah elemen 4 sampai elemen terakhir :", data)

#tambah element list
dataA = [2,5,3]
dataB = [6,7]
print("List A :", dataA)
print("List B :", dataB)

dataB.append(15)
print("Menambah List B dengan nilai string :", dataB)

dataB.extend([1, 27, 53])
print("Menambah List B dengan 3 nilai :", dataB)

dataC = dataA + dataB
print("Menggabungkan List A dan List B :", dataC)

dataA.extend(dataB)
print("", dataA)
```

Output: 

![list](https://user-images.githubusercontent.com/116176746/203888948-2cffce6f-831d-4088-ac86-0d4fe5539064.png)

# Tugas Praktikum
>Buat program sederhana untuk menambahkan data kedalam sebuah
list dengan rincian sebagai berikut:
• Progam meminta memasukkan data sebanyak-banyaknya (gunakan
perulangan)
• Tampilkan pertanyaan untuk menambah data (y/t?), apabila jawaban
t (Tidak), maka program akan menampilkan daftar datanya. • Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%,
uts: 35%, uas: 35%)
• Buat flowchart dan penjelasan programnya


**Flowchart**
![flowchartpraktikum](https://user-images.githubusercontent.com/116176746/203956460-f147b7e9-2d6f-420d-9a45-0f1fd6f16500.png)
