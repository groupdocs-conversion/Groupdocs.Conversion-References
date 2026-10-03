---
title: "WebDateityp"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Definiert Webdokumente."
type: docs
weight: 27
url: /de/java/com.groupdocs.conversion.filetypes/webfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WebFileType extends FileType implements Serializable
```

Definiert Webdokumente.
Enthält die folgenden Typen:
[Xml](../../com.groupdocs.conversion.filetypes/webfiletype#Xml),
[Json](../../com.groupdocs.conversion.filetypes/webfiletype#Json),
[Html](../../com.groupdocs.conversion.filetypes/webfiletype#Html),
[Htm](../../com.groupdocs.conversion.filetypes/webfiletype#Htm),
[Mht](../../com.groupdocs.conversion.filetypes/webfiletype#Mht),
[Mhtml](../../com.groupdocs.conversion.filetypes/webfiletype#Mhtml),
[Chm](../../com.groupdocs.conversion.filetypes/webfiletype#Chm),
Erfahren Sie mehr über Web‑Formate [hier](../https://wiki.fileformat.com/web).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WebFileType()](#WebFileType--) | Serialisierungskonstruktor |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Xml](#Xml) | XML steht für Extensible Markup Language, das ähnlich wie HTML ist, sich jedoch dadurch unterscheidet, dass es Tags zur Definition von Objekten verwendet. |
|
|  | [Json](#Json) | JSON (JavaScript Object Notation) ist ein offener Standard-Dateiformat zum Austausch von Daten, das menschenlesbaren Text verwendet, um Daten zu speichern und zu übertragen. |
|
|  | [Html](#Html) | HTML (Hyper Text Markup Language) ist die Dateierweiterung für Webseiten, die zur Anzeige in Browsern erstellt wurden. |
|
|  | [Htm](#Htm) | HTM (Hyper Text Markup Language) ist die Dateierweiterung für Webseiten, die zur Anzeige in Browsern erstellt wurden. |
|
|  | [Mht](#Mht) | Dateien mit der MHTML-Erweiterung stellen ein Webseitensicherungsformat dar, das von einer Reihe verschiedener Anwendungen erstellt werden kann. |
|
|  | [Mhtml](#Mhtml) | Dateien mit der MHTML-Erweiterung stellen ein Webseitensicherungsformat dar, das von einer Reihe verschiedener Anwendungen erstellt werden kann. |
|
|  | [Chm](#Chm) | Das CHM-Dateiformat stellt die Microsoft HTML-Hilfedatei dar, die aus einer Sammlung von HTML-Seiten besteht. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WebFileType() {#WebFileType--}
```
public WebFileType()
```


Serialisierungskonstruktor


### Xml {#Xml}
```
public static final WebFileType Xml
```


XML steht für Extensible Markup Language, das ähnlich wie HTML ist, sich jedoch dadurch unterscheidet, dass es Tags zur Definition von Objekten verwendet. Weitere Informationen zu diesem Dateiformat finden Sie [hier](../https://wiki.fileformat.com/web/xml).


### Json {#Json}
```
public static final WebFileType Json
```


JSON (JavaScript Object Notation) ist ein offener Standard-Dateiformat zum Austausch von Daten, das menschenlesbaren Text verwendet, um Daten zu speichern und zu übertragen. Weitere Informationen zu diesem Dateiformat finden Sie [hier](../https://docs.fileformat.com/web/json).


### Html {#Html}
```
public static final WebFileType Html
```


HTML (Hyper Text Markup Language) ist die Dateierweiterung für Webseiten, die zur Anzeige in Browsern erstellt wurden. Weitere Informationen zu diesem Dateiformat finden Sie [hier](../https://wiki.fileformat.com/web/html).


### Htm {#Htm}
```
public static final WebFileType Htm
```


HTM (Hyper Text Markup Language) ist die Dateierweiterung für Webseiten, die zur Anzeige in Browsern erstellt wurden. Weitere Informationen zu diesem Dateiformat finden Sie [hier](../https://wiki.fileformat.com/web/html).


### Mht {#Mht}
```
public static final WebFileType Mht
```


Dateien mit der MHTML-Erweiterung stellen ein Webseitensicherungsformat dar, das von einer Reihe verschiedener Anwendungen erstellt werden kann. Das Format ist als Archivformat bekannt, weil es den Web‑HTML‑Code und zugehörige Ressourcen in einer einzigen Datei speichert. Weitere Informationen zu diesem Dateiformat finden Sie [hier](../https://wiki.fileformat.com/web/mhtml).


### Mhtml {#Mhtml}
```
public static final WebFileType Mhtml
```


Dateien mit der MHTML-Erweiterung stellen ein Webseitensicherungsformat dar, das von einer Reihe verschiedener Anwendungen erstellt werden kann. Das Format ist als Archivformat bekannt, weil es den Web‑HTML‑Code und zugehörige Ressourcen in einer einzigen Datei speichert. Weitere Informationen zu diesem Dateiformat finden Sie [hier](../https://wiki.fileformat.com/web/mhtml).


### Chm {#Chm}
```
public static final WebFileType Chm
```


Das CHM-Dateiformat stellt die Microsoft HTML-Hilfedatei dar, die aus einer Sammlung von HTML-Seiten besteht. Es bietet einen Index für den schnellen Zugriff auf die Themen und die Navigation zu verschiedenen Teilen des Hilfedokuments. Weitere Informationen zu diesem Dateiformat finden Sie [hier](../https://docs.fileformat.com/web/chm).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Standard‑Ladeoptionen für den Quelldateityp vorbereitet


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Standard‑Konvertierungsoptionen für den Dateityp vorbereitet


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
