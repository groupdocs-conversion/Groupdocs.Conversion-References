---
title: "NoteFileType"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mendefinisikan format pencatatan."
type: docs
weight: 19
url: /id/java/com.groupdocs.conversion.filetypes/notefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class NoteFileType extends FileType
```

Mendefinisikan format pencatatan. Menyertakan tipe file berikut:
[One](../../com.groupdocs.conversion.filetypes/notefiletype#One).
Pelajari lebih lanjut tentang format pencatatan [di sini](../https://wiki.fileformat.com/note-taking).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [NoteFileType()](#NoteFileType--) | Konstruktor serialisasi |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [One](#One) | File dengan ekstensi .ONE dibuat oleh aplikasi Microsoft OneNote. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### NoteFileType() {#NoteFileType--}
```
public NoteFileType()
```


Konstruktor serialisasi


### One {#One}
```
public static final NoteFileType One
```


File dengan ekstensi .ONE dibuat oleh aplikasi Microsoft OneNote. OneNote memungkinkan Anda mengumpulkan informasi menggunakan aplikasi tersebut seolah-olah Anda menggunakan buku catatan untuk mencatat.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/note-taking/one).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Menyiapkan opsi muat default untuk tipe file sumber


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
