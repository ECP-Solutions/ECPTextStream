---
title: DetectEncoding
parent: Methods
grand_parent: API
nav_order: 2
---

# DetectEncoding
{: .fs-9 }

Use heuristics to try to infer the encoding of the target text file.
{: .fs-6 .fw-300 }

---

## Syntax

*expression*.`DetectEncoding`*(FilePath)*

### Parameters

The required *FilePath* argument is an identifier specifying a `String` type variable.

### Return value

*Type*: `String`

>📝**Note**
>{: .text-grey-lt-000 .bg-green-000 }
>The `DetectEncoding` method supports files with or without BOM. the following encodings can be detected: `ANSI`, `UTF-8` and `UTF-16`(BE,LE).
{: .text-grey-dk-300 .bg-grey-lt-000 }

See also
: [ReadText Method](https://ecp-solutions.github.io/ECPTextStream/api/methods/readtext.html).

---

[Back to Methods overview](https://ecp-solutions.github.io/VBA-CSV-interface/api/methods/)
