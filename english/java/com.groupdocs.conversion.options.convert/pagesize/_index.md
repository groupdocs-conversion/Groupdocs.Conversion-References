---
title: PageSize
second_title: GroupDocs.Conversion for Java API Reference
description: 
type: docs
weight: 59
url: /java/com.groupdocs.conversion.options.convert/pagesize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IPageSize](../../com.groupdocs.conversion.options.convert/ipagesize)
```
public enum PageSize extends Enum<PageSize> implements IPageSize
```
## Fields

| Field | Description |
| --- | --- |
| [A3](#A3) |  |
| [A4](#A4) |  |
| [A5](#A5) |  |
| [B4](#B4) |  |
| [B5](#B5) |  |
| [CUSTOM](#CUSTOM) |  |
| [ENVELOPE_DL](#ENVELOPE-DL) |  |
| [EXECUTIVE](#EXECUTIVE) |  |
| [FOLIO](#FOLIO) |  |
| [LEDGER](#LEDGER) |  |
| [LEGAL](#LEGAL) |  |
| [LETTER](#LETTER) |  |
| [PAPER_10_X_14](#PAPER-10-X-14) |  |
| [PAPER_11_X_17](#PAPER-11-X-17) |  |
| [QUARTO](#QUARTO) |  |
| [STATEMENT](#STATEMENT) |  |
| [TABLOID](#TABLOID) |  |
| [UNSET](#UNSET) |  |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [createCustom(float width, float height)](#createCustom-float-float-) |  |
| [getKey()](#getKey--) |  |
| [getName()](#getName--) |  |
| [getWidth()](#getWidth--) |  |
| [getHeight()](#getHeight--) |  |
| [pointsToPixels(float points, int dpi)](#pointsToPixels-float-int-) |  |
| [pixelsToPoints(int pixels, int dpi)](#pixelsToPoints-int-int-) |  |
### A3 {#A3}
```
public static final PageSize A3
```


### A4 {#A4}
```
public static final PageSize A4
```


### A5 {#A5}
```
public static final PageSize A5
```


### B4 {#B4}
```
public static final PageSize B4
```


### B5 {#B5}
```
public static final PageSize B5
```


### CUSTOM {#CUSTOM}
```
public static final PageSize CUSTOM
```


### ENVELOPE_DL {#ENVELOPE-DL}
```
public static final PageSize ENVELOPE_DL
```


### EXECUTIVE {#EXECUTIVE}
```
public static final PageSize EXECUTIVE
```


### FOLIO {#FOLIO}
```
public static final PageSize FOLIO
```


### LEDGER {#LEDGER}
```
public static final PageSize LEDGER
```


### LEGAL {#LEGAL}
```
public static final PageSize LEGAL
```


### LETTER {#LETTER}
```
public static final PageSize LETTER
```


### PAPER_10_X_14 {#PAPER-10-X-14}
```
public static final PageSize PAPER_10_X_14
```


### PAPER_11_X_17 {#PAPER-11-X-17}
```
public static final PageSize PAPER_11_X_17
```


### QUARTO {#QUARTO}
```
public static final PageSize QUARTO
```


### STATEMENT {#STATEMENT}
```
public static final PageSize STATEMENT
```


### TABLOID {#TABLOID}
```
public static final PageSize TABLOID
```


### UNSET {#UNSET}
```
public static final PageSize UNSET
```


### values() {#values--}
```
public static PageSize[] values()
```




**Returns:**
com.groupdocs.conversion.options.convert.PageSize[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PageSize valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### createCustom(float width, float height) {#createCustom-float-float-}
```
public static PageSize.PageSizeCustom createCustom(float width, float height)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | float |  |
| height | float |  |

**Returns:**
[PageSizeCustom](../../com.groupdocs.conversion.options.convert/pagesizecustom)
### getKey() {#getKey--}
```
public String getKey()
```




**Returns:**
java.lang.String
### getName() {#getName--}
```
public String getName()
```




**Returns:**
java.lang.String
### getWidth() {#getWidth--}
```
public double getWidth()
```




**Returns:**
double
### getHeight() {#getHeight--}
```
public double getHeight()
```




**Returns:**
double
### pointsToPixels(float points, int dpi) {#pointsToPixels-float-int-}
```
public static int pointsToPixels(float points, int dpi)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | float |  |
| dpi | int |  |

**Returns:**
int
### pixelsToPoints(int pixels, int dpi) {#pixelsToPoints-int-int-}
```
public static float pixelsToPoints(int pixels, int dpi)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixels | int |  |
| dpi | int |  |

**Returns:**
float
