---
title: Fix title!
---

ALERT - Several of the links below are broken - IF you know the correct locations, please edit.  

Natural Language Processing in general is a thriving field, with open source projects such as [openNLP](http://incubator.apache.org/opennlp/).

Dictionaries and thesauruses
----------------------------

- Digitize dictionaries([D](http://www.sanskrit-lexicon.uni-koeln.de/), [B](http://sanskrit1.ccv.brown.edu/tomcat/sl/Cologne)), comparative dictionaries([T](http://end.translatum.gr/wiki/%E0%A4%AA%E0%A4%A5%E0%A4%BF%E0%A4%A8%E0%A5%8D)), sUtras and thesarauses([H](http://sanskrit.uohyd.ac.in/scl/amarakosha/index.html)), enable online search([B](http://sanskrit1.ccv.brown.edu/tomcat/sl/Cologne), [2B](http://sanskrit1.ccv.brown.edu/tomcat/sl/FunderburkInterface?type=1)).

    - Make them available on phones as convenient apps ([S](http://sparshapps.com/)) and as stardict/ goldendict files ([here](https://sites.google.com/site/sanskritcode/dictionaries), **[A](http://www.aupasana.com/stardict)**, **[H](http://sanskrit.inria.fr/goldendict.html)**).
    - On windows [here](https://sourceforge.net/projects/sandic/files/stats/timeline?dates=2012-03-01+to+2017-04-24).

- [Some](http://spokensanskrit.de/) online dictionaries enable collaborative editing.

    - Some do have the following limitations:
    
        *   But database updated in this manner is not publicly available.
        *   They don't currently provide an online API (application programming interface) to build on them easily.

- Concordence tools ([J](http://www.antlab.sci.waseda.ac.jp/software.html)), perhaps using word-roots ([D](http://kjc-fs-cluster.kjc.uni-heidelberg.de/dcs/)[](http://www.antlab.sci.waseda.ac.jp/software.html)). Word-nets ([IITB](http://www.cfilt.iitb.ac.in/wordnet/webswn/)).
- Morph analyzer + dictionary chrome plugin and command line tool (**[M](http://morph.diglossa.org/sa)**-git,).
- Sorting tools \[[**A**](http://anubhav-chattoraj.github.io/indic-tools/devanagari_sorter/), [D](https://docs.google.com/document/d/1t5tWom5GcZIA4TY0U_h84MRdGl4gghQugyti7vacoJA/edit#)\]
- Hyphenation \[[**Y**](https://github.com/ekmett/hyphenation/blob/master/data/hyph-sa.lic.txt)\]
- Apps! \[[sp](http://sparshapps.com/), [SJ](https://play.google.com/store/apps/developer?id=Srujan+Jha), [GP](https://play.google.com/store/search?q=sanskrit&c=apps&docType=1&sp=CAFiCgoIc2Fuc2tyaXR6BRgAwAECigECCAE%3D:S:ANO1ljKT9XE), [BV_GOI](http://sanskrit.bharatavani.in/it-tools/)\]
- Browser extensions \[[SWN_IIT](https://chrome.google.com/webstore/detail/sanskrit-wordnet/aekdldgbleokkpbekjpamfcgoaaggffi/related)\]

Grammar: word generation and analysis
-------------------------------------

- General aShTAdhyAyI simulation ([**aruNa**](https://github.com/sanskrit/vyakarana), )

    - pratyAhAra-tools \[**[D](https://github.com/drdhaval2785/pratyahara/tree/master), [V](http://sanskritnlp.appspot.com/forms/pratyAhAra.htm)**\].
    - Domain specific languages tailored for the saMskR^ita grammar are beginning to be seen ([V](https://github.com/vasya10/samskritam)).

- Sandhi and samAsa (**[D](http://www.sanskritworld.in/sanskrittool/sandhi.html)**, [F](http://sanskrit.inria.fr/DICO/grammar.html), [H](http://sanskrit.uohyd.ac.in/scl/sandhi/index.html), [MH](http://sanskrit.uohyd.ac.in/%7Ekarunakara/android/Samsaadhani.apk), [C](http://sktutils.com/pratyaharaAction.do), [C2](http://sarovar.org/projects/sandhiprogram/), **[Sch](https://github.com/funderburkjim/ScharfSandhi)**)

- sandhi and samAsa analysis ([1H](http://sanskrit.uohyd.ac.in/Heritage/DICO/reader.html), [2H](http://sanskrit.uohyd.ac.in/scl/sandhi_splitter/index.html))

- papers (**[O_DE](https://groups.google.com/d/msg/sanskrit-programmers/Ms3Fdv-axMw/3-0-5jEdDQAJ)**)

- prAtipadika declension

- Produce declensions while showing sUtra-s (**[D](http://lanover.com/lan/sanskrit/subanta.html)**).  
    
- Inflected word generation is usually based on the 'word and paradigm' model,  close to the work such as ruupa chandrikaa which gives the naamaruupaavalii for 'typical' words ending in different var.nas in different lingas.

    - ([D](http://www.sanskrit-lexicon.uni-koeln.de/work/fflex/index.html), [I](http://tdil-dc.in/san/skt_gen/generators.html)=[H1](http://sanskrit.uohyd.ac.in/lang_tech/21st-oct/downloads.html), [H](http://sanskrit.uohyd.ac.in/scl/ashtadhyayi_simulator/index.html), [H2](http://sanskrit.uohyd.ac.in/scl/skt_gen/generators.html), [F](http://sanskrit.inria.fr/DICO/grammar.html), [B](http://sanskrit1.ccv.brown.edu/tomcat/sl/NominalMorphology))
    - Apps ([ViPra](https://plus.google.com/113859883459735318216/posts/Bcv6wpT3qcA))
    - Limitation: However, as a generative model the above is not perfect because, not being based firmly on pANini's rules (which separate saMskR^ita from apabhraMShA), they may generate wrong inflections.

- These can in-turn be used to analyze inflected words ([1F](http://sanskrit.uohyd.ac.in/Heritage/DICO/index.html#stemmer), [2F](http://sanskrit.inria.fr/DICO/index.html#stemmer), I=[H](http://sanskrit.uohyd.ac.in/scl/morph/index.html), [B](http://sanskrit1.ccv.brown.edu/tomcat/sl/FunderburkInterface?type=2), [Dl](http://sanskrit.jnu.ac.in/subanta/rsubanta.jsp))
- Produce dictionaries of inflected words ([F](http://sanskrit.inria.fr/DATA/XML/)) and find concordence ([G](http://kjc-fs-cluster.kjc.uni-heidelberg.de/dcs/index.php)).

- dhAtu conjugation (**[धवल](http://www.sanskritworld.in/sanskrittool/SanskritVerb/tiGanta.html)**, [F](http://sanskrit.inria.fr/DICO/grammar.html), [I](http://tdil-dc.in/san/skt_gen/verb/verb_gen.html)=[H](http://sanskrit.uohyd.ac.in/Heritage/DICO/grammar.html#roots), [3B](http://sanskrit1.ccv.brown.edu/tomcat/sl/VerbalMorphology), [5B](http://sanskrit1.ccv.brown.edu/Sanskrit/software/gshell/index2.html), [H2](http://sanskrit.uohyd.ac.in/scl/skt_gen/generators.html), [Dl](http://sanskrit.jnu.ac.in/tinanta/tinanta.jsp?t=164), )
- kRdanta([I](http://tdil-dc.in/san/skt_gen/kqw/kqw_gen.html)=[H1](http://sanskrit.uohyd.ac.in/lang_tech/21st-oct/downloads.html), [H2](http://sanskrit.uohyd.ac.in/scl/skt_gen/generators.html), [F](http://sanskrit.inria.fr/DICO/grammar.html))
- taddhitAnta ([I](http://tdil-dc.in/san/skt_gen/waxXiwa/waxXiwa_gen.html)=[H1](http://sanskrit.uohyd.ac.in/lang_tech/21st-oct/downloads.html), [H2](http://sanskrit.uohyd.ac.in/scl/skt_gen/generators.html)) rules.
- Tools to help understand grammer sUtras ([3V](http://sanskritdocuments.org/learning_tools/AshtadyaayiSuutrapaaThaHAlphabeticalandNumericalarrangement.xlsx), [T](http://www.taralabalu.org/panini/), [D](http://sanskrit.sai.uni-heidelberg.de/Panini/HTML/list_all_rules.html), [A](http://www.avg-sanskrit.org/avgupload/sutras/1-1-1.html), [Ar](http://www.sanskrit-sanscrito.com.ar/en/essentials_software/index2_software.shtml)).
- Also see apps linked under dictionaries.

Parsing and Translation
-----------------------

- Mechanically parsing ([H](http://sanskrit.uohyd.ac.in/Heritage/DICO/reader.html)) Sanskrit text, doing part of speech tagging([D](http://kjc-fs-cluster.kjc.uni-heidelberg.de/dcs/index.php)). Producing, standardizing Sanskrit corpora ([I](http://tdil.mit.gov.in/pdf/speech%20corpora/TTS%20Corpus%20specification.pdf), [Ms](http://www.ldc.upenn.edu/Catalog/CatalogEntry.jsp?catalogId=LDC2011T04)..).  
    
- Translating Sanskrit into a more familiar language. ([F](http://sanskrit.inria.fr/%7Eanusaaraka/sanskrit/sankshipt_ramayan/)=[H](http://sanskrit.uohyd.ac.in/%7Eanusaaraka/sanskrit/sampark/), [2H](http://sanskrit.uohyd.ac.in/scl/SHMT/shmt.html), [BuSt](https://www.youtube.com/watch?v=_9D4_L9yllk#t=422))
- kramapATha-generator ([B](http://sanskrit1.ccv.brown.edu/tomcat/sl/Kramapatha)).
- Help beginning Sanskrit readers by marking up roots and vibhakti-s ([F](http://sanskrit.inria.fr/DICO/reader.en.html)).
- Translation UI-s \[[**V**](http://docs.translatehouse.org/projects/virtaal/en/latest/using_virtaal.html) \- [P](https://discourse.suttacentral.net/t/translating-the-four-nikayas/341),\]

Verse
-----

- Tools to identify metre([D](http://sanskrit.sai.uni-heidelberg.de/Chanda/HTML/list_all.html), [**S**](http://sanskritmetres.appspot.com/), [IITB](http://www.cfilt.iitb.ac.in/mitweb/)). Code only: ([C](http://sktutils.com/metricAnalyzerAction.do), [C2](http://code.google.com/p/sktutilities/)).

Script and Input
----------------

- Text to speech tools ([G](http://translate.google.com/#hi/en/%E0%A4%A4%E0%A4%A4%E0%A5%8B%20%E0%A4%B0%E0%A4%BE%E0%A4%B5%E0%A4%A3%E0%A4%A8%E0%A5%80%E0%A4%A4%E0%A4%BE%E0%A4%AF%E0%A4%BE%E0%A4%83%20%E0%A4%B8%E0%A5%80%E0%A4%A4%E0%A4%BE%E0%A4%AF%E0%A4%BE%E0%A4%83%20%E0%A4%B6%E0%A4%A4%E0%A5%8D%E0%A4%B0%E0%A5%81%E0%A4%95%E0%A4%B0%E0%A5%8D%E0%A4%B6%E0%A4%A8%E0%A4%83%20%E0%A5%A4%0A%E0%A4%87%E0%A4%AF%E0%A5%87%E0%A4%B7%20%E0%A4%AA%E0%A4%A6%E0%A4%AE%E0%A4%A8%E0%A5%8D%E0%A4%B5%E0%A5%87%E0%A4%B7%E0%A5%8D%E0%A4%9F%E0%A5%81%E0%A4%82%20%E0%A4%9A%E0%A4%BE%E0%A4%B0%E0%A4%A3%E0%A4%BE%E0%A4%9A%E0%A4%B0%E0%A4%BF%E0%A4%A4%E0%A5%87%20%E0%A4%AA%E0%A4%A5%E0%A4%BF%20%E0%A5%A4%E0%A5%A4), [D](http://dhvani.sourceforge.net/), [JNU](https://groups.google.com/forum/#!topic/sanskrit-programmers/q88i732oruU), [**ES**](http://sourceforge.net/projects/espeak/?source=typ_redirect)). See also hindii.
- Transliteration tools, encoding converters ([S](http://shreevatsa.appspot.com/sanskrit/transliterate.html), [Js](http://learnsanskrit.org/tools/sanscript), [**Py**](https://github.com/sanskrit/detect.py), **[ACzoom](https://www.aczoom.com/itrans/online/) \[flexible table\]**, [H](http://sanskrit.uohyd.ac.in/scl/transliteration/), [W](https://github.com/wikimedia/jquery.ime/), [B](http://sanskrit1.ccv.brown.edu/tomcat/sl/TranscodeText), [B](http://sanskrit1.ccv.brown.edu/Sanskrit/SanskritTransliterate/index2.html), [Gv](http://www.granthamandira.com/diCrunch/diCrunch.php), [V](http://www.virtualvinodh.com/aksaramukha), [D](http://www.aai.uni-hamburg.de/indtib/INDOLIPI/Indolipi.htm), [C](http://sktutils.com/), [Rd](http://rishida.net/scripts/uniview/), [Rp](http://people.w3.org/rishida/scripts/pickers/devanagari/), [Ar](http://www.sanskrit-sanscrito.com.ar/en/essentials_software/index2_software.shtml), **[TechH](https://sites.google.com/site/technicalhindi/home/converters)**...)
- IMEs

    - Linux: m17n with ibus.
    
        - Necessary packages:
        
            *   debian search [here](https://packages.debian.org/search?searchon=names&keywords=m17n).
            *    Suggested ubuntu packages: ibus sanskrit iBus-m17n ibus-qt4 m17n-db m17n-contrib ttf-indic-fonts . See our [note here](https://sites.google.com/site/sanskritcode/optitrans).
    
        - Debugging / update tips
        
            - Restart ibus:  ibus-daemon -Rd
            - MDEBUG_INPUT=1 m17n-edit --im hi-optitransv2
            - Configure: m17n-im-config or [http://i.imgur.com/vtq0njh.png](http://i.imgur.com/vtq0njh.png)

    - Windows([I](http://en.wikipedia.org/wiki/Intelligent_Input_Bus), [G](http://www.google.com/ime/transliteration/), [M](http://specials.msn.co.in/ilit/WebEmbed.aspx?language=Kannada), [B](https://sites.google.com/site/bhashaime/)..) to input Indic script directly without copy-pasting.

    - MAC:  
        
        - See [here](http://www.hpnadig.net/blog/typing-kannada-mac-uim-and-m17n-mac-os-x).  [Mac UIM](http://code.google.com/p/macuim/) lets you use m17n (shrIvatsa uses this).
        - for IAST: [EasyIAST](https://shreevatsa.wordpress.com/2013/01/22/a-better-keyboard-layout-for-typing-iast-on-mac-os-x-based-on-easyunicode/).

- Other lists are available at \[[N](http://sanskritdocuments.org/processing_tools/), [N2](http://sanskritlinks.blogspot.com/2010_03_01_archive.html), [W](http://hi.wikipedia.org/wiki/Hindi_Computing_Resources_on_the_Internet#Hindi_Text_Analysis.2C_Text_Processing_and_Concordance), W2\].

- Some tools/ websites ([1W](http://sahityam.net/wiki/Main_Page), [2W](http://stotrasamhita.net/wiki/Main_Page), ) enable viewing text in script of reader's choice.
- Also see this [hindI wiki page](http://hi.wikipedia.org/wiki/%E0%A4%B5%E0%A4%BF%E0%A4%95%E0%A4%BF%E0%A4%AA%E0%A5%80%E0%A4%A1%E0%A4%BF%E0%A4%AF%E0%A4%BE:%E0%A4%87%E0%A4%A3%E0%A5%8D%E0%A4%9F%E0%A4%B0%E0%A4%A8%E0%A5%87%E0%A4%9F_%E0%A4%AA%E0%A4%B0_%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80_%E0%A4%95%E0%A5%87_%E0%A4%B8%E0%A4%BE%E0%A4%A7%E0%A4%A8#Hindi_Text_to_Speech_.28_TTS_.29_and_Speech_to_Text_Tools).

Fonts, OCR and Scanning
-----------------------

- OCR - [see here](https://sites.google.com/site/sanskritcode/ocr/1-ocr-ing).
- Formal attempts at encoding Indian scripts in Unicode([B](http://sanskrit1.ccv.brown.edu/tomcat/sl/ScriptTable), [I](http://tdil.mit.gov.in/Request_Feedback/Grantha.aspx) ), fonts ([**M**](http://svayambhava.org/index.php/en/)). Tools to convert old custom fonts to unicode (P, [T](http://hindi-store.tipsadda.com/2010/11/all-hindi-font-converters.html)).
- DLI downloaders

- See[here](http://sanskritdocuments.org/scannedbooks/). [Sh](https://github.com/sanskrit-coders/DLI-tools).

- Reading scanned books on tablet

- Desiderata [here](https://www.facebook.com/vishvas.vasuki/posts/10152929928722989?comment_id=10152930576477989&offset=0&total_comments=4&notif_t=feed_comment).
- Google Play does a decent job.

Interesting collections
-----------------------

*   Maven and pypi search terms:

    *   Indic
    *   Transliterate Transliteration
    *   sanskrit
    *   hindi

*   [https://github.com/sanskrit-coders](https://github.com/sanskrit-coders)
*   [https://github.com/libindic](https://github.com/libindic)
*   [https://github.com/vedavaapi](https://github.com/vedavaapi)
*   [https://github.com/egangotri](https://github.com/egangotri)

Desiderata
----------

In some cases above source code for Sanskrit tools are available (the links in bold are said to be - our gratitude!); but much good software is not open-source; and there is quite a bit of duplication of effort. Besides the limitations noted above, what is conspicuously missing from the above are tools directed at meeting important needs of the popular spoken Sanskrit movement, especially as we increasingly interact with information through computers and the internet.  

- Consuming documents and webpages written in other languages in saMskRRita (There is no google-translate like device at present nor will there be one in the near future).
- Sanskrit UI versions of commonly used software don't exist (Unlike Arabic, Hebrew..).
- There are no good Sanskrit browser scripts or extensions to do common things like look up word meanings with a click or a mouse-over.
- No effort at generating Sanskrit content easily. Eg: Sanskrit wikipedia is nowhere close to the english version. Same goes for the wiktionary.