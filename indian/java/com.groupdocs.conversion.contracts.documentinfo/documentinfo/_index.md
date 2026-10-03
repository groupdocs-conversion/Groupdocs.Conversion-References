---
title: "DocumentInfo"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "बहुरूपीय दस्तावेज़ जानकारी प्राप्त करने के लिए बेस कार्यान्वयन प्रदान करता है"
type: docs
weight: 16
url: /hi/java/com.groupdocs.conversion.contracts.documentinfo/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.documentinfo.IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo)
```
public abstract class DocumentInfo implements IDocumentInfo
```

बहुरूपीय दस्तावेज़ जानकारी प्राप्त करने के लिए बेस कार्यान्वयन प्रदान करता है

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getPropertyNames()](#getPropertyNames--) | {@inheritDoc} |
|
|  | [getProperty(String propertyName)](#getProperty-java.lang.String-) | {@inheritDoc} |
|
|  | [getPagesCount()](#getPagesCount--) | {@inheritDoc} |
|
|  | [getFormat()](#getFormat--) | {@inheritDoc} |
|
|  | [getSize()](#getSize--) | {@inheritDoc} |
|
|  | [getCreationDate()](#getCreationDate--) | {@inheritDoc} |
|
### getPropertyNames() {#getPropertyNames--}
```
public List<String> getPropertyNames()
```


वर्तमान दस्तावेज़ जानकारी के लिए प्राप्त किए जा सकने वाले सभी गुणों की सूची


**Returns:**
java.util.List<java.lang.String>
### getProperty(String propertyName) {#getProperty-java.lang.String-}
```
public String getProperty(String propertyName)
```


कुंजी के रूप में प्रदान किए गए गुण का मान प्राप्त करें


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propertyName | java.lang.String |  |

**Returns:**
java.lang.String
### getPagesCount() {#getPagesCount--}
```
public int getPagesCount()
```


दस्तावेज़ पृष्ठों की गिनती।


**Returns:**
int
### getFormat() {#getFormat--}
```
public String getFormat()
```


दस्तावेज़ प्रारूप


**Returns:**
java.lang.String
### getSize() {#getSize--}
```
public long getSize()
```


बाइट्स में दस्तावेज़ आकार


**Returns:**
long
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


दस्तावेज़ निर्माण तिथि


**Returns:**
java.util.Date
