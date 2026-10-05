---
title: "`listener` प्रॉपर्टी"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "कनवर्टर लिस्नर कार्यान्वयन जिसका उपयोग रूपांतरण स्थिति और प्रगति की निगरानी के लिए किया जाता है, जिसमें इसके Started, Progress, और Completed कॉलबैक ConversionEvents.onconversionstarted को अग्रेषित किए जाते हैं…"
type: docs
url: /hi/python-net/groupdocs.conversion/convertersettings/listener/
is_root: false
weight: 2030
---


## listener property

परिवर्तन स्थिति और प्रगति की निगरानी के लिए उपयोग किया जाने वाला कनवर्टर लिस्नर कार्यान्वयन, जिसके Started, Progress, और Completed कॉलबैक को [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), और [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) पर अग्रेषित किया जाता है, जब [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) का निर्माण किया जाता है।

### Definition:
```python
@property
def listener(self):
    ...
@listener.setter
def listener(self, value):
    ...
```

### साथ ही देखें
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
