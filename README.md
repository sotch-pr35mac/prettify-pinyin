# prettify-pinyin [![Build Status](https://travis-ci.org/johnheroy/prettify-pinyin.svg?branch=master)](https://travis-ci.org/johnheroy/prettify-pinyin) [![Coverage Status](https://img.shields.io/coveralls/johnheroy/prettify-pinyin.svg)](https://coveralls.io/r/johnheroy/prettify-pinyin)

prettify-pinyin will take your pinyin written with letters and numbers (i.e. 'ni3 hao3') and add tone marks, so you don't have to. I am using this module to show pretty formats for the pronunciation entries for the CC-CEDICT dictionary which is written with letters and numbers.

## Usage

```
var pinyin = require('prettify-pinyin');

pinyin.prettify("ma1 ma2 ma3 ma4 ma"); // => mā má mǎ mà ma

```

## License

MIT
