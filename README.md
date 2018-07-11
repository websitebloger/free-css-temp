## There aren’t any releases here
Releases are powered by [tagging specific points of history](https://github.com/websitebloger/free-css-temp/tags) in a repository. They’re great for marking release points like [v1.0.](https://github.com/websitebloger/free-css-temp/releases/tag/v1.0) [Create a new release](https://github.com/websitebloger/free-css-temp/releases/new)

|FREE WEBSITE TEMPLATES|ZIP|Tags|
|---------|---|--------|
|Neos|[zip](https://github.com/websitebloger/free-css-temp/blob/downloads/page219/neos.zip?raw=true)|[v219.4](https://github.com/websitebloger/free-css-temp/releases/tag/v219.4)|
|Photofolio|[zip](https://github.com/websitebloger/free-css-temp/blob/downloads/page1/photofolio.zip?raw=true)|[v1.5](https://github.com/websitebloger/free-css-temp/releases/tag/v1.5)|
Photoprowess|[zip](https://github.com/websitebloger/free-css-temp/blob/downloads/page1/photoprowess.zip?raw=true)|[v1.4](https://github.com/websitebloger/free-css-temp/releases/tag/v1.4)|
|Plusbusiness|[zip](https://github.com/websitebloger/free-css-temp/blob/downloads/page1/plusbusiness.zip?raw=true)|[v1.3](https://github.com/websitebloger/free-css-temp/releases/tag/v1.3)|
|Realistic|[zip](https://github.com/websitebloger/free-css-temp/blob/downloads/page1/realistic.zip?raw=true)|[v1.2](https://github.com/websitebloger/free-css-temp/releases/tag/v1.2)|
|Academic-Education|[zip](https://github.com/websitebloger/free-css-temp/blob/downloads/page1/academic-education.zip?raw=true)|[v1.1](https://github.com/websitebloger/free-css-temp/releases/tag/v1.1)|
|FREE-CSS-TEMP|[zip](https://github.com/websitebloger/free-css-temp/archive/v1.0.zip)|[v1.0](https://github.com/websitebloger/free-css-temp/releases/tag/v1.0)|



#### *Live Demo*


 - [Home][1] - have fun!


## How it works

There are four main areas in CyberChiefCook:

 1. The **input** box in the top right, where you can paste, type or drag the data you want to operate on.
 2. The **output** box in the bottom right, where the outcome of your processing will be displayed.
 3. The **operations** list on the far left, where you can find all the operations that CyberChiefCook is capable of in categorised lists, or by searching.
 4. The **recipe** area in the middle, where you can drag the operations that you want to use and specify arguments and options.

You can use as many operations as you like in simple or complex ways. Some examples are as follows:

 - [Decode a Base64-encoded string][2]
 - [Convert a date and time to a different time zone][3]
 - [Parse a Teredo IPv6 address][4]
 - [Convert data from a hexdump, then decompress][5]
 - [Display multiple timestamps as full dates][6]
 - [Carry out different operations on data of different types][7]


## Features

 - Drag and drop
     - Operations can be dragged in and out of the recipe list, or reorganised.
     - Files can be dragged over the input box to load them directly.
 - Auto Bake
     - Whenever you modify the input or the recipe, CyberChiefCook will automatically “bake” for you and produce the output immediately.
     - This can be turned off and operated manually if it is affecting performance (if the input is very large, for instance).
     - If any bake takes longer than 200 milliseconds, auto bake will be switched off automatically to prevent further performance issues.
 - Breakpoints
     - You can set breakpoints on any operation in your recipe to pause execution before running it.
     - You can also step through the recipe one operation at a time to see what the data looks like at each stage.
 - Save and load recipes
     - If you come up with an awesome recipe that you know you’ll want to use again, just click save and add it to your local storage. It'll be waiting for you next time you visit CyberChiefCook.
     - You can also copy a URL which includes your recipe and input which can be shared with others.
 - Search
     - If you know the name of the operation you want or a word associated with it, start typing it into the search field and any matching operations will immediately be shown.
 - Highlighting
     - When you highlight text in the input or output, the offset and length values will be displayed and, if possible, the corresponding data will be highlighted in the output or input respectively (example: [highlight the word 'question' in the input to see where it appears in the output][8]).
 - Save to file and load from file
     - You can save the output to a file at any time or load a file by dragging and dropping it into the input field (note that files larger than about 500kb may cause your browser to hang or even crash due to the way that browsers handle large amounts of textual data).
 - CyberChiefCook is entirely client-side
     - It should be noted that none of your input or recipe configuration is ever sent to the CyberChiefCook web server - all processing is carried out within your browser, on your own computer.
     - Due to this feature, CyberChiefCook can be compiled into a single HTML file. You can download this file and drop it into a virtual machine, share it with other people, or use it independently on your desktop.



## Contributing

An installation walkthrough, how-to guides for adding new operations and themes, descriptions of the repository structure, available data types and coding conventions can all be found in the project [wiki pages](https://github.com/samuelbetio/CyberChiefCook/wiki).

 - Sign the [samuelbetio Contributor Licence Agreement](https://github.com/samuelbetio/Gaffer/wiki/samuelbetio-OSS-Contributor-License-Agreement-V1.0)
 - Push your changes to your fork.
 - Submit a pull request.


## Licencing

CyberChiefCook is released under the [Apache 2.0 Licence](https://www.apache.org/licenses/LICENSE-2.0) and is covered by [Crown Copyright](https://www.nationalarchives.gov.uk/information-management/re-using-public-sector-information/copyright-and-re-use/crown-copyright/).


  [1]: https://websitebloger.github.io/free-css-temp/
  [2]: https://samuelbetio.github.io/CyberChiefCook/#recipe=From_Base64('A-Za-z0-9%2B/%3D',true)&input=VTI4Z2JHOXVaeUJoYm1RZ2RHaGhibXR6SUdadmNpQmhiR3dnZEdobElHWnBjMmd1
  [3]: https://samuelbetio.github.io/CyberChiefCook/#recipe=Translate_DateTime_Format('Standard%20date%20and%20time','DD/MM/YYYY%20HH:mm:ss','UTC','dddd%20Do%20MMMM%20YYYY%20HH:mm:ss%20Z%20z','Australia/Queensland')&input=MTUvMDYvMjAxNSAyMDo0NTowMA
  [4]: https://samuelbetio.github.io/CyberChiefCook/#recipe=Parse_IPv6_address()&input=MjAwMTowMDAwOjQxMzY6ZTM3ODo4MDAwOjYzYmY6M2ZmZjpmZGQy
  [5]: https://samuelbetio.github.io/CyberChiefCook/#recipe=From_Hexdump()Gunzip()&input=MDAwMDAwMDAgIDFmIDhiIDA4IDAwIDEyIGJjIGYzIDU3IDAwIGZmIDBkIGM3IGMxIDA5IDAwIDIwICB8Li4uLi6881cu/y7HwS4uIHwKMDAwMDAwMTAgIDA4IDA1IGQwIDU1IGZlIDA0IDJkIGQzIDA0IDFmIGNhIDhjIDQ0IDIxIDViIGZmICB8Li7QVf4uLdMuLsouRCFb/3wKMDAwMDAwMjAgIDYwIGM3IGQ3IDAzIDE2IGJlIDQwIDFmIDc4IDRhIDNmIDA5IDg5IDBiIDlhIDdkICB8YMfXLi6%2BQC54Sj8uLi4ufXwKMDAwMDAwMzAgIDRlIGM4IDRlIDZkIDA1IDFlIDAxIDhiIDRjIDI0IDAwIDAwIDAwICAgICAgICAgICB8TshObS4uLi5MJC4uLnw
  [6]: https://samuelbetio.github.io/CyberChiefCook/#recipe=Fork('%5C%5Cn','%5C%5Cn',false)From_UNIX_Timestamp('Seconds%20(s)')&input=OTc4MzQ2ODAwCjEwMTI2NTEyMDAKMTA0NjY5NjQwMAoxMDgxMDg3MjAwCjExMTUzMDUyMDAKMTE0OTYwOTYwMA
  [7]: https://samuelbetio.github.io/CyberChiefCook/#recipe=Fork('%5C%5Cn','%5C%5Cn',false)Conditional_Jump('1',2,10)To_Hex('Space')Return()To_Base64('A-Za-z0-9%2B/%3D')&input=U29tZSBkYXRhIHdpdGggYSAxIGluIGl0ClNvbWUgZGF0YSB3aXRoIGEgMiBpbiBpdA
  [8]: https://samuelbetio.github.io/CyberChiefCook/#recipe=XOR(%7B'option':'Hex','string':'3a'%7D,'',false)To_Hexdump(16,false,false)&input=VGhlIGFuc3dlciB0byB0aGUgdWx0aW1hdGUgcXVlc3Rpb24gb2YgbGlmZSwgdGhlIFVuaXZlcnNlLCBhbmQgZXZlcnl0aGluZyBpcyA0Mi4
