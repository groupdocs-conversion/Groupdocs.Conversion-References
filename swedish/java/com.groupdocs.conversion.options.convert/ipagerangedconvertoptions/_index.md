---
title: "IPageRangedConvertOptions"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Representerar konverteringsalternativ som stödjer konvertering av en specifik lista med sidor"
type: docs
weight: 52
url: /sv/java/com.groupdocs.conversion.options.convert/ipagerangedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageRangedConvertOptions extends IConvertOptions
```

Representerar konverteringsalternativ som stödjer konvertering av en specifik lista med sidor

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPages()](#getPages--) | Hämtar listan med sidindex som ska konverteras. |
|
|  | [setPages(List<Integer> pages)](#setPages-java.util.List-java.lang.Integer--) | Ställer in listan med sidindex som ska konverteras. |
|
### getPages() {#getPages--}
```
public abstract List<Integer> getPages()
```


Hämtar listan över sidindex som ska konverteras. Ska specificeras för att konvertera specifika sidor.


**Returns:**
java.util.List<java.lang.Integer> - Listan med sidindex som ska konverteras. Ska specificeras för att konvertera specifika sidor.

### setPages(List<Integer> pages) {#setPages-java.util.List-java.lang.Integer--}
```
public abstract void setPages(List<Integer> pages)
```


Ställer in listan över sidindex som ska konverteras. Ska specificeras för att konvertera specifika sidor.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | pages | java.util.List<java.lang.Integer> | Listan med sidindex som ska konverteras. Ska specificeras för att konvertera specifika sidor. |
|

