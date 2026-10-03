---
title: "PossibleConversions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Stelt een mapping voor van welke conversieparen worden ondersteund voor een specifiek bronbestandformaat."
type: docs
weight: 13
url: /nl/java/com.groupdocs.conversion.contracts/possibleconversions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public final class PossibleConversions extends ValueObject
```

Stelt een mapping voor van welke conversieparen worden ondersteund voor een specifiek bronbestandformaat.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PossibleConversions(FileType source)](#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-) | Maakt een mogelijke conversielijst voor het opgegeven bron‑bestandformaat |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
| [NULL](#NULL) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getLoadOptions()](#getLoadOptions--) | Vooraf gedefinieerde laadopties die kunnen worden gebruikt om van het huidige type te converteren |
|
|  | [getAll()](#getAll--) | Alle doel‑bestandstypen en primaire/secundaire vlag |
|
|  | [getTargetConversion(FileType target)](#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-) | Retourneert doelconversie voor het opgegeven doel‑bestandstype |
|
| [getTargetConversion(String extension)](#getTargetConversion-java.lang.String-) |  |
|  | [getPrimary()](#getPrimary--) | Primaire doel‑bestandstypen |
|
|  | [getSecondary()](#getSecondary--) | Secundaire doel‑bestandstypen |
|
|  | [add(ConversionPair pair)](#add-com.groupdocs.conversion.contracts.ConversionPair-) | Voeg conversie‑paar toe |
|
|  | [forTarget(FileType target)](#forTarget-com.groupdocs.conversion.filetypes.FileType-) | Zoek conversie‑paar in de huidige lijst voor het doel‑bestandstype |
|
|  | [getSource()](#getSource--) | Bron‑bestandformaten |
|
### PossibleConversions(FileType source) {#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-}
```
public PossibleConversions(FileType source)
```


Maakt een mogelijke conversielijst voor het opgegeven bron‑bestandformaat


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | bron‑bestandstype |
|

### NULL {#NULL}
```
public static final PossibleConversions NULL
```


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Vooraf gedefinieerde laadopties die kunnen worden gebruikt om van het huidige type te converteren


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - load options

### getAll() {#getAll--}
```
public Iterable<TargetConversion> getAll()
```


Alle doel‑bestandstypen en primaire/secundaire vlag


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.contracts.TargetConversion> - Iterable van [TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)

### getTargetConversion(FileType target) {#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-}
```
public TargetConversion getTargetConversion(FileType target)
```


Retourneert doelconversie voor het opgegeven doel‑bestandstype


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | doelbestandstype |
|

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion) - conversions

### getTargetConversion(String extension) {#getTargetConversion-java.lang.String-}
```
public TargetConversion getTargetConversion(String extension)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| extensie | java.lang.String |  |

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)
### getPrimary() {#getPrimary--}
```
public Iterable<FileType> getPrimary()
```


Primaire doel‑bestandstypen


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - primaire doelbestandstypen

### getSecondary() {#getSecondary--}
```
public Iterable<FileType> getSecondary()
```


Secundaire doel‑bestandstypen


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - secundaire doelbestandstypen

### add(ConversionPair pair) {#add-com.groupdocs.conversion.contracts.ConversionPair-}
```
public void add(ConversionPair pair)
```


Voeg conversie‑paar toe


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | pair | [ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) | conversie‑paar |
|

### forTarget(FileType target) {#forTarget-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionPair forTarget(FileType target)
```


Zoek conversie‑paar in de huidige lijst voor het doel‑bestandstype


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | doelbestandstype |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - conversion pair

### getSource() {#getSource--}
```
public FileType getSource()
```


Bron‑bestandformaten


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file formats

