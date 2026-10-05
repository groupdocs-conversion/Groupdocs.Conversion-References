---
title: "Antarmuka Baris Perintah"
linkTitle: "Command Line Interface"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Konversi dokumen langsung dari terminal dengan alat baris perintah groupdocs-conversion — tidak memerlukan skrip Python. Periksa dokumen, daftar format yang didukung, dan terapkan lisensi, semuanya dari shell."
type: docs
url: /id/python-net/guides/command-line-interface/
is_root: false
weight: 120
---


Menginstal paket `groupdocs-conversion-net` juga menempatkan skrip konsol `groupdocs-conversion` pada `PATH` Anda. Ini merupakan pembungkus tipis di atas API Python, dibuat untuk kasus di mana menjalankan skrip Python terlalu berlebihan — pipeline shell, aturan Make, langkah CI, dan konversi satu kali.

## Prerequisites

CLI disertakan dalam paket, jadi tidak diperlukan instalasi tambahan. Pastikan `groupdocs-conversion-net` terinstal (lihat [Quick Start Guide]()), lalu verifikasi skrip konsol tersedia:

```bash
groupdocs-conversion --version
```

Anda akan melihat versi paket tercetak, misalnya `groupdocs-conversion 26.9.0`.

Jika perintah `groupdocs-conversion` tidak ditemukan, direktori skrip paket mungkin tidak ada di `PATH` Anda. Anda selalu dapat memanggil CLI melalui bentuk modul Python sebagai gantinya: `python -m groupdocs.conversion`. Kedua cara tersebut setara.

## Commands

CLI menyediakan empat subperintah. Jalankan `groupdocs-conversion --help` untuk melihat daftar lengkap flag, atau `groupdocs-conversion <command> --help` untuk subperintah tertentu.

### convert

Konversi dokumen ke format lain. Format target disimpulkan dari ekstensi file output; gunakan `--format` untuk menggantikannya.

```bash
# Ekstensi menentukan format target
groupdocs-conversion convert business-plan.docx business-plan.pdf

# Ganti format ketika nama output tidak memiliki ekstensi yang dapat digunakan
groupdocs-conversion convert business-plan.docx output.bin --format pdf

# Konversi satu halaman (indeks 1) — berguna untuk target raster
groupdocs-conversion convert annual-review.pdf page1.png --page 1 --count 1

# Buka sumber yang dilindungi kata sandi
groupdocs-conversion convert protected.docx protected.pdf --password "secret"
```

| Opsi | Deskripsi |
| :- | :- |
| `--format` | Token format target (menimpa ekstensi output). |
| `--password` | Kata sandi untuk dokumen sumber yang dilindungi. |
| `--page` | Halaman pertama yang akan dikonversi, indeks 1. |
| `--count` | Jumlah halaman yang akan dikonversi. |

Jika berhasil, perintah mencetak jalur output dan keluar dengan kode `0`.

### info

Cetak informasi dasar tentang dokumen — format, ukuran, jumlah halaman, dan tanggal pembuatan bila tersedia.

```bash
groupdocs-conversion info annual-review.pdf
```

```text
format:         pdf
size:           291788
pages_count:    10
```

Gunakan `--password` untuk sumber yang dilindungi.

### list-formats

Daftar semua format target yang dapat dihasilkan mesin untuk dokumen masukan tertentu, dibagi menjadi target utama dan sekunder.

```bash
groupdocs-conversion list-formats business-plan.docx
```

Gunakan `--password` untuk sumber yang dilindungi.

### list-all-formats

Cetak matriks konversi sumber-ke-target lengkap yang diketahui mesin — setiap format masukan dan target yang dapat dikonversi.

```bash
groupdocs-conversion list-all-formats
```

Perintah ini tidak memerlukan file masukan.

## Global options

Opsi-opsi ini berlaku untuk setiap perintah:

| Opsi | Deskripsi |
| :- | :- |
| `--license PATH` | Terapkan file lisensi sebelum menjalankan perintah. |
| `--version` | Cetak versi CLI dan keluar. |
| `--help` | Tampilkan bantuan penggunaan dan keluar. |

Terapkan lisensi di awal dengan menempatkan `--license` sebelum subperintah:

```bash
groupdocs-conversion --license GroupDocs.Conversion.lic convert business-plan.docx business-plan.pdf
```

CLI juga menghormati variabel lingkungan `GROUPDOCS_LIC_PATH` — jika disetel, lisensi diterapkan secara otomatis dan Anda dapat menghilangkan `--license`. Lihat topik [Licensing]() untuk detail.

## Format tokens

`convert` memetakan ekstensi output — atau nilai `--format`, dalam huruf kecil — ke opsi konversi yang cocok dan tipe file. Token yang didukung adalah:

| Kategori | Token |
| :- | :- |
| PDF | `pdf` |
| Pengolahan kata | `doc`, `docx`, `rtf`, `odt`, `txt`, `md` |
| Lembar kerja | `xls`, `xlsx`, `xlsm`, `ods`, `csv`, `tsv` |
| Presentasi | `ppt`, `pptx`, `pptm`, `odp` |
| Web | `html`, `htm`, `mhtml` |
| Gambar | `jpg`, `jpeg`, `png`, `bmp`, `gif`, `tiff`, `tif`, `webp`, `svg` |
| eBook | `epub`, `mobi`, `azw3` |

Token tidak dikenal menyebabkan perintah keluar dengan kode `2` dan mencetak daftar token yang diterima.

## Exit codes

| Kode | Arti |
| :- | :- |
| `0` | Berhasil. |
| `2` | Kesalahan pengguna — token format tidak dikenal atau file input tidak ada. |
| `1` | Kesalahan runtime — pesan pengecualian .NET yang mendasari dicetak ke standar error. |

Kode-kode ini memudahkan penggunaan CLI dalam skrip shell dan pipeline CI.

## When to use the Python API instead

CLI mencakup kasus konversi dokumen tunggal yang umum. Untuk hal di luar itu — panggilan balik per halaman, aliran dalam memori, watermark, font, atau opsi rentang sel, dan hierarki kontainer multi-dokumen — gunakan API Python secara langsung. API ini menyediakan permukaan yang lebih kaya dibandingkan flag CLI. Lihat [Panduan Pengembang]() untuk set fitur lengkap.

## Next Steps

- [Quick Start Guide](): Convert your first document with the Python API.
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Apply a license to remove evaluation limits.
- [Technical Support](): Contact support if you encounter issues.
