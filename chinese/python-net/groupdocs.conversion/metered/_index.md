---
title: "Metered 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "管理计量（按使用付费）许可。"
type: docs
url: /zh/python-net/groupdocs.conversion/metered/
is_root: false
weight: 210
---


## Metered class

管理计量（按使用付费）许可。

Metered 许可证根据实际消耗计费（通常是页面或
处理的文档）。在此处一次性设置公钥/私钥对：
应用程序启动时；包装器会将使用情况报告回 GroupDocs
后台的许可证服务器。

Metered 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [get_consumption_credit](/conversion/python-net/groupdocs.conversion/metered/get_consumption_credit/) | 返回当前密钥的剩余计量额度。 |
| [get_consumption_quantity](/conversion/python-net/groupdocs.conversion/metered/get_consumption_quantity/) | 返回迄今为止消耗的总计量数量。 |
| [set_metered_key](/conversion/python-net/groupdocs.conversion/metered/set_metered_key/#public_key-private_key) | 使用给定的公钥/私钥对激活计量计费。 |

### 另见
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
