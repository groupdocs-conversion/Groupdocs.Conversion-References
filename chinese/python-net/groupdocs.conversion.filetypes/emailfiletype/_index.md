---
title: "EmailFileType 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "定义电子邮件应用程序用于存储消息、附件、文件夹、通讯录和其他数据的电子邮件文件格式。"
type: docs
url: /zh/python-net/groupdocs.conversion.filetypes/emailfiletype/
is_root: false
weight: 70
---


## EmailFileType class

定义电子邮件应用程序用于存储消息、附件、文件夹、通讯录和其他数据的电子邮件文件格式。

包括以下文件类型：
- [`EmailFileType.eml`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/eml/)
- [`EmailFileType.emlx`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/emlx/)
- [`EmailFileType.msg`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/msg/)
- [`EmailFileType.vcf`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/vcf/)
- [`EmailFileType.mbox`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/mbox/)
- [`EmailFileType.pst`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/pst/)
- [`EmailFileType.ost`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ost/)
- [`EmailFileType.olm`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/olm/)

了解更多关于电子邮件格式的信息，请访问 https://wiki.fileformat.com/email。

EmailFileType 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/__init__/) | 初始化一个用于序列化的新的 EmailFileType。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | 比较当前对象与其他对象。（继承自 [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)） |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | （继承自 [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)） |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | 实现由 [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/) 定义的相等比较。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | （继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | （继承自 [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)） |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | （继承自 [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)） |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | 获取提供的文件扩展名对应的 FileType。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | 返回指定 file_name 的 FileType。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | 返回提供的文档流的 FileType。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | （继承自 [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)） |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | （继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | 提供默认的哈希函数。（继承自 [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)） |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | 文件类型的字符串表示。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |

### 属性
| 属性 | 描述 |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | 文件类型描述。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | 文件扩展名。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | 文件族。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | 文件格式。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |

### 字段
| 字段 | 描述 |
| :- | :- |
| [MSG](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/msg/) | MSG 是一种文件格式，Microsoft Outlook 和 Exchange 使用它来存储电子邮件、联系人、约会或其他任务。了解更多关于此文件格式的信息，请点击此处。 |
| [EML](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/eml/) | EML 文件格式表示使用 Outlook 和其他相关应用程序保存的电子邮件。几乎所有的邮件客户端都支持此文件格式，因为它符合 RFC-822 互联网消息格式标准。了解更多关于此文件格式的信息，请点击此处。 |
| [EMLX](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/emlx/) | EMLX 文件格式由 Apple 实现和开发。Apple Mail 应用程序使用 EMLX 文件格式导出电子邮件。了解更多关于此文件格式的信息，请点击此处。 |
| [VCF](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/vcf/) | VCF（虚拟名片格式）或 vCard 是一种用于存储联系信息的数字文件格式。该格式被广泛用于流行信息交换应用程序之间的数据互换。了解更多关于此文件格式的信息，请点击此处。 |
| [MBOX](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/mbox/) | MBox 文件格式是一个通用术语，表示用于收集电子邮件的容器。邮件及其附件都存储在该容器中。了解更多关于此文件格式的信息，请点击此处。 |
| [PST](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/pst/) | .PST 扩展名的文件代表 Outlook 个人存储文件（也称为个人存储表），用于存储各种用户信息。了解更多关于此文件格式的信息，请点击此处。 |
| [OST](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ost/) | OST（离线存储文件）表示用户在使用 Microsoft Outlook 注册 Exchange Server 后，在本地机器的离线模式下的邮箱数据。了解更多关于此文件格式的信息，请点击此处。 |
| [OLM](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/olm/) | .olm 扩展名的文件是针对 macOS 的 Microsoft Outlook 文件。OLM 文件存储电子邮件、日志、日历数据以及其他类型的应用数据。它们类似于 Windows 操作系统上 Outlook 使用的 PST 文件。然而，Mac 版 Outlook 创建的 OLM 文件无法在 Windows 版 Outlook 中打开。了解更多关于此文件格式的信息，请点击此处。 |
| [ICS](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ics/) | ICS（iCalendar）文件格式用于表示和交换日历及调度信息，如事件、待办事项和空闲/忙碌数据。了解更多关于此文件格式的信息，请点击此处。 |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | 未知文件类型（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |

### 另见
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
