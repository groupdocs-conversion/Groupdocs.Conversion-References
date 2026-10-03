---
title: "ICache"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "定义存储渲染文档和文档资源缓存所需的方法。"
type: docs
weight: 20
url: /zh/net/groupdocs.conversion.caching/icache/
---
## ICache interface

定义存储渲染文档和文档资源缓存所需的方法。

```csharp
public interface ICache
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetKeys](../../groupdocs.conversion.caching/icache/getkeys)(string) | 返回所有匹配过滤器的键。 |
| [Set](../../groupdocs.conversion.caching/icache/set)(string, object) | 将缓存条目插入缓存中。 |
| [TryGetValue](../../groupdocs.conversion.caching/icache/trygetvalue)(string, out object) | 获取与此键关联的条目（如果存在）。 |

### 另见

* namespace [GroupDocs.Conversion.Caching](../../groupdocs.conversion.caching)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
