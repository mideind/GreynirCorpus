[![Join the chat at https://gitter.im/Greynir/Lobby](https://badges.gitter.im/Greynir/Lobby.svg)](https://gitter.im/Greynir/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

<img src="img/greynir-logo-large.png" alt="Greynir" width="200" height="200" align="right" style="margin-left:20px; margin-bottom: 30px;">

# GreynirCorpus 1.0

*(Texti á íslensku fyrir neðan.)*

### A large treebank of parsed Icelandic text

**GreynirCorpus** is a large, parsed treebank of modern Icelandic text.

The treebank consists of **7 million sentences** containing approximately 110 million words.
The text is extracted from news and government sites on the web and parsed into full
constituency trees in flat text format. The format is similar to that of the
[Penn Treebank](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.9.8216&rep=rep1&type=pdf) and
[The Icelandic Parsed Historical Corpus (IcePaHC)](https://linguist.is/icelandic_treebank/Icelandic_Parsed_Historical_Corpus_(IcePaHC)).

The treebank is published under the
[**Creative Commons CC-BY 4.0 license**](https://creativecommons.org/licenses/by/4.0/)
and is thus open and free for general use, with attribution.

The treebank has two parts:

1. Seven million sentences, shuffled and **parsed mechanically**
   using the [Greynir](https://github.com/mideind/ReynirPackage) rule-based parser.
   This treebank is contained in the single file `psd/greynir_corpus.zip`. Note that the file
   is about 1.6 gigabytes in compressed form, or 9 gigabytes uncompressed.

2. A **gold standard** corpus of 2,610 sentences with parse trees that have been
   manually corrected and verified. This corpus is contained in the `gold/` directory,
   in text files named `greynir_corpus_*.psd`. Each text file contains 10 manually
   annotated sentences. The sentences tend to get longer with higher file numbers.

The annotation scheme is extensively described in this 60-page
[guideline document](https://github.com/mideind/ReynirPackage/blob/master/doc/_static/annotation_instructions.pdf?raw=true) (Icelandic-language PDF).

GreynirCorpus is a product of [Miðeind ehf.](https://mideind.is), Reykjavík, Iceland,
to which it should be attributed.

This project was partially funded by the Icelandic government's
*Strategic research and development programme for language technology*
(*Markáætlun í máltækni*), operated by [Rannís](https://rannis.is).

----------

### Stór trjábanki með þáttuðum íslenskum texta

**GreynirCorpus** er stórt safn af fullþáttuðum texta á nútímaíslensku.

Trjábankinn inniheldur **7 milljónir málsgreina**, u.þ.b. 110 milljónir orða.
Textinn er sóttur á vefsíður fréttamiðla og opinberra aðila, og fullþáttaður í setningatré
sem geymd eru í flötu textaformi. Gagnaformið er svipað og í
[Penn Treebank](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.9.8216&rep=rep1&type=pdf) og
[The Icelandic Parsed Historical Corpus (IcePaHC)](https://linguist.is/icelandic_treebank/Icelandic_Parsed_Historical_Corpus_(IcePaHC)).

Trjábankinn er gefinn út undir 
[**Creative Commons CC-BY 4.0 leyfi**](https://creativecommons.org/licenses/by/4.0/)
og er þannig opinn og frjáls til afnota, sé uppruna getið.

Trjábankinn er í tveimur hlutum:

1. Sjö milljónir málsgreina, stokkaðar í handahófskennda röð og **vélþáttaðar**
   með regluþáttaranum [Greyni](https://github.com/mideind/ReynirPackage).
   Þessi hluti trjábankans er geymdur í einni skrá, `psd/greynir_corpus.zip`. Athugið að
   skráin er um 1,6 gígabæti í þjöppuðu formi, eða 9 gígabæti óþjöppuð.

2. **Gullstaðall** sem samanstendur af 2.610 málsgreinum og þáttunartrjám þeirra, sem hafa
   verið handyfirfarin og leiðrétt. Þessi hluti trjábankans er í `gold/` möppunni,
   í textaskrám sem nefnast `greynir_corpus_*.psd`. Hver textaskrá inniheldur 10 handþáttaðar
   málsgreinar. Málsgreinarnar eru almennt lengri eftir því sem skrárnúmer hækka.

Þáttunarskemanu er ýtarlega lýst í þessu 60 síðna 
[leiðbeiningarskjali (PDF)](https://github.com/mideind/ReynirPackage/blob/master/doc/_static/annotation_instructions.pdf?raw=true).

GreynirCorpus er gefinn út á vegum [Miðeindar ehf.](https://mideind.is), Reykjavík,
sem geta skal sem útgefanda þegar gögnin eru notuð skv. CC-BY 4.0 leyfinu.

Verkefnið naut styrks úr *Markáætlun í máltækni* á vegum [Rannís](https://rannis.is).
