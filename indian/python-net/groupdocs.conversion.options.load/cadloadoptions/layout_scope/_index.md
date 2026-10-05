---
title: "layout_scope प्रॉपर्टी"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "वह लेआउट स्कोप जो निर्धारित करता है कि कौन से ड्रॉइंग स्पेस परिवर्तित होते हैं।"
type: docs
url: /hi/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/
is_root: false
weight: 2070
---


## layout_scope property

वह लेआउट स्कोप जो निर्धारित करता है कि कौन से रेखांकन स्थान परिवर्तित होते हैं। डिफ़ॉल्ट रूप से [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/) पर सेट है, जो परिवर्तन को प्रतिबंधित नहीं करता। जब [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) प्रदान किया जाता है, तो इसे अनदेखा किया जाता है, क्योंकि स्पष्ट लेआउट नाम हमेशा जीतते हैं। एक `None` मान को [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/) के रूप में माना जाता है।

यदि स्कोप ड्रॉइंग द्वारा प्रदान की गई किसी भी शीट को नहीं चुनता है, तो रूपांतरण `InvalidLoadOptionsException` के साथ विफल हो जाता है, जो स्कोप और उपलब्ध शीट्स का नाम बताता है, बजाय बाहर रखे गए स्पेसेस को रेंडर करने के। एक ड्रॉइंग जो बिल्कुल भी शीट नहीं देती, वह अप्रभावित रहती है और फिर भी एक इकाई के रूप में परिवर्तित होती है। PDF/UA-1 में रूपांतरण करते समय इसे मान्यता नहीं दी जाती, जैसा कि [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) पर दिया गया कारण है।

### Definition:
```python
@property
def layout_scope(self):
    ...
@layout_scope.setter
def layout_scope(self, value):
    ...
```

### साथ ही देखें
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
