---
title: "NsfLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Opciones para cargar documentos de Nsf."
type: docs
weight: 25
url: /es/java/com.groupdocs.conversion.options.load/nsfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class NsfLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Opciones para cargar documentos de Nsf.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [NsfLoadOptions()](#NsfLoadOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [isConvertOwner()](#isConvertOwner--) |  |
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### NsfLoadOptions() {#NsfLoadOptions--}
```
public NsfLoadOptions()
```


### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Obtiene la opción para controlar si el contenedor de los documentos debe convertirse


**Returns:**
booleano
### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Opción para controlar si los documentos propios en el contenedor de documentos deben convertirse


**Returns:**
booleano
### getDepth() {#getDepth--}
```
public int getDepth()
```


Opción para controlar cuántos niveles de profundidad se deben usar para realizar la conversión


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| depth | int |  |

