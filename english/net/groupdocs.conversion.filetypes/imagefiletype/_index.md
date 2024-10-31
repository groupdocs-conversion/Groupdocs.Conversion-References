---
title: ImageFileType
second_title: GroupDocs.Conversion for .NET API Reference
description: Defines image documents. Includes the following file types Ai./imagefiletype/ai Bmp./imagefiletype/bmp Cdr./imagefiletype/cdr Cmx./imagefiletype/cmx Dcm./imagefiletype/dcm Dib./imagefiletype/dib DjVu./imagefiletype/djvu Dng./imagefiletype/dng Emf./imagefiletype/emf Emz./imagefiletype/emz Gif./imagefiletype/gif Heic./imagefiletype/heicIco./imagefiletype/ico J2c./imagefiletype/j2c J2k./imagefiletype/j2k Jls./imagefiletype/jls Jp2./imagefiletype/jp2 Jpc./imagefiletype/jpc Jfif./imagefiletype/jfif. Jpeg./imagefiletype/jpeg Jpf./imagefiletype/jpf Jpg./imagefiletype/jpg Jpm./imagefiletype/jpm Jpx./imagefiletype/jpx Odg./imagefiletype/odg Png./imagefiletype/png Psd./imagefiletype/psd Svgz./imagefiletype/svgz Tif./imagefiletype/tif Tiff./imagefiletype/tiff Webp./imagefiletype/webp Wmf./imagefiletype/wmf. Wmz./imagefiletype/wmz. Learn more about Image formats herehttps//wiki.fileformat.com/image.
type: docs
weight: 990
url: /net/groupdocs.conversion.filetypes/imagefiletype/
---
## ImageFileType class

Defines image documents. Includes the following file types: [`Ai`](./ai), [`Bmp`](./bmp), [`Cdr`](./cdr), [`Cmx`](./cmx), [`Dcm`](./dcm), [`Dib`](./dib), [`DjVu`](./djvu), [`Dng`](./dng), [`Emf`](./emf), [`Emz`](./emz), [`Gif`](./gif), [`Heic`](./heic)[`Ico`](./ico), [`J2c`](./j2c), [`J2k`](./j2k), [`Jls`](./jls), [`Jp2`](./jp2), [`Jpc`](./jpc), [`Jfif`](./jfif). [`Jpeg`](./jpeg), [`Jpf`](./jpf), [`Jpg`](./jpg), [`Jpm`](./jpm), [`Jpx`](./jpx), [`Odg`](./odg), [`Png`](./png), [`Psd`](./psd), [`Svgz`](./svgz), [`Tif`](./tif), [`Tiff`](./tiff), [`Webp`](./webp), [`Wmf`](./wmf). [`Wmz`](./wmz). Learn more about Image formats [here](https://wiki.fileformat.com/image).

```csharp
public sealed class ImageFileType : FileType
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageFileType](imagefiletype)() | Serialization constructor |

## Properties

| Name | Description |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | File type description |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | The file extension |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | The file family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | The file format |
| [IsRaster](../../groupdocs.conversion.filetypes/imagefiletype/israster) { get; } | Defines if the image is raster |

## Methods

| Name | Description |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compares current object to other. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implements [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determines whether two object instances are equal. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Serves as the default hash function. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | String representation |

## Fields

| Name | Description |
| --- | --- |
| static readonly [Ai](../../groupdocs.conversion.filetypes/imagefiletype/ai) | AI, Adobe Illustrator Artwork, represents single-page vector-based drawings in either the EPS or PDF formats. |
| static readonly [Bmp](../../groupdocs.conversion.filetypes/imagefiletype/bmp) | BMP represent Bitmap Image files that are used to store bitmap digital images. These images are independent of graphics adapter and are also called device independent bitmap (DIB) file format. Learn more about this file format [here](https://wiki.fileformat.com/image/bmp). |
| static readonly [Cdr](../../groupdocs.conversion.filetypes/imagefiletype/cdr) | A CDR file is a vector drawing image file that is natively created with CorelDRAW for storing digital image encoded and compressed. Such a drawing file contains text, lines, shapes, images, colours and effects for vector representation of image contents. Learn more about this file format [here](https://wiki.fileformat.com/image/cdr). |
| static readonly [Cmx](../../groupdocs.conversion.filetypes/imagefiletype/cmx) | Files with CMX extension are Corel Exchange image file format that is used as presentation by CorelSuite applications. Learn more about this file format [here](https://wiki.fileformat.com/image/cmx). |
| static readonly [Dcm](../../groupdocs.conversion.filetypes/imagefiletype/dcm) | Files with .DCM extension represent digital image which stores medical information of patients such as MRIs, CT scans and ultrasound images. Learn more about this file format [here](https://wiki.fileformat.com/image/dcm). |
| static readonly [Dib](../../groupdocs.conversion.filetypes/imagefiletype/dib) | DIB (Device Independent Bitmap) file is a raster image file that is similar in structure to the standard Bitmap files (BMP) but has a different header. Learn more about this file format [here](https://wiki.fileformat.com/image/dib). |
| static readonly [Dicom](../../groupdocs.conversion.filetypes/imagefiletype/dicom) | Files with .DICOM extension represent digital image which stores medical information of patients such as MRIs, CT scans and ultrasound images. Learn more about this file format [here](https://wiki.fileformat.com/image/dicom). |
| static readonly [DjVu](../../groupdocs.conversion.filetypes/imagefiletype/djvu) | DjVu is a graphics file format intended for scanned documents and books especially those which contain the combination of text, drawings, images and photographs. Learn more about this file format [here](https://wiki.fileformat.com/image/djvu). |
| static readonly [Dng](../../groupdocs.conversion.filetypes/imagefiletype/dng) | DNG is a digital camera image format used for the storage of raw files. It has been developed by Adobe in September 2004. It was basically developed for digital photography. Learn more about this file format [here](https://wiki.fileformat.com/image/dng). |
| static readonly [Emf](../../groupdocs.conversion.filetypes/imagefiletype/emf) | Enhanced metafile format (EMF) stores graphical images device-independently. Metafiles of EMF comprises of variable-length records in chronological order that can render the stored image after parsing on any output device. Learn more about this file format [here](https://wiki.fileformat.com/image/emf). |
| static readonly [Emz](../../groupdocs.conversion.filetypes/imagefiletype/emz) | An EMZ file is actually a compressed version of a Microsoft EMF file. This allows for easier distribution of the file online. When an EMF file is compressed using the .GZIP compression algorithm, it is then given the .emz file extension. |
| static readonly [Fodg](../../groupdocs.conversion.filetypes/imagefiletype/fodg) | FODG is a uncompressed XML-format file used for storing OpenDocument text data. FODG extension is associated with open source office productivity suites Libre Office and OpenOffice.org. |
| static readonly [Gif](../../groupdocs.conversion.filetypes/imagefiletype/gif) | A GIF or Graphical Interchange Format is a type of highly compressed image. For each image GIF typically allow up to 8 bits per pixel and up to 256 colours are allowed across the image. Learn more about this file format [here](https://wiki.fileformat.com/image/gif). |
| static readonly [Heic](../../groupdocs.conversion.filetypes/imagefiletype/heic) | An HEIC file is a High-Efficiency Container Image file format that can store multiple images as a collection in a single file. The format was adopted by Apple as variant of the HEIF with the launch of iOS 11. Learn more about this file format [here](https://docs.fileformat.com/image/heic/). |
| static readonly [Ico](../../groupdocs.conversion.filetypes/imagefiletype/ico) | Files with ICO extension are image file types used as icon for representation of an application on Microsoft Windows. Learn more about this file format [here](https://wiki.fileformat.com/image/ico). |
| static readonly [J2c](../../groupdocs.conversion.filetypes/imagefiletype/j2c) | J2c document format |
| static readonly [J2k](../../groupdocs.conversion.filetypes/imagefiletype/j2k) | J2K file is an image that is compressed using the wavelet compression instead of DCT compression. Learn more about this file format [here](https://wiki.fileformat.com/image/j2k). |
| static readonly [Jfif](../../groupdocs.conversion.filetypes/imagefiletype/jfif) | JFIF (JPEG File Interchange Format (JFIF)) is an image format file that uses the .jfif extension. JFIF builds over JIF (JPEG Interchange Format) by reducing complexity and solving its limitations. Learn more about this file format [here](https://docs.fileformat.com/image/jfif/). |
| static readonly [Jls](../../groupdocs.conversion.filetypes/imagefiletype/jls) | Jls document format |
| static readonly [Jp2](../../groupdocs.conversion.filetypes/imagefiletype/jp2) | JPEG 2000 (JP2) is an image coding system and state-of-the-art image compression standard. Learn more about this file format [here](https://wiki.fileformat.com/image/jp2). |
| static readonly [Jpc](../../groupdocs.conversion.filetypes/imagefiletype/jpc) | Jpc document format |
| static readonly [Jpeg](../../groupdocs.conversion.filetypes/imagefiletype/jpeg) | A JPEG is a type of image format that is saved using the method of lossy compression. The output image, as result of compression, is a trade-off between storage size and image quality. Learn more about this file format [here](https://wiki.fileformat.com/image/jpeg). |
| static readonly [Jpf](../../groupdocs.conversion.filetypes/imagefiletype/jpf) | Jpf document format |
| static readonly [Jpg](../../groupdocs.conversion.filetypes/imagefiletype/jpg) | A JPG is a type of image format that is saved using the method of lossy compression. The output image, as result of compression, is a trade-off between storage size and image quality. Learn more about this file format [here](https://wiki.fileformat.com/image/jpeg). |
| static readonly [Jpm](../../groupdocs.conversion.filetypes/imagefiletype/jpm) | Jpm document format |
| static readonly [Jpx](../../groupdocs.conversion.filetypes/imagefiletype/jpx) | Jpx document format |
| static readonly [Odg](../../groupdocs.conversion.filetypes/imagefiletype/odg) | The ODG file format is used by Apache OpenOffice's Draw application to store drawing elements as a vector image. Learn more about this file format [here](https://wiki.fileformat.com/image/odg). |
| static readonly [Otg](../../groupdocs.conversion.filetypes/imagefiletype/otg) | An OTG file is a drawing template that is created using the OpenDocument standard that follows the OASIS Office Applications 1.0 specification. Learn more about this file format [here](https://wiki.fileformat.com/image/otg). |
| static readonly [Png](../../groupdocs.conversion.filetypes/imagefiletype/png) | PNG, Portable Network Graphics, refers to a type of raster image file format that use loseless compression. This file format was created as a replacement of Graphics Interchange Format (GIF) and has no copyright limitations. Learn more about this file format [here](https://wiki.fileformat.com/image/png). |
| static readonly [Psb](../../groupdocs.conversion.filetypes/imagefiletype/psb) | Adobe photoshop saves files in two formats. Files having 30,000 by 30,000 pixels in size are saved with PSD extension and files larger than PSD upto 300,000 by 300,000 pixels are saved with PSB extension known as “Photoshop Big”. Learn more about this file format [here](https://docs.fileformat.com/image/psb). |
| static readonly [Psd](../../groupdocs.conversion.filetypes/imagefiletype/psd) | PSD, Photoshop Document, represents Adobe Photoshop's native file format used for graphics designing and development. Learn more about this file format [here](https://wiki.fileformat.com/image/psd). |
| static readonly [Svgz](../../groupdocs.conversion.filetypes/imagefiletype/svgz) | An SVGZ file is actually a compressed version of a SVG file. This allows for easier distribution of the file online. When an SVG file is compressed using the .GZIP compression algorithm, it is then given the .svgz file extension. |
| static readonly [Tga](../../groupdocs.conversion.filetypes/imagefiletype/tga) | A file with .tga extension is a raster graphic format and was created by Truevision Inc. Learn more about this file format [here](https://docs.fileformat.com/image/tga). |
| static readonly [Tif](../../groupdocs.conversion.filetypes/imagefiletype/tif) | TIF, Tagged Image File Format, represents raster images that are meant for usage on a variety of devices that comply with this file format standard. It is capable of describing bilevel, grayscale, palette-color and full-color image data in several color spaces. Learn more about this file format [here](https://wiki.fileformat.com/image/tiff). |
| static readonly [Tiff](../../groupdocs.conversion.filetypes/imagefiletype/tiff) | TIFF, Tagged Image File Format, represents raster images that are meant for usage on a variety of devices that comply with this file format standard. It is capable of describing bilevel, grayscale, palette-color and full-color image data in several color spaces. Learn more about this file format [here](https://wiki.fileformat.com/image/tiff). |
| static readonly [Webp](../../groupdocs.conversion.filetypes/imagefiletype/webp) | WebP, introduced by Google, is a modern raster web image file format that is based on lossless and lossy compression. It provides same image quality while considerably reducing the image size. Learn more about this file format [here](https://wiki.fileformat.com/image/webp). |
| static readonly [Wmf](../../groupdocs.conversion.filetypes/imagefiletype/wmf) | Files with WMF extension represent Microsoft Windows Metafile (WMF) for storing vector as well as bitmap-format images data. Learn more about this file format [here](https://wiki.fileformat.com/image/wmf). |
| static readonly [Wmz](../../groupdocs.conversion.filetypes/imagefiletype/wmz) | An WMZ file is actually a compressed version of a Microsoft WMF file. This allows for easier distribution of the file online. When an EWMFMF file is compressed using the .GZIP compression algorithm, it is then given the .wmz file extension. |

### See Also

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
