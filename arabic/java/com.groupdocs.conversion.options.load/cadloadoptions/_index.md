---
title: "CadLoadOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات تحميل مستندات CAD."
type: docs
weight: 12
url: /ar/java/com.groupdocs.conversion.options.load/cadloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadLoadOptions extends LoadOptions implements Serializable
```

خيارات تحميل مستندات CAD.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [CadLoadOptions()](#CadLoadOptions--) | ينشئ نسخة جديدة من الفئة [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions). |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getLayoutNames()](#getLayoutNames--) | يحدد أي تخطيطات CAD سيتم تحويلها |
|
|  | [setLayoutNames(String[] value)](#setLayoutNames-java.lang.String---) | يحدد أي تخطيطات CAD سيتم تحويلها |
|
|  | [getDrawType()](#getDrawType--) | يحصل على نوع الرسم. |
|
|  | [setDrawType(CadDrawTypeMode drawType)](#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-) | يضبط نوع الرسم. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | يحصل على لون الخلفية. |
|
|  | [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | يضبط لون الخلفية. |
|
| [getFontDirectories()](#getFontDirectories--) |  |
| [setFontDirectories(List<String> fontDirectories)](#setFontDirectories-java.util.List-java.lang.String--) |  |
|  | [getCtbSources()](#getCtbSources--) | يحصل على مصادر CTB. |
|
|  | [setCtbSources(Map<String,InputStream> ctbSources)](#setCtbSources-java.util.Map-java.lang.String-java.io.InputStream--) | يضبط مصادر CTB. |
|
|  | [getDrawColor()](#getDrawColor--) | يحصل على لون المقدمة. |
|
|  | [setDrawColor(System.Drawing.Color drawColor)](#setDrawColor-com.aspose.ms.System.Drawing.Color-) | يضبط لون المقدمة. |
|
### CadLoadOptions() {#CadLoadOptions--}
```
public CadLoadOptions()
```


ينشئ نسخة جديدة من الفئة [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions).


### getFormat() {#getFormat--}
```
public CadFileType getFormat()
```


نوع ملف المستند الإدخالي


**Returns:**
[CadFileType](../../com.groupdocs.conversion.filetypes/cadfiletype)
### getLayoutNames() {#getLayoutNames--}
```
public final String[] getLayoutNames()
```


يحدد أي تخطيطات CAD سيتم تحويلها


**Returns:**
java.lang.String[]
### setLayoutNames(String[] value) {#setLayoutNames-java.lang.String---}
```
public final void setLayoutNames(String[] value)
```


يحدد أي تخطيطات CAD سيتم تحويلها


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String[] |  |

### getDrawType() {#getDrawType--}
```
public CadDrawTypeMode getDrawType()
```


يحصل على نوع الرسم.


**Returns:**
[CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode)
### setDrawType(CadDrawTypeMode drawType) {#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-}
```
public void setDrawType(CadDrawTypeMode drawType)
```


يضبط نوع الرسم.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| drawType | [CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


يحصل على لون الخلفية.


**Returns:**
com.aspose.ms.System.Drawing.Color
### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


يضبط لون الخلفية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| backgroundColor | com.aspose.ms.System.Drawing.Color |  |

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```




**Returns:**
java.util.List<java.lang.String>
### setFontDirectories(List<String> fontDirectories) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> fontDirectories)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontDirectories | java.util.List<java.lang.String> |  |

### getCtbSources() {#getCtbSources--}
```
public Map<String,InputStream> getCtbSources()
```


يحصل على مصادر CTB.


**Returns:**
java.util.Map<java.lang.String,java.io.InputStream>
### setCtbSources(Map<String,InputStream> ctbSources) {#setCtbSources-java.util.Map-java.lang.String-java.io.InputStream--}
```
public void setCtbSources(Map<String,InputStream> ctbSources)
```


يضبط مصادر CTB.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ctbSources | java.util.Map<java.lang.String,java.io.InputStream> |  |

### getDrawColor() {#getDrawColor--}
```
public System.Drawing.Color getDrawColor()
```


يحصل على لون المقدمة.


**Returns:**
com.aspose.ms.System.Drawing.Color
### setDrawColor(System.Drawing.Color drawColor) {#setDrawColor-com.aspose.ms.System.Drawing.Color-}
```
public void setDrawColor(System.Drawing.Color drawColor)
```


يضبط لون المقدمة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| drawColor | com.aspose.ms.System.Drawing.Color |  |

