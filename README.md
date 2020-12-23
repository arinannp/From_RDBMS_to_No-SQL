# From_RDBMS_to_No-SQL
Transformasi Data dari RDBMS MySQL atau SQLite ke No-SQL MongoDB

Python yang digunakan adalah Python versi 3.

Package yang dibutuhkan:
- sqlalchemy 
- create_engine
- pymysql
- sqlite3
- pymongo
- pandas
- jupyter notebook/ anaconda

'\n\n'
### Konfigurasi dengan Database SQLite

Untuk dapat melakukan transformasi data dari database SQLite ke MongoDB, pertama atur koneksi sqlite dan mongodb ke python sebagai berikut:

```python
mongodb_conn = "..."
sqlite_conn = "..."
```

Silahkan ganti tanda ... dengan lokasi file database sqlite dan atur localhost mongodb dari direktori Anda. Tetap gunakan tanda petik " " karena connection harus bertipe _string_.

### Akses Tabel dari SQLite dan Membuat Database serta Collection Baru di MongoDB

Silahkan ubah tabel_name untuk akses tabel yang ingin diakses dari database sqlite, serta buat database_mongo_name dan collection_name baru sebagai tempat transformasi dari database sqlite.

__CONTOH:__
```python
tabel_name = "tracks"
database_mongo_name = "dbproject"
collection_name = "mycollection"
```
'\n\n'
### Konfigurasi dengan Database MySQL

Untuk dapat melakukan transformasi data dari database MySQL ke MongoDB, pertama atur koneksi mysql dan mongodb ke python sebagai berikut:

```python
username = "..." 
password = "..." 
host = "..."
mongodb_conn = "..."
```

Silahkan ganti tanda ... dengan konfigurasi yang telah Anda atur saat proses instalasi mysql dan mongodb. Tetap gunakan tanda petik " " karena connection harus bertipe _string_.

### Akses Tabel dari MySQL dan Membuat Database serta Collection Baru di MongoDB

Silahkan ubah tabel_name dan database_name untuk akses tabel yang ingin diakses dari database mysql, serta buat database_mongo_name dan collection_name baru sebagai tempat transformasi dari database mysql.

__CONTOH:__
```python
database_name = "superstore"
tabel_name = "tracks"
database_mongo_name = "dbproject"
collection_name = "mycollection"
```
