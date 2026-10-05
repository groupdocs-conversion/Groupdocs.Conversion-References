---
title: "PossibleConversions"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Stelt een mapping voor van welke conversieparen worden ondersteund voor een specifiek bronbestandsformaat"
type: docs
weight: 13
url: /nl/nodejs-java/com.groupdocs.conversion.contracts/possibleconversions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public final class PossibleConversions extends ValueObject
```

Stelt een mapping voor van welke conversieparen worden ondersteund voor een specifiek bronbestandsformaat
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PossibleConversions(FileType source)](#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-) | Maakt een mogelijke conversielijst aan voor het opgegeven bronbestandformaat |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [NULL](#NULL) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) | Vooraf gedefinieerde laadopties die kunnen worden gebruikt om te converteren van het huidige type |
| [getAll()](#getAll--) | Alle doelbestandstypen en primaire/secundaire vlag |
| [getTargetConversion(FileType target)](#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-) | Retourneert de doelconversie voor het opgegeven doelbestandstype |
| [getTargetConversion(String extension)](#getTargetConversion-java.lang.String-) |  |
| [getPrimary()](#getPrimary--) | Primaire doelbestandstypen |
| [getSecondary()](#getSecondary--) | Secundaire doelbestandstypen |
| [add(ConversionPair pair)](#add-com.groupdocs.conversion.contracts.ConversionPair-) | Conversie-paar toevoegen |
| [forTarget(FileType target)](#forTarget-com.groupdocs.conversion.filetypes.FileType-) | Zoek conversie-paar in huidige lijst voor doelfiletype |
| [getSource()](#getSource--) | Bronbestandsformaten |
### PossibleConversions(FileType source) {#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-}
```
public PossibleConversions(FileType source)
```


Maakt een mogelijke conversielijst aan voor het opgegeven bronbestandformaat

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | bronbestandstype |

### NULL {#NULL}
```
public static final PossibleConversions NULL
```


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Vooraf gedefinieerde laadopties die kunnen worden gebruikt om te converteren van het huidige type

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - load options
### getAll() {#getAll--}
```
public Iterable<TargetConversion> getAll()
```


Alle doelbestandstypen en primaire/secundaire vlag

**Returns:**
java.lang.Iterable<com.groupdocs.conversion.contracts.TargetConversion> - Iterabel van [TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)
### getTargetConversion(FileType target) {#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-}
```
public TargetConversion getTargetConversion(FileType target)
```


Retourneert de doelconversie voor het opgegeven doelbestandstype

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | doelfiletype |

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


Primaire doelbestandstypen

**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - primaire doelfiletypes
### getSecondary() {#getSecondary--}
```
public Iterable<FileType> getSecondary()
```


Secundaire doelbestandstypen

**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - secundaire doelfiletypes
### add(ConversionPair pair) {#add-com.groupdocs.conversion.contracts.ConversionPair-}
```
public void add(ConversionPair pair)
```


Conversie-paar toevoegen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pair | [ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) | conversie-paar |

### forTarget(FileType target) {#forTarget-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionPair forTarget(FileType target)
```


Zoek conversie-paar in huidige lijst voor doelfiletype

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | doelfiletype |

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - conversion pair
### getSource() {#getSource--}
```
public FileType getSource()
```


Bronbestandsformaten

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file formats
