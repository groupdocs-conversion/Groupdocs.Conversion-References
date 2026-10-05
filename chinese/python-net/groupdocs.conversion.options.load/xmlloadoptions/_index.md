---
title: "XmlLoadOptions 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "加载 XML 文档的选项。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.load/xmlloadoptions/
is_root: false
weight: 590
---


## XmlLoadOptions class

加载 XML 文档的选项。

XmlLoadOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/__init__/) | 初始化一个新的 [`XmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/) 实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | 确定两个对象实例是否相等。 (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | 用作默认的哈希函数。 (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### 属性
| 属性 | 描述 |
| :- | :- |
| [custom_css_style](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/custom_css_style/) | 在转换期间要应用于文档的自定义 CSS 样式。 |
| [format](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/format/) | 输入文档的文件类型。 |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/margin_settings/) | 页面边距设置。 |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/orientation_settings/) | 页面方向设置。 |
| [page_layout_options](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/page_layout_options/) | 加载文档时要应用的页面布局缩放。默认：无。 |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/page_numbering/) | 转换后文档的页码生成标志（默认：False）。 |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/size_settings/) | 页面尺寸设置。 |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/skip_external_resources/) | 该属性指示是否加载外部资源。 |
| [use_as_data_source](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/use_as_data_source/) | XML 文档用作数据源。 |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/whitelisted_resources/) | 始终会被加载的外部资源。 |
| [xsl_fo_factory](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/xsl_fo_factory/) | 使用 XSL-FO 标记文件将 XML 转换的 XSL-FO 文档流。 |
| [xslt_factory](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/xslt_factory/) | 执行 XSL 转换为 HTML 的 XML 转换的 XSLT 文档流。 |
| [base_path](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/base_path/) | HTML 的基础路径/URL。（继承自 [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)） |
| [configure_headers](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/configure_headers/) | 用于配置请求头的操作，第一个参数是 Uri。（继承自 [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)） |
| [credentials_provider](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/credentials_provider/) | Uri 的凭据提供程序。（继承自 [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)） |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/encoding/) | 加载网页文档时使用的编码。如果设置为 None，将根据文档的字符集属性确定编码。（继承自 [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)） |
| [html_rendering_mode](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/html_rendering_mode/) | HTML 渲染模式控制 HTML 内容的渲染方式。默认：AbsolutePositioning。（继承自 [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)） |
| [resource_loading_timeout](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/resource_loading_timeout/) | 加载外部资源的超时时间。（继承自 [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)） |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/use_pdf/) | 该属性指示是否在转换中使用 PDF（默认：False）。（继承自 [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)） |
| [zoom](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/zoom/) | 在转换前以百分比形式应用于文档 `<body>` 标签的缩放级别，缩放文档的视觉外观。（继承自 [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)） |

### 另见
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
