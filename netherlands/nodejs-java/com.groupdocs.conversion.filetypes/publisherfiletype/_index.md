---
title: "PublisherFileType"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Definieert Publisher-documenten."
type: docs
weight: 24
url: /nl/nodejs-java/com.groupdocs.conversion.filetypes/publisherfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PublisherFileType extends FileType implements Serializable
```

Definieert Publisher‑documenten. Bevat de volgende typen: [Pub](../../com.groupdocs.conversion.filetypes/publisherfiletype\#Pub), Meer informatie over lettertypeformaten [hier][].


[here]: https://wiki.fileformat.com/publisher
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PublisherFileType()](#PublisherFileType--) | Serialisatieconstructor |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Pub](#Pub) | Een PUB‑bestand is een Microsoft Publisher‑documentbestandsformaat. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PublisherFileType() {#PublisherFileType--}
```
public PublisherFileType()
```


Serialisatieconstructor

### Pub {#Pub}
```
public static final PublisherFileType Pub
```


Een PUB‑bestand is een Microsoft Publisher‑documentbestandsformaat. Het wordt gebruikt om verschillende soorten ontwerp‑lay-outdocumenten te maken, zoals nieuwsbrieven, flyers, brochures, ansichtkaarten, enz. PUB‑bestanden kunnen tekst, raster‑ en vectorafbeeldingen bevatten. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/publisher/pub/

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Voorbereide standaard laadopties voor het bronbestandstype

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
