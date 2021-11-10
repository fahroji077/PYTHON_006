# PYTHON_006

1. Exception

```y
try:
    level = input("level kamu : ")
    level = int(level)
    print(level)
    
except ValueError:
    print("yang kamu masukkan itu bukan angka")
```
![image](https://user-images.githubusercontent.com/93015185/141060283-22d29264-391f-4faf-861b-65169ae4fffa.png)

2. General Exception

```y
try:
    level = input("level kamu : ")
    level = int(level)
    level = level / 0
    print(level)
    
except:
    print("telah terjadi kesalahan")
```
![image](https://user-images.githubusercontent.com/93015185/141060707-68676ce4-42d9-41d1-adaf-278e7b6d950c.png)

3.Membaca File

```y
users = open("file tgs membaca file.py", "r")

#read untuk membaca semua
#readline untuk membaca baris awal saja

#print(users.readline())

Array = users.readlines()
print(Array [1])

users.close()

# "r" untuk menulis data di file
# "a" untuk menambahkan data ke file yang sudah ada
# "r+" untuk membaca dan bisa menulis
```

![image](https://user-images.githubusercontent.com/93015185/141061731-1d2fff0b-d33c-4829-ab5d-4f5dcd18b8bb.png)
![image](https://user-images.githubusercontent.com/93015185/141062070-c676be25-f842-40fe-9d2e-6a910d6d4e5d.png)


4. Menulis File

```y
users = open("file tgs membaca file.py", "a")

users.write(" belum_makan - dari_pagi")
users.close()
```
![image](https://user-images.githubusercontent.com/93015185/141062013-6610fcd6-704c-438d-ac0c-1427272c0b7a.png)
![image](https://user-images.githubusercontent.com/93015185/141062034-e2d11625-2885-4211-8596-a9114a39d259.png)
