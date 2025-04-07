---
layout: default
title: Home
has_children: true
nav_order: 1
description: "ECPTextStream Home."
---

# Introductory things
{: .fs-9 }

ECPTextStream is an easy-to-use class module developed to enable I/O operations over "big" text files, at high speed, from VBA. The class module doesn't use Excel Worksheets, neither any external reference such as MS Scripting Runtime.
{: .fs-6 .fw-300 }

## Advantages

* The fastest way for I/O operations over "big" text files from VBA (up to 600 MB/sec.).
* [UTF-8](https://www.unicode.org/faq/utf_bom.html#UTF8) encoding support. Do you have a text file, perhaps in chinese or some other foreign cyrillic language, downloaded from the Internet? This library is made to help you deal with it! You will be able to read and write UTF-8 encoded files in an easy way. 
* Supports files up to 2 GB of size.
* Supports CRLF, LF and CR as end of each single stream. This is useful when working with structured files like CSVs.
* No memory overloads. Text files being read with buffer.
* Minimal CPU overheat.
* Configurable buffer size.
* Coded in pure VBA. The module hasn’t reference to any external API library.