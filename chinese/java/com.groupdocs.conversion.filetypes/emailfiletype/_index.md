---
title: "EmailFileType"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "定义电子邮件文件格式，这些格式被电子邮件应用程序用于存储各种数据，包括电子邮件、附件、文件夹、通讯录等。"
type: docs
weight: 15
url: /zh/java/com.groupdocs.conversion.filetypes/emailfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EmailFileType extends FileType implements Serializable
```

定义电子邮件文件格式，电子邮件应用程序用于存储各种数据，包括电子邮件、附件、文件夹、通讯录等。
包括以下文件类型：
[Eml](../../com.groupdocs.conversion.filetypes/emailfiletype#Eml),
[Emlx](../../com.groupdocs.conversion.filetypes/emailfiletype#Emlx),
[Msg](../../com.groupdocs.conversion.filetypes/emailfiletype#Msg),
[Vcf](../../com.groupdocs.conversion.filetypes/emailfiletype#Vcf).
[Pst](../../com.groupdocs.conversion.filetypes/emailfiletype#Pst).
[Ost](../../com.groupdocs.conversion.filetypes/emailfiletype#Ost).
[Olm](../../com.groupdocs.conversion.filetypes/emailfiletype#Olm).
了解更多关于电子邮件格式的信息 [here](../https://wiki.fileformat.com/email).

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [EmailFileType()](#EmailFileType--) | 序列化构造函数 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Msg](#Msg) | MSG 是一种文件格式，Microsoft Outlook 和 Exchange 使用它来存储电子邮件、联系人、约会或其他任务。 |
|
|  | [Eml](#Eml) | EML 文件格式表示使用 Outlook 和其他相关应用程序保存的电子邮件。 |
|
|  | [Emlx](#Emlx) | EMLX 文件格式由 Apple 实现和开发。 |
|
|  | [Vcf](#Vcf) | VCF（虚拟名片格式）或 vCard 是一种用于存储联系信息的数字文件格式。 |
|
|  | [Mbox](#Mbox) | MBox 文件格式是一个通用术语，表示用于收集电子邮件的容器。 |
|
|  | [Pst](#Pst) | 扩展名为 .PST 的文件代表 Outlook 个人存储文件（亦称 Personal Storage Table），用于存储各种用户信息。 |
|
|  | [Ost](#Ost) | OST（离线存储文件）表示用户在使用 Microsoft Outlook 注册 Exchange Server 后，在本地机器上离线模式下的邮箱数据。 |
|
|  | [Olm](#Olm) | 扩展名为 .olm 的文件是适用于 macOS 的 Microsoft Outlook 文件。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### EmailFileType() {#EmailFileType--}
```
public EmailFileType()
```


序列化构造函数


### Msg {#Msg}
```
public static final EmailFileType Msg
```


MSG 是一种文件格式，Microsoft Outlook 和 Exchange 使用它来存储电子邮件、联系人、约会或其他任务。
了解更多关于此文件格式的信息 [here](../https://wiki.fileformat.com/email/msg).


### Eml {#Eml}
```
public static final EmailFileType Eml
```


EML 文件格式表示使用 Outlook 和其他相关应用程序保存的电子邮件消息。几乎所有电子邮件客户端都支持此文件格式，因为它符合 RFC-822 Internet Message Format 标准。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/email/eml)。


### Emlx {#Emlx}
```
public static final EmailFileType Emlx
```


EMLX 文件格式由 Apple 实现和开发。Apple Mail 应用程序使用 EMLX 文件格式导出电子邮件。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/email/emlx)。


### Vcf {#Vcf}
```
public static final EmailFileType Vcf
```


VCF（虚拟名片格式）或 vCard 是一种用于存储联系信息的数字文件格式。该格式被广泛用于流行信息交换应用程序之间的数据互换。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/email/vcf)。


### Mbox {#Mbox}
```
public static final EmailFileType Mbox
```


MBox 文件格式是一个通用术语，表示用于收集电子邮件消息的容器。邮件以及其附件都存储在该容器中。
了解更多关于此文件格式的信息，请点击[此处](../https://docs.fileformat.com/email/mbox/)。


### Pst {#Pst}
```
public static final EmailFileType Pst
```


.PST 扩展名的文件代表 Outlook 个人存储文件（也称为个人存储表），用于存储各种用户信息。了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/email/pst)。


### Ost {#Ost}
```
public static final EmailFileType Ost
```


OST（离线存储文件）表示用户在使用 Microsoft Outlook 注册 Exchange Server 后，在本地机器上离线模式下的邮箱数据。了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/email/ost)。


### Olm {#Olm}
```
public static final EmailFileType Olm
```


.olm 扩展名的文件是适用于 macOS 的 Microsoft Outlook 文件。OLM 文件存储电子邮件、日志、日历数据以及其他类型的应用数据。这些文件类似于 Windows 操作系统上 Outlook 使用的 PST 文件。然而，由 Outlook for Mac 创建的 OLM 文件无法在 Windows 版 Outlook 中打开。了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/email/olm)。


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


为源文件类型准备了默认加载选项


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


为文件类型准备了默认转换选项


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
