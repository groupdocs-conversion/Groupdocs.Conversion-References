---
title: "طريقة get_hash_code"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يعمل كدالة التجزئة الافتراضية."
type: docs
url: /ar/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/
is_root: false
weight: 1040
---


## get_hash_code

يعمل كدالة التجزئة الافتراضية.

يتم تجزئة مكونات Array و list و dictionary بناءً على محتوياتها، بما يتطابق مع طريقة مقارنة المساواة لها، لذا فإن كائنين يُقارنان على أنهما متساويان سيُجَزّيان أيضًا بشكل متساوٍ ويمكن استخدامهما كمفاتيح للقاموس أو كعناصر في مجموعة.

هذا لا يمتد إلى مكوّن يكون من نوع آخر `System.Collections.IEnumerable`: يتم تجزئة مثل هذا المكوّن بالمرجع، وأي مكوّن يُعرض كمُكرّر كسول ينتج قيمة مختلفة في كل مرة يتم الوصول إليها، لذا فإن الكائن الذي يحمل هذا المكوّن لا يمكن استخدامه كمفتاح على الإطلاق. كما يتم مقارنة وتجزيء المجموعات المتداخلة بالمرجع بدلاً من التجزئة المتكررة.

النتيجة الأخرى هي أن تعديل مجموعة يكشفها كائن قيمة – إضافة إلى قائمة صفحات أو كتابة في مصفوفة اسم التخطيط – يغيّر تجزئة ذلك الكائن، وبالتالي يصبح المثال المخزن مسبقًا في حاوية التجزئة غير قابل للوصول. عالج كائن القيمة كأنه ثابت بمجرد استخدامه كمفتاح.

```python
def get_hash_code(self):
    ...
```

**Returns:** A hash code for the current object.

### انظر أيضًا
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)
