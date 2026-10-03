---
title: "GetHashCode"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "充当默认的哈希函数。"
type: docs
weight: 20
url: /zh/net/groupdocs.conversion.contracts/valueobject/gethashcode/
---
## ValueObject.GetHashCode method

充当默认的哈希函数。

```csharp
public override int GetHashCode()
```

### 返回值

当前对象的哈希码。

### 备注

Array、list 和 dictionary 组件通过其内容进行哈希，与相等比较的方式相匹配，因此两个相等的对象也会产生相同的哈希值，可用作字典键或集合成员。这 NOT 适用于其他 IEnumerable 类型的组件：此类组件按引用进行哈希，而作为惰性迭代器暴露的组件在每次访问时会产生不同的值，因此携带它的对象根本无法用作键。嵌套集合同样是按引用比较和哈希，而不是递归。另一个后果是，修改值对象所暴露的集合——例如向页面列表添加元素，或向布局名称数组写入——会改变该对象的哈希值，使已存储在哈希容器中的实例变得不可达。值对象在被用作键后应视为不可变。

### 另见

* class [ValueObject](../../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
