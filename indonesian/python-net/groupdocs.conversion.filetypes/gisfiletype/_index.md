---
title: "kelas GisFileType"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Definisi tipe dokumen GIS."
type: docs
url: /id/python-net/groupdocs.conversion.filetypes/gisfiletype/
is_root: false
weight: 110
---


## GisFileType class

Definisi tipe dokumen GIS.

Menyertakan tipe file berikut: [`GisFileType.shp`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/shp/), [`GisFileType.geo_json`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/geo_json/), [`GisFileType.gdb`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gdb/), [`GisFileType.gml`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gml/), [`GisFileType.kml`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/kml/), [`GisFileType.gpx`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gpx/), [`GisFileType.topo_json`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/topo_json/), [`GisFileType.osm`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/osm/).

Tipe GisFileType mengekspos anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/__init__/) | Menginisialisasi GisFileType untuk serialisasi. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | Membandingkan objek saat ini dengan yang lain. (diturunkan dari [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | (diturunkan dari [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | Mengimplementasikan perbandingan kesetaraan yang didefinisikan oleh [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/). (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | (diturunkan dari [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | (diturunkan dari [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | Mendapatkan FileType untuk ekstensi file yang diberikan. (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | Mengembalikan FileType untuk file_name yang ditentukan. (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | Mengembalikan FileType untuk aliran dokumen yang diberikan. (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | (diturunkan dari [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | Menyediakan fungsi hash default. (diturunkan dari [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | Representasi string dari tipe file. (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | Deskripsi tipe file. (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | Ekstensi file. (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | Keluarga file. (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | Format file. (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Bidang
| Bidang | Deskripsi |
| :- | :- |
| [SHP](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/shp/) | SHP adalah ekstensi file untuk salah satu tipe file utama yang digunakan untuk representasi ESRI Shapefile. Ini mewakili informasi Geospasial dalam bentuk data vektor yang akan digunakan oleh aplikasi Geographic Information Systems (GIS). Pelajari lebih lanjut tentang format file ini di sini. |
| [GEO_JSON](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/geo_json/) | GeoJSON adalah format berbasis JSON yang dirancang untuk merepresentasikan fitur geografis beserta atribut non-spasialnya. Format ini mendefinisikan berbagai objek JSON (JavaScript Object Notation) dan cara penggabungannya. Format JSON menyajikan informasi kolektif tentang fitur geografis, ekstensi spasial, dan properti mereka. Pelajari lebih lanjut tentang format file ini di sini. |
| [GDB](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gdb/) | Geodatabase file ESRI (FileGDB) adalah kumpulan file dalam sebuah folder di disk yang menyimpan data geospasial terkait seperti dataset fitur, kelas fitur, dan tabel terkait. Dibutuhkan beberapa file lain yang disimpan bersama file .gdb di direktori yang sama agar dapat berfungsi. Pelajari lebih lanjut tentang format file ini di sini. |
| [GML](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gml/) | GML merupakan singkatan dari Geography Markup Language yang berbasis pada spesifikasi XML yang dikembangkan oleh Open Geospatial Consortium (OGC). Format ini digunakan untuk menyimpan fitur data geografis untuk pertukaran antar format file yang berbeda. Ini berfungsi sebagai bahasa pemodelan untuk sistem geografis serta sebagai format pertukaran terbuka untuk transaksi geografis di internet. Pelajari lebih lanjut tentang format file ini di sini. |
| [KML](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/kml/) | KML (Keyhole Markup Language) berisi informasi geospasial dalam notasi XML. File yang disimpan sebagai KML dapat dibuka di aplikasi Sistem Informasi Geografis (GIS) asalkan mereka mendukungnya. Banyak aplikasi telah mulai menyediakan dukungan untuk format file KML setelah diadopsi sebagai standar internasional. KML menggunakan struktur berbasis tag dengan elemen bersarang dan atribut. Pelajari lebih lanjut tentang format file ini di sini. |
| [GPX](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gpx/) | File dengan ekstensi GPX mewakili format GPS Exchange untuk pertukaran data GPS antara aplikasi dan layanan web di internet. Ini adalah format file XML ringan yang berisi data GPS yaitu waypoint, rute, dan trek yang dapat diimpor dan dibaca oleh banyak program. Pelajari lebih lanjut tentang format file ini di sini. |
| [TOPO_JSON](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/topo_json/) | TopoJSON adalah ekstensi dari GeoJSON yang mengkodekan topologi. Alih-alih merepresentasikan geometri secara terpisah, geometri dalam file TopoJSON dijahit bersama dari segmen garis bersama yang disebut arc. |
| [OSM](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/osm/) | Format file OSM adalah format data terstruktur yang digunakan untuk menyimpan data geografis dalam proyek OpenStreetMap. File OSM biasanya berformat XML dan berisi informasi seperti lokasi jalan, bangunan, titik kepentingan, dan fitur lain pada peta. Pelajari lebih lanjut tentang format file ini di sini. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Tipe file tidak diketahui (diturunkan dari [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Lihat Juga
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
