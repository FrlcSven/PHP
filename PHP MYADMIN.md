
# Struktur Pegawai
![strukturpegawai.png]

# Data Pegawai
![[pegawai.png]]
## Before
![[ASET PHPMYADMIN/before.png]]
## After
![[strukturpegawai.png]]
# Cabang
## Before 

![[cabang.png]]

## After
![[cabang2.png]]

# Relasi 

![[RELASII.png]]

![[nilai.png]]

```mysql
SELECT m.nama AS Nama_Murid, n.nilai AS Nilai FROM nilai AS n INNER JOIN murid AS m ON m.nis = n.id_siswa WHERE n.nilai > 75;
```