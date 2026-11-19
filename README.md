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
- Denah Labtek V lantai 2–4: papan Rute Evakuasi Darurat di Labtek V (difoto 19 Nov 2026)
- Rundown & teknis lapangan: STEIcation Day 2 (Minggu, 22 Nov 2026)

## Batasan
- Elevasi ±3–5 m, tidak menangkap tangga/undakan. Area utara (Saraga/Sabuga) belum punya data elevasi.
- Posisi simbol dari peta AMI ±10 m.
- Labtek V: posisi tangga & ruang L2–L4 dari denah evakuasi (±1 m); lebar dan dimensi anak tangga masih dibaca dari gambar dan perlu diukur. Lantai 1 belum ada denahnya.
- Jumlah peserta Day 2 diasumsikan 240 (40 per career path) sampai ada angka final.
