---
title: "PersonalStorageLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Opciones para cargar documentos de almacenamiento personal."
type: docs
weight: 28
url: /es/java/com.groupdocs.conversion.options.load/personalstorageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class PersonalStorageLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Opciones para cargar documentos de almacenamiento personal.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PersonalStorageLoadOptions()](#PersonalStorageLoadOptions--) | Inicializa una nueva instancia de la clase. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFolder()](#getFolder--) | Carpeta que se procesará. El valor predeterminado es Inbox. |
|
|  | [setFolder(String folder)](#setFolder-java.lang.String-) | Establecer la carpeta que se procesará |
|
|  | [isConvertOwner()](#isConvertOwner--) | {@inheritDoc} El propietario no será convertido |
|
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
|  | [getDepth()](#getDepth--) | {@inheritDoc} |
|
|  | [setDepth(int depth)](#setDepth-int-) | {@inheritDoc} |
|
### PersonalStorageLoadOptions() {#PersonalStorageLoadOptions--}
```
public PersonalStorageLoadOptions()
```


Inicializa una nueva instancia de la clase.


### getFolder() {#getFolder--}
```
public String getFolder()
```


Carpeta que se procesará. El valor predeterminado es Inbox.


**Returns:**
java.lang.String - Carpeta que se procesará

### setFolder(String folder) {#setFolder-java.lang.String-}
```
public void setFolder(String folder)
```


Establecer la carpeta que se procesará


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | carpeta | java.lang.String | carpeta |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Obtiene la opción para controlar si el contenedor de documentos debe ser convertido. El propietario no será convertido


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

