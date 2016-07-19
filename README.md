# wikidict-dsl-sv - Wikidata Bilingual DSL Dictionaries (Swedish)

This repository makes available a collection of bilingual Swedish dictionaries in DSL format derived from interwiki links (links between article titles in different languages) in Wikipedia. The data has been extracted from [Wikidata](https://www.wikidata.org/).

## Format

ABBYY Lingvo DSL is a flexible dictionary format that can be read by dictionary applications such as [Goldendict](https://github.com/goldendict/goldendict) and converted to other formats using tools such as [pyglossary](https://github.com/ilius/pyglossary). There are also a number of tools for creating DSL format dictionaries available in the [dsl-tools](https://github.com/dohliam/dsl-tools) project.

DSL files *must* be saved as UTF-16 to be usable by dictionary programs. The raw source files in this repository are saved in UTF-8 format, which is both significantly smaller in terms of file size, and also readable (and diffable) by git. However, there are fully encoded and compressed `.dsl.dz` dictionaries ready for use available in the [Releases](https://github.com/open-dsl-dict/wikidict-dsl-sv/releases) section.

You can also use the `rezip_dsl.rb` and `unzip_dsl.rb` [scripts](https://github.com/dohliam/dsl-tools/tree/master/zip_unzip) provided by the [dsl-tools](https://github.com/dohliam/dsl-tools) repo to encode/compress and decode/uncompress the dictionaries either individually or as a group.

## Data

The data directory contains the bilingual dictionaries in pairs according to [ISO language code](http://en.wikipedia.org/wiki/ISO_639-1).

The basic filename pattern is `[ISO]-sv_wikidict.dsl`, with `[ISO]` being the source language ISO code. A list of all language pairs is [below](#available-language-pairs).

## Available language pairs

Language codes | Language names
-------------- | --------------
`af-sv` | Afrikaans => Swedish
`am-sv` | Amharic => Swedish
`ang-sv` | Anglo-Saxon => Swedish
`ar-sv` | Arabic => Swedish
`arc-sv` | Aramaic => Swedish
`bg-sv` | Bulgarian => Swedish
`bi-sv` | Bislama => Swedish
`bn-sv` | Bengali => Swedish
`bo-sv` | Tibetan => Swedish
`br-sv` | Breton => Swedish
`bs-sv` | Bosnian => Swedish
`ca-sv` | Catalan => Swedish
`cdo-sv` | Min Dong => Swedish
`chr-sv` | Cherokee => Swedish
`chy-sv` | Cheyenne => Swedish
`cr-sv` | Cree => Swedish
`cs-sv` | Czech => Swedish
`cy-sv` | Welsh => Swedish
`da-sv` | Danish => Swedish
`de-sv` | German => Swedish
`el-sv` | Greek => Swedish
`en-sv` | English => Swedish
`eo-sv` | Esperanto => Swedish
`es-sv` | Spanish => Swedish
`et-sv` | Estonian => Swedish
`eu-sv` | Basque => Swedish
`fa-sv` | Persian => Swedish
`ff-sv` | Fula => Swedish
`fi-sv` | Finnish => Swedish
`fr-sv` | French => Swedish
`ga-sv` | Irish => Swedish
`gan-sv` | Gan => Swedish
`gd-sv` | Scottish Gaelic => Swedish
`gu-sv` | Gujarati => Swedish
`gv-sv` | Manx => Swedish
`ha-sv` | Hausa => Swedish
`hak-sv` | Hakka => Swedish
`haw-sv` | Hawaiian => Swedish
`he-sv` | Hebrew => Swedish
`hi-sv` | Hindi => Swedish
`hr-sv` | Croatian => Swedish
`ht-sv` | Haitian => Swedish
`hu-sv` | Hungarian => Swedish
`hy-sv` | Armenian => Swedish
`id-sv` | Indonesian => Swedish
`ig-sv` | Igbo => Swedish
`is-sv` | Icelandic => Swedish
`it-sv` | Italian => Swedish
`iu-sv` | Inuktitut => Swedish
`ja-sv` | Japanese => Swedish
`jbo-sv` | Lojban => Swedish
`jv-sv` | Javanese => Swedish
`ka-sv` | Georgian => Swedish
`kg-sv` | Kongo => Swedish
`ki-sv` | Kikuyu => Swedish
`kl-sv` | Greenlandic => Swedish
`km-sv` | Khmer => Swedish
`ko-sv` | Korean => Swedish
`la-sv` | Latin => Swedish
`lg-sv` | Luganda => Swedish
`lo-sv` | Lao => Swedish
`lt-sv` | Lithuanian => Swedish
`lv-sv` | Latvian => Swedish
`mg-sv` | Malagasy => Swedish
`mi-sv` | Maori => Swedish
`mn-sv` | Mongolian => Swedish
`ms-sv` | Malay => Swedish
`mt-sv` | Maltese => Swedish
`nah-sv` | Nahuatl => Swedish
`ne-sv` | Nepali => Swedish
`nl-sv` | Dutch => Swedish
`nn-sv` | Norwegian (Nynorsk) => Swedish
`no-sv` | Norwegian => Swedish
`nv-sv` | Navajo => Swedish
`ny-sv` | Chichewa => Swedish
`oc-sv` | Occitan => Swedish
`pa-sv` | Punjabi => Swedish
`pi-sv` | Pali => Swedish
`pl-sv` | Polish => Swedish
`ps-sv` | Pashto => Swedish
`pt-sv` | Portuguese => Swedish
`qu-sv` | Quechua => Swedish
`ro-sv` | Romanian => Swedish
`ru-sv` | Russian => Swedish
`sa-sv` | Sanskrit => Swedish
`se-sv` | Northern Sami => Swedish
`sh-sv` | Serbo-Croatian => Swedish
`sk-sv` | Slovak => Swedish
`sl-sv` | Slovenian => Swedish
`sn-sv` | Shona => Swedish
`so-sv` | Somali => Swedish
`sq-sv` | Albanian => Swedish
`sr-sv` | Serbian => Swedish
`sw-sv` | Kiswahili => Swedish
`ta-sv` | Tamil => Swedish
`te-sv` | Telugu => Swedish
`th-sv` | Thai => Swedish
`tl-sv` | Tagalog => Swedish
`tpi-sv` | Tok Pisin => Swedish
`tr-sv` | Turkish => Swedish
`ug-sv` | Uyghur => Swedish
`uk-sv` | Ukrainian => Swedish
`ur-sv` | Urdu => Swedish
`vi-sv` | Vietnamese => Swedish
`wo-sv` | Wolof => Swedish
`wuu-sv` | Wu => Swedish
`xh-sv` | Xhosa => Swedish
`yi-sv` | Yiddish => Swedish
`yo-sv` | Yoruba => Swedish
`za-sv` | Zhuang => Swedish
`zh-sv` | Chinese (Mandarin) => Swedish
`zh_classical-sv` | Classical Chinese => Swedish
`zh_min_nan-sv` | Min Nan => Swedish
`zh_yue-sv` | Cantonese => Swedish
`zu-sv` | Zulu => Swedish

## Statistics

### Dictionary size

Language pair | # of entries
------------- | ------------
`af-sv` | 21679
`am-sv` | 5323
`ang-sv` | 2068
`ar-sv` | 91834
`arc-sv` | 1244
`bg-sv` | 84872
`bi-sv` | 396
`bn-sv` | 16444
`bo-sv` | 2334
`br-sv` | 29628
`bs-sv` | 22575
`ca-sv` | 187206
`cdo-sv` | 1933
`chr-sv` | 447
`chy-sv` | 535
`cr-sv` | 88
`cs-sv` | 112372
`cy-sv` | 24818
`da-sv` | 96018
`de-sv` | 302823
`el-sv` | 43006
`en-sv` | 539689
`eo-sv` | 71967
`es-sv` | 309777
`et-sv` | 53278
`eu-sv` | 141650
`fa-sv` | 113787
`ff-sv` | 184
`fi-sv` | 159339
`fr-sv` | 351442
`ga-sv` | 18770
`gan-sv` | 4219
`gd-sv` | 10077
`gu-sv` | 3216
`gv-sv` | 3851
`ha-sv` | 382
`hak-sv` | 2406
`haw-sv` | 611
`he-sv` | 74855
`hi-sv` | 20087
`hr-sv` | 54232
`ht-sv` | 10536
`hu-sv` | 100372
`hy-sv` | 30826
`id-sv` | 159692
`ig-sv` | 696
`is-sv` | 21481
`it-sv` | 272805
`iu-sv` | 345
`ja-sv` | 158761
`jbo-sv` | 1127
`jv-sv` | 14212
`ka-sv` | 42703
`kg-sv` | 577
`ki-sv` | 232
`kl-sv` | 1528
`km-sv` | 1253
`ko-sv` | 96095
`la-sv` | 67558
`lg-sv` | 146
`lo-sv` | 993
`lt-sv` | 57214
`lv-sv` | 32710
`mg-sv` | 35857
`mi-sv` | 2134
`mn-sv` | 9109
`ms-sv` | 76045
`mt-sv` | 2019
`nah-sv` | 6184
`ne-sv` | 6305
`nl-sv` | 754069
`nn-sv` | 49488
`no-sv` | 162463
`nv-sv` | 1787
`ny-sv` | 93
`oc-sv` | 60407
`pa-sv` | 7277
`pi-sv` | 2207
`pl-sv` | 261501
`ps-sv` | 2375
`pt-sv` | 256002
`qu-sv` | 10515
`ro-sv` | 105372
`ru-sv` | 237844
`sa-sv` | 4372
`se-sv` | 5621
`sh-sv` | 70984
`sk-sv` | 90429
`sl-sv` | 45726
`sn-sv` | 1419
`so-sv` | 2211
`sq-sv` | 21597
`sr-sv` | 86613
`sw-sv` | 15257
`ta-sv` | 18849
`te-sv` | 6998
`th-sv` | 40942
`tl-sv` | 22302
`tpi-sv` | 753
`tr-sv` | 79470
`ug-sv` | 2002
`uk-sv` | 160675
`ur-sv` | 25485
`vi-sv` | 656755
`wo-sv` | 838
`wuu-sv` | 1836
`xh-sv` | 246
`yi-sv` | 6334
`yo-sv` | 11284
`za-sv` | 604
`zh-sv` | 207636
`zh_classical-sv` | 1882
`zh_min_nan-sv` | 9215
`zh_yue-sv` | 14971
`zu-sv` | 535

### Top ten dictionaries by number of entries

Language pair | # of entries
------------- | ------------
`nl-sv` | 754069
`vi-sv` | 656755
`en-sv` | 539689
`fr-sv` | 351442
`es-sv` | 309777
`de-sv` | 302823
`it-sv` | 272805
`pl-sv` | 261501
`pt-sv` | 256002
`ru-sv` | 237844

## License

According to the Wikidata website:

> All structured data from the main and property namespace is available under the Creative Commons CC0 License

The data in this repository is therefore made available under the same [Creative Commons CC0 License](https://creativecommons.org/publicdomain/zero/1.0/) as that used by the Wikidata project. All of the data has been derived from the Wikidata JSON format [database dumps](https://dumps.wikimedia.org/wikidatawiki/entities/).
