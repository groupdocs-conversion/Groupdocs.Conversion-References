---
title: "ProjectManagementFileType 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "定义由项目管理软件（如 Microsoft Project、Primavera P6 等）创建的 Project 文件格式。"
type: docs
url: /zh/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/
is_root: false
weight: 170
---


## ProjectManagementFileType class

定义由项目管理软件（如 Microsoft Project、Primavera P6 等）创建的 Project 文件格式。

项目文件是任务、资源及其调度的集合，用于以产品或服务的形式获得可衡量的输出。项目管理文档。包括以下文件类型：[`ProjectManagementFileType.mpp`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpp/)、[`ProjectManagementFileType.mpt`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpt/)、[`ProjectManagementFileType.mpx`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpx/)。了解更多关于项目管理格式的信息请访问此处：https://wiki.fileformat.com/project-management。

ProjectManagementFileType 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/__init__/) | 初始化一个用于序列化的 ProjectManagementFileType。 |

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
| [MPT](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpt/) | Microsoft Project 模板文件包含用于创建 .MPP 文件的基本信息、结构以及文档设置。了解此文件格式的更多信息请访问此处。 |
| [MPP](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpp/) | MPP 是 Microsoft Project 数据文件，以集成方式存储与项目管理相关的信息。了解此文件格式的更多信息请访问此处。 |
| [MPX](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpx/) | Microsoft Exchange 文件格式是一种 ASCII 文件格式，用于在 Microsoft Project（MSP）与支持 MPX 文件格式的其他应用程序（如 Primavera Project Planner、Sciforma 和 Timerline Precision Estimating）之间传输项目信息。了解此文件格式的更多信息请访问此处。 |
| [XER](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/xer/) | XER 文件格式是一种专有的项目文件格式，供 Primavera P6 项目规划和管理应用程序使用。了解此文件格式的更多信息请访问此处。 |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | 未知文件类型（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |

### 另见
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
