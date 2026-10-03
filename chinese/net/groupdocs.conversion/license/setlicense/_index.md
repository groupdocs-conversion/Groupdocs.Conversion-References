---
title: "SetLicense"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "为组件授权。"
type: docs
weight: 30
url: /zh/net/groupdocs.conversion/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

为组件授权。

```csharp
public void SetLicense(Stream licenseStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| licenseStream | Stream | 许可证流。 |

### 示例

以下示例演示如何通过许可证文件的 Stream 设置许可证。

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
    lic.SetLicense(licenseStream);
}
```

### 另见

* class [License](../../license)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## SetLicense(string) {#setlicense_1}

为组件授权。

```csharp
public void SetLicense(string licensePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| licensePath | String | 许可证路径。 |

### 示例

以下示例演示如何通过许可证文件的路径设置许可证。

```csharp
string licensePath = "GroupDocs.Conversion.lic";
GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
lic.SetLicense(licensePath);
```

### 另见

* class [License](../../license)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
