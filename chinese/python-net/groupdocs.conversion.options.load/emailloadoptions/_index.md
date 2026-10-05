---
title: "EmailLoadOptions 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "提供加载 Email 文档的选项。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.load/emailloadoptions/
is_root: false
weight: 130
---


## EmailLoadOptions class

提供加载 Email 文档的选项。

EmailLoadOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/__init__/) | 初始化 [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/) 类的新实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/clone/) | 克隆当前实例。 |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | 确定两个对象实例是否相等。 (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | 用作默认的哈希函数。 (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### 属性
| 属性 | 描述 |
| :- | :- |
| [attachment_icons](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/attachment_icons/) | 附件图标列表，可自定义以为不同文件类型提供特定图标。 |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/convert_owned/) | 该属性实现 [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/)。默认值为 True。 |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/convert_owner/) | convert_owner 属性实现 [`IDocumentsContainerLoadOptions.convert_owner`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owner/)。默认值为 True。 |
| [custom_css_style](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/custom_css_style/) | 自定义 CSS 样式，实现 [`ICustomCssStyleOptions.custom_css_style`](/conversion/python-net/groupdocs.conversion.options.load/icustomcssstyleoptions/custom_css_style/)。 |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/default_font/) | 电子邮件文档的默认字体。如果缺少所需字体，将使用此字体。 |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/depth/) | 文档容器加载选项的深度。 |
| [display_attachments](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_attachments/) | 在标题中显示或隐藏附件的选项。默认：True。 |
| [display_bcc_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_bcc_email_address/) | 显示或隐藏 Bcc 电子邮件地址的选项。默认：False。 |
| [display_cc_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_cc_email_address/) | 显示或隐藏 \"Cc\" 电子邮件地址的选项，默认值为 False。 |
| [display_email_addresses](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_email_addresses/) | 控制是否在名称旁显示电子邮件地址的选项。默认值为 True。 |
| [display_from_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_from_email_address/) | 显示或隐藏 \"from\" 电子邮件地址的选项。默认：True。 |
| [display_header](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_header/) | 显示或隐藏电子邮件标题的选项。默认：True。 |
| [display_sent](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_sent/) | 显示或隐藏标题中发送的日期/时间的选项。默认值为 True。 |
| [display_subject](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_subject/) | 显示或隐藏标题中主题的选项。默认值为 True。 |
| [display_to_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_to_email_address/) | 显示或隐藏 \"to\" 电子邮件地址的选项。默认：True。 |
| [field_text_map](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/field_text_map/) | 电子邮件消息 [`EmailField`](/conversion/python-net/groupdocs.conversion.options.load/emailfield/) 与字段文本表示之间的映射。 |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/font_substitutes/) | 字体替代列表。 |
| [format](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/format/) | 输入文档的文件类型。 |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/margin_settings/) | 边距设置。 |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/orientation_settings/) | 方向设置。 |
| [page_layout_options](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/page_layout_options/) | 该属性实现了 [`IPageLayoutOptions.page_layout_options`](/conversion/python-net/groupdocs.conversion.options.load/ipagelayoutoptions/page_layout_options/)。 |
| [preserve_original_date](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/preserve_original_date/) | 该属性决定在保存时是否保留邮件消息中的原始日期标题字符串。默认值为 True。 |
| [resource_loading_timeout](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/resource_loading_timeout/) | 加载外部资源的超时时间。 |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/size_settings/) | 电子邮件加载操作的页面大小设置。 |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/skip_external_resources/) | 实现了 [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/skip_external_resources/) 的属性。 |
| [time_zone_offset](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/time_zone_offset/) | 消息日期的协调世界时 (UTC) 偏移量。 |
| [use_default_attachment_icons](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/use_default_attachment_icons/) | 指示是否使用默认附件图标的标志（默认值为 True）。 |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/whitelisted_resources/) | 该属性实现了 [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/)。 |

### 另见
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
