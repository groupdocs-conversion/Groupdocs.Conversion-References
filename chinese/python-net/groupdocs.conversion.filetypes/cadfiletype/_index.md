---
title: "CadFileType 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "表示用于 3D 图形文件格式的 CAD 文档（计算机辅助设计），可能包含 2D 或 3D 设计。"
type: docs
url: /zh/python-net/groupdocs.conversion.filetypes/cadfiletype/
is_root: false
weight: 20
---


## CadFileType class

表示用于 3D 图形文件格式的 CAD 文档（计算机辅助设计），可能包含 2D 或 3D 设计。

包括以下类型：
- [`CadFileType.cf2`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/cf2/)
- [`CadFileType.dgn`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dgn/)
- [`CadFileType.dwf`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dwf/)
- [`CadFileType.dwfx`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dwfx/)
- [`CadFileType.dwg`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dwg/)
- [`CadFileType.dwt`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dwt/)
- [`CadFileType.dxf`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dxf/)
- [`CadFileType.ifc`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/ifc/)
- [`CadFileType.igs`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/igs/)
- [`CadFileType.plt`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/plt/)
- [`CadFileType.stl`](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/stl/)

了解更多 CAD 格式（https://wiki.fileformat.com/cad）。

CadFileType 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/__init__/) | 初始化一个用于序列化的新的 CadFileType 实例。 |

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
| [DXF](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dxf/) | DXF，绘图交换格式或绘图交换格式，是 AutoCAD 绘图文件的带标签数据表示。了解此文件格式的更多信息请访问此处。 |
| [DWG](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dwg/) | 扩展名为 DWG 的文件是用于存储 2D 和 3D 设计数据的专有二进制文件。与 DXF（ASCII 文件）不同，DWG 代表 CAD（计算机辅助设计）图纸的二进制文件格式。了解此文件格式的更多信息请访问此处。 |
| [DGN](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dgn/) | DGN（设计）文件是由 MicroStation、Intergraph Interactive Graphics Design System 等 CAD 应用程序创建并支持的图纸。了解此文件格式的更多信息请访问此处。 |
| [DWF](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dwf/) | Design Web Format（DWF）以压缩格式表示用于查看、审阅或打印的 2D/3D 图纸。它将图形和文本作为设计数据的一部分，并因压缩格式而减小文件大小。了解此文件格式的更多信息请访问此处。 |
| [STL](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/stl/) | STL（立体光刻的缩写）是一种可互换的文件格式，用于表示三维表面几何。该文件格式在快速原型制造、3D 打印和计算机辅助制造等多个领域中得到应用。了解此文件格式的更多信息请访问此处。 |
| [IFC](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/ifc/) | 扩展名为 IFC 的文件指的是行业基础类（Industry Foundation Classes，IFC）文件格式，该格式建立了用于导入和导出建筑对象及其属性的国际标准。此文件格式实现了不同软件应用之间的互操作性。了解此文件格式的更多信息请访问此处。 |
| [PLT](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/plt/) | PLT 文件格式是 Autodesk, Inc. 推出的基于矢量的绘图仪文件，包含特定 CAD 文件的信息。绘图细节在生产中需要精确和准确，使用 PLT 文件能够保证这一点，因为所有图像均使用线条而非点进行打印。了解此文件格式的更多信息请访问此处。 |
| [IGS](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/igs/) | Igs 文档格式 |
| [DWT](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dwt/) | DWT 文件是 AutoCAD 绘图模板文件，用作创建可保存为 DWG 文件的图纸的起始模板。了解此文件格式的更多信息请访问此处。 |
| [DWFX](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/dwfx/) | DWFX 文件是使用 Autodesk CAD 软件创建的 2D 或 3D 图纸。它以 DWFx 格式保存，该格式类似于 DWF 文件，但采用 Microsoft 的 XML Paper Specification（XPS）进行格式化。 |
| [CF2](/conversion/python-net/groupdocs.conversion.filetypes/cadfiletype/cf2/) | 通用文件格式（Common File Format）文件。该 CAD 文件包含 3D 包装设计或其他模型数据；可由 CAD/CAM 机器（如模切设备）进行加工和切割。 |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | 未知文件类型（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |

### 另见
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
