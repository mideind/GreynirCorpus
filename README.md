[![Join the chat at https://gitter.im/Greynir/Lobby](https://badges.gitter.im/Greynir/Lobby.svg)](https://gitter.im/Greynir/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

<img src="img/greynir-corpus-icon.png" alt="Greynir" width="200" height="200" align="right" style="margin-left:20px; margin-bottom: 30px;">

# GreynirCorpus 1.1

<img src="img/is.png" width="16" height="11"> Texti
[á íslensku](#user-content-stór-trjábanki-með-þáttuðum-íslenskum-texta) fyrir neðan.

### A large treebank of parsed Icelandic text

**GreynirCorpus** is a large, parsed treebank of modern Icelandic text.

The treebank consists of **10 million sentences** containing approximately 140 million words.
The text was extracted from news and government sites on the web in the years 2015-2021 and
parsed into full constituency trees in flat text format. The format is similar to that of the
[Penn Treebank](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.9.8216&rep=rep1&type=pdf) and
[The Icelandic Parsed Historical Corpus (IcePaHC)](https://linguist.is/icelandic_treebank/Icelandic_Parsed_Historical_Corpus_(IcePaHC)).

The treebank is published under the
[**Creative Commons CC-BY 4.0 license**](https://creativecommons.org/licenses/by/4.0/)
and is thus open and free for general use, with attribution.

The treebank has three parts:

1. A **copper standard** corpus of ten million sentences, shuffled and **parsed mechanically**
   using the [Greynir](https://github.com/mideind/GreynirPackage) rule-based parser.
   This treebank is contained in ten gzip-compressed files in the  [`psd/copper`](psd/copper)
   directory, each containing one million sentences. Each file is about 200 MB in compressed
   form and about 1.3 GB uncompressed.

2. A **silver standard** corpus of one million *unique* mechanically parsed sentences selected
   based on various grammatical attributes. Found in the [`psd/copper`](psd/copper) directory.

3. A **gold standard** corpus of 2,610 sentences with parse trees that have been
   manually corrected and verified. This corpus is contained in the `gold/` directory,
   in text files named `greynir_corpus_*.psd`. Each text file contains 10 manually
   annotated sentences. The sentences tend to get longer with higher file numbers.

The mechanically parsed sentences in this corpus were parsed using
[Greynir v3.1.0](https://github.com/mideind/GreynirPackage/releases/tag/3.1.0) and
[Tokenizer v3.1.1](https://github.com/mideind/Tokenizer/releases/tag/3.1.0).

The annotation scheme is described extensively in this 60-page
[guideline document](https://github.com/mideind/GreynirPackage/blob/master/doc/_static/annotation_instructions.pdf?raw=true) (Icelandic-language PDF).

**Please note that [git-lfs](https://git-lfs.github.com/) is required to clone this repository.**

GreynirCorpus is a product of [Miðeind ehf.](https://mideind.is), Reykjavík, Iceland,
to which it should be attributed.

This project was partially funded by the Icelandic government's
*Strategic research and development programme for language technology*
(*Markáætlun í máltækni*), operated by [Rannís](https://rannis.is).

----------

### Stór trjábanki með þáttuðum íslenskum texta

**GreynirCorpus** er stórt safn af fullþáttuðum texta á nútímaíslensku.

Trjábankinn inniheldur **10 milljónir málsgreina**, u.þ.b. 140 milljónir orða.
Textinn var sóttur á vefsíður fréttamiðla og opinberra aðila á árunum 2015-2021, og
fullþáttaður í setningatré sem geymd eru í flötu textaformi. Gagnaformið er svipað og í
[Penn Treebank](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.9.8216&rep=rep1&type=pdf) og
[The Icelandic Parsed Historical Corpus (IcePaHC)](https://linguist.is/icelandic_treebank/Icelandic_Parsed_Historical_Corpus_(IcePaHC)).

Trjábankinn er gefinn út undir 
[**Creative Commons CC-BY 4.0 leyfi**](https://creativecommons.org/licenses/by/4.0/)
og er þannig opinn og frjáls til afnota, sé uppruna getið.

Trjábankinn er í þremur hlutum:

1. **Koparstaðall**, tíu milljón málsgreinar, stokkaðar í handahófskennda röð og **vélþáttaðar**
   með regluþáttaranum [Greyni](https://github.com/mideind/GreynirPackage).
   Þessi hluti trjábankans er geymdur í tíu skrám í [`psd/copper`](psd/copper) möppunni. Hver skrá er
   um 200 megabæti í þjöppuðu formi og u.þ.b. 1,3 gígabæti óþjöppuð.

2. **Silfurstaðall**, ein milljón *einstakar*, stokkaðar og vélþáttaðar málsgreinar valdar út frá
  margvíslegum málfræðilegum eiginleikum. Trjábanka þennan má finna í
  [`psd/silver`](psd/silver) möppunni.

3. **Gullstaðall** sem samanstendur af 2.610 málsgreinum og þáttunartrjám þeirra, sem hafa
   verið handyfirfarin og leiðrétt. Þessi hluti trjábankans er í `gold/` möppunni,
   í textaskrám sem nefnast `greynir_corpus_*.psd`. Hver textaskrá inniheldur 10 handþáttaðar
   málsgreinar. Málsgreinarnar eru almennt lengri eftir því sem skrárnúmer hækka.

Vélþáttaðar setningar í trjábankanum voru þáttaðar með
[Greyni útgáfu 3.1.0](https://github.com/mideind/GreynirPackage/releases/tag/3.1.0) og
[Tokenizer útgáfu 3.1.1](https://github.com/mideind/Tokenizer/releases/tag/3.1.0).

Þáttunarskemanu er ýtarlega lýst í þessu 60 síðna 
[leiðbeiningarskjali (PDF)](https://github.com/mideind/GreynirPackage/blob/master/doc/_static/annotation_instructions.pdf?raw=true).

**Git-afritun á kóðasafninu krefst [git-lfs](https://git-lfs.github.com/).**

GreynirCorpus er gefinn út á vegum [Miðeindar ehf.](https://mideind.is), Reykjavík,
sem geta skal sem útgefanda þegar gögnin eru notuð skv. CC-BY 4.0 leyfinu.

Verkefnið naut styrks úr *Markáætlun í máltækni* á vegum [Rannís](https://rannis.is).
