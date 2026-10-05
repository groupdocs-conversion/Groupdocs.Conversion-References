---
title: "with_events मेथड"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "कनवर्ज़न लाइफ़साइकल इवेंट हैंडलर को एक ConversionEvents बैग पर पंजीकृत करता है जो कनवर्टर के जीवनकाल तक रहता है और प्रत्येक कनवर्ज़न रन पर ट्रिगर होता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

कनवर्टर के जीवनकाल तक रहने वाले एक [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) बैग पर रूपांतरण जीवनचक्र इवेंट हैंडलर्स को पंजीकृत करता है और प्रत्येक रूपांतरण रन पर ट्रिगर होते हैं।

यह उसी प्रवेश चरण पर स्थित है जैसा कि [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/) है। कई कॉल्स जमा होते हैं: वही आंतरिक बैग प्रत्येक `configure` कार्रवाई को पास किया जाता है, इसलिए पहले की कॉल्स में सेट किए गए हैंडलर तब तक रहते हैं जब तक बाद की कॉल द्वारा ओवरराइट न किए जाएँ।

```python
def with_events(self, configure):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | इवेंट्स बैग को बदलने वाली कार्रवाई। |

**Returns:** The source-selection stage so that `Load` may be chained.

### साथ ही देखें
* class [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/)
