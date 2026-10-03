---
title: "NoteFileType"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Define formatos para tomar notas."
type: docs
weight: 19
url: /es/java/com.groupdocs.conversion.filetypes/notefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class NoteFileType extends FileType
```

Define formatos de toma de notas. Incluye los siguientes tipos de archivo:
[One](../../com.groupdocs.conversion.filetypes/notefiletype#One).
Obtén más información sobre los formatos de toma de notas [aquí](../https://wiki.fileformat.com/note-taking).

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [NoteFileType()](#NoteFileType--) | Constructor de serialización |
|
## Campos

| Campo | Descripción |
| --- | --- |
|  | [One](#One) | Los archivos con extensión .ONE son creados por la aplicación Microsoft OneNote. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### NoteFileType() {#NoteFileType--}
```
public NoteFileType()
```


Constructor de serialización


### One {#One}
```
public static final NoteFileType One
```


Los archivos con extensión .ONE son creados por la aplicación Microsoft OneNote. OneNote te permite recopilar información usando la aplicación como si estuvieras usando tu bloc de notas para tomar notas.
Obtén más información sobre este formato de archivo [aquí](../https://wiki.fileformat.com/note-taking/one).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Opciones de carga predeterminadas preparadas para el tipo de archivo de origen


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
