---
title: get_hash_code method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Serves as the default hash function."
type: docs
url: /python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/
is_root: false
weight: 1040
---


## get_hash_code

Serves as the default hash function.

Array, list and dictionary components are hashed by their contents, matching how equality compares them, so two objects that compare equal also hash equally and can be used as dictionary keys or set members.

This does NOT extend to a component that is some other `System.Collections.IEnumerable`: such a component is hashed by reference, and one exposed as a lazy iterator yields a different value on every access, so an object carrying it is not usable as a key at all. Nested collections are likewise compared and hashed by reference rather than recursively.

The other consequence is that mutating a collection a value object exposes - adding to a page list, or writing into a layout-name array - changes that object's hash, so an instance already stored in a hash container becomes unreachable. Treat a value object as frozen once it has been used as a key.

```python
def get_hash_code(self):
    ...
```

**Returns:** A hash code for the current object.

### See Also
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)
