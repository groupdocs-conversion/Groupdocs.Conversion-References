---
title: "RtfOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "用于转换为 RTF 文件类型的选项。"
type: docs
weight: 39
url: /zh/java/com.groupdocs.conversion.options.convert/rtfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class RtfOptions extends ValueObject implements Serializable
```

用于转换为 RTF 文件类型的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RtfOptions()](#RtfOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getExportImagesForOldReaders()](#getExportImagesForOldReaders--) | 指定是否将 "old readers" 的关键字写入 RTF。 |
|
|  | [setExportImagesForOldReaders(boolean value)](#setExportImagesForOldReaders-boolean-) | 指定是否将 "old readers" 的关键字写入 RTF。 |
|
### RtfOptions() {#RtfOptions--}
```
public RtfOptions()
```


### getExportImagesForOldReaders() {#getExportImagesForOldReaders--}
```
public final boolean getExportImagesForOldReaders()
```


指定是否将 "old readers" 的关键字写入 RTF。
这可能会显著影响 RTF 文档的大小。默认值为 False。


**Returns:**
布尔
### setExportImagesForOldReaders(boolean value) {#setExportImagesForOldReaders-boolean-}
```
public final void setExportImagesForOldReaders(boolean value)
```


指定是否将 "old readers" 的关键字写入 RTF。
这可能会显著影响 RTF 文档的大小。默认值为 False。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

