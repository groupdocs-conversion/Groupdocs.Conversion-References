---
title: "IPageRangedConvertOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Geeft de conversie‑opties weer die conversie van een specifieke lijst pagina's ondersteunen."
type: docs
weight: 52
url: /nl/java/com.groupdocs.conversion.options.convert/ipagerangedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageRangedConvertOptions extends IConvertOptions
```

Geeft de conversie‑opties weer die conversie van een specifieke lijst pagina's ondersteunen.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPages()](#getPages--) | Haalt de lijst met paginanummers op die moeten worden geconverteerd. |
|
|  | [setPages(List<Integer> pages)](#setPages-java.util.List-java.lang.Integer--) | Stelt de lijst met paginanummers in die moeten worden geconverteerd. |
|
### getPages() {#getPages--}
```
public abstract List<Integer> getPages()
```


Haalt de lijst met paginanummers op die moeten worden geconverteerd. Moet worden opgegeven om specifieke pagina's te converteren.


**Returns:**
java.util.List<java.lang.Integer> - De lijst met paginanummers die moeten worden geconverteerd. Moet worden opgegeven om specifieke pagina's te converteren.

### setPages(List<Integer> pages) {#setPages-java.util.List-java.lang.Integer--}
```
public abstract void setPages(List<Integer> pages)
```


Stelt de lijst met paginanummers in die moeten worden geconverteerd. Moet worden opgegeven om specifieke pagina's te converteren.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | pages | java.util.List<java.lang.Integer> | De lijst met paginanummers die moeten worden geconverteerd. Moet worden opgegeven om specifieke pagina's te converteren. |
|

