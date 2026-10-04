---
title: "ThreeDFileType"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mendefinisikan dokumen 3D Menyertakan tipe berikut Fbx./threedfiletype/fbxThreeDS./threedfiletype/threedsThreeMF./threedfiletype/threemfAmf./threedfiletype/amfAse./threedfiletype/aseRvm./threedfiletype/rvmDae./threedfiletype/daeDrc./threedfiletype/drcGltf./threedfiletype/gltfObj./threedfiletype/objPly./threedfiletype/plyJt./threedfiletype/jtU3d./threedfiletype/u3dUsd./threedfiletype/usdUsdz./threedfiletype/usdzVrml./threedfiletype/vrmlX./threedfiletype/xGlb./threedfiletype/glbMa./threedfiletype/maMb./threedfiletype/mb Pelajari lebih lanjut tentang format 3D di sinihttps//wiki.fileformat.com/3d."
type: docs
weight: 1250
url: /id/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

Mendefinisikan dokumen 3D Menyertakan tipe berikut: [`Fbx`](./fbx)[`ThreeDS`](./threeds)[`ThreeMF`](./threemf)[`Amf`](./amf)[`Ase`](./ase)[`Rvm`](./rvm)[`Dae`](./dae)[`Drc`](./drc)[`Gltf`](./gltf)[`Obj`](./obj)[`Ply`](./ply)[`Jt`](./jt)[`U3d`](./u3d)[`Usd`](./usd)[`Usdz`](./usdz)[`Vrml`](./vrml)[`X`](./x)[`Glb`](./glb)[`Ma`](./ma)[`Mb`](./mb) Pelajari lebih lanjut tentang format 3D [di sini](https://wiki.fileformat.com/3d).

```csharp
public sealed class ThreeDFileType : FileType
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | Konstruktor Serialisasi |

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
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | Sebuah file AMF terdiri dari pedoman untuk deskripsi objek agar dapat digunakan oleh proses Manufaktur Aditif. File ini berisi tag XML pembuka dan diakhiri dengan sebuah elemen. Ini didahului oleh baris deklarasi XML yang menentukan versi XML dan pengkodean file. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/3d/amf). |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | File dengan ekstensi .ase adalah format file Autodesk ASCII Scene Export yang merupakan representasi ASCII dari sebuah adegan, berisi informasi 2D atau 3D saat mengekspor data adegan menggunakan Autodesk. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/3d/ase). |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | File DAE adalah format file Digital Asset Exchange yang digunakan untuk pertukaran data antara aplikasi 3D interaktif. Format file ini didasarkan pada skema XML COLLADA (COLLAborative Design Activity) yang merupakan skema XML standar terbuka untuk pertukaran aset digital di antara aplikasi perangkat lunak grafis. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/3d/dae). |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | File dengan ekstensi .drc adalah format file 3D terkompresi yang dibuat dengan pustaka Google Draco. Google menyediakan Draco sebagai pustaka sumber terbuka untuk mengompresi dan mendekompresi mesh geometrik 3D serta awan titik, dan meningkatkan penyimpanan serta transmisi grafis 3D. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/3d/drc). |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX, FilmBox, adalah format file 3D populer yang awalnya dikembangkan oleh Kaydara untuk MotionBuilder. Format ini diakuisisi oleh Autodesk Inc pada tahun 2006 dan kini menjadi salah satu format pertukaran 3D utama yang digunakan oleh banyak alat 3D. FBX tersedia dalam format file biner maupun ASCII. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/3d/fbx). |
| static readonly [Glb](../../groupdocs.conversion.filetypes/threedfiletype/glb) | GLB adalah representasi format file biner dari model 3D yang disimpan dalam GL Transmission Format (glTF). Format biner ini menyimpan aset glTF (JSON, .bin, dan gambar) dalam sebuah blob biner. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/3d/glb). |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF (GL Transmission Format) adalah format file 3D yang menyimpan informasi model 3D dalam format JSON. Penggunaan JSON meminimalkan ukuran aset 3D serta pemrosesan runtime yang diperlukan untuk membuka dan menggunakan aset tersebut. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/3d/gltf). |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT (Jupiter Tessellation) adalah format data 3D yang efisien, berfokus pada industri, dan fleksibel yang distandarisasi ISO, dikembangkan oleh Siemens PLM Software. Domain CAD mekanik di bidang Dirgantara, industri otomotif, dan Peralatan Berat menggunakan JT sebagai format visualisasi 3D terkemuka mereka. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/3d/jt). |
| static readonly [Ma](../../groupdocs.conversion.filetypes/threedfiletype/ma) | File dengan ekstensi .ma adalah file proyek 3D yang dibuat dengan aplikasi Autodesk Maya. File ini berisi daftar panjang perintah teks untuk menentukan informasi tentang file tersebut. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/3d/ma). |
| static readonly [Mb](../../groupdocs.conversion.filetypes/threedfiletype/mb) | File dengan ekstensi .mb adalah file proyek biner yang dibuat dengan aplikasi Autodesk Maya. Tidak seperti format file MA, yang berbentuk format file ASCII, file MB disimpan dalam format file biner. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/3d/mb). |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | File OBJ digunakan oleh aplikasi Advanced Visualizer milik Wavefront untuk mendefinisikan dan menyimpan objek geometris. Transmisi data geometris mundur dan maju dimungkinkan melalui file OBJ. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/3d/obj). |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY, Polygon File Format, merupakan format file 3D yang menyimpan objek grafis yang dijelaskan sebagai kumpulan poligon. Tujuan format file ini adalah untuk membuat tipe file yang sederhana dan mudah serta cukup umum untuk berguna bagi berbagai model. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/3d/ply). |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | File data RVM terkait dengan AVEVA PDMS. File RVM adalah file proyek Model Sistem Manajemen Desain Pabrik AVEVA. Sistem Manajemen Desain Pabrik (PDMS) milik AVEVA adalah sistem desain 3D paling populer yang menggunakan teknologi berpusat pada data untuk mengelola proyek. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/3d/rvm). |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | File dengan ekstensi .3ds merupakan format file mesh 3D Sudio (DOS) yang digunakan oleh Autodesk 3D Studio. Autodesk 3D Studio telah berada di pasar format file 3D sejak tahun 1990-an dan kini telah berkembang menjadi 3D Studio MAX untuk bekerja dengan pemodelan 3D, animasi, dan rendering. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/3d/3ds). |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF, 3D Manufacturing Format, digunakan oleh aplikasi untuk merender model objek 3D ke berbagai aplikasi, platform, layanan, dan printer lainnya. Format ini dibuat untuk menghindari keterbatasan dan masalah pada format file 3D lain, seperti STL, dalam bekerja dengan versi terbaru printer 3D. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/3d/3mf). |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D) adalah format file terkompresi dan struktur data untuk grafis komputer 3D. Ia berisi informasi model 3D seperti mesh segitiga, pencahayaan, shading, data gerakan, garis, dan titik dengan warna serta struktur. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/3d/u3d). |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | File dengan ekstensi .usd adalah format file Universal Scene Description yang mengkodekan data untuk tujuan pertukaran dan augmentasi data antar aplikasi pembuatan konten digital. Dikembangkan oleh Pixar, USD menyediakan kemampuan untuk menukar aset elementer (seperti model) atau animasi. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/3d/usd). |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | File dengan ekstensi .usdz adalah arsip ZIP yang tidak terkompresi dan tidak terenkripsi untuk format file USD (Universal Scene Description) yang berisi dan menjadi proxy untuk file dari format lain (seperti tekstur, dan animasi) yang disematkan dalam arsip dan menjalankannya secara langsung dengan runtime USD tanpa perlu mengekstrak. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/3d/usdz). |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | Virtual Reality Modeling Language (VRML) adalah format file untuk representasi objek dunia 3D interaktif di World Wide Web (www). Ia digunakan untuk membuat representasi tiga dimensi dari adegan kompleks seperti ilustrasi, definisi, dan presentasi realitas virtual. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/3d/vrml). |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | File dengan ekstensi .x mengacu pada format file warisan DirectX 3D Graphics yang diperkenalkan bersama Microsoft DirectX 2.0. Format ini digunakan untuk rendering grafis 3D dalam game dan menentukan struktur untuk mesh, tekstur, animasi, serta objek yang didefinisikan pengguna. Format ini telah dihentikan sejak 2014 karena format file Autodesk FBX lebih cocok sebagai format yang lebih modern. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/3d/x). |

### Lihat Juga

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
