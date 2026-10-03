---
title: "WebFileType"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Definierar webb-dokument."
type: docs
weight: 27
url: /sv/java/com.groupdocs.conversion.filetypes/webfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WebFileType extends FileType implements Serializable
```

Definierar webb-dokument.
Inkluderar följande typer:
[Xml](../../com.groupdocs.conversion.filetypes/webfiletype#Xml),
[Json](../../com.groupdocs.conversion.filetypes/webfiletype#Json),
[Html](../../com.groupdocs.conversion.filetypes/webfiletype#Html),
[Htm](../../com.groupdocs.conversion.filetypes/webfiletype#Htm),
[Mht](../../com.groupdocs.conversion.filetypes/webfiletype#Mht),
[Mhtml](../../com.groupdocs.conversion.filetypes/webfiletype#Mhtml),
[Chm](../../com.groupdocs.conversion.filetypes/webfiletype#Chm),
Läs mer om webbformat [här](../https://wiki.fileformat.com/web).

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [WebFileType()](#WebFileType--) | Serialiseringskonstruktor |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Xml](#Xml) | XML står för Extensible Markup Language som liknar HTML men skiljer sig åt genom att använda taggar för att definiera objekt. |
|
|  | [Json](#Json) | JSON (JavaScript Object Notation) är ett öppet standardfilformat för att dela data som använder människoläsbar text för att lagra och överföra data. |
|
|  | [Html](#Html) | HTML (Hyper Text Markup Language) är filändelsen för webbsidor som skapats för visning i webbläsare. |
|
|  | [Htm](#Htm) | HTM (Hyper Text Markup Language) är filändelsen för webbsidor som skapats för visning i webbläsare. |
|
|  | [Mht](#Mht) | Filer med MHTML‑tillägg representerar ett webbsidesarkivformat som kan skapas av ett antal olika program. |
|
|  | [Mhtml](#Mhtml) | Filer med MHTML‑tillägg representerar ett webbsidesarkivformat som kan skapas av ett antal olika program. |
|
|  | [Chm](#Chm) | CHM‑filformatet representerar Microsoft HTML-hjälpfil som består av en samling HTML‑sidor. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WebFileType() {#WebFileType--}
```
public WebFileType()
```


Serialiseringskonstruktor


### Xml {#Xml}
```
public static final WebFileType Xml
```


XML står för Extensible Markup Language som liknar HTML men skiljer sig åt genom att använda taggar för att definiera objekt. Läs mer om detta filformat [här](../https://wiki.fileformat.com/web/xml).


### Json {#Json}
```
public static final WebFileType Json
```


JSON (JavaScript Object Notation) är ett öppet standardfilformat för att dela data som använder människoläsbar text för att lagra och överföra data. Läs mer om detta filformat [här](../https://docs.fileformat.com/web/json).


### Html {#Html}
```
public static final WebFileType Html
```


HTML (Hyper Text Markup Language) är filändelsen för webbsidor som skapats för visning i webbläsare. Läs mer om detta filformat [här](../https://wiki.fileformat.com/web/html).


### Htm {#Htm}
```
public static final WebFileType Htm
```


HTM (Hyper Text Markup Language) är filändelsen för webbsidor som skapats för visning i webbläsare. Läs mer om detta filformat [här](../https://wiki.fileformat.com/web/html).


### Mht {#Mht}
```
public static final WebFileType Mht
```


Filer med MHTML‑tillägg representerar ett webbsidesarkivformat som kan skapas av ett antal olika program. Formatet är känt som arkivformat eftersom det sparar web‑HTML‑koden och tillhörande resurser i en enda fil. Läs mer om detta filformat [här](../https://wiki.fileformat.com/web/mhtml).


### Mhtml {#Mhtml}
```
public static final WebFileType Mhtml
```


Filer med MHTML‑tillägg representerar ett webbsidesarkivformat som kan skapas av ett antal olika program. Formatet är känt som arkivformat eftersom det sparar web‑HTML‑koden och tillhörande resurser i en enda fil. Läs mer om detta filformat [här](../https://wiki.fileformat.com/web/mhtml).


### Chm {#Chm}
```
public static final WebFileType Chm
```


CHM‑filformatet representerar Microsoft HTML‑hjälpfil som består av en samling HTML‑sidor. Det tillhandahåller ett index för snabb åtkomst till ämnena och navigering till olika delar av hjälpdokumentet. Läs mer om detta filformat [här](../https://docs.fileformat.com/web/chm).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Förberedda standardalternativ för inläsning för källfiltypen


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Förberedda standardalternativ för konvertering för filtypen


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
