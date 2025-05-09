# MicroNotoSans

A fork of the Noto Sans font, subset around carefully researched text encoding formats for embedded devices. This font aims to deliver a balance between file size and language support.

This font is intended to be used as a modular system to insert extended language support into fonts that do not have the characters to do so.

This repository contains both ttf files as well as textfiles containing the glyphs used to create the subset.

---

## Breakdown


|Language|Format|Characters|Source|
|---------------|---------------|---------------|---------------|
|Simplified Chinese & Kanji|[IICore 2.2](https://en.wikipedia.org/wiki/International_Ideographs_Core)|10,566|[IICoreRSIndex.pdf](https://www.unicode.org/versions/IICoreRSIndex.pdf)|
|Korean|[KSx1001](https://en.wikipedia.org/wiki/KS_X_1001)|2,349|[hangul-generation.html](https://www.unifoundry.com/hangul/hangul-generation.html)|

|Language|Unicode Block|Characters|
|--------------------|--------------------|--------------------|
|Arabic|                    |305|
|Cyrillic|                    |310|
|Georgian|                    |82|
|Greek|                    |214|
|Hebrew||173|
|Thai||83|
|Symbols||WIP|


