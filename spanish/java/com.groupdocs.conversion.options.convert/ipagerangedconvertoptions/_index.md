---
title: "IPageRangedConvertOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Representa las opciones de conversión que admiten la conversión de una lista específica de páginas"
type: docs
weight: 52
url: /es/java/com.groupdocs.conversion.options.convert/ipagerangedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageRangedConvertOptions extends IConvertOptions
```

Representa las opciones de conversión que admiten la conversión de una lista específica de páginas

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPages()](#getPages--) | Obtiene la lista de índices de página a convertir. |
|
|  | [setPages(List<Integer> pages)](#setPages-java.util.List-java.lang.Integer--) | Establece la lista de índices de página a convertir. |
|
### getPages() {#getPages--}
```
public abstract List<Integer> getPages()
```


Obtiene la lista de índices de página que se convertirán. Debe especificarse para convertir páginas específicas.


**Returns:**
java.util.List<java.lang.Integer> - La lista de índices de página a convertir. Debe especificarse para convertir páginas específicas.

### setPages(List<Integer> pages) {#setPages-java.util.List-java.lang.Integer--}
```
public abstract void setPages(List<Integer> pages)
```


Establece la lista de índices de página que se convertirán. Debe especificarse para convertir páginas específicas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | páginas | java.util.List<java.lang.Integer> | La lista de índices de página a convertir. Debe especificarse para convertir páginas específicas. |
|

