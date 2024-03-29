---
title: ConvertOptionsProvider
second_title: .NET API संदर्भ के लिए GroupDocs.Conversion
description: वशष्ट स्रत दस्तवेज़ के लए कन्वर्ट वकल्प प्रदन करने के लए प्रतनध क वर्णन करत है प्रतनध क प्रत्येक रूपंतरण से पहले बुलय जएग और वंछत लक्ष्य रूपंतरण के लए वशष्ट कन्वर्ट वकल्प प्रदन करने क मक प्रदन करेग प्रदन कए गए स्रत फ़इल नम और स्रत फ़इल के आधर पर नर्णय लय ज सकत है टइप.
type: docs
weight: 100
url: /hi/net/groupdocs.conversion.contracts/convertoptionsprovider/
---
## ConvertOptionsProvider delegate

विशिष्ट स्रोत दस्तावेज़ के लिए कन्वर्ट विकल्प प्रदान करने के लिए प्रतिनिधि का वर्णन करता है। प्रतिनिधि को प्रत्येक रूपांतरण से पहले बुलाया जाएगा और वांछित लक्ष्य रूपांतरण के लिए विशिष्ट कन्वर्ट विकल्प प्रदान करने का मौका प्रदान करेगा। प्रदान किए गए स्रोत फ़ाइल नाम और स्रोत फ़ाइल के आधार पर निर्णय लिया जा सकता है टाइप.

```csharp
public delegate ConvertOptions ConvertOptionsProvider(string sourceDocumentName, 
    FileType sourceType);
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceDocumentName | String | स्रोत फ़ाइल नाम |
| sourceType | FileType | स्रोत फ़ाइल प्रकार |

### प्रतिलाभ की मात्रा

अवश्य लौटाएं[`ConvertOptions`](../../groupdocs.conversion.options.convert/convertoptions) के रूपांतरण के लिए उपयोग किया जाना है[`स्रोत प्रकार`](../../groupdocs.conversion.filetypes/filetype) दस्तावेज़

### यह सभी देखें

* class [ConvertOptions](../../groupdocs.conversion.options.convert/convertoptions)
* class [FileType](../../groupdocs.conversion.filetypes/filetype)
* नाम स्थान [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* सभा [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
