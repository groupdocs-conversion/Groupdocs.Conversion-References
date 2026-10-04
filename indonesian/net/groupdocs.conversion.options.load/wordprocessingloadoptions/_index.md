---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk memuat dokumen WordProcessing."
type: docs
weight: 2950
url: /id/net/groupdocs.conversion.options.load/wordprocessingloadoptions/
---
## WordProcessingLoadOptions class

Opsi untuk memuat dokumen WordProcessing.

```csharp
public class WordProcessingLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IFontTransformationLoadOptions, IMetadataLoadOptions, 
    IPageMarginOptions, IPageNumberingLoadOptions, IPageSizeOptions, IResourceLoadingOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [WordProcessingLoadOptions](wordprocessingloadoptions)() | Menginisialisasi instance baru dari kelas [`WordProcessingLoadOptions`](../wordprocessingloadoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AutoDetectRtlDirection](../../groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection) { get; set; } | Jika bernilai true (default), paragraf dan run yang teksnya dominan kanan-ke-kiri akan memiliki flag bidi yang diperbaiki sebelum konversi. Ini cocok dengan heuristik yang diterapkan oleh Microsoft Word dan LibreOffice serta memperbaiki rendering dokumen Arab/Hebrew yang dihasilkan oleh pembuat (khususnya Google Docs) yang menghasilkan OOXML tanpa &lt;w:bidi/&gt; dan dengan &lt;w:rtl w:val="0"/&gt; pada run yang hanya berisi skrip RTL. Atur ke false untuk mempertahankan interpretasi OOXML yang ketat dari markup sumber. |
| [BookmarkOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/bookmarkoptions) { get; set; } | Opsi bookmark |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearbuiltindocumentproperties) { get; set; } | Menghapus properti metadata bawaan dari dokumen. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearcustomdocumentproperties) { get; set; } | Menghapus properti metadata kustom dari dokumen. |
| [CommentDisplayMode](../../groupdocs.conversion.options.load/wordprocessingloadoptions/commentdisplaymode) { get; set; } | Menentukan bagaimana komentar harus ditampilkan dalam dokumen output. Default adalah ShowInBalloons. |
| [ConvertOwned](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowned) { get; set; } | Menerapkan [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Default adalah false |
| [ConvertOwner](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowner) { get; set; } | Menerapkan [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Default adalah true |
| [DefaultFont](../../groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont) { get; set; } | Mengatur font default untuk dokumen WordProcessing. |
| [Depth](../../groupdocs.conversion.options.load/wordprocessingloadoptions/depth) { get; set; } | Menerapkan [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Default: 1 |
| [EmbedTrueTypeFonts](../../groupdocs.conversion.options.load/wordprocessingloadoptions/embedtruetypefonts) { get; set; } | Jika EmbedTrueTypeFonts bernilai true, GroupDocs.Conversion menyematkan font true type dalam dokumen output. Default: true |
| [FontConfigSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontconfigsubstitutionenabled) { get; set; } | Secara otomatis menggantikan font yang hilang berdasarkan FontConfig di sistem. Default: false. |
| [FontInfoSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontinfosubstitutionenabled) { get; set; } | Secara otomatis menggantikan font yang hilang berdasarkan FontInfo dalam dokumen. Default: false. |
| [FontNameSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontnamesubstitutionenabled) { get; set; } | Secara otomatis menggantikan font yang hilang berdasarkan nama font. Default: false. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontsubstitutes) { get; set; } | Mengganti font tertentu saat mengonversi dokumen WordsProcessing. |
| [FontTransformations](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fonttransformations) { get; set; } | Mengubah font yang ada setelah pemuatan dokumen dan substitusi font selesai. Transformasi font dapat memodifikasi semua font dalam dokumen, termasuk font yang berhasil dimuat. |
| [Format](../../groupdocs.conversion.options.load/wordprocessingloadoptions/format) { get; set; } | Tipe berkas dokumen input. Nilainya `null` sampai format ditetapkan, jadi periksa apakah `null` daripada membandingkannya dengan [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), yang tidak pernah sama. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipe berkas dokumen input. |
| [HideWordTrackedChanges](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hidewordtrackedchanges) { get; set; } | Sembunyikan markup dan lacak perubahan untuk dokumen Word. |
| [HyphenationOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenationoptions) { get; set; } | Atur opsi hyphenation untuk dokumen WordProcessing. |
| [KeepDateFieldOriginalValue](../../groupdocs.conversion.options.load/wordprocessingloadoptions/keepdatefieldoriginalvalue) { get; set; } | Pertahankan nilai asli dari field tanggal. Default: false |
| [MarginSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/marginsettings) { get; set; } | Pengaturan margin halaman |
| [PageNumbering](../../groupdocs.conversion.options.load/wordprocessingloadoptions/pagenumbering) { get; set; } | Aktifkan atau nonaktifkan pembuatan penomoran halaman dalam dokumen yang dikonversi. Default: false |
| [Password](../../groupdocs.conversion.options.load/wordprocessingloadoptions/password) { get; set; } | Atur kata sandi untuk membuka proteksi dokumen yang dilindungi. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preservedocumentstructure) { get; set; } | Menentukan apakah struktur dokumen harus dipertahankan saat mengonversi ke PDF (default adalah false). |
| [PreserveFormFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preserveformfields) { get; set; } | Menentukan apakah akan mempertahankan field formulir Microsoft Word sebagai field formulir di PDF atau mengubahnya menjadi teks. Default adalah false. |
| [ShowFullCommenterName](../../groupdocs.conversion.options.load/wordprocessingloadoptions/showfullcommentername) { get; set; } | Tampilkan nama lengkap pemberi komentar dalam komentar. Default adalah false. |
| [SizeSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/sizesettings) { get; set; } | Pengaturan ukuran halaman |
| [SkipExternalResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/skipexternalresources) { get; set; } | Menerapkan [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UpdateFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatefields) { get; set; } | Perbarui field setelah pemuatan. Default: false |
| [UpdatePageLayout](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatepagelayout) { get; set; } | Perbarui tata letak halaman setelah pemuatan. Default: false |
| [UseTextShaper](../../groupdocs.conversion.options.load/wordprocessingloadoptions/usetextshaper) { get; set; } | Menentukan apakah akan menggunakan text shaper untuk tampilan kerning yang lebih baik. Default adalah false. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/whitelistedresources) { get; set; } | Menerapkan [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Catatan

**Font Processing Pipeline:**

**Phase 1 - Font Substitution (during document loading):**

• Menangani font yang hilang/tidak tersedia menggunakan FontSubstitutes, DefaultFont, dan substitusi sistem

• Urutan pemrosesan: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

**Phase 2 - Font Replacement (after document loading):**

• Memodifikasi semua font yang ada dalam dokumen yang dimuat menggunakan FontReplacements

• Diterapkan setelah semua substitusi font selesai

### Lihat Juga

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IFontTransformationLoadOptions](../ifonttransformationloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
