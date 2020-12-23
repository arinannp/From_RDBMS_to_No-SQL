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

### Konfigurasi dengan Database SQLite

Untuk dapat melakukan transformasi data dari database SQLite ke MongoDB, pertama atur koneksi sqlite dan mongodb ke python sebagai berikut:

```python
mongodb_conn = "..."
sqlite_conn = "..."
```

Silahkan ganti tanda ... dengan lokasi file database sqlite dan atur localhost mongodb dari direktori Anda. Tetap gunakan tanda petik "" karena connection harus bertipe _string_.
