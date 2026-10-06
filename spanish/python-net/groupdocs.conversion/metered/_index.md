---
title: "Clase Metered"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Administra la licencia medida (pago por uso)."
type: docs
url: /es/python-net/groupdocs.conversion/metered/
is_root: false
weight: 210
---


## Metered class

Administra la licencia medida (pago por uso).

Las licencias Metered facturan según el consumo real (típicamente páginas o
documentos procesados). Establezca el par de claves pública/privada una vez en
el inicio de la aplicación; el contenedor informa el uso de vuelta al GroupDocs
servidor de licencias en segundo plano.

El tipo Metered expone los siguientes miembros:

### Métodos
| Método | Descripción |
| :- | :- |
| [get_consumption_credit](/conversion/python-net/groupdocs.conversion/metered/get_consumption_credit/) | Devuelve el crédito Metered restante para la clave actual. |
| [get_consumption_quantity](/conversion/python-net/groupdocs.conversion/metered/get_consumption_quantity/) | Devuelve la cantidad total Metered consumida hasta ahora. |
| [set_metered_key](/conversion/python-net/groupdocs.conversion/metered/set_metered_key/#public_key-private_key) | Activa la facturación Metered con el par de claves pública/privada proporcionado. |

### Ver también
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
