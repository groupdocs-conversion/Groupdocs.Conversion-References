---
title: "OlmLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Opciones para cargar documentos Olm."
type: docs
weight: 29
url: /es/nodejs-java/com.groupdocs.conversion.options.load/olmloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions), java.lang.Cloneable, java.io.Serializable
```
public final class OlmLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions, Cloneable, Serializable
```

Opciones para cargar documentos Olm.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [OlmLoadOptions()](#OlmLoadOptions--) | Inicializa una nueva instancia de la clase [OlmLoadOptions](../../com.groupdocs.conversion.options.load/olmloadoptions). |
## Campos

| Campo | Descripción |
| --- | --- |
| [folder](#folder) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [memberwiseClone()](#memberwiseClone--) |  |
| [isConvertOwner()](#isConvertOwner--) | El propietario no será convertido |
| [isConvertOwned()](#isConvertOwned--) | \\{@inheritDoc\\} |
| [getFolder()](#getFolder--) | Carpeta que se procesará. El valor predeterminado es Bandeja de entrada |
| [setFolder(String folder)](#setFolder-java.lang.String-) |  |
| [getDepth()](#getDepth--) | \{@inheritDoc\} Predeterminado: 3 |
| [setDepth(int depth)](#setDepth-int-) |  |
| [deepClone()](#deepClone--) | Clona la instancia actual. |
### OlmLoadOptions() {#OlmLoadOptions--}
```
public OlmLoadOptions()
```


Inicializa una nueva instancia de la clase [OlmLoadOptions](../../com.groupdocs.conversion.options.load/olmloadoptions).

### folder {#folder}
```
public String folder
```


### memberwiseClone() {#memberwiseClone--}
```
public Object memberwiseClone()
```




**Returns:**
java.lang.Object
### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


El propietario no será convertido

**Returns:**
boolean
### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Opción para controlar si los documentos propiedad en el contenedor de documentos deben convertirse

**Returns:**
boolean
### getFolder() {#getFolder--}
```
public String getFolder()
```


Carpeta que se procesará. El valor predeterminado es Bandeja de entrada

**Returns:**
java.lang.String
### setFolder(String folder) {#setFolder-java.lang.String-}
```
public void setFolder(String folder)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| carpeta | java.lang.String |  |

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
| profundidad | int |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clona la instancia actual.

**Returns:**
java.lang.Object
