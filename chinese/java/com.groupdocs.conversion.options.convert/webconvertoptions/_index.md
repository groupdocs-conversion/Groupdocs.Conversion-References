---
title: "WebConvertOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "用于转换为 Web 文件类型的选项。"
type: docs
weight: 46
url: /zh/java/com.groupdocs.conversion.options.convert/webconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions
```
public class WebConvertOptions extends CommonConvertOptions<WebFileType>
```

用于转换为 Web 文件类型的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [WebConvertOptions()](#WebConvertOptions--) | 初始化类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [isUsePdf()](#isUsePdf--) |  |
| [setUsePdf(boolean usePdf)](#setUsePdf-boolean-) |  |
| [isFixedLayout()](#isFixedLayout--) |  |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) |  |
| [isFixedLayoutShowBorders()](#isFixedLayoutShowBorders--) |  |
| [setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)](#setFixedLayoutShowBorders-boolean-) |  |
| [getZoom()](#getZoom--) |  |
| [setZoom(int zoom)](#setZoom-int-) |  |
|  | [isEmbedFontResources()](#isEmbedFontResources--) | 指定是否在主 HTML 中嵌入字体资源。 |
|
|  | [setEmbedFontResources(boolean embedFontResources)](#setEmbedFontResources-boolean-) | 指定是否在主 HTML 中嵌入字体资源。 |
|
### WebConvertOptions() {#WebConvertOptions--}
```
public WebConvertOptions()
```


初始化类的新实例。


### isUsePdf() {#isUsePdf--}
```
public boolean isUsePdf()
```




**Returns:**
布尔
### setUsePdf(boolean usePdf) {#setUsePdf-boolean-}
```
public void setUsePdf(boolean usePdf)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| usePdf | 布尔 |  |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```




**Returns:**
布尔
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fixedLayout | 布尔 |  |

### isFixedLayoutShowBorders() {#isFixedLayoutShowBorders--}
```
public boolean isFixedLayoutShowBorders()
```




**Returns:**
布尔
### setFixedLayoutShowBorders(boolean fixedLayoutShowBorders) {#setFixedLayoutShowBorders-boolean-}
```
public void setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fixedLayoutShowBorders | 布尔 |  |

### getZoom() {#getZoom--}
```
public int getZoom()
```




**Returns:**
int
### setZoom(int zoom) {#setZoom-int-}
```
public void setZoom(int zoom)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| zoom | int |  |

### isEmbedFontResources() {#isEmbedFontResources--}
```
public boolean isEmbedFontResources()
```


指定是否在主 HTML 中嵌入字体资源。默认值为 false。注意：如果 FixedLayout 设置为 true，字体资源将始终被嵌入。


**Returns:**
布尔
### setEmbedFontResources(boolean embedFontResources) {#setEmbedFontResources-boolean-}
```
public void setEmbedFontResources(boolean embedFontResources)
```


指定是否在主 HTML 中嵌入字体资源。默认值为 false。注意：如果 FixedLayout 设置为 true，字体资源将始终被嵌入。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| embedFontResources | 布尔 |  |

