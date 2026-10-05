---
title: "WebFileType"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Definieert webdocumenten."
type: docs
weight: 27
url: /nl/nodejs-java/com.groupdocs.conversion.filetypes/webfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WebFileType extends FileType implements Serializable
```

Definieert webdocumenten. Bevat de volgende typen: [Xml](../../com.groupdocs.conversion.filetypes/webfiletype\#Xml), [Json](../../com.groupdocs.conversion.filetypes/webfiletype\#Json), [Html](../../com.groupdocs.conversion.filetypes/webfiletype\#Html), [Htm](../../com.groupdocs.conversion.filetypes/webfiletype\#Htm), [Mht](../../com.groupdocs.conversion.filetypes/webfiletype\#Mht), [Mhtml](../../com.groupdocs.conversion.filetypes/webfiletype\#Mhtml), [Chm](../../com.groupdocs.conversion.filetypes/webfiletype\#Chm), Meer informatie over webformaten [here][].


[here]: https://wiki.fileformat.com/web
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [WebFileType()](#WebFileType--) | Serialisatieconstructor |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Xml](#Xml) | XML staat voor Extensible Markup Language, die vergelijkbaar is met HTML maar verschilt in het gebruik van tags voor het definiëren van objecten. |
| [Json](#Json) | JSON (JavaScript Object Notation) is een open standaard bestandsformaat voor het delen van gegevens dat menselijk leesbare tekst gebruikt om data op te slaan en te verzenden. |
| [Html](#Html) | HTML (Hyper Text Markup Language) is de extensie voor webpagina’s die zijn gemaakt voor weergave in browsers. |
| [Htm](#Htm) | HTM (Hyper Text Markup Language) is de extensie voor webpagina’s die zijn gemaakt voor weergave in browsers. |
| [Mht](#Mht) | Bestanden met de MHTML‑extensie vertegenwoordigen een webpagina‑archiefformaat dat door verschillende toepassingen kan worden aangemaakt. |
| [Mhtml](#Mhtml) | Bestanden met de MHTML‑extensie vertegenwoordigen een webpagina‑archiefformaat dat door verschillende toepassingen kan worden aangemaakt. |
| [Chm](#Chm) | Het CHM‑bestandsformaat vertegenwoordigt een Microsoft HTML‑helpbestand dat bestaat uit een verzameling HTML‑pagina’s. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WebFileType() {#WebFileType--}
```
public WebFileType()
```


Serialisatieconstructor

### Xml {#Xml}
```
public static final WebFileType Xml
```


XML staat voor Extensible Markup Language, die vergelijkbaar is met HTML maar verschilt in het gebruik van tags voor het definiëren van objecten. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/web/xml

### Json {#Json}
```
public static final WebFileType Json
```


JSON (JavaScript Object Notation) is een open standaard bestandsformaat voor het delen van gegevens dat menselijk leesbare tekst gebruikt om data op te slaan en te verzenden. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/web/json

### Html {#Html}
```
public static final WebFileType Html
```


HTML (Hyper Text Markup Language) is de extensie voor webpagina’s die zijn gemaakt voor weergave in browsers. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/web/html

### Htm {#Htm}
```
public static final WebFileType Htm
```


HTM (Hyper Text Markup Language) is de extensie voor webpagina’s die zijn gemaakt voor weergave in browsers. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/web/html

### Mht {#Mht}
```
public static final WebFileType Mht
```


Bestanden met de MHTML‑extensie vertegenwoordigen een webpagina‑archiefformaat dat door verschillende toepassingen kan worden aangemaakt. Het formaat staat bekend als archiefformaat omdat het de web‑HTML‑code en bijbehorende bronnen in één enkel bestand opslaat. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/web/mhtml

### Mhtml {#Mhtml}
```
public static final WebFileType Mhtml
```


Bestanden met de MHTML‑extensie vertegenwoordigen een webpagina‑archiefformaat dat door verschillende toepassingen kan worden aangemaakt. Het formaat staat bekend als archiefformaat omdat het de web‑HTML‑code en bijbehorende bronnen in één enkel bestand opslaat. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/web/mhtml

### Chm {#Chm}
```
public static final WebFileType Chm
```


Het CHM-bestandsformaat vertegenwoordigt het Microsoft HTML-helpbestand dat bestaat uit een verzameling HTML-pagina's. Het biedt een index voor snelle toegang tot de onderwerpen en navigatie naar verschillende delen van het helpdocument. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/web/chm

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Voorbereide standaard laadopties voor het bronbestandstype

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Voorbereide standaard conversie‑opties voor het bestandstype

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
