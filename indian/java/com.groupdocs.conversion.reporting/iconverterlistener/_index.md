---
title: "IConverterListener"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "कनवर्टर लिसनिंग करने के लिए उपयोग की जाने वाली विधियों को परिभाषित करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.conversion.reporting/iconverterlistener/
---```
public interface IConverterListener
```

Defines the methods that are used to perform converter listening. **Learn more** More about monitoring conversion progress: [Listening to conversion process events](../https://docs.groupdocs.com/display/conversionnet/Listening)

## Methods

| Method | Description |
| --- | --- |
| [started()](#started--) | This method will be called as soon as actual conversion started.
 |
| [progress(byte current)](#progress-byte-) | This method will be called each time when conversion progress changed.
 |
| [completed()](#completed--) | This method will be called as soon as conversion completed.
 |
### started() {#started--}
```
public abstract void started()
```


This method will be called as soon as actual conversion started.


### progress(byte current) {#progress-byte-}
```
public abstract void progress(byte current)
```


This method will be called each time when conversion progress changed.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| current | byte | Current conversion progress in percentage
 |

### completed() {#completed--}
```
public abstract void completed()
```


This method will be called as soon as conversion completed.


