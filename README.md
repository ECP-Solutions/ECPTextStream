# ![ECPTextStream](/docs/assets/img/ECPTextStream.png)
[![GitHub](https://img.shields.io/github/license/ecp-solutions/ECPTextStream?style=plastic)](https://github.com/ecp-solutions/ECPTextStream/blob/main/LICENSE) [![GitHub release (latest by date)](https://img.shields.io/github/v/release/ecp-solutions/ECPTextStream?style=plastic)](https://github.com/ecp-solutions/ECPTextStream/releases/latest)

## Introductory words

ECPTextStream is an easy-to-use class module developed to enable buffered text stream on VBA. In other words, ECPTextStream is a VBA text buffered reader designed to manage text streams in Microsoft Office applications.

## Advantages
* The fastest way for I/O operations over "big" text files from VBA (up to 600 MB/sec.).
  ![Benchmark](/docs/home/TextRead-Benchmark.png)
* [UTF-8](https://www.unicode.org/faq/utf_bom.html#UTF8) encoding support. Do you have a text file, perhaps in chinese or some other foreign cyrillic language, downloaded from the Internet? This library is made to help you deal with it! You will be able to read and write UTF-8 encoded files in an easy way. 
* Supports files up to 2 GB of size.
* Supports streams delimited by CRLF, LF and CR characters. This is useful when working with structured files like CSVs.
* No memory overloads. Text files being read using a buffer, small enough to hold a single data line. 
* Minimal CPU overheat.
* Configurable buffer size.
* Coded in pure VBA. The module hasn’t reference to any external API library.

## Getting started

If you don't know how to get started with ECPTextStream class, visit the [documentation repo](https://ecp-solutions.github.io/ECPTextStream/). If you don't know if this tool can help you, take a look to the popular [CSV Interface repo](https://github.com/ws-garcia/VBA-CSV-interface) or to this [sample project](https://ecp-solutions.github.io/ECPTextStream/project_sample/).

## Contributing

In order to contribute with in this project, please see the [guidance for contributing](https://ws-garcia.github.io/ECPTextStream/contributing.html).

## Benchmark

The benchmark results for ECPTextStream are available at [this site](https://ws-garcia.github.io/ECPTextStream/home/getting_started.html#benchmark).

## Limitations

Visit [this site](https://ws-garcia.github.io/ECPTextStream/limitations/index.html) in order to known around file size considerations.

## License

Copyright (C) 2025  [ECP Solutions](https://github.com/ecp-solutions/).

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see <https://www.gnu.org/licenses/gpl-3.0.html>.

