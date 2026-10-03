---
title: "TxtLoadOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options de chargement des documents Txt."
type: docs
weight: 34
url: /fr/java/com.groupdocs.conversion.options.load/txtloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class TxtLoadOptions extends LoadOptions implements Serializable
```

Options de chargement des documents Txt.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [TxtLoadOptions()](#TxtLoadOptions--) | Initialise une nouvelle instance de la classe [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDetectNumberingWithWhitespaces()](#getDetectNumberingWithWhitespaces--) | Permet de spécifier comment les éléments de listes numérotées sont reconnus lors de la conversion d'un document texte brut. |
|
|  | [setDetectNumberingWithWhitespaces(boolean value)](#setDetectNumberingWithWhitespaces-boolean-) | Permet de spécifier comment les éléments de listes numérotées sont reconnus lors de la conversion d'un document texte brut. |
|
|  | [getTrailingSpacesOptions()](#getTrailingSpacesOptions--) | Obtient ou définit l'option préférée de gestion des espaces de fin. |
|
|  | [setTrailingSpacesOptions(TxtTrailingSpacesOptions value)](#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-) | Obtient ou définit l'option préférée de gestion des espaces de fin. |
|
|  | [getLeadingSpacesOptions()](#getLeadingSpacesOptions--) | Obtient ou définit l'option préférée de gestion des espaces de début. |
|
|  | [setLeadingSpacesOptions(TxtLeadingSpacesOptions value)](#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-) | Obtient ou définit l'option préférée de gestion des espaces de début. |
|
|  | [getEncoding()](#getEncoding--) | Obtient ou définit l'encodage qui sera utilisé lors du chargement du document Txt. |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Obtient ou définit l'encodage qui sera utilisé lors du chargement du document Txt. |
|
### TxtLoadOptions() {#TxtLoadOptions--}
```
public TxtLoadOptions()
```


Initialise une nouvelle instance de la classe [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions).


### getFormat() {#getFormat--}
```
public WordProcessingFileType getFormat()
```


Type de fichier du document d’entrée.


**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDetectNumberingWithWhitespaces() {#getDetectNumberingWithWhitespaces--}
```
public final boolean getDetectNumberingWithWhitespaces()
```


Permet de spécifier comment les éléments de listes numérotées sont reconnus lors de la conversion d'un document texte brut.
La valeur par défaut est vraie.

<br />

*** ** * ** ***

Si cette option est définie sur false, l'algorithme de reconnaissance des listes détecte les paragraphes de listes, lorsque les numéros de liste se terminent par
soit un point, un crochet droit ou des symboles de puce (comme "\\u2022", "*", "-" ou "o").

Si cette option est définie sur true, les espaces blancs sont également utilisés comme délimiteurs de numéros de liste :
L'algorithme de reconnaissance des listes pour la numérotation de style arabe (1., 1.1.2.) utilise à la fois les espaces blancs et le symbole point (\".\").

<br />



**Returns:**
booléen
### setDetectNumberingWithWhitespaces(boolean value) {#setDetectNumberingWithWhitespaces-boolean-}
```
public final void setDetectNumberingWithWhitespaces(boolean value)
```


Permet de spécifier comment les éléments de listes numérotées sont reconnus lors de la conversion d'un document texte brut.
La valeur par défaut est vraie.

<br />

*** ** * ** ***

Si cette option est définie sur false, l'algorithme de reconnaissance des listes détecte les paragraphes de listes, lorsque les numéros de liste se terminent par
soit un point, un crochet droit ou des symboles de puce (comme "\\u2022", "*", "-" ou "o").

Si cette option est définie sur true, les espaces blancs sont également utilisés comme délimiteurs de numéros de liste :
L'algorithme de reconnaissance des listes pour la numérotation de style arabe (1., 1.1.2.) utilise à la fois les espaces blancs et le symbole point (\".\").

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getTrailingSpacesOptions() {#getTrailingSpacesOptions--}
```
public final TxtTrailingSpacesOptions getTrailingSpacesOptions()
```


Obtient ou définit l'option préférée de gestion des espaces de fin.
La valeur par défaut est [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim).


**Returns:**
[TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions)
### setTrailingSpacesOptions(TxtTrailingSpacesOptions value) {#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-}
```
public final void setTrailingSpacesOptions(TxtTrailingSpacesOptions value)
```


Obtient ou définit l'option préférée de gestion des espaces de fin.
La valeur par défaut est [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions) |  |

### getLeadingSpacesOptions() {#getLeadingSpacesOptions--}
```
public final TxtLeadingSpacesOptions getLeadingSpacesOptions()
```


Obtient ou définit l'option préférée de gestion des espaces de début.
La valeur par défaut est [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent).


**Returns:**
[TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions)
### setLeadingSpacesOptions(TxtLeadingSpacesOptions value) {#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-}
```
public final void setLeadingSpacesOptions(TxtLeadingSpacesOptions value)
```


Obtient ou définit l'option préférée de gestion des espaces de début.
La valeur par défaut est [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions) |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Obtient ou définit l'encodage qui sera utilisé lors du chargement du document Txt. Peut être null. La valeur par défaut est null.


**Returns:**
java.nio.charset.Charset
### getEncodingInternal() {#getEncodingInternal--}
```
public System.Text.Encoding getEncodingInternal()
```




**Returns:**
com.aspose.ms.System.Text.Encoding
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Obtient ou définit l'encodage qui sera utilisé lors du chargement du document Txt. Peut être null. La valeur par défaut est null.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.nio.charset.Charset |  |

