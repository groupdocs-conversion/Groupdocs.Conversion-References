---
title: "Clase SpreadsheetLoadOptions"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Proporciona opciones para cargar documentos de hoja de cálculo."
type: docs
url: /es/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/
is_root: false
weight: 440
---


## SpreadsheetLoadOptions class

Proporciona opciones para cargar documentos de hoja de cálculo.

El tipo SpreadsheetLoadOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/__init__/) | Inicializa una nueva instancia de [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/). |

### Métodos
| Método | Descripción |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clone/) | Clona la instancia actual. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Determina si dos instancias de objeto son iguales. (heredado de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (heredado de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (heredado de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Sirve como la función hash predeterminada. (heredado de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [all_columns_in_one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/all_columns_in_one_page_per_sheet/) | La propiedad determina si todo el contenido de columnas de una hoja se renderiza en una sola página en el resultado. |
| [auto_fit_rows](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/auto_fit_rows/) | Las filas se ajustan automáticamente al convertir. |
| [check_excel_restriction](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/) | La propiedad determina si se verifican las restricciones de archivos Excel al modificar objetos relacionados con celdas. |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clear_built_in_document_properties/) | La propiedad ClearBuiltInDocumentProperties determina si se borran las propiedades de documento incorporadas al cargar una hoja de cálculo. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clear_custom_document_properties/) | La propiedad ClearCustomDocumentProperties. |
| [columns_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/columns_per_page/) | El número de columnas por página utilizado para dividir una hoja de cálculo en páginas; el valor predeterminado es 0, lo que desactiva la paginación. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_owned/) | La propiedad implementa [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/) y por defecto es False. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_owner/) | La propiedad que implementa [`IDocumentsContainerLoadOptions.convert_owner`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owner/). Por defecto es True. |
| [convert_range](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_range/) | El rango a convertir al convertir a un formato que no sea hoja de cálculo, p.\u00a0ej., "D1:F8". |
| [culture_info](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/culture_info/) | La información de cultura del sistema utilizada al cargar el archivo. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/default_font/) | La fuente predeterminada para un documento de hoja de cálculo. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/depth/) | La profundidad de las opciones de carga del contenedor de documentos. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/font_substitutes/) | Los sustitutos de fuentes utilizados al convertir un documento de hoja de cálculo. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/format/) | El tipo de archivo del documento de entrada. |
| [ignore_formula_calculation_errors](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/ignore_formula_calculation_errors/) | La propiedad indica si se deben ignorar los errores de cálculo de fórmulas. El error puede ser una función no compatible, enlaces externos, etc. Por defecto es False. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/margin_settings/) | Los ajustes de margen. |
| [one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/one_page_per_sheet/) | La propiedad indica si el contenido de cada hoja se convierte en una sola página en el documento PDF. El valor predeterminado es True. |
| [optimize_pdf_size](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/optimize_pdf_size/) | La conversión está optimizada para un tamaño de archivo menor en lugar de la calidad de impresión cuando se establece en True al convertir a PDF. |
| [password](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/password/) | La contraseña utilizada para desproteger un documento protegido. |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/preserve_document_structure/) | La bandera que indica si la estructura del documento debe preservarse al convertir a PDF (el valor predeterminado es False). |
| [print_comments](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/print_comments/) | La forma en que se imprimen los comentarios con la hoja. Por defecto es PrintNoComments. |
| [reset_font_folders](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/reset_font_folders/) | Las carpetas de fuentes se restablecen antes de cargar el documento. |
| [rows_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/rows_per_page/) | El número de filas por página utilizado para dividir una hoja de cálculo en páginas, con un valor predeterminado de 0 que significa sin paginación. |
| [sheet_indexes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheet_indexes/) | La lista de índices de hoja a convertir. |
| [sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheets/) | El nombre de la hoja a convertir. |
| [show_grid_lines](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_grid_lines/) | La opción de mostrar líneas de cuadrícula al convertir archivos Excel. |
| [show_hidden_sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_hidden_sheets/) | La opción de mostrar hojas ocultas al convertir archivos Excel. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/size_settings/) | Los ajustes de tamaño, según lo definido por [`IPageSizeOptions`](/conversion/python-net/groupdocs.conversion.options/ipagesizeoptions/). |
| [skip_empty_rows_and_columns](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_empty_rows_and_columns/) | La configuración que omite filas y columnas vacías al convertir. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_external_resources/) | La propiedad implementa [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/skip_external_resources/). |
| [skip_footers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_footers/) | La propiedad determina si los pies de página se omiten al convertir documentos de hoja de cálculo. Predeterminado: False. |
| [skip_headers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_headers/) | La opción de omitir encabezados al convertir documentos de hoja de cálculo. Predeterminado: False. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/whitelisted_resources/) | Los recursos en lista blanca según lo definido por [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |

### Ver también
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
