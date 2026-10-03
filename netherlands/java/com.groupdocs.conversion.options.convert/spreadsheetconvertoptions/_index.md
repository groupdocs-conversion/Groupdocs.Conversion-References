---
title: "SpreadsheetConvertOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Opties voor conversie naar spreadsheet‑bestandstype."
type: docs
weight: 40
url: /nl/java/com.groupdocs.conversion.options.convert/spreadsheetconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class SpreadsheetConvertOptions extends CommonConvertOptions<SpreadsheetFileType> implements Serializable
```

Opties voor conversie naar spreadsheet‑bestandstype.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [SpreadsheetConvertOptions()](#SpreadsheetConvertOptions--) | Initialiseert een nieuw exemplaar van de klasse [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions). |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPassword()](#getPassword--) | Stel deze eigenschap in als u het geconverteerde document met een wachtwoord wilt beveiligen. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Stel deze eigenschap in als u het geconverteerde document met een wachtwoord wilt beveiligen. |
|
|  | [getZoom()](#getZoom--) | Specificeert het zoomniveau in procenten. |
|
|  | [setZoom(int value)](#setZoom-int-) | Specificeert het zoomniveau in procenten. |
|
|  | [getSeparator()](#getSeparator--) | Specificeert het scheidingsteken dat moet worden gebruikt bij het converteren naar gescheiden formaten. |
|
| [setSeparator(char separator)](#setSeparator-char-) |  |
| [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) |  |
### SpreadsheetConvertOptions() {#SpreadsheetConvertOptions--}
```
public SpreadsheetConvertOptions()
```


Initialiseert een nieuw exemplaar van de klasse [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions).


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Stel deze eigenschap in als u het geconverteerde document met een wachtwoord wilt beveiligen.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Stel deze eigenschap in als u het geconverteerde document met een wachtwoord wilt beveiligen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Specificeert het zoomniveau in procenten. Standaard is 100.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Specificeert het zoomniveau in procenten. Standaard is 100.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getSeparator() {#getSeparator--}
```
public char getSeparator()
```


Specificeert het scheidingsteken dat moet worden gebruikt bij het converteren naar gescheiden formaten.


**Returns:**
char
### setSeparator(char separator) {#setSeparator-char-}
```
public void setSeparator(char separator)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scheidingsteken | char |  |

### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


Het gewenste bestandstype waarnaar het invoerdocument moet worden geconverteerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

