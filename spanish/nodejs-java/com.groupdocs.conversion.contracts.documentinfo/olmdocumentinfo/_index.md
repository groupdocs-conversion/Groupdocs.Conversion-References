---
title: "OlmDocumentInfo"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Contiene metadatos del documento olm"
type: docs
weight: 27
url: /es/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/olmdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class OlmDocumentInfo extends DocumentInfo
```

Contiene metadatos del documento olm
## Constructores

| Constructor | Descripción |
| --- | --- |
| [OlmDocumentInfo(OlmStorage storage, long size)](#OlmDocumentInfo-com.aspose.email.OlmStorage-long-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFolders()](#getFolders--) | Carpetas en el almacenamiento |
### OlmDocumentInfo(OlmStorage storage, long size) {#OlmDocumentInfo-com.aspose.email.OlmStorage-long-}
```
public OlmDocumentInfo(OlmStorage storage, long size)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| almacenamiento | com.aspose.email.OlmStorage |  |
| tamaño | long |  |

### getFolders() {#getFolders--}
```
public List<OlmFolderInfo> getFolders()
```


Carpetas en el almacenamiento

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.OlmFolderInfo>
