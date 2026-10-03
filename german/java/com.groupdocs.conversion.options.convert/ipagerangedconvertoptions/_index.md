---
title: "IPageRangedConvertOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Stellt Konvertierungsoptionen dar, die die Konvertierung einer spezifischen Seitenliste unterstützen"
type: docs
weight: 52
url: /de/java/com.groupdocs.conversion.options.convert/ipagerangedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageRangedConvertOptions extends IConvertOptions
```

Stellt Konvertierungsoptionen dar, die die Konvertierung einer spezifischen Seitenliste unterstützen

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPages()](#getPages--) | Gibt die Liste der Seitenindizes zurück, die konvertiert werden sollen. |
|
|  | [setPages(List<Integer> pages)](#setPages-java.util.List-java.lang.Integer--) | Legt die Liste der Seitenindizes fest, die konvertiert werden sollen. |
|
### getPages() {#getPages--}
```
public abstract List<Integer> getPages()
```


Ruft die Liste der Seitenindizes ab, die konvertiert werden sollen. Sollte angegeben werden, um bestimmte Seiten zu konvertieren.


**Returns:**
java.util.List<java.lang.Integer> - Die Liste der Seitenindizes, die konvertiert werden sollen. Sollte angegeben werden, um bestimmte Seiten zu konvertieren.

### setPages(List<Integer> pages) {#setPages-java.util.List-java.lang.Integer--}
```
public abstract void setPages(List<Integer> pages)
```


Setzt die Liste der Seitenindizes, die konvertiert werden sollen. Sollte angegeben werden, um bestimmte Seiten zu konvertieren.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | pages | java.util.List<java.lang.Integer> | Die Liste der Seitenindizes, die konvertiert werden sollen. Sollte angegeben werden, um bestimmte Seiten zu konvertieren. |
|

