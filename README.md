colemak for German text and Programming
=======================================

The Colemak keyboard layout for windows optimized for switching between typing german text and programming with the english symbols ([]{};/\). 

The original layout from colemak.com was tweaked by changing a few symbols and third level mapping only! Two layouts are created for quickly switching or just using one permanently.

For the german variant the Umlaute are directly accessable and the displaced parenthesis can be activated with Alt-Gr. The english layout was changed for easier indirect access to Umlaute, so AltGr+a=ä, AltGr+s=ß etc.


Motivation
----------

As a German software developer I have to type lots of code and communicate with my German colleagues. 

The emails are written in German and therefore use lots of Umlaute (äÄöÖüÜß). With the standard [colemak layout](http://colemak.com) those are only accessable by using AltGr which hinders the typing flow.

While coding there is no need for Umlaute, but for all the special symbols in the source code (/\|[]{};<>~). Those are hard to reach on the standard German QWERTZ-layout, again mostly with AltGr. So coding is much easier with the English layout, even with QWERTY.

Before I learned of colemak, I used both the QWERTY and QWERTZ layout. Easy configuration and switching is possible in Windows and Linux for ages now. With just one push of "LeftShift"+"LeftAlt" you can cycle through the configured layouts. I usually use the German layout as default and switch to the English layout for my editors and IDE. Configuring the keyboard layout to not be changed globally but for each application helps here. Then in each application I can type using the optimal layout. Sounds complicated but it is very easy, since only a few keys are different.

With the introduction of colemak to my system, it was harder to switch between German QWERTZ and coding colemak since the layout was different in a lot of ways. That was when I adapted the colemak layout to enable easy German typing by moving the Umlaute to the first level. 

Now I can alternate between German colemak and English/coding colemak. Which is easier then switching between QWERTZ and QWERTY since no damn change between Z and Y. So no more switching the location of undo with Ctrl+Z. To further ease the alternating use, the original colemak mapping of the symbols used while codind (/\|[]{}<>) are moved to the AltGr level on the German layout. So on a standard QWERTY keyboard you can still see them in the right place and they are where you know them to be with colemak. Just hit that AltGr or leftAlt+leftCtrl and the memorized key.

Also the Umlaute are on the AltGr level on the corresponding keys if you need a quick Umlaut in the English layout. AltGr+a=ä and so on.


Installation
------------

Either use the exportet files of the Microsoft Keyboard Layout Creator 1.4 under [the dir "installer"](https://github.com/itbastian/colemakForGerman/tree/master/install)

OR

1. Download the official [Microsoft Keyboard Layout Creator 1.4](https://www.microsoft.com/en-us/download/details.aspx?id=22339)
2. File/Load Source File...
3. Project/Build DLL and Setup Package
4. run the setup.exe

Afterwards you can configure Windows' keyboards and input methods.




License
-------
The MIT License (MIT)

Copyright (c) 2014 itbastian

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
