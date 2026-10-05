---
title: "MarkdownOptions 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "表示转换为 markdown 文件类型的选项。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.convert/markdownoptions/
is_root: false
weight: 290
---


## MarkdownOptions class

表示转换为 markdown 文件类型的选项。

MarkdownOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/__init__/) | 初始化 [`MarkdownOptions`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/) 类的新实例。 |

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
| [export_images_as_base64](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/export_images_as_base64/) | export_images_as_base64 选项决定是否将图像导出为 base64。 |
| [image_saving_callback](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/image_saving_callback/) | 在保存 Markdown 时，每个图像调用一次的回调。允许调用者在外部持久化图像并替换文档中嵌入的 URI。当不为 None 时，此回调优先于 [`MarkdownOptions.export_images_as_base64`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/export_images_as_base64/)。 |

### 另见
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
