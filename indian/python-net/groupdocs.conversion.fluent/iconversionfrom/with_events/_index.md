---
title: "with_events मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "कनवर्टर के जीवनकाल के दौरान मौजूद ConversionEvents बैग पर रूपांतरण जीवनचक्र इवेंट हैंडलर पंजीकृत करें, जो प्रत्येक रूपांतरण रन पर सक्रिय होते हैं।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionfrom/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

परिवर्तन जीवनचक्र इवेंट हैंडलर्स को एक [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) बैग पर पंजीकृत करें जो कनवर्टर के जीवनकाल तक रहता है और प्रत्येक परिवर्तन रन पर ट्रिगर होता है।

[`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/) से पहले या बाद में कॉल किया जा सकता है।
एकाधिक कॉलें संचित होती हैं: वही आंतरिक बैग प्रत्येक `configure` एक्शन को पास किया जाता है, इसलिए पहले की कॉलों में सेट किए गए हैंडलर तब तक बने रहते हैं जब तक बाद की कॉल द्वारा ओवरराइट न किया जाए।

```python
def with_events(self, configure):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | इवेंट्स बैग को बदलने वाली कार्रवाई। |

**Returns:** This stage so that further entry-stage calls or `Load` may be chained.

### साथ ही देखें
* class [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/)
