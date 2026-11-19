# OLEAT Kampus ITB Ganesa

Model 3D interaktif kampus ITB Ganesa untuk perencanaan layout acara dan alur mobilisasi.

- `index.html`: model kampus (gedung, jalan, elevasi, kemiringan, gerbang, fasilitas, himpunan, booth)
- `labtek-v/index.html`: model Labtek V (tangga, arus peserta, titik kumpul)

Cukup dibuka di peramban; tidak perlu instalasi. Library 3D (three.js r128) dimuat dari cdnjs.

## Sumber data
- Bentuk gedung & jalan: © kontributor OpenStreetMap, lisensi ODbL (https://www.openstreetmap.org/copyright)
- Elevasi: tile terrain Mapzen/AWS Terrain Tiles (gabungan SRTM dkk.), resolusi ±30 m
- Foto udara: Peta ITB Kampus Ganesha (FITB ITB, foto udara 2016)
- Nama gedung/jalan, gerbang, fasilitas, himpunan: Peta Kampus ITB Ganesha (Capantour ITB Day AMI 2026) dan Peta Capanlap ITB Day AMI 2026

## Batasan
- Elevasi ±3–5 m, tidak menangkap tangga/undakan. Area utara (Saraga/Sabuga) belum punya data elevasi.
- Posisi simbol dari peta AMI ±10 m.
- Isi dalam Labtek V (tangga, ruang, pintu) masih TAKSIRAN sampai ada denah dan pengukuran lapangan.
