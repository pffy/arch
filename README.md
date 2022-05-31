# arch
object properties and functions

## DevOps Productivity Computing

  + export tools for markdown table?, wikitable? or html-table??

## Chinese Language Computing

### Objects

  + `idx` - key-value pairs generated using ML
    + implements extended metapinyin for punctuation, etc.
    + output organized as objects

  + IdxHanyuPinyin
  + IdxToneMarks
  + IdxToneMarksIso
  + IdxToneRemoval
  + IdxToneFive
  + IdxTraditionalSimplified - converts ftz to jtz

  + `HanyuPinyin` - converts Chinese characters to pinyin with or without tones
    + tone numbers (for maximum portability)
    + tone marks (for learners)
    + ISO-compliant (ISO 7098) tone marks (for library indexing or archiving)
    + no tones (for karaoke or search engine hashing)

  + `ChineseNumber` - converts integers into Chinese characters with pinyin
    + `ChineseDigits` - enumerates the Mandarin Chinese digits 0 to 9 with pinyin
    + `ChineaeUnits` - enumerates the Mandarin Chinese classifiers and placeholders 
    + `ChineseAbacus` - counts values of placeholders given number input
  + `ChineseMoney` - converts currency input into Chinese characters with pinyin
  + `ChineseFraction` - converts fractional representations into Chinese characters with pinyin
  + `ChineseDecimal`

> **NOTE:** The Chinese abacus allows us to build numbers in multiple Asian languages.
 
  + `CantoneseNumber`
    + `CantoneseDigits`
    + `CantoneseUnits`
    + `ChineseAbacus`
 
  + ThaiNumber`
    + `ThaiDigits`
    + `ThaiUnits`
    + `ChineseAbacus`




