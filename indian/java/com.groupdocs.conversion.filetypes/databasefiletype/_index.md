---
title: "DatabaseFileType"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "CAD दस्तावेज़ (Computer Aided Design) को परिभाषित करता है, जो 3D ग्राफ़िक्स फ़ाइल फ़ॉर्मेट के लिए उपयोग होते हैं और 2D या 3D डिज़ाइन शामिल कर सकते हैं।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.conversion.filetypes/databasefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DatabaseFileType extends FileType implements Serializable
```

CAD दस्तावेज़ (Computer Aided Design) को परिभाषित करता है जो 3d ग्राफ़िक्स फ़ाइल फ़ॉर्मेट के लिए उपयोग होते हैं और 2d या 3d डिज़ाइन शामिल कर सकते हैं।
निम्नलिखित प्रकार शामिल हैं:
[Nsf](../../com.groupdocs.conversion.filetypes/databasefiletype#Nsf),
[Log](../../com.groupdocs.conversion.filetypes/databasefiletype#Log),
[Sql](../../com.groupdocs.conversion.filetypes/databasefiletype#Sql),
CAD फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](../https://wiki.fileformat.com/cad).

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [DatabaseFileType()](#DatabaseFileType--) | सीरियलाइज़ेशन कंस्ट्रक्टर |
|
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [Nsf](#Nsf) | .nsf (Notes Storage Facility) एक्सटेंशन वाली फ़ाइल IBM Notes सॉफ़्टवेयर द्वारा उपयोग किया जाने वाला डेटाबेस फ़ाइल फ़ॉर्मेट है, जिसे पहले Lotus Notes के नाम से जाना जाता था। |
|
|  | [Log](#Log) | .log एक्सटेंशन वाली फ़ाइल टाइमस्टैम्प के साथ साधारण टेक्स्ट की सूची रखती है। |
|
|  | [Sql](#Sql) | .sql एक्सटेंशन वाली फ़ाइल एक स्ट्रक्चर्ड क्वेरी लैंग्वेज (SQL) फ़ाइल है जिसमें रिलेशनल डेटाबेस के साथ काम करने के लिए कोड होता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### DatabaseFileType() {#DatabaseFileType--}
```
public DatabaseFileType()
```


सीरियलाइज़ेशन कंस्ट्रक्टर


### Nsf {#Nsf}
```
public static final DatabaseFileType Nsf
```


.nsf (Notes Storage Facility) एक्सटेंशन वाली फ़ाइल IBM Notes सॉफ़्टवेयर द्वारा उपयोग किया जाने वाला डेटाबेस फ़ाइल फ़ॉर्मेट है, जिसे पहले Lotus Notes के नाम से जाना जाता था। यह विभिन्न प्रकार की वस्तुओं जैसे ईमेल, अपॉइंटमेंट, दस्तावेज़, फ़ॉर्म और व्यूज़ को संग्रहीत करने के लिए स्कीमा निर्धारित करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/database/nsf).


### Log {#Log}
```
public static final DatabaseFileType Log
```


.log एक्सटेंशन वाली फ़ाइल टाइमस्टैम्प के साथ साधारण टेक्स्ट की सूची रखती है। आमतौर पर, कुछ गतिविधियों के विवरण को सॉफ़्टवेयर या ऑपरेटिंग सिस्टम द्वारा लॉग किया जाता है ताकि डेवलपर्स या उपयोगकर्ता किसी विशेष समय अवधि में क्या हो रहा था, इसे ट्रैक कर सकें। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/database/log).


### Sql {#Sql}
```
public static final DatabaseFileType Sql
```


.sql एक्सटेंशन वाली फ़ाइल एक स्ट्रक्चर्ड क्वेरी लैंग्वेज (SQL) फ़ाइल है जिसमें रिलेशनल डेटाबेस के साथ काम करने के लिए कोड होता है। यह डेटाबेस पर CRUD (Create, Read, Update, and Delete) ऑपरेशनों के लिए SQL स्टेटमेंट लिखने में उपयोग होती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/database/sql).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


स्रोत फ़ाइल प्रकार के लिए डिफ़ॉल्ट लोड विकल्प तैयार किए गए


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
