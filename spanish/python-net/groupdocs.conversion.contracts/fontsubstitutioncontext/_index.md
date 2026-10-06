---
title: "Clase FontSubstitutionContext"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Describe una única sustitución de fuente que ocurrió al cargar o renderizar un documento fuente."
type: docs
url: /es/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/
is_root: false
weight: 190
---


## FontSubstitutionContext class

Describe una única sustitución de fuente que ocurrió al cargar o renderizar un documento fuente.

Las instancias se pasan a [`ConversionEvents.on_font_substituted`](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/).

El tipo FontSubstitutionContext expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/__init__/#source_file_name-original_font_name-substitute_font_name-reason) | Inicializa un nuevo FontSubstitutionContext. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [original_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/original_font_name/) | El nombre de la fuente referenciada por el documento fuente pero no disponible para la canalización de conversión. |
| [reason](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/) | El mensaje de sustitución exactamente como lo informa la pipeline de conversión, literalmente y sin analizar. |
| [source_file_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/source_file_name/) | El nombre de archivo del documento fuente que se está convirtiendo. Cuando la fuente se proporcionó como un flujo que no es un `io.RawIOBase`, esto contiene un identificador generado en lugar de un nombre de archivo real. |
| [substitute_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/substitute_font_name/) | El nombre de la fuente utilizada como sustituta. Puede ser None para documentos cuyo motor informa la sustitución solo como texto descriptivo — en ese caso lea [`FontSubstitutionContext.reason`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/). |

### Ver también
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
