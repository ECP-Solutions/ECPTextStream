---
title: autoDetectEncoding
parent: Properties
grand_parent: API
nav_order: 2
---

# autoDetectEncoding
{: .fs-9 }

Defines whether the tool should attempt to automatically infer the file encoding.
{: .fs-6 .fw-300 }

---

## ReadWrite

_Yes_

---

## Syntax

|**_Accesor_**|**_Syntax_**|
|:----------|:----------|
|Get|*expression*.`autoDetectEncoding`|
|Let|*expression*.`autoDetectEncoding` = value|

|**_Accesor_**|**_Parameters_**|
|:----------|:----------|
|Get|_None_|
|Let|*Name*: Value<br>*Type*: `Boolean`<br>*Modifiers*: `ByVal`|

|**_Accesor_**|**_Returns Type_**|
|:----------|:----------|
|Get|`Boolean`|
|Let|_None_|

>📝**Note**
>{: .text-grey-lt-000 .bg-green-000 }
>At the moment the tool can detect the following encodings: `ANSI`, `UTF-8` and `UTF-16`(BE,LE).
{: .text-grey-dk-300 .bg-grey-lt-000 }

See also
: [ReadText Method](https://ecp-solutions.github.io/ECPTextStream/api/methods/readtext.html).

---

[Back to Properties overview](https://ecp-solutions.github.io/ECPTextStream/api/properties/)
