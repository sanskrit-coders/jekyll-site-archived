---
title: Fonts
---
- Formal attempts at encoding Indian scripts in Unicode([B](http://sanskrit1.ccv.brown.edu/tomcat/sl/ScriptTable), [I](http://tdil.mit.gov.in/Request_Feedback/Grantha.aspx) ), fonts ([**M**](http://svayambhava.org/index.php/en/)). 
- Tools to convert old custom fonts to unicode (P, [T](http://hindi-store.tipsadda.com/2010/11/all-hindi-font-converters.html)).


## Font styles
There
is one major dichotomy, alluded to by various names: Bombay/Calcutta,
Southern/Northern,
Modern/Old. [http://i.imgur.com/O68gV2O.png](https://google.com/url?sa=D&q=http%3A%2F%2Fi.imgur.com%2FO68gV2O.png) illustrates
this.
A
few other resources here:
  - [Archive
    collection](https://google.com/url?sa=D&q=https%3A%2F%2Farchive.org%2Fdownload%2FDevanAgarITypographyResources) .
  - Velthius
    Manual [here](ftp://ftp.tex.ac.uk/tex-archive/language/devanagari/velthuis/doc/generic/velthuis/manual.pdf).
  - Resources:
    See messages/ attachments in
    \[[1](https://groups.google.com/forum/#!topic/sanskrit-programmers/zqzAXZvE92Y), [2](https://groups.google.com/forum/#!topic/sanskrit-programmers/kdUCcoQk3us)\].
Fonts
that are close to the old style:
  - Sanskrit 2003 font was
    based on nirNaya-sAgar
    books.
  - Uttara
    font
    ([http://www.sanskritweb.net/cakram/](http://www.google.com/url?q=http%3A%2F%2Fwww.sanskritweb.net%2Fcakram%2F&sa=D&sntz=1&usg=AFQjCNGDxpeBekYbly2K1YHXoFzdfiTntA))
  - Sahadeva
    ([http://bombay.indology.info/software/fonts/devanagari/](http://www.google.com/url?q=http%3A%2F%2Fbombay.indology.info%2Fsoftware%2Ffonts%2Fdevanagari%2F&sa=D&sntz=1&usg=AFQjCNEYLX-ZHFJ1xCk1ThF8yic28Djthg))
Other information on
Ulrich's
site: [here](http://www.sanskritweb.net/itrans/index.html#S99FONTS).
Font
directories
  - Alan
    Woods'
    listing [here](http://www.alanwood.net/unicode/fonts-south-asian.html#devanagari).
  - devanAgarI.net
    listing [here](http://www.devanaagarii.net/fonts/).

## Best practices for webmasters.

Motivation:
  - Don't want to rely on (potentially inadequate) fonts and text
    rendering engines users have? Some users see weird renderings and
    report "spelling mistakes" where none exist?
Solution:
Use web-fonts (fonts that will be automatically downloaded from the net
as needed) and css
[noto
guidelines](https://www.google.com/get/noto/help/guidelines/) (note :
earlyaccess fonts there don't support vaidika svara-s
    well.)
Example: 
  - [1-notosans-devanagari-github.html](https://github.com/sanskrit-coders/sanskritnlpjava/blob/master/src/main/webapp/fonts/1-notosans-devanagari-github.html "1-notosans-devanagari-github.html")
  - [2-kannada.html](http://sanskritnlp.appspot.com/fonts/2-kannada.html)
    (view its source) . 
  - sanskrit-documents ([pic1](http://i.imgur.com/YiPNBQF.png))
Thread with explanation by shrIvatsa
[here](https://groups.google.com/d/msg/sanskrit-programmers/PEQBZ4b4OOg/EQeNSKBsWXkJ).

## Report bugs

[GNU Freefont](https://savannah.gnu.org/bugs/?group=freefont).
Chrome.
  - Outstanding bugs: . (Reported bugs:
    [here](https://code.google.com/p/chromium/issues/list?can=1&q=vishvas&colspec=ID+Pri+M+Week+ReleaseBlock+Cr+Status+Owner+Summary+OS+Modified&x=m&y=releaseblock&cells=tiles).)
Free desktop
  - Outstanding bugs
    [1](https://bugs.freedesktop.org/show_bug.cgi?id=70509).
Noto \[below are dead links, moved to git
[here](https://github.com/googlei18n/noto-fonts/issues)\]
  - 
    
    
    
      
    
    
    
    
    
      
    
    
    
    
    
      
    
    
    
    
    
    
    
    
  - 
    
    
    
    svarita before visarga
    - 
    
    

## Testing

Test using the harfbuzz tool : Ubuntu instructions
[here](https://groups.google.com/d/msg/sanskrit-programmers/PEQBZ4b4OOg/pPlKqPeEI74J).
  -  hb-view /usr/share/fonts/truetype/ttf-devanagari-fonts/sahadeva.ttf
    अत्र
pango
pango-view --font "Sahadeva 40" -t अत्र
pango-view --markup --text '\<span font\_family="FreeSerif"
lang="sa" fallback="false"\> अत्र\'
  - Markup language
    [here](http://www.pygtk.org/pygtk2reference/pango-markup-language.html).
Google [font
tester](http://www.google.com/fonts#ChoosePlace:select/Script:devanagari).

### Testing on Chrome

Fonts can also be tested on chrome by following a two step process.


Install the font.
Choose to use the font in
Chrome:
  - Go to settings
  - Search for "font" in
    settings
  - get to the "Customize
    fonts" button
  - set all choices to the
    font you
    test. Or view
    a text file in Chrome after setting just the monospace font.
gmail and its compose window may use some other
font.


  

## Text to test

  - [svara-s
    in](http://www.sanskritweb.net/sansdocs/tbsvaras.pdf)
    taittirIya-brAhmaNa.
  - [Rgveda
    scan](https://en.wikipedia.org/wiki/File:Rigveda_MS2097.jpg).

```
कॢप्तिः। ॐ॥ प्रीतिः। लोगों को देखो। हाँ। ಹಿಮಾದ್ರಿಸುತೇ ಪಾಹಿ ಮ್ಮಾಮ್।

धातुपाठे गमॢ। अश्वरुहः। शङ्करः।  काळी काळे।

Check udAtta and anudAtta collusions.
अ॒ग्निमी॑ळे पु॒रोहि॑तं य॒ज्ञस्य॑ दे॒वमृ॒त्विज॑म् । 
मू॒ मॄ॒ मॢ॒ मॣ॒। ई॑ ऐ॑ ओ॑ औ॑ अं॑ अ॑ः। मि॑ मी॑ मे॑ मै॑ मो॑ मौ॑ मं॑ 

Visarga and anusvAra with svara modifiers
म॑ं म॑ः
ससजुषो रुँः ।

Check anunAsika ँ collision
अनुनासिकचिह्नम् - लीँ

क्त्य क्त्व छ्य ड्य।

ೱ ೲ ᳵ ᳶ
लीँ

कॆ कॊ कॅ
```
