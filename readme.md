This project made using Common Javascript (NodeJS)
Databases Management System using SQL method from postgreSQL
ORM : using from npm nodejs library means to sequalize

In server system handled by expressjs

Some path API writen in .http file

For running this program, use DockerCompose to instance some dependency 
    postgress, pgadmin4

To run server 
npm i
npm start

### ENDPOINT API NOPOL

GET [http://104.198.154.97:3000](http://104.198.154.97:3000/)

### FIND ALL

GET [http://104.198.154.97:3000/laporan](http://104.198.154.97:3000/laporan)

### CREATE

POST  [http://104.198.154.97:3000/laporan/create](http://104.198.154.97:3000/laporan/create)
Content-Type: application/json

{
"userID": "1" ,
"kendaraanID": "1" ,
"type": "tipe A",
"judul": "Judul A",
"lokasi": "Lokasi A",
"tanggal": "Date A",
"imagePath": "A",
"deskripsi": "Deskripsi A"
}

### UPDATE ONE

POST  [http://104.198.154.97:3000/laporan/update/1](http://104.198.154.97:3000/laporan/update/1)
Content-Type: application/json

{
"userID": "9" ,
"kendaraanID": "1" ,
"type": "tipe B",
"judul": "Judul B",
"lokasi": "Lokasi B",
"tanggal": "Date B",
"imagePath": "B",
"deskripsi": "Deskripsi B"
}

### FIND ONE

GET [http://104.198.154.97:3000/laporan/1](http://104.198.154.97:3000/laporan/1)

### DELETE ONE

GET [http://104.198.154.97:3000/laporan/delete/6](http://104.198.154.97:3000/laporan/delete/6)

###! DELETE ALL (ERR)
GET [http://104.198.154.97:3000/laporan/deleteall/important](http://104.198.154.97:3000/laporan/deleteall/important)

### KENDARAAN

### FIND ALL

GET [http://104.198.154.97:3000/kendaraan](http://104.198.154.97:3000/kendaraan)

### FIND ONE

GET [http://104.198.154.97:3000/kendaraan/2](http://104.198.154.97:3000/kendaraan/2)

### CREATE

POST  [http://104.198.154.97:3000/kendaraan/create](http://104.198.154.97:3000/kendaraan/create)
Content-Type: application/json

{
"userID": "1" ,
"nopol": "1" ,
"type": "tipe A"
}

### UPDATE

POST  [http://104.198.154.97:3000/kendaraan/update/5](http://104.198.154.97:3000/kendaraan/update/5)
Content-Type: application/json

{
"userID": "5" ,
"nopol": "5" ,
"type": "tipe E"
}

### DELETE ONE

GET [http://104.198.154.97:3000/kendaraan/delete/3](http://104.198.154.97:3000/kendaraan/delete/3)

### Tags

### FIND ALL

GET [http://104.198.154.97:3000/tag](http://104.198.154.97:3000/tag)

### FIND ONE

GET [http://104.198.154.97:3000/tag/5](http://104.198.154.97:3000/tag/5)

### CREATE

POST  [http://104.198.154.97:3000/tag/create](http://104.198.154.97:3000/tag/create)
Content-Type: application/json

{
"kendaraanID": "1" ,
"tagName": "Tag 1"
}

### UPDATE

POST  [http://104.198.154.97:3000/tag/update/5](http://104.198.154.97:3000/tag/update/5)
Content-Type: application/json

{
"kendaraanID": "5" ,
"tagName": "Tag 5"
}

### DELETE ONE

GET [http://104.198.154.97:3000/tag/delete/5](http://104.198.154.97:3000/tag/delete/5)

### DELETE ALL

GET [http://104.198.154.97:3000/tag/deleteall/important](http://104.198.154.97:3000/tag/deleteall/important)

### (KENDARAAN)

### FIND ALL

GET [http://104.198.154.97:3000/kendaraan](http://104.198.154.97:3000/kendaraan)

### FIND ONE

GET [http://104.198.154.97:3000/kendaraan/2](http://104.198.154.97:3000/kendaraan/2)

### CREATE

POST  [http://104.198.154.97:3000/kendaraan/create](http://104.198.154.97:3000/kendaraan/create)
Content-Type: application/json

{
"userID": "1" ,
"nopol": "1" ,
"type": "tipe A"
}

### UPDATE

POST  [http://104.198.154.97:3000/kendaraan/update/5](http://104.198.154.97:3000/kendaraan/update/5)
Content-Type: application/json

{
"userID": "5" ,
"nopol": "5" ,
"type": "tipe E"
}

### DELETE ONE

GET [http://104.198.154.97:3000/kendaraan/delete/3](http://104.198.154.97:3000/kendaraan/delete/3)

### DELETE ALL

GET [http://104.198.154.97:3000/kendaraan/deleteall/important](http://104.198.154.97:3000/kendaraan/deleteall/important)

### (PUJIAN)

### FIND ALL

GET [http://104.198.154.97:3000/pujian](http://104.198.154.97:3000/pujian)

### FIND ONE

GET [http://104.198.154.97:3000/pujian/2](http://104.198.154.97:3000/pujian/2)

### CREATE

POST  [http://104.198.154.97:3000/pujian/create](http://104.198.154.97:3000/pujian/create)
Content-Type: application/json

{
"kendaraanID": "1" ,
"type": "Tag 1",
"value" : "Value Tag"
}

### UPDATE

POST  [http://104.198.154.97:3000/pujian/update/2](http://104.198.154.97:3000/pujian/update/2)
Content-Type: application/json

{
"kendaraanID": "2" ,
"type": "Tag 2",
"value" : "Value Tag"
}

### DELETE ONE

GET [http://104.198.154.97:3000/pujian/delete/2](http://104.198.154.97:3000/pujian/delete/2)

### DELETE ALL

GET [http://104.198.154.97:3000/pujian/deleteall/important](http://104.198.154.97:3000/pujian/deleteall/important)
