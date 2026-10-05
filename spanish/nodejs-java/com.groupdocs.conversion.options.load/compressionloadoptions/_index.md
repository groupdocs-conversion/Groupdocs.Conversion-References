---
title: "CompressionLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Opciones para cargar documentos de compresión."
type: docs
weight: 13
url: /es/nodejs-java/com.groupdocs.conversion.options.load/compressionloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class CompressionLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Opciones para cargar documentos de compresión.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CompressionLoadOptions()](#CompressionLoadOptions--) | Inicializa una nueva instancia de  clase. |
## Métodos

| Método | Descripción |
| --- | --- |
| [isConvertOwner()](#isConvertOwner--) | El propietario no será convertido |
| [isConvertOwned()](#isConvertOwned--) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
| [getPassword()](#getPassword--) |  |
| [setPassword(String password)](#setPassword-java.lang.String-) | Establecer contraseña para cargar documento protegido. |
| [getEqualityComponents()](#getEqualityComponents--) |  |
### CompressionLoadOptions() {#CompressionLoadOptions--}
```
public CompressionLoadOptions()
```


Inicializa una nueva instancia de  clase.

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
### getDepth() {#getDepth--}
```
public int getDepth()
```


Opción para controlar cuántos niveles de profundidad se deben convertir

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

### getPassword() {#getPassword--}
```
public String getPassword()
```




**Returns:**
java.lang.String
### setPassword(String password) {#setPassword-java.lang.String-}
```
public void setPassword(String password)
```


Establecer contraseña para cargar documento protegido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| password | java.lang.String | password |

### getEqualityComponents() {#getEqualityComponents--}
```
public List<Object> getEqualityComponents()
```




**Returns:**
java.util.List<java.lang.Object>
