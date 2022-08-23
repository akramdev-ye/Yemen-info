# Yemen-info

Here are some files for the most important information for Yemen programmatically. We have information about Yemeni governance, and districts in both Arabic and English languages.
The Arabic names are introduced in many forms: with Tashkeel, without it, and as a normalized text.
The English names are provided as close as possible to the Arabic name, and we have another format as a normalized text. These normalized texts are very useful for searching on the web or mobile applications.

## Why?

Many governments have open data centers with an incredible amount of information that is very useful for programmers, data scientists, and researchers. Unfortunately, we don't have something like this so we decided to build it ourselves.
For example, a simple question as: "What are the governance and districts of Yemen with the right pronunciation" is not answerable because of the lack of information.
This repository will help. Yes a little, it is helpful!

## Methodology and Notes

- Capital Districts are chosen for every governance except Amant Al-Asmah, Sanaa, and Aden. regarding the Yemeni governorate.
- We have done our best to make the information accurate, but we don't make any warranty whatsoever for the accuracy of the information provided. If you know any mistakes you are sure about, we are more than welcome to correct them.
- We have done our research in August 2022. So, if our information is outdated because of the changes in the governance and districts, we hope to update this repo with the latest information.
- We have chosen the Fusha pronunciation over some local pronunciations in the Tashkeel.

## How to use it

Simply, just download the [yemen.json](https://github.com/Yemeni-Open-Source/Yemen-info/blob/main/yemen.json) file and use it however you want. It is a JSON file, so it is language agnostic, and most programming languages support it easily.

You can also use the [cspell dictionary file Here](https://github.com/Yemeni-Open-Source/Yemen-info/blob/main/.cspell/custom-dictionary-workspace.txt) to ignore Yemeni cities/governance's names from underlined spell checker. This was a side effect of the main goal but we are thankful for it.

## TODO

- [x] Add Tashkeel in addition to Arabic names. we can use this automatic service at the beginning: [modaqiq](https://dictionary.alc.ae/modaqiq), then we add Tashkeel manually based on people who know them.
- [x] add phone code for every city.
- [x] add custom cspell dictionary for spell checkers, to ignore Yemeni cities/governance's names. [Here](https://github.com/Yemeni-Open-Source/Yemen-info/blob/main/.cspell/custom-dictionary-workspace.txt) you can find it and copy the text and paste it into any text editor that has the functionality of a spelling dictionary and the user dictionary, like Microsoft Word, LibreOffice, or Even [Arabic - Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-arabic) extension on VS Code.
- [x] add an id for every governance and district.
- [x] add capital districts for every governance.
- [ ] add text_normalization for every governance/districts in both Arabic and English.
- [ ] sort governance/districts by name (Arabic or English).
- [ ] add script to convert json file automatically to: CSV, XML, YAML, and SQL formats.

## Later On Future

This list is for todos that are not in our scope now, but if we have time and resources we may do it, or we can do it separately in another repo.

- [ ] Add polygon for map coordinates.
- [ ] Add latitude and longitude for map coordinates in governance / districts centers.
- [ ] add useful and joyful JS map like [this](https://yemenlg.org/ar/).

## Resources

some resources that helped us to build this project:

- [Modaqiq](https://dictionary.alc.ae/modaqiq) was used for automatic Tashkeel before we checked it ourselves.
- [Countries States Cities Database](https://github.com/dr5hn/countries-states-cities-database)
- [Local Governance in Yemen](https://yemenlg.org/ar/resources-by-governorate/)
- [Yemen Information Center](https://yemen-nic.info/)
- [PyArabic Python library](https://github.com/linuxscout/pyarabic)
- [Yemen Embassy- Cairo](http://www.yemenembassy-cairo.com/aboutyemen6.asp)

# Thanks

For all people who contributed to this repository. You can find the contributors on the [Contributors Page](https://github.com/Yemeni-Open-Source/Yemen-info/graphs/contributors).

But also other people who helped us with some of the names of Yemeni governance and districts, and are:

- ضياء الجبوبي
- صفوان بنيان
- يعقوب الكهادي
- طلال محرم
- عبداللطيف الرداعي
- أمجد الهتاري
