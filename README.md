# MicroNotoSans

A fork of the Noto Sans font, subset around carefully researched text encoding formats for embedded devices. This font aims to deliver a balance between file size and language support.

This font is intended to be used as a modular system to insert extended language support into fonts that do not have the characters to do so.

This repository contains both ttf files as well as textfiles containing the glyphs used to create the subset.

---

## Breakdown


|Language|Format|Characters|Source|
|---------------|---------------|---------------|---------------|
|Simplified Chinese|[IICore 2.2](https://en.wikipedia.org/wiki/International_Ideographs_Core)|10,566|[IICoreRSIndex.pdf](https://www.unicode.org/versions/IICoreRSIndex.pdf)|
|Korean|[KSx1001](https://en.wikipedia.org/wiki/KS_X_1001)|2,349|[hangul-generation.html](https://www.unifoundry.com/hangul/hangul-generation.html)|
|Japanese|[JIS X 0208](https://en.wikipedia.org/wiki/JIS_X_0208)|6756|[Subset compiled by Shingo Tajima](https://qiita.com/gonshi_com/items/b54736d2e0e0f4586f6e)|

|Language|Unicode Blocks|Characters|
|--------------------|--------------------|--------------------|
|Arabic|[Arabic](https://en.wikipedia.org/wiki/Arabic_(Unicode_block)), [Arabic Supplement](https://en.wikipedia.org/wiki/Arabic_Supplement)|305|
|Cyrillic|[Cyrillic](https://en.wikipedia.org/wiki/Cyrillic_(Unicode_block)), [Cyrillic Supplement](https://en.wikipedia.org/wiki/Cyrillic_Supplement)|310|
|Georgian|[Georgian](https://en.wikipedia.org/wiki/Georgian_(Unicode_block))|82|
|Greek|[Greek and Coptic](https://en.wikipedia.org/wiki/Greek_and_Coptic), [Letterlike Symbols](https://en.wikipedia.org/wiki/Letterlike_Symbols)|214|
|Hebrew|[Hebrew](https://en.wikipedia.org/wiki/Hebrew_(Unicode_block))|173|
|Thai|[Thai](https://en.wikipedia.org/wiki/Thai_(Unicode_block))|83|

**Note on Symbols:** The "symbols" subset includes a variety of symbols and characters that did not fit into the subset categories above. Included in this section are Katakana, Hirgana, Bopomofo, Hangul Jamo and various dingbats and symbols that might be of use.


