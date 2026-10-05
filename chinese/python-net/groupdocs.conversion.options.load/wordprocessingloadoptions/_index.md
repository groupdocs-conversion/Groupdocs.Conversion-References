---
title: "WordProcessingLoadOptions 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "提供加载 WordProcessing 文档的选项。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/
is_root: false
weight: 580
---


## WordProcessingLoadOptions class

提供加载 WordProcessing 文档的选项。

字体处理管道：

阶段 1 - 字体替换（文档加载期间）:
- Handles missing/unavailable fonts using FontSubstitutes, DefaultFont, and system substitution
- Processing order: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

阶段 2 - 字体替换（文档加载后）:
- Modifies any existing fonts in the loaded document using FontReplacements
- Applied after all font substitution is complete

WordProcessingLoadOptions 类型公开以下成员:

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/__init__/) | 初始化一个新的 [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/) 实例。 |

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
| [auto_detect_rtl_direction](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/) | auto_detect_rtl_direction 属性决定在转换之前，段落和运行的主要从右到左文本是否会修复其双向标志。 |
| [bookmark_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/bookmark_options/) | 书签选项。 |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_built_in_document_properties/) | 标志指示在加载 Word 处理文档时是否清除内置文档属性。 |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_custom_document_properties/) | ClearCustomDocumentProperties 属性。 |
| [comment_display_mode](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/comment_display_mode/) | 注释显示模式指定应如何在输出文档中显示注释。默认是 `ShowInBalloons`。 |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owned/) | 该属性实现了 [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/)。默认值为 False。 |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owner/) | convert_owner 标志指示是否转换文档所有者。默认值为 True。 |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/default_font/) | WordProcessing 文档的默认字体。 |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/depth/) | 文档容器加载选项的深度。默认值为 1。 |
| [embed_true_type_fonts](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/embed_true_type_fonts/) | embed_true_type_fonts 属性决定是否在输出文档中嵌入 TrueType 字体。默认值为 True。 |
| [font_config_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_config_substitution_enabled/) | 该属性基于系统 FontConfig 启用缺失字体的自动替代。默认值为 False。 |
| [font_info_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/) | 该标志基于文档中的 FontInfo 启用缺失字体的自动替代。默认值：False。 |
| [font_name_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/) | 该属性指示是否基于字体名称自动替代缺失的字体。默认值：False。 |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/) | 转换 WordProcessing 文档时使用的字体替代。 |
| [font_transformations](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_transformations/) | 在文档加载和字体替代完成后应用的字体转换，允许修改文档中的任何字体，包括成功加载的字体。 |
| [format](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/format/) | 输入文档的文件类型。 |
| [hide_word_tracked_changes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hide_word_tracked_changes/) | hide_word_tracked_changes 属性隐藏 Word 文档的标记和修订更改。 |
| [hyphenation_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenation_options/) | WordProcessing 文档的连字符选项。 |
| [keep_date_field_original_value](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/keep_date_field_original_value/) | keep_date_field_original_value 属性决定是否保留日期字段的原始值。默认值为 False。 |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/margin_settings/) | 边距设置。 |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/page_numbering/) | 转换后文档的页码生成标志（默认：False）。 |
| [password](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/password/) | 用于解除受保护文档的密码。 |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_document_structure/) | 指示在转换为 PDF 时是否应保留文档结构的标志（默认值为 False）。 |
| [preserve_form_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_form_fields/) | 该属性指示在生成的 PDF 中是否将 Microsoft Word 表单字段保留为表单字段，或转换为文本。默认值为 False。 |
| [show_full_commenter_name](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/show_full_commenter_name/) | 当设置为 True 时，评论中会显示完整的评论者姓名。默认值为 False。 |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/size_settings/) | WordProcessing 文档的尺寸设置（[`IPageSizeOptions`](/conversion/python-net/groupdocs.conversion.options/ipagesizeoptions/)）。 |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/skip_external_resources/) | 确定在加载文档时是否跳过外部资源的标志。 |
| [update_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_fields/) | 加载后更新字段的选项。默认：False。 |
| [update_page_layout](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_page_layout/) | 加载后页面布局会被更新。默认：False。 |
| [use_text_shaper](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/use_text_shaper/) | 该属性指示是否使用文本整形器以获得更好的字距显示。默认值为 False。 |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/whitelisted_resources/) | 用于加载外部内容的白名单资源，实现了 [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/)。 |

### 示例

```python
from groupdocs.conversion.options.load import WordProcessingLoadOptions

load_options = WordProcessingLoadOptions()
load_options.password = "secret"
```

### Guides
使用 `WordProcessingLoadOptions` 的任务指南：

* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### 另见
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
