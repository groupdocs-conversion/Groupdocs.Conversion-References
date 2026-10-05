---
title: "get_hash_code 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "用作默认哈希函数。"
type: docs
url: /zh/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/
is_root: false
weight: 1040
---


## get_hash_code

用作默认哈希函数。

数组、列表和字典组件会根据其内容进行哈希，与相等性比较的方式保持一致，因此两个相等的对象也会产生相同的哈希值，且可以用作字典键或集合成员。

这并不适用于某些其他 `System.Collections.IEnumerable` 组件：此类组件按引用进行哈希，而作为惰性迭代器暴露的组件在每次访问时会产生不同的值，因此携带它的对象根本无法用作键。嵌套集合同样是按引用比较和哈希，而不是递归进行。

另一个后果是，对值对象公开的集合进行变更——例如向页面列表添加元素，或向布局名称数组写入——会改变该对象的哈希值，从而导致已存储在哈希容器中的实例变得不可访问。值对象一旦被用作键，就应视为不可变。

```python
def get_hash_code(self):
    ...
```

**Returns:** A hash code for the current object.

### 另见
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)
