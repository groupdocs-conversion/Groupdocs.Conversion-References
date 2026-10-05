---
title: "CadLoadOptions"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "CAD belgelerini yükleme seçenekleri."
type: docs
weight: 12
url: /tr/nodejs-java/com.groupdocs.conversion.options.load/cadloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadLoadOptions extends LoadOptions implements Serializable
```

CAD belgelerini yükleme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CadLoadOptions()](#CadLoadOptions--) | Yeni bir [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getWidth()](#getWidth--) | CAD belgesini dönüştürmek için istenen sayfa genişliğini ayarlar |
| [setWidth(int value)](#setWidth-int-) | CAD belgesini dönüştürmek için istenen sayfa genişliğini ayarlar |
| [getHeight()](#getHeight--) | CAD belgesini dönüştürmek için istenen sayfa yüksekliğini ayarlar |
| [setHeight(int value)](#setHeight-int-) | CAD belgesini dönüştürmek için istenen sayfa yüksekliğini ayarlar |
| [getLayoutNames()](#getLayoutNames--) | Dönüştürülecek CAD düzenlerini belirtir |
| [setLayoutNames(String[] value)](#setLayoutNames-java.lang.String---) | Dönüştürülecek CAD düzenlerini belirtir |
| [getDrawType()](#getDrawType--) | Çizimin tipini alır. |
| [setDrawType(CadDrawTypeMode drawType)](#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-) | Çizimin tipini ayarlar. |
| [getBackgroundColor()](#getBackgroundColor--) | Arka plan rengini alır. |
| [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | Arka plan rengini ayarlar. |
| [getFontDirectories()](#getFontDirectories--) |  |
| [setFontDirectories(List<String> fontDirectories)](#setFontDirectories-java.util.List-java.lang.String--) |  |
### CadLoadOptions() {#CadLoadOptions--}
```
public CadLoadOptions()
```


Yeni bir [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions) sınıfının örneğini başlatır.

### getFormat() {#getFormat--}
```
public CadFileType getFormat()
```


Girdi belge dosya türü

**Returns:**
[CadFileType](../../com.groupdocs.conversion.filetypes/cadfiletype)
### getWidth() {#getWidth--}
```
public final int getWidth()
```


CAD belgesini dönüştürmek için istenen sayfa genişliğini ayarlar

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


CAD belgesini dönüştürmek için istenen sayfa genişliğini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


CAD belgesini dönüştürmek için istenen sayfa yüksekliğini ayarlar

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


CAD belgesini dönüştürmek için istenen sayfa yüksekliğini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getLayoutNames() {#getLayoutNames--}
```
public final String[] getLayoutNames()
```


Dönüştürülecek CAD düzenlerini belirtir

**Returns:**
java.lang.String[]
### setLayoutNames(String[] value) {#setLayoutNames-java.lang.String---}
```
public final void setLayoutNames(String[] value)
```


Dönüştürülecek CAD düzenlerini belirtir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String[] |  |

### getDrawType() {#getDrawType--}
```
public CadDrawTypeMode getDrawType()
```


Çizimin tipini alır.

**Returns:**
[CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode)
### setDrawType(CadDrawTypeMode drawType) {#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-}
```
public void setDrawType(CadDrawTypeMode drawType)
```


Çizimin tipini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| drawType | [CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


Arka plan rengini alır.

**Returns:**
com.aspose.ms.System.Drawing.Color
### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


Arka plan rengini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontDirectories | java.util.List<java.lang.String> |  |

