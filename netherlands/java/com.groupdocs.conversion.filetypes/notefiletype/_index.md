---
title: "NoteFileType"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Definieert notitie‑formaten."
type: docs
weight: 19
url: /nl/java/com.groupdocs.conversion.filetypes/notefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class NoteFileType extends FileType
```

Definieert notitieformaten. Bevat de volgende bestandstypen:
[One](../../com.groupdocs.conversion.filetypes/notefiletype#One).
Meer informatie over notitieformaten [hier](../https://wiki.fileformat.com/note-taking).

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [NoteFileType()](#NoteFileType--) | Serialisatieconstructor |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [One](#One) | Bestand met de .ONE-extensie wordt gemaakt door de Microsoft OneNote-toepassing. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### NoteFileType() {#NoteFileType--}
```
public NoteFileType()
```


Serialisatieconstructor


### One {#One}
```
public static final NoteFileType One
```


Bestand met de .ONE-extensie wordt gemaakt door de Microsoft OneNote-toepassing. OneNote stelt je in staat informatie te verzamelen met de toepassing alsof je je kladblok gebruikt om notities te maken.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/note-taking/one).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Voorbereide standaard laadopties voor het bronbestandstype


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
