---
title: "PresentationConvertOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Beschreibt Optionen für die Konvertierung zum Präsentationsdateityp."
type: docs
weight: 33
url: /de/java/com.groupdocs.conversion.options.convert/presentationconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class PresentationConvertOptions extends CommonConvertOptions<PresentationFileType> implements Serializable
```

Beschreibt Optionen für die Konvertierung zum Präsentationsdateityp.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PresentationConvertOptions()](#PresentationConvertOptions--) | Initialisiert eine neue Instanz der Klasse [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions). |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPassword()](#getPassword--) | Setzen Sie diese Eigenschaft, wenn Sie das konvertierte Dokument mit einem Passwort schützen möchten. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Setzen Sie diese Eigenschaft, wenn Sie das konvertierte Dokument mit einem Passwort schützen möchten. |
|
|  | [getZoom()](#getZoom--) | Gibt den Zoom‑Wert in Prozent an. |
|
|  | [setZoom(int value)](#setZoom-int-) | Gibt den Zoom‑Wert in Prozent an. |
|
### PresentationConvertOptions() {#PresentationConvertOptions--}
```
public PresentationConvertOptions()
```


Initialisiert eine neue Instanz der Klasse [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions).


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Setzen Sie diese Eigenschaft, wenn Sie das konvertierte Dokument mit einem Passwort schützen möchten.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Setzen Sie diese Eigenschaft, wenn Sie das konvertierte Dokument mit einem Passwort schützen möchten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Gibt den Zoom‑Wert in Prozent an. Standard ist 100.
Standard‑Zoom wird bis Microsoft PowerPoint 2010 unterstützt. Ab Microsoft PowerPoint 2013 wird der Standard‑Zoom nicht mehr auf das Dokument gesetzt, stattdessen scheint der Zoom‑Faktor des zuletzt geöffneten Dokuments verwendet zu werden.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Gibt den Zoom‑Wert in Prozent an. Standard ist 100.
Standard‑Zoom wird bis Microsoft PowerPoint 2010 unterstützt. Ab Microsoft PowerPoint 2013 wird der Standard‑Zoom nicht mehr auf das Dokument gesetzt, stattdessen scheint der Zoom‑Faktor des zuletzt geöffneten Dokuments verwendet zu werden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

