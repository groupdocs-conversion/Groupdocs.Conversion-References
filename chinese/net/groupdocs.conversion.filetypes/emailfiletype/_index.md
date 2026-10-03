---
title: "EmailFileType"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "定义电子邮件文件格式，这些格式被电子邮件应用程序用于存储各种数据，包括电子邮件消息、附件、文件夹、地址簿等。包括以下文件类型：Eml./emailfiletype/eml Emlx./emailfiletype/emlx Msg./emailfiletype/msg Vcf./emailfiletype/vcf. Mbox./emailfiletype/mbox. Pst./emailfiletype/pst. Ost./emailfiletype/ost. Olm./emailfiletype/olm. 了解更多关于电子邮件格式的信息 herehttps//wiki.fileformat.com/email。"
type: docs
weight: 1120
url: /zh/net/groupdocs.conversion.filetypes/emailfiletype/
---
## EmailFileType class

定义电子邮件文件格式，这些格式被电子邮件应用程序用于存储各种数据，包括电子邮件消息、附件、文件夹、地址簿等。包括以下文件类型：[`Eml`](./eml)、[`Emlx`](./emlx)、[`Msg`](./msg)、[`Vcf`](./vcf)。[`Mbox`](./mbox)。[`Pst`](./pst)。[`Ost`](./ost)。[`Olm`](./olm)。了解更多关于电子邮件格式[此处](https://wiki.fileformat.com/email)。

```csharp
public sealed class EmailFileType : FileType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmailFileType](emailfiletype)() | 序列化构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | 文件类型描述 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | 文件扩展名 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | 文件族 |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | 文件格式 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 将当前对象与其他对象进行比较。 |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | 实现 [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 充当默认的哈希函数。 |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 字符串表示 |

## Fields

| 名称 | 描述 |
| --- | --- |
| static readonly [Eml](../../groupdocs.conversion.filetypes/emailfiletype/eml) | EML 文件格式表示使用 Outlook 等相关应用程序保存的电子邮件消息。几乎所有的电子邮件客户端都支持此文件格式，因为它符合 RFC-822 Internet Message Format 标准。了解更多关于此文件格式的信息[此处](https://wiki.fileformat.com/email/eml)。 |
| static readonly [Emlx](../../groupdocs.conversion.filetypes/emailfiletype/emlx) | EMLX 文件格式由 Apple 实现和开发。Apple Mail 应用程序使用 EMLX 文件格式导出电子邮件。了解更多关于此文件格式的信息[此处](https://wiki.fileformat.com/email/emlx)。 |
| static readonly [Ics](../../groupdocs.conversion.filetypes/emailfiletype/ics) | ICS（iCalendar）文件格式用于表示和交换日历及调度信息，如事件、待办事项以及空闲/忙碌数据。了解更多关于此文件格式的信息[此处](https://wiki.fileformat.com/email/ics)。 |
| static readonly [Mbox](../../groupdocs.conversion.filetypes/emailfiletype/mbox) | MBox 文件格式是一个通用术语，表示用于存放电子邮件消息集合的容器。消息以及它们的附件都存储在该容器中。了解更多关于此文件格式的信息[此处](https://docs.fileformat.com/email/mbox/)。 |
| static readonly [Msg](../../groupdocs.conversion.filetypes/emailfiletype/msg) | MSG 是 Microsoft Outlook 和 Exchange 用于存储电子邮件消息、联系人、约会或其他任务的文件格式。了解更多关于此文件格式的信息[此处](https://wiki.fileformat.com/email/msg)。 |
| static readonly [Olm](../../groupdocs.conversion.filetypes/emailfiletype/olm) | 扩展名为 .olm 的文件是适用于 macOS 的 Microsoft Outlook 文件。OLM 文件存储电子邮件、日志、日历数据以及其他类型的应用数据。这些文件类似于 Windows 上 Outlook 使用的 PST 文件。然而，Mac 版 Outlook 创建的 OLM 文件无法在 Windows 版 Outlook 中打开。了解更多关于此文件格式的信息[此处](https://wiki.fileformat.com/email/olm)。 |
| static readonly [Ost](../../groupdocs.conversion.filetypes/emailfiletype/ost) | OST（离线存储文件）表示用户在本地机器上离线模式下的邮箱数据，该数据在使用 Microsoft Outlook 注册 Exchange Server 时创建。了解更多关于此文件格式的信息[此处](https://wiki.fileformat.com/email/ost)。 |
| static readonly [Pst](../../groupdocs.conversion.filetypes/emailfiletype/pst) | 扩展名为 .PST 的文件代表 Outlook Personal Storage Files（也称为 Personal Storage Table），用于存储各种用户信息。了解更多关于此文件格式的信息[此处](https://wiki.fileformat.com/email/pst)。 |
| static readonly [Vcf](../../groupdocs.conversion.filetypes/emailfiletype/vcf) | VCF（Virtual Card Format）或 vCard 是一种用于存储联系信息的数字文件格式。该格式被广泛用于流行信息交换应用之间的数据互换。了解更多关于此文件格式的信息[此处](https://wiki.fileformat.com/email/vcf)。 |

### 另见

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
