Hey, Thanks for [downloading](https://github.com/websitebloger/free-css-temp/releases) '[the template!](https://github.com/websitebloger/free-css-temp/tree/downloads/docs/download)' Please note we don't reserved the copy rights for used images.
If you like our templates, 

do not forget to join to our [Google Classroom.](https://classroom.google.com/c/NzE3MjAzMTgxOVpa).

WEBSITEBLOGER
-- Designstub

## How to join Class
## ![join team](doc/join%20team.png?raw=true)
Join Team
## Auto Sign-in
Automatically sign in to websites using stored credentials. If disabled, you will be asked for confirmation every time before signing in to a website.
## ![How to join Class](doc/Class%20code.png?raw=true)
copy and add code...
## Class code
1yycvrb

# CyberChiefCook

[![Build Status](https://travis-ci.org/samuelbetio/CyberChiefCook.svg?branch=master)](https://travis-ci.org/samuelbetio/CyberChiefCook)
[![npm](https://badge.fury.io/js/CyberChiefCook.svg)](https://www.npmjs.com/package/CyberChiefCook)
![](https://reposs.herokuapp.com/?path=samuelbetio/CyberChiefCook&color=brightgreen)

#### *The Cyber Swiss Army Knife*

CyberChiefCook is a simple, intuitive web app for carrying out all manner of "cyber" operations within a web browser. These operations include simple encoding like XOR or Base64, more complex encryption like AES, DES and Blowfish, creating binary and hexdumps, compression and decompression of data, calculating hashes and checksums, IPv6 and X.509 parsing, changing character encodings, and much more.

The tool is designed to enable both technical and non-technical analysts to manipulate data in complex ways without having to deal with complex tools or algorithms. It was conceived, designed, built and incrementally improved by an analyst in their 10% innovation time over several years. Every effort has been made to structure the code in a readable and extendable format, however it should be noted that the analyst is not a professional developer.

## Live demo

CyberChiefCook is still under active development. As a result, it shouldn't be considered a finished product. There is still testing and bug fixing to do, new features to be added and additional documentation to write. Please contribute!

Cryptographic operations in CyberChiefCook should not be relied upon to provide security in any situation. No guarantee is offered for their correctness.

[A live demo can be found here][1] - have fun!


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


## Browser support

CyberChiefCook is built to support

 - Google Chrome 40+
 - Mozilla Firefox 35+
 - Microsoft Edge 14+


## Contributing

An installation walkthrough, how-to guides for adding new operations and themes, descriptions of the repository structure, available data types and coding conventions can all be found in the project [wiki pages](https://github.com/samuelbetio/CyberChiefCook/wiki).

 - Sign the [samuelbetio Contributor Licence Agreement](https://github.com/samuelbetio/Gaffer/wiki/samuelbetio-OSS-Contributor-License-Agreement-V1.0)
 - Push your changes to your fork.
 - Submit a pull request.


## Licencing


