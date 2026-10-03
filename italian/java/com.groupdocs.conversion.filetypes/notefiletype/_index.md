---
title: "NoteFileType"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Definisce i formati per prendere appunti."
type: docs
weight: 19
url: /it/java/com.groupdocs.conversion.filetypes/notefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class NoteFileType extends FileType
```

Definisce i formati per prendere appunti. Include i seguenti tipi di file:
[One](../../com.groupdocs.conversion.filetypes/notefiletype#One).
Scopri di più sui formati per prendere appunti [qui](../https://wiki.fileformat.com/note-taking).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [NoteFileType()](#NoteFileType--) | Costruttore di serializzazione |
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [One](#One) | I file con estensione .ONE sono creati dall'applicazione Microsoft OneNote. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### NoteFileType() {#NoteFileType--}
```
public NoteFileType()
```


Costruttore di serializzazione


### One {#One}
```
public static final NoteFileType One
```


I file con estensione .ONE sono creati dall'applicazione Microsoft OneNote. OneNote ti consente di raccogliere informazioni usando l'applicazione come se stessi usando il tuo blocco note per prendere appunti.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/note-taking/one).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Opzioni di caricamento predefinite preparate per il tipo di file di origine


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
