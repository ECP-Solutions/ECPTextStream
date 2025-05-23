---
title: ReadText
parent: Methods
grand_parent: API
nav_order: 4
---

# ReadText
{: .fs-9 }

Reads a number of characters from the stream file and saves the result to the current instance.
{: .fs-6 .fw-300 }

---

## Syntax

*expression*.`ReadText`

### Parameters

_None_

### Return value

_None_

>📝**Note**
>{: .text-grey-lt-000 .bg-green-000 }
>Before read data, user must open a stream to the target text file. 
{: .text-grey-dk-300 .bg-grey-lt-000 }

See also
: [OpenStream Method](https://ecp-solutions.github.io/ECPTextStream/api/methods/openstream.html).

---

## Behavior

Each call to the `ReadText` method will read a set of characters until the buffer size is reached. If the `EndStreamOnLineBreak` property is set to `True`, the stream will cut off at the first occurrence of a line break (CRLF, CR or LF) in the reverse left direction (from right to left) or add some extra data until a line break character in the forward direction is encountered. The `ReadText` method will continue reading data until the pointer exceeds the length of the current streamed text file.

>📝**Note**
>{: .text-grey-lt-000 .bg-green-000 }
>If the streams need to end on line breaks, the buffer size must to be set to be enough to hold a couple of lines of the file. 
{: .text-grey-dk-300 .bg-grey-lt-000 }

See also
:[BufferSize Property](https://ecp-solutions.github.io/ECPTextStream/api/properties/buffersize.html), [EndStreamOnLineBreak Property](https://ecp-solutions.github.io/ECPTextStream/api/properties/endstreamonlinebreak.html).

[Back to Methods overview](https://ecp-solutions.github.io/ECPTextStream/api/methods/)
