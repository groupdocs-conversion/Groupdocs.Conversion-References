---
title: "GisFileType"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mendefinisikan dokumen GIS. Menyertakan tipe file berikut Shp./gisfiletype/shp. GeoJson./gisfiletype/geojson. GeoJsonSeq./gisfiletype/geojsonseq. Gdb./gisfiletype/gdb. Gml./gisfiletype/gml. Kml./gisfiletype/kml. Kmz./gisfiletype/kmz. Gpx./gisfiletype/gpx. TopoJson./gisfiletype/topojson. Osm./gisfiletype/osm."
type: docs
weight: 1160
url: /id/net/groupdocs.conversion.filetypes/gisfiletype/
---
## GisFileType class

Mendefinisikan dokumen GIS. Menyertakan tipe file berikut: [`Shp`](./shp). [`GeoJson`](./geojson). [`GeoJsonSeq`](./geojsonseq). [`Gdb`](./gdb). [`Gml`](./gml). [`Kml`](./kml). [`Kmz`](./kmz). [`Gpx`](./gpx). [`TopoJson`](./topojson). [`Osm`](./osm).

```csharp
public sealed class GisFileType : FileType
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [GisFileType](gisfiletype)() | Konstruktor Serialisasi |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Deskripsi tipe file |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Ekstensi file |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Keluarga file |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Format file |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Membandingkan objek saat ini dengan objek lain. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Mengimplementasikan [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Berfungsi sebagai fungsi hash default. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representasi string |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [Gdb](../../groupdocs.conversion.filetypes/gisfiletype/gdb) | Geodatabase file ESRI (FileGDB) adalah kumpulan file dalam sebuah folder di disk yang menyimpan data geospasial terkait seperti dataset fitur, kelas fitur, dan tabel terkait. Ia memerlukan beberapa file lain yang disimpan bersamaan dengan file .gdb di direktori yang sama agar dapat berfungsi. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/database/gdb/). |
| static readonly [GeoJson](../../groupdocs.conversion.filetypes/gisfiletype/geojson) | GeoJSON adalah format berbasis JSON yang dirancang untuk merepresentasikan fitur geografis beserta atribut non-spasialnya. Format ini mendefinisikan berbagai objek JSON (JavaScript Object Notation) dan cara penggabungannya. Format JSON menyajikan informasi kolektif tentang fitur geografis, ekstensi spasial, dan propertinya. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/gis/geojson/). |
| static readonly [GeoJsonSeq](../../groupdocs.conversion.filetypes/gisfiletype/geojsonseq) | GeoJSON Text Sequence adalah aliran rekaman GeoJSON independen bukan satu dokumen yang membungkus, setiap rekaman dipisahkan oleh baris baru atau karakter kontrol RS. Ini digunakan untuk umpan yang ditambahkan seiring waktu, di mana akhir koleksi tidak diketahui saat penulisan dimulai. |
| static readonly [Gml](../../groupdocs.conversion.filetypes/gisfiletype/gml) | GML merupakan singkatan dari Geography Markup Language yang berbasis pada spesifikasi XML yang dikembangkan oleh Open Geospatial Consortium (OGC). Format ini digunakan untuk menyimpan fitur data geografis untuk pertukaran antar format file yang berbeda. Ia berfungsi sebagai bahasa pemodelan untuk sistem geografis serta sebagai format pertukaran terbuka untuk transaksi geografis di internet. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/gis/gml/). |
| static readonly [Gpx](../../groupdocs.conversion.filetypes/gisfiletype/gpx) | File dengan ekstensi GPX mewakili format GPS Exchange untuk pertukaran data GPS antara aplikasi dan layanan web di internet. Ini adalah format file XML ringan yang berisi data GPS seperti waypoint, rute, dan trek yang dapat diimpor dan dibaca oleh banyak program. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/gis/gpx/). |
| static readonly [Kml](../../groupdocs.conversion.filetypes/gisfiletype/kml) | KML (Keyhole Markup Language) berisi informasi geospasial dalam notasi XML. File yang disimpan sebagai KML dapat dibuka di aplikasi Geographic Information System (GIS) asalkan mereka mendukungnya. Banyak aplikasi telah mulai menyediakan dukungan untuk format file KML setelah diadopsi sebagai standar internasional. KML menggunakan struktur berbasis tag dengan elemen bersarang dan atribut. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/gis/kml/). |
| static readonly [Kmz](../../groupdocs.conversion.filetypes/gisfiletype/kmz) | KMZ adalah arsip ZIP yang membawa dokumen KML, secara konvensional dinamai doc.kml di akar arsip, bersama dengan sumber daya apa pun yang dirujuk dokumen tersebut. Memampatkan markup adalah tujuannya: umpan KML berukuran apa pun menyusut secara dramatis, itulah mengapa penerbit mendistribusikan KMZ daripada KML. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/gis/kmz/). |
| static readonly [Osm](../../groupdocs.conversion.filetypes/gisfiletype/osm) | Format file OSM adalah format data terstruktur yang digunakan untuk menyimpan data geografis dalam proyek OpenStreetMap. File OSM biasanya berformat XML dan berisi informasi seperti lokasi jalan, bangunan, titik kepentingan, dan fitur lain pada peta. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/gis/osm/). |
| static readonly [Shp](../../groupdocs.conversion.filetypes/gisfiletype/shp) | SHP adalah ekstensi file untuk salah satu tipe file utama yang digunakan untuk representasi ESRI Shapefile. Ia mewakili informasi Geospasial dalam bentuk data vektor yang akan digunakan oleh aplikasi Geographic Information Systems (GIS). Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/gis/shp/). |
| static readonly [TopoJson](../../groupdocs.conversion.filetypes/gisfiletype/topojson) | TopoJSON adalah ekstensi dari GeoJSON yang mengkodekan topologi. Alih-alih merepresentasikan geometri secara terpisah, geometri dalam file TopoJSON dijahit bersama dari segmen garis bersama yang disebut arcs. |

### Lihat Juga

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
