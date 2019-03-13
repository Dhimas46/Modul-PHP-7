# Modul-PHP-7
belajar PHP

1.Contoh Kode connect ke database : $host = "localhost";
                                    $db = "db_universitas";
                                    $uname = "root";
                                    $pass = "";

                                    $connect = mysqli_connect($host, $uname, $pass, $db
2.-Membuka tools xampp
  -Mengaktifkan Apache dan Mysql
  -Masuk Admin pada Mysql
  -Create New Database
  -Beri Nama database
  -Buat table
  -Beri Salah satu item menjadi primary key
  -Jika Selesai save data
3.Contoh kode query untuk menampilkan data : $query = "SELECT * FROM dosen";
4.Contoh kode query untuk mengupdate data : $query = "UPDATE dosen SET nama_dosen = '$nama_dosen',telp ='$telp' WHERE id_dosen = $id_dosen";
5.Contoh kode query untuk menghapus data : $query = "DELETE FROM dosen WHERE id_dosen = $id_dosen";

