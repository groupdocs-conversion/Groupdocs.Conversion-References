---
title: "PresentationConvertOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Décrit les options de conversion vers le type de fichier Presentation."
type: docs
weight: 33
url: /fr/java/com.groupdocs.conversion.options.convert/presentationconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class PresentationConvertOptions extends CommonConvertOptions<PresentationFileType> implements Serializable
```

Décrit les options de conversion vers le type de fichier Presentation.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PresentationConvertOptions()](#PresentationConvertOptions--) | Initialise une nouvelle instance de la classe [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPassword()](#getPassword--) | Définissez cette propriété si vous souhaitez protéger le document converti avec un mot de passe. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Définissez cette propriété si vous souhaitez protéger le document converti avec un mot de passe. |
|
|  | [getZoom()](#getZoom--) | Spécifie le niveau de zoom en pourcentage. |
|
|  | [setZoom(int value)](#setZoom-int-) | Spécifie le niveau de zoom en pourcentage. |
|
### PresentationConvertOptions() {#PresentationConvertOptions--}
```
public PresentationConvertOptions()
```


Initialise une nouvelle instance de la classe [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions).


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Définissez cette propriété si vous souhaitez protéger le document converti avec un mot de passe.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Définissez cette propriété si vous souhaitez protéger le document converti avec un mot de passe.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Spécifie le niveau de zoom en pourcentage. La valeur par défaut est 100.
Le zoom par défaut est pris en charge jusqu'à Microsoft Powerpoint 2010. À partir de Microsoft Powerpoint 2013, le zoom par défaut n'est plus défini sur le document ; il semble plutôt utiliser le facteur de zoom du dernier document ouvert.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Spécifie le niveau de zoom en pourcentage. La valeur par défaut est 100.
Le zoom par défaut est pris en charge jusqu'à Microsoft Powerpoint 2010. À partir de Microsoft Powerpoint 2013, le zoom par défaut n'est plus défini sur le document ; il semble plutôt utiliser le facteur de zoom du dernier document ouvert.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

