---
title: SetLicense
second_title: .NET API संदर्भ के लिए GroupDocs.Conversion
description: घटक क लइसेंस देत है
type: docs
weight: 20
url: /hi/net/groupdocs.conversion/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

घटक को लाइसेंस देता है।

```csharp
public void SetLicense(Stream licenseStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| licenseStream | Stream | लाइसेंस धारा। |

### उदाहरण

निम्न उदाहरण दर्शाता है कि लाइसेंस लाइसेंस फ़ाइल की पासिंग स्ट्रीम कैसे सेट करें।

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
    lic.SetLicense(licenseStream);
}
```

### यह सभी देखें

* class [License](../../license)
* नाम स्थान [GroupDocs.Conversion](../../license)
* सभा [GroupDocs.Conversion](../../../)

---

## SetLicense(string) {#setlicense_1}

घटक को लाइसेंस देता है।

```csharp
public void SetLicense(string licensePath)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| licensePath | String | लाइसेंस पथ। |

### उदाहरण

निम्न उदाहरण दर्शाता है कि कैसे एक लाइसेंस सेट करना है लाइसेंस फ़ाइल के पथ को पार करना।

```csharp
string licensePath = "GroupDocs.Conversion.lic";
GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
lic.SetLicense(licensePath);
```

### यह सभी देखें

* class [License](../../license)
* नाम स्थान [GroupDocs.Conversion](../../license)
* सभा [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->