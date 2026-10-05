---
title: "NoteFileType"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Definierar anteckningsformat."
type: docs
weight: 19
url: /sv/nodejs-java/com.groupdocs.conversion.filetypes/notefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class NoteFileType extends FileType
```

Definierar anteckningsformat. Inkluderar följande filtyper: [One](../../com.groupdocs.conversion.filetypes/notefiletype\#One). Läs mer om anteckningsformat [here][].


[here]: https://wiki.fileformat.com/note-taking
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [NoteFileType()](#NoteFileType--) | Serialiseringskonstruktor |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [One](#One) | Filer med .ONE‑tillägg skapas av Microsoft OneNote‑applikationen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### NoteFileType() {#NoteFileType--}
```
public NoteFileType()
```


Serialiseringskonstruktor

### One {#One}
```
public static final NoteFileType One
```


Filer med .ONE‑tillägg skapas av Microsoft OneNote‑applikationen. OneNote låter dig samla information med applikationen som om du använde ditt anteckningsblock för att ta anteckningar. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/note-taking/one

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Förberedda standardalternativ för inläsning för källfiltypen

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
