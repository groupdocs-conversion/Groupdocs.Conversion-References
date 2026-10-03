---
title: "NoteFileType"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Definiert Notizformate."
type: docs
weight: 19
url: /de/java/com.groupdocs.conversion.filetypes/notefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class NoteFileType extends FileType
```

Definiert Notizformate. Enthält die folgenden Dateitypen:
[One](../../com.groupdocs.conversion.filetypes/notefiletype#One).
Erfahren Sie mehr über Notizformate [hier](../https://wiki.fileformat.com/note-taking).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [NoteFileType()](#NoteFileType--) | Serialisierungskonstruktor |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [One](#One) | Dateien mit der Erweiterung .ONE werden von der Microsoft OneNote-Anwendung erstellt. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### NoteFileType() {#NoteFileType--}
```
public NoteFileType()
```


Serialisierungskonstruktor


### One {#One}
```
public static final NoteFileType One
```


Dateien mit der Erweiterung .ONE werden von der Microsoft OneNote-Anwendung erstellt. OneNote ermöglicht es Ihnen, Informationen zu sammeln, als würden Sie Ihr Notizblock zum Notieren verwenden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/note-taking/one).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Standard‑Ladeoptionen für den Quelldateityp vorbereitet


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
