---
title: "EmailLoadOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "加载电子邮件文档的选项。"
type: docs
weight: 18
url: /zh/java/com.groupdocs.conversion.options.load/emailloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions), java.lang.Cloneable, java.io.Serializable
```
public final class EmailLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions, Cloneable, Serializable
```

加载电子邮件文档的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [EmailLoadOptions()](#EmailLoadOptions--) | 初始化 [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions) 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDisplayHeader()](#getDisplayHeader--) | 显示或隐藏电子邮件标题的选项。 |
|
|  | [setDisplayHeader(boolean value)](#setDisplayHeader-boolean-) | 显示或隐藏电子邮件标题的选项。 |
|
|  | [getDisplayFromEmailAddress()](#getDisplayFromEmailAddress--) | 显示或隐藏 "from" 邮件地址的选项。 |
|
|  | [setDisplayFromEmailAddress(boolean value)](#setDisplayFromEmailAddress-boolean-) | 显示或隐藏 "from" 邮件地址的选项。 |
|
|  | [getDisplayToEmailAddress()](#getDisplayToEmailAddress--) | 显示或隐藏 "to" 邮件地址的选项。 |
|
|  | [setDisplayToEmailAddress(boolean value)](#setDisplayToEmailAddress-boolean-) | 显示或隐藏 "to" 邮件地址的选项。 |
|
|  | [getDisplayCcEmailAddress()](#getDisplayCcEmailAddress--) | 显示或隐藏 "Cc" 邮件地址的选项。 |
|
|  | [setDisplayCcEmailAddress(boolean value)](#setDisplayCcEmailAddress-boolean-) | 显示或隐藏 "Cc" 邮件地址的选项。 |
|
|  | [getDisplayBccEmailAddress()](#getDisplayBccEmailAddress--) | 显示或隐藏 "Bcc" 邮件地址的选项。 |
|
|  | [setDisplayBccEmailAddress(boolean value)](#setDisplayBccEmailAddress-boolean-) | 显示或隐藏 "Bcc" 邮件地址的选项。 |
|
|  | [getTimeZoneOffset()](#getTimeZoneOffset--) | 获取或设置消息日期的协调世界时（UTC）偏移量。 |
|
| [getTimeZoneOffsetInternal()](#getTimeZoneOffsetInternal--) |  |
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | 加载外部资源的超时时间 |
|
|  | [setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)](#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-) | 加载外部资源的超时时间（设置器） |
|
|  | [setTimeZoneOffset(Double value)](#setTimeZoneOffset-java.lang.Double-) | 获取或设置消息日期的协调世界时（UTC）偏移量。 |
|
|  | [deepClone()](#deepClone--) | 克隆当前实例。 |
|
|  | [getFieldTextMap()](#getFieldTextMap--) | 获取电子邮件消息与字段文本表示之间的映射 |
|
|  | [setFieldTextMap(Map<EmailField,String> fieldTextMap)](#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--) | 设置电子邮件消息与字段文本表示之间的映射 |
|
|  | [isPreserveOriginalDate()](#isPreserveOriginalDate--) | 定义在保存邮件时是否需要保留原始日期标头字符串（默认值为 true） |
|
|  | [setPreserveOriginalDate(boolean preserveOriginalDate)](#setPreserveOriginalDate-boolean-) | 定义在保存邮件时是否需要保留原始日期标头字符串 |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
|  | [isDisplayAttachments()](#isDisplayAttachments--) | 获取在标头中显示或隐藏附件的选项。 |
|
|  | [setDisplayAttachments(boolean displayAttachments)](#setDisplayAttachments-boolean-) | 设置在标头中显示或隐藏附件的选项。 |
|
|  | [isDisplaySubject()](#isDisplaySubject--) | 获取在标头中显示或隐藏主题的选项。 |
|
|  | [setDisplaySubject(boolean displaySubject)](#setDisplaySubject-boolean-) | 设置在标头中显示或隐藏主题的选项 |
|
|  | [isDisplaySent()](#isDisplaySent--) | 获取在标头中显示或隐藏发送日期/时间的选项。 |
|
|  | [setDisplaySent(boolean displaySent)](#setDisplaySent-boolean-) | 设置在标头中显示或隐藏发送日期/时间的选项。 |
|
|  | [isSkipExternalResources()](#isSkipExternalResources--) | 如果为 true，则跳过 http 资源加载 |
|
| [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) |  |
### EmailLoadOptions() {#EmailLoadOptions--}
```
public EmailLoadOptions()
```


初始化 [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions) 类的新实例。


### getFormat() {#getFormat--}
```
public final EmailFileType getFormat()
```


输入文档文件类型


**Returns:**
[EmailFileType](../../com.groupdocs.conversion.filetypes/emailfiletype)
### getDisplayHeader() {#getDisplayHeader--}
```
public final boolean getDisplayHeader()
```


显示或隐藏电子邮件标头的选项。默认：true。


**Returns:**
布尔
### setDisplayHeader(boolean value) {#setDisplayHeader-boolean-}
```
public final void setDisplayHeader(boolean value)
```


显示或隐藏电子邮件标头的选项。默认：true。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getDisplayFromEmailAddress() {#getDisplayFromEmailAddress--}
```
public final boolean getDisplayFromEmailAddress()
```


显示或隐藏 "from" 邮件地址的选项。默认：true。


**Returns:**
布尔
### setDisplayFromEmailAddress(boolean value) {#setDisplayFromEmailAddress-boolean-}
```
public final void setDisplayFromEmailAddress(boolean value)
```


显示或隐藏 "from" 邮件地址的选项。默认：true。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getDisplayToEmailAddress() {#getDisplayToEmailAddress--}
```
public final boolean getDisplayToEmailAddress()
```


显示或隐藏 "to" 邮件地址的选项。默认：true。


**Returns:**
布尔
### setDisplayToEmailAddress(boolean value) {#setDisplayToEmailAddress-boolean-}
```
public final void setDisplayToEmailAddress(boolean value)
```


显示或隐藏 "to" 邮件地址的选项。默认：true。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getDisplayCcEmailAddress() {#getDisplayCcEmailAddress--}
```
public final boolean getDisplayCcEmailAddress()
```


显示或隐藏 "Cc" 邮件地址的选项。默认：false。


**Returns:**
布尔
### setDisplayCcEmailAddress(boolean value) {#setDisplayCcEmailAddress-boolean-}
```
public final void setDisplayCcEmailAddress(boolean value)
```


显示或隐藏 "Cc" 邮件地址的选项。默认：false。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getDisplayBccEmailAddress() {#getDisplayBccEmailAddress--}
```
public final boolean getDisplayBccEmailAddress()
```


显示或隐藏 "Bcc" 邮件地址的选项。默认：false。


**Returns:**
布尔
### setDisplayBccEmailAddress(boolean value) {#setDisplayBccEmailAddress-boolean-}
```
public final void setDisplayBccEmailAddress(boolean value)
```


显示或隐藏 "Bcc" 邮件地址的选项。默认：false。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public final Double getTimeZoneOffset()
```


获取或设置消息日期的协调世界时（UTC）偏移量。此属性定义本地时间与 UTC 之间的时区差异。


**Returns:**
java.lang.Double
### getTimeZoneOffsetInternal() {#getTimeZoneOffsetInternal--}
```
public System.TimeSpan getTimeZoneOffsetInternal()
```




**Returns:**
com.aspose.ms.System.TimeSpan
### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public System.TimeSpan getResourceLoadingTimeout()
```


加载外部资源的超时时间


**Returns:**
com.aspose.ms.System.TimeSpan
### setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout) {#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-}
```
public void setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)
```


加载外部资源的超时时间（设置器）


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resourceLoadingTimeout | com.aspose.ms.System.TimeSpan |  |

### setTimeZoneOffset(Double value) {#setTimeZoneOffset-java.lang.Double-}
```
public final void setTimeZoneOffset(Double value)
```


获取或设置消息日期的协调世界时（UTC）偏移量。此属性定义本地时间与 UTC 之间的时区差异。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


克隆当前实例。


**Returns:**
java.lang.Object -
### getFieldTextMap() {#getFieldTextMap--}
```
public Map<EmailField,String> getFieldTextMap()
```


获取电子邮件消息与字段文本表示之间的映射


**Returns:**
java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> - 映射

### setFieldTextMap(Map<EmailField,String> fieldTextMap) {#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--}
```
public void setFieldTextMap(Map<EmailField,String> fieldTextMap)
```


设置电子邮件消息与字段文本表示之间的映射


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fieldTextMap | java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> | 映射 |
|

### isPreserveOriginalDate() {#isPreserveOriginalDate--}
```
public boolean isPreserveOriginalDate()
```


定义在保存邮件时是否需要保留原始日期标头字符串（默认值为 true）


**Returns:**
boolean - 如果为 true，则保留原始日期

### setPreserveOriginalDate(boolean preserveOriginalDate) {#setPreserveOriginalDate-boolean-}
```
public void setPreserveOriginalDate(boolean preserveOriginalDate)
```


定义在保存邮件时是否需要保留原始日期标头字符串


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | preserveOriginalDate | 布尔 | 保留原始日期 |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


获取选项以控制文档容器本身是否必须转换


**Returns:**
布尔
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| convertOwner | 布尔 |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


选项，用于控制文档容器中的所属文档是否必须转换


**Returns:**
布尔
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| convertOwned | 布尔 |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


选项，用于控制转换的深度层级数


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| depth | int |  |

### isDisplayAttachments() {#isDisplayAttachments--}
```
public boolean isDisplayAttachments()
```


获取在标题中显示或隐藏附件的选项。默认值：true。


**Returns:**
布尔
### setDisplayAttachments(boolean displayAttachments) {#setDisplayAttachments-boolean-}
```
public void setDisplayAttachments(boolean displayAttachments)
```


设置在标头中显示或隐藏附件的选项。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| displayAttachments | 布尔 |  |

### isDisplaySubject() {#isDisplaySubject--}
```
public boolean isDisplaySubject()
```


获取在标题中显示或隐藏主题的选项。默认值：true。


**Returns:**
布尔
### setDisplaySubject(boolean displaySubject) {#setDisplaySubject-boolean-}
```
public void setDisplaySubject(boolean displaySubject)
```


设置在标头中显示或隐藏主题的选项


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| displaySubject | 布尔 |  |

### isDisplaySent() {#isDisplaySent--}
```
public boolean isDisplaySent()
```


获取在标题中显示或隐藏发送日期/时间的选项。默认值：true。


**Returns:**
布尔
### setDisplaySent(boolean displaySent) {#setDisplaySent-boolean-}
```
public void setDisplaySent(boolean displaySent)
```


设置在标头中显示或隐藏发送日期/时间的选项。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| displaySent | 布尔 |  |

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


如果为 true，则跳过 http 资源加载


**Returns:**
布尔
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| skipExternalResources | 布尔 |  |

