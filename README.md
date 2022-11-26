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


Code:
```python
data = []
while True :
	nama	= input	("Nama 		:")
	nim		= input ("NIM 		:")
	tugas	= int(input("Nilai Tugas :"))
	uts 	= int(input("Nilai UTS 	:"))
	uas 	= int(input("Nilai UAS 	:"))
	nilaiakhir = float(tugas)*30/100+(uts)*35/100+(uas)*35/100
	data.append ([nama,nim,tugas,uts,uas,nilaiakhir])
	lagi = input ("Tambah lagi (y/t)?")
	if lagi.lower() =="t":
		break


print ("=======================================================================================")
print ("| No |	 Nama 	| NIM 	| TUGAS | UTS 	|	 UAS 	|	 NILAI AKHIR 	|")
print ("=======================================================================================")
i=0
for x in data:
	i+=1
	print ("|{6:2}  | {0:9}| {1:6}| {2:3}   |{3:3}    |	 {4:3}	| 	{5:10.2f}  	|"\
		.format (x[0][:9],x[1][:6],x[2],x[3],x[4],x[5],i))
print("=======================================================================================")
```

Output:
![output data](https://user-images.githubusercontent.com/116176746/204072279-bf0970a4-3b8a-4004-8c4c-085cdcb15e4d.png)

