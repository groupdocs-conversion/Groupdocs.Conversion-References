---
title: "PossibleConversions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Stellt eine Zuordnung dar, welche Konvertierungspaare für ein bestimmtes Quelldateiformat unterstützt werden."
type: docs
weight: 13
url: /de/java/com.groupdocs.conversion.contracts/possibleconversions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public final class PossibleConversions extends ValueObject
```

Stellt eine Zuordnung dar, welche Konvertierungspaare für ein bestimmtes Quelldateiformat unterstützt werden.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PossibleConversions(FileType source)](#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-) | Erstellt mögliche Konvertierungsliste für das angegebene Quelldateiformat |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
| [NULL](#NULL) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getLoadOptions()](#getLoadOptions--) | Vordefinierte Ladeoptionen, die verwendet werden können, um vom aktuellen Typ zu konvertieren |
|
|  | [getAll()](#getAll--) | Alle Ziel-Dateitypen und Primär-/Sekundär-Flag |
|
|  | [getTargetConversion(FileType target)](#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-) | Gibt die Zielkonvertierung für den angegebenen Ziel-Dateityp zurück |
|
| [getTargetConversion(String extension)](#getTargetConversion-java.lang.String-) |  |
|  | [getPrimary()](#getPrimary--) | Primäre Ziel-Dateitypen |
|
|  | [getSecondary()](#getSecondary--) | Sekundäre Ziel-Dateitypen |
|
|  | [add(ConversionPair pair)](#add-com.groupdocs.conversion.contracts.ConversionPair-) | Konvertierungspaar hinzufügen |
|
|  | [forTarget(FileType target)](#forTarget-com.groupdocs.conversion.filetypes.FileType-) | Konvertierungspaar in der aktuellen Liste für den Ziel-Dateityp finden |
|
|  | [getSource()](#getSource--) | Quell-Dateiformate |
|
### PossibleConversions(FileType source) {#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-}
```
public PossibleConversions(FileType source)
```


Erstellt mögliche Konvertierungsliste für das angegebene Quelldateiformat


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Quell-Dateityp |
|

### NULL {#NULL}
```
public static final PossibleConversions NULL
```


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Vordefinierte Ladeoptionen, die verwendet werden können, um vom aktuellen Typ zu konvertieren


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - load options

### getAll() {#getAll--}
```
public Iterable<TargetConversion> getAll()
```


Alle Ziel-Dateitypen und Primär-/Sekundär-Flag


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.contracts.TargetConversion> - Iterable von [TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)

### getTargetConversion(FileType target) {#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-}
```
public TargetConversion getTargetConversion(FileType target)
```


Gibt die Zielkonvertierung für den angegebenen Ziel-Dateityp zurück


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Ziel-Dateityp |
|

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion) - conversions

### getTargetConversion(String extension) {#getTargetConversion-java.lang.String-}
```
public TargetConversion getTargetConversion(String extension)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Erweiterung | java.lang.String |  |

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)
### getPrimary() {#getPrimary--}
```
public Iterable<FileType> getPrimary()
```


Primäre Ziel-Dateitypen


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - primäre Ziel-Dateitypen

### getSecondary() {#getSecondary--}
```
public Iterable<FileType> getSecondary()
```


Sekundäre Ziel-Dateitypen


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - sekundäre Ziel-Dateitypen

### add(ConversionPair pair) {#add-com.groupdocs.conversion.contracts.ConversionPair-}
```
public void add(ConversionPair pair)
```


Konvertierungspaar hinzufügen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | pair | [ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) | Konvertierungspaar |
|

### forTarget(FileType target) {#forTarget-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionPair forTarget(FileType target)
```


Konvertierungspaar in der aktuellen Liste für den Ziel-Dateityp finden


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Ziel-Dateityp |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - conversion pair

### getSource() {#getSource--}
```
public FileType getSource()
```


Quell-Dateiformate


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file formats

