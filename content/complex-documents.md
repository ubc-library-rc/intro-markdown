---
layout: page
title: Complex documents
permalink: /complex-documents/
parent: Part 2 - Diving deeper
nav_order: 12
---

## Working with complex documents

Markdown is great for short, simple documents -- it was designed for publishing to the web. However, issues may arise when trying to create more complex documents.

For academic writing and more complex documents, [AsciiDoc](https://asciidoctor.org/) may be a better choice. This format is superficially very similar to Markdown, but includes support for footnotes, call-outs blocks, complex tables, math, embedded files, and more.

![](slides/images/asciidoc.png)

AsciiDoc is a format designed for formal publishing -- for example by publishing companies like O'Reilly:

![](slides/images/atlas.png)

You can quickly see the difference that writing with AsciiDoc makes by looking at the examples below. These are just a sample of the kinds of complex layouts that can be created based on very minimal plain text source files with AsciiDoc markup:

* [Letter](https://dohliam.github.io/asciidoctor-skins/docstyles/letter/) ([Source](https://raw.githubusercontent.com/dohliam/asciidoctor-skins/docstyles-testing/docstyles/letter/letter.adoc), [PDF](https://raw.githubusercontent.com/Mogztter/asciidoctor-web-pdf/master/examples/letter/letter.pdf))
* [Resume](https://dohliam.github.io/asciidoctor-skins/docstyles/resume/) ([Source](https://raw.githubusercontent.com/dohliam/asciidoctor-skins/docstyles-testing/docstyles/resume/resume.adoc), [PDF](https://raw.githubusercontent.com/Mogztter/asciidoctor-web-pdf/master/examples/resume/resume.pdf))
* [Book](https://raw.githubusercontent.com/Mogztter/asciidoctor-web-pdf/master/examples/book/book.pdf) ([Source](https://raw.githubusercontent.com/Mogztter/asciidoctor-web-pdf/master/examples/book/chapter_1.adoc))
* [Cheatsheet](https://raw.githubusercontent.com/Mogztter/asciidoctor-web-pdf/master/examples/cheat-sheet/maven-security-cheat-sheet.pdf) ([Source](https://raw.githubusercontent.com/Mogztter/asciidoctor-web-pdf/master/examples/cheat-sheet/maven-security-cheat-sheet.adoc))
