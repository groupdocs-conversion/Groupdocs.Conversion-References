---
title: "FileCache"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "文件缓存行为。表示缓存存储在文件系统上"
type: docs
weight: 10
url: /zh/net/groupdocs.conversion.caching/filecache/
---
## FileCache class

文件缓存行为。表示缓存存储在文件系统上

```csharp
public sealed class FileCache : ICache
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [FileCache](filecache)(string) | 创建 FileCache 类的新实例 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetKeys](../../groupdocs.conversion.caching/filecache/getkeys)(string) | 返回所有匹配过滤器的键。 |
| [Set](../../groupdocs.conversion.caching/filecache/set)(string, object) | 将缓存条目插入缓存中。 |
| [TryGetValue](../../groupdocs.conversion.caching/filecache/trygetvalue)(string, out object) | 获取与此键关联的条目（如果存在）。 |

### 备注

**Learn more**

* More about caching and optimizing conversion process performance: [Caching conversion results](https://docs.groupdocs.com/display/conversionnet/Caching)

### 另见

* interface [ICache](../icache)
* namespace [GroupDocs.Conversion.Caching](../../groupdocs.conversion.caching)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
