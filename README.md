# Mengenal MongoDB

1. no table -> document.

      {
        "_id": ObjectId("asd847646745765467445"),
        "title": "Artikel Satu",
        "body": "Ini adalah artikel body"
      }

2. noSQL no relation db (tidak berelasi/join)

Keuntungan
- Fast
- Schalability
- Object Oriented Database
- Agile


Cara Membuat Database Baru

- use NAMADATABASE
- db
- show dbs //Melihat database
- db.createCollection("NAMA COLLECTION/TABEL") //Membuat Collection/Tabel
- show collections (Melihat collection/tabel) //Melihat collection
- db.siswa.insert({name: 'Dwi', kelas: 'Javascript', trainer: 'Fad'}) //Memasukan data ke collection
- db.siswa.find({}) //Melihat isi data pada collection
- db.siswa.find({}).pretty() //Melihat isi data secara rapih

GUI MongoDb -> mongodb compass
