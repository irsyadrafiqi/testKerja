# testKerja
# NO 4
# SELECT b.tanggal_lahir, SUBSTRING(a.code_jurusan, 4) AS kode,
SUBSTRING(b.temps, 10) AS temps
FROM tbl_jurusan a,tbl_mhs b
