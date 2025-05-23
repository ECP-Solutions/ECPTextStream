---
title: endStreamOnLineBreak
parent: Properties
grand_parent: API
nav_order: 7
---

# endStreamOnLineBreak
{: .fs-9 }

Allows to end buffer just after the first, from right to left, line break character.
{: .fs-6 .fw-300 }

---

## ReadWrite

_Yes_

---

## Syntax

|**_Accesor_**|**_Syntax_**|
|:----------|:----------|
|Get|*expression*.`endStreamOnLineBreak`|
|Let|*expression*.`endStreamOnLineBreak` = value|

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
>It is recommended to set this property to `True` when working with non-ANSI encoded files.
{: .text-grey-dk-300 .bg-grey-lt-000 }

See also
: [ReadText Method](https://ecp-solutions.github.io/ECPTextStream/api/methods/readtext.html).
 
 ---
 
[Back to Properties overview](https://ecp-solutions.github.io/ECPTextStream/api/properties/)
