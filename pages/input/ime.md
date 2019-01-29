---
title: IME/ typing
---

## Linux

### m17n with ibus.

#### Necessary packages:

*   debian search [here](https://packages.debian.org/search?searchon=names&keywords=m17n).
*    Suggested ubuntu packages: ibus sanskrit iBus-m17n ibus-qt4 m17n-db m17n-contrib ttf-indic-fonts . See our [note here](https://sites.google.com/site/sanskritcode/optitrans).

#### Debugging / update tips

- Restart ibus:  ibus-daemon -Rd
- MDEBUG_INPUT=1 m17n-edit --im hi-optitransv2
- Configure: m17n-im-config or [http://i.imgur.com/vtq0njh.png](http://i.imgur.com/vtq0njh.png)

#### Optitrans
- Linux ibus hindi/ sanskrit/ kannada users: For your typing convenience download and use - see [optitrans](optitrans.md).

## Windows

([I](http://en.wikipedia.org/wiki/Intelligent_Input_Bus), [G](http://www.google.com/ime/transliteration/), [MSN](http://specials.msn.co.in/ilit/WebEmbed.aspx?language=Kannada), [Bhasha IME](https://sites.google.com/site/bhashaime/)..) to input Indic script directly without copy-pasting.

## MAC

- shreevatsa uses a modified version of [PC-unicode](http://www.palitext.com/subpages/PC_Unicode.htm).
- Lipika IME for IOS and OS X - [github wiki](https://github.com/ratreya/lipika-ime).
- See [here](http://www.hpnadig.net/blog/typing-kannada-mac-uim-and-m17n-mac-os-x).  [Mac UIM](http://code.google.com/p/macuim/) lets you use m17n (shrIvatsa uses this).
- for IAST: [EasyIAST](https://shreevatsa.wordpress.com/2013/01/22/a-better-keyboard-layout-for-typing-iast-on-mac-os-x-based-on-easyunicode/).

