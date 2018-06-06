---
title: Procedure
---
[OCR](/site/sanskritcode/ocr)‎ \> ‎

### 1\. OCR-ing

  

## What's a good OCR?

- A good OCR has high accuracy.
- It may be better to keep the OCR result as separate pages, and have them associated with the original images. This can help in the following ways:
    - helps proofreading, as [described here](corrections.html).
    - it may be helpful to include with each entry a link to the page in the book, so that even if the reader/user suspects OCR errors, they can click on the link and see the original page. (I've used this feature in the MW dictionary a few times.)

## How to OCR?

### Software
- Sanskrit optical character recognition (OCR) tools in roughly decreasing order of popularity (SanskritOCR: [indisenz](http://www.indsenz.com/int/index.php), Gdrive-[SP](https://groups.google.com/forum/#!topic/sanskrit-programmers/5noVN-XpeVY), [T](https://github.com/tesseract-ocr)ess, ocrlib[A](https://code.google.com/p/ocrlib/), OH[D1](http://learnsanskrit.org/tools/ocr), ILT[B](http://www.cedar.buffalo.edu/ilt/tool.html), **[ocropy](https://github.com/tmbdev/ocropy)**, [X](http://vimeo.com/4714623), [tessIndic](https://code.google.com/archive/p/tesseractindic/), [tess-parichit](https://code.google.com/archive/p/parichit/downloads), [tessHindI](https://sourceforge.net/projects/tesseracthindi/). [TDIL](http://ocr.tdil-dc.gov.in/)).
- Comparison
  - [2018 - google ocr vs sanskritocr]({{ site.baseurl }}{% post_url 2018-06-05-ocr-comparison %})
- Sanskrit OCR guide [by dhaval here](https://github.com/sanskrit-coders/sanskrit-ocr-r0/issues/8).
- Android -
    - [Textfairy](https://play.google.com/store/apps/details?id=com.renard.ocr&rdid=com.renard.ocr) uses Tesseract, and is open source and free. OCRing sanskrit using hindI pack is unsatisfactory. Sanskrit support is requested \[[github](https://github.com/renard314/textfairy/issues/157)\].
- If you work at some companies (say Google), you may have wonderful infrastructure and a couple of hundred machines to get good OCR's fast. Ask around - your colleagues may have ideas! 

### Training data
    - wikisource pages
        - Techniques
            - Process html source ([example](https://sa.wikisource.org/wiki/%E0%A4%AE%E0%A5%87%E0%A4%98%E0%A4%B8%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%87%E0%A4%B6%E0%A4%83_-_%E0%A4%A6%E0%A4%95%E0%A5%8D%E0%A4%B7%E0%A4%BF%E0%A4%A3%E0%A4%BE%E0%A4%B5%E0%A4%B0%E0%A5%8D%E0%A4%A4%E0%A4%A8%E0%A4%BE%E0%A4%A5%E0%A4%83_-%E0%A5%A7%E0%A5%AF%E0%A5%A7%E0%A5%AF)) to find tags like <span class="pagenum" id=".E0.A5.A9.E0.A5.A7" title="पुटम्:मेघसन्देशः - दक्षिणावर्तनाथः - १९१९.djvu/31"></span>.
            - Get it from index pages ([example](https://sa.wikisource.org/wiki/%E0%A4%AA%E0%A5%81%E0%A4%9F%E0%A4%AE%E0%A5%8D%3A%E0%A4%AE%E0%A5%87%E0%A4%98%E0%A4%B8%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%87%E0%A4%B6%E0%A4%83_-_%E0%A4%A6%E0%A4%95%E0%A5%8D%E0%A4%B7%E0%A4%BF%E0%A4%A3%E0%A4%BE%E0%A4%B5%E0%A4%B0%E0%A5%8D%E0%A4%A4%E0%A4%A8%E0%A4%BE%E0%A4%A5%E0%A4%83_-_%E0%A5%A7%E0%A5%AF%E0%A5%A7%E0%A5%AF.djvu/31)).
        - konkaNI vishvakosha [index](https://wikisource.org/wiki/Main_Page/Konkani).
        - meghasandesha [here](https://sa.wikisource.org/wiki/%E0%A4%85%E0%A4%A8%E0%A5%81%E0%A4%95%E0%A5%8D%E0%A4%B0%E0%A4%AE%E0%A4%A3%E0%A4%BF%E0%A4%95%E0%A4%BE:%E0%A4%AE%E0%A5%87%E0%A4%98%E0%A4%B8%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%87%E0%A4%B6%E0%A4%83_-_%E0%A4%A6%E0%A4%95%E0%A5%8D%E0%A4%B7%E0%A4%BF%E0%A4%A3%E0%A4%BE%E0%A4%B5%E0%A4%B0%E0%A5%8D%E0%A4%A4%E0%A4%A8%E0%A4%BE%E0%A4%A5%E0%A4%83_-_%E0%A5%A7%E0%A5%AF%E0%A5%A7%E0%A5%AF.djvu).
    - Other collections:
        -  [http://ocr.iiit.ac.in/Hindi100.html](http://ocr.iiit.ac.in/Hindi100.html)
        - shrIdevI [https://github.com/Shreeshrii/imagessan](https://github.com/Shreeshrii/imagessan) and [https://github.com/Shreeshrii/imageshin](https://github.com/Shreeshrii/imageshin).
    - Also, Tesseract-OCR has a program called text2image which takes unicode text and can create images files in different fonts as well as apply some degradation to it so simulate scanned pages. The program doesn't compile/work on windows, but works on Linux.
    - One can even bootstrap using output of other OCR tools.
    - See repositories of relevant indic OCR projects.

### Fora
- [Indic OCR](https://groups.google.com/forum/#!forum/indic-ocr), [parichit](https://groups.google.com/forum/#!forum/parichit-ocr).

## Alternatives to OCR

PDF text extraction: see thread [here](https://groups.google.com/d/msg/sanskrit-programmers/UGwL8dcl1g0/-ign5NVeBQAJ).

## What is the workflow for an OCR volunteer?

- First off - you should have access to OCR technology, and you should be willing to (learn to) use it.
- Look for requests on [the issues page](https://github.com/sanskrit-coders/sanskrit-ocr-r0/issues).
- Assign a request to yourself and work on it.
- Once you get the OCR-ed text, we need to pass it on to proof-reading and to early users/ readers.
    - So initially, store the result in a separate folder in github repo such as [sanskrit-ocr-r0](https://github.com/sanskrit-coders/sanskrit-ocr-r0).
        - Follow the structure you see in the [left pane of this page](https://sites.google.com/site/samskrtamsfo).
    - Create a README.md file which will track the progress of the project.
        - Please include terms a person searching on an internet search engine may use.
            - Transliterate the title into the appropriate scripts.
            - Use '-' to separate terms in a samAsa. Eg. कुलार्णव-तन्त्रम् kulArNava-tantram
- Announce the fact that you've OCR-ed the file on samskrita@googlegroups .
- Mark the issue with the milestone "[ocred](https://github.com/sanskrit-coders/sanskrit-ocr-r0/milestones/ocred)".

## Why be an OCR volunteer?

- You will be helping many other knowledge-lovers. (see "[why digitize](intro.md)?" section here.)
- You will have the satisfaction of putting your technical skills and time to good use.
