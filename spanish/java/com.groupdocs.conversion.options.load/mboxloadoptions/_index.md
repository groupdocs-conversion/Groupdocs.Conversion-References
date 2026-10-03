---
title: "MboxLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Opciones para cargar documentos de Mbox."
type: docs
weight: 23
url: /es/java/com.groupdocs.conversion.options.load/mboxloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class MboxLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Opciones para cargar documentos de Mbox.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [MboxLoadOptions()](#MboxLoadOptions--) | Inicializa una nueva instancia de la clase. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isConvertOwner()](#isConvertOwner--) | El propietario no será convertido |
|
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
|  | [getDepth()](#getDepth--) | {@inheritDoc} Predeterminado: 3 |
|
|  | [setDepth(int depth)](#setDepth-int-) | {@inheritDoc} |
|
|  | [getEqualityComponents()](#getEqualityComponents--) | {@inheritDoc} |
|
### MboxLoadOptions() {#MboxLoadOptions--}
```
public MboxLoadOptions()
```


Inicializa una nueva instancia de la clase.


### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


El propietario no será convertido


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


Opción para controlar cuántos niveles de profundidad se deben convertir Predeterminado: 3


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

### getEqualityComponents() {#getEqualityComponents--}
```
public List<Object> getEqualityComponents()
```




**Returns:**
java.util.List<java.lang.Object>
