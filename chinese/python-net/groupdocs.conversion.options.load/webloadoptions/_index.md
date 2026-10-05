---
title: "WebLoadOptions 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "提供加载 Web 文档的选项。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.load/webloadoptions/
is_root: false
weight: 550
---


## WebLoadOptions class

提供加载 Web 文档的选项。

该 WebLoadOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/__init__/) | 初始化一个新的 [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/) 实例。 |

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
| [base_path](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/base_path/) | HTML 的基础路径/URL。 |
| [configure_headers](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/configure_headers/) | 用于配置请求头的操作，其中第一个参数是 Uri。 |
| [credentials_provider](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/credentials_provider/) | Uri 的凭据提供程序。 |
| [custom_css_style](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/custom_css_style/) | 该属性实现了 [`ICustomCssStyleOptions.custom_css_style`](/conversion/python-net/groupdocs.conversion.options.load/icustomcssstyleoptions/custom_css_style/)。 |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/encoding/) | 加载网页文档时使用的编码。如果设置为 None，将根据文档的字符集属性确定编码。 |
| [format](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/format/) | 输入文档的文件类型。 |
| [html_rendering_mode](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/html_rendering_mode/) | HTML 渲染模式控制 HTML 内容的渲染方式。默认：AbsolutePositioning。 |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/margin_settings/) | 边距设置。 |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/orientation_settings/) | 方向设置。 |
| [page_layout_options](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/page_layout_options/) | 加载网页文档时使用的页面布局选项。 |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/page_numbering/) | 启用或禁用在转换后文档中生成页码的标志。默认：False。 |
| [resource_loading_timeout](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/resource_loading_timeout/) | 加载外部资源的超时时间。 |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/size_settings/) | 尺寸设置。 |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/skip_external_resources/) | 该属性实现了 [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/skip_external_resources/)。 |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/use_pdf/) | 该属性指示是否在转换中使用 PDF（默认：False）。 |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/whitelisted_resources/) | 白名单资源属性实现了 [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/)。 |
| [zoom](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/zoom/) | 在转换前，以百分比形式应用于文档的 `<body>` 标签的缩放级别，用于缩放文档的视觉外观。 |

### 另见
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
