---
title: "IPageRangedConvertOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Représente les options de conversion qui prennent en charge la conversion d'une liste spécifique de pages."
type: docs
weight: 52
url: /fr/java/com.groupdocs.conversion.options.convert/ipagerangedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageRangedConvertOptions extends IConvertOptions
```

Représente les options de conversion qui prennent en charge la conversion d'une liste spécifique de pages.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPages()](#getPages--) | Obtient la liste des index de pages à convertir. |
|
|  | [setPages(List<Integer> pages)](#setPages-java.util.List-java.lang.Integer--) | Définit la liste des index de pages à convertir. |
|
### getPages() {#getPages--}
```
public abstract List<Integer> getPages()
```


Obtient la liste des index de pages à convertir. Doit être spécifié pour convertir des pages spécifiques.


**Returns:**
java.util.List<java.lang.Integer> - La liste des index de pages à convertir. Doit être spécifiée pour convertir des pages spécifiques.

### setPages(List<Integer> pages) {#setPages-java.util.List-java.lang.Integer--}
```
public abstract void setPages(List<Integer> pages)
```


Définit la liste des index de pages à convertir. Doit être spécifié pour convertir des pages spécifiques.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | pages | java.util.List<java.lang.Integer> | La liste des index de pages à convertir. Doit être spécifiée pour convertir des pages spécifiques. |
|

