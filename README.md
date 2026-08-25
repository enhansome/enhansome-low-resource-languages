# Awesome Low Resource Languages with stars

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources for the conservation, development, and documentation of low resource (human) languages.

According to some estimates, half of the 7,000+ currently spoken languages are expected to become extinct this century. However, there is a lot of work by academics, independent scholars, organizations, communities, and individuals which goes towards stopping or slowing this trend. This list provides open source code and tools useful for documenting, conserving, developing, preserving, or working with endangered and low resource languages.

**Publication**

A white paper describing this repository was published at the LREC 2016 CCURL Workshop (Collaboration and Computing for Under-Resourced Languages). The paper is in this repository, in the `papers` folder. Download the raw paper here: [Open Source Code Serving Endangered Languages](https://raw.githubusercontent.com/RichardLitt/low-resource-languages/master/paper/Open%20Source%20Code%20Serving%20Endangered%20Languages.pdf).

## Contribute

To edit this list on GitHub, simply [click here](https://github.com/RichardLitt/low-resource-languages/edit/master/README.md) ⭐ 456 | 🐛 2 | 🌐 TeX | 📅 2026-06-26. If you would like to discuss anything at all related to this, please [open an issue](https://github.com/RichardLitt/low-resource-languages/issues) ⭐ 456 | 🐛 2 | 🌐 TeX | 📅 2026-06-26. If you know of any resource available that is not on this list, please add it, either using the link above or by submitting pull requests.

There are more details on contributing in the [CONTRIBUTING](CONTRIBUTING.md) guide.

If you're interested in discussing the list in some offline capacity, get in touch with [@RichardLitt](https://github.com/RichardLitt). I'd be more than happy to have a phone call or email exchange.

# Table of Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc) ⭐ 4,461 | 🐛 27 | 🌐 JavaScript | 📅 2026-08-04*

* [Definitions](#definitions)
* [Generic Repositories](#generic-repositories)
  * [Single language lexicography projects and utilities](#single-language-lexicography-projects-and-utilities)
    * [Utilities](#utilities)
  * [Software](#software)
* [Keyboard Layout Configuration Helpers](#keyboard-layout-configuration-helpers)
* [Annotation](#annotation)
* [Format Specifications](#format-specifications)
* [i18n-related Repositories](#i18n-related-repositories)
* [Audio automation](#audio-automation)
* [Text-to-Speech (TTS)](#text-to-speech-tts)
* [Automatic Speech Recognition (ASR)](#automatic-speech-recognition-asr)
* [Text automation](#text-automation)
* [Experimentation](#experimentation)
* [Flashcards](#flashcards)
* [Natural language generation](#natural-language-generation)
* [Computing systems](#computing-systems)
* [Android Applications](#android-applications)
* [Chrome Extensions](#chrome-extensions)
* [FieldDB](#fielddb)
  * [FieldDB Webservices/Components/Plugins](#fielddb-webservicescomponentsplugins)
* [Academic Research Paper-Specific Repositories](#academic-research-paper-specific-repositories)
* [Example Repositories](#example-repositories)
* [Fonts](#fonts)
* [Corpora](#corpora)
* [Organizations](#organizations)
  * [On GitHub](#on-github)
  * [Other OSS Organizations](#other-oss-organizations)
* [Tutorials](#tutorials)
* [Language Specific Projects](#language-specific-projects)
  * [Afrikaans](#afrikaans)
  * [Albanian](#albanian)
  * [Alutiiq](#alutiiq)
  * [Amharic](#amharic)
  * [Basque](#basque)
  * [Belarusian](#belarusian)
  * [Bengali](#bengali)
  * [Chichewa](#chichewa)
  * [Galician](#galician)
    * [Apertium](#apertium)
  * [Georgian](#georgian)
    * [Fonts](#fonts-1)
    * [Internationalization and Localization (i18n/l10n)](#internationalization-and-localization-i18nl10n)
  * [Guarani](#guarani)
  * [Hausa](#hausa)
  * [Hindi](#hindi)
  * [Høgnorsk](#h%C3%B8gnorsk)
  * [Icelandic](#icelandic)
  * [Inuktitut](#inuktitut)
  * [Irish](#irish)
  * [Kinyarwanda](#kinyarwanda)
  * [Kurdish](#kurdish)
  * [Lingala](#lingala)
  * [Lushootseed](#lushootseed)
  * [Malay](#malay)
  * [Malagasy](#malagasy)
  * [Manx](#manx)
  * [Migmaq](#migmaq)
  * [Minderico](#minderico)
  * [Nishnaabe](#nishnaabe)
  * [Oromo](#oromo)
  * [Quechua](#quechua)
  * [Sami](#sami)
  * [Scottish Gaelic](#scottish-gaelic)
  * [Secwepemctsin](#secwepemctsin)
  * [Somali](#somali)
  * [Tigrinya](#tigrinya)
  * [Uralic](#uralic)
  * [Zulu](#zulu)
* [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Definitions

**Endangered languages** are human languages that are in danger of extinction. This list also encompasses minority languages - languages which are spoken by a stable, but small, population (for example, Maltese or Hawai'ian); and low- or under-resourced languages, which may be spoken by a large population but are under-represented digitally (for instance, Quechua). These languages share certain characteristics in common; the most pertinent is sparse data and a lack of resources, ranging from spell-checkers to grammars to machine translation corpora. Other under-resourced languages that do not fall under this list include constructed languages (for instance, Klingon or Na'vi), computer languages (for instance, Javascript or Lua), and extinct languages that are so sparse as to be rendered computationally irrelevant for most purposes (for instance, Tocharian).

**Open Source** "promotes a universal access via a free license to a product's design or blueprint, and universal redistribution of that design or blueprint, including subsequent improvements to it by anyone." ([Wiki](https://en.wikipedia.org/wiki/Open_source)). This is important because money and resources allocated towards a language or project that are not open source is spent at the expense of possible extensibility elsewhere.

This list used to be named `endangered-languages`. It was renamed to reflect that endangerment is a loaded term that both may not reflect the views of language communities speaking minority languages. `low-resource-languages` focuses this list on a lack of digital resources compared to other, high resourced languages.

Tools which are built for these languages are not included (unless relevant for dialects or variants): Arabic, Bulgarian, Catalan, Chinese, Croatian, Czech, Danish, Dutch, English, Estonian, Finnish, Flemish, French, German, Greek, Hebrew, Hungarian, Indonesian, Italian, Japanese, Korean, Latvian, Lithuanian, Norwegian, Norwegian (Bokmål), Persian, Polish, Portuguese, Romanian, Russian, Serbian, Slovak, Slovenian, Spanish, Swedish, Thai, Turkish, Ukrainian, Valencian, Vietnamese. This list comes from the list of most popular content languages for websites, [on this Wikipedia page](https://en.wikipedia.org/wiki/Languages_used_on_the_Internet). Other metrics could be used - if you have another one, please suggest it!

This list is particularly good at one thing; showing the kinds of tools that exist in the field, generically. However, for in depth research into a specific language or tool suite, it does not perform exceptionally well. For instance, listing all of the [Firefox language packs](https://addons.mozilla.org/eu/firefox/language-tools/) or [Apertium language modules](https://github.com/apertium/apertium-languages) ⭐ 40 | 🐛 4 | 📅 2021-05-27 for each low resource language would be unhelpful, as would be including all of the tools available for Basque noted in the [ACL Wiki](https://aclweb.org/aclwiki/Resources_for_Basque), which would mainly mean cataloguing tools through the [IXA group](http://ixa.si.ehu.es/produktuak?language=en), some of which are open source, and some are not. Instead, view this list as a starting point for more research.

Looking for resources for code languages? Take a look at [the awesome lists collection](https://github.com/sindresorhus/awesome) ⭐ 499,907 | 🐛 106 | 📅 2026-08-21.

## Generic Repositories

* [NLTK](https://github.com/nltk/nltk) ⭐ 14,702 | 🐛 232 | 🌐 Python | 📅 2026-08-25 - *Python* Natural Language Tool Kit. NLTK Source <http://www.nltk.org/>.
* [Indic NLP Library](https://github.com/anoopkunchukuttan/indic_nlp_library) ⭐ 645 | 🐛 34 | 🌐 Python | 📅 2024-06-07 - Python library for common text processing and NLP tasks in Indian languages including tokenization, normalization, and transliteration.
* [IndicTrans2](https://github.com/AI4Bharat/IndicTrans2) ⭐ 462 | 🐛 16 | 🌐 Python | 📅 2025-10-03 - Open-source translation models for all 22 scheduled languages of India.
* [CorpusTools](https://github.com/PhonologicalCorpusTools/CorpusTools) ⭐ 123 | 🐛 118 | 🌐 Python | 📅 2025-05-24 - Phonological CorpusTools <http://phonologicalcorpustools.github.io/CorpusTools/>.
* [iLanguage](https://github.com/iLanguage/iLanguage) ⭐ 22 | 🐛 5 | 🌐 JavaScript | 📅 2017-11-28 - A semi-unsupervised language independent morphological analyzer useful for stemming unknown language text, or getting a rough estimate of possible parses for morphemes in a word. Input: a corpus. Uses compression, maximum entropy and fieldlinguistics.
* [Apertium](http://apertium.org/) - A free/open-source machine translation platform, initially aimed at related-language pairs but expanded to deal with more divergent language pairs (Wikipedia-like army of other MT linguists). Wikipedia has a [list](https://en.wikipedia.org/wiki/Apertium) of all language pairs.
* [Common Language Resources and Technology Infrastructure (CLARIN)](http://www.clarin.eu/content/about-clarin) - CLARIN is a research infrastructure that was initiated from the vision that all digital language resources and tools from all over Europe and beyond are accessible through a single sign-on online environment for the support of researchers in the humanities and social sciences.
* [Living Tongues](http://livingtongues.org/) - Living Tongues Institute for Endangered Languages works to document, revitalize, and maintain endangered languages.

### Single language lexicography projects and utilities

#### Utilities

* [WeSay](https://github.com/sillsdev/wesay) ⭐ 20 | 🐛 3 | 🌐 C# | 📅 2026-01-30 - Allows language communities to build their own dictionaries. <https://software.sil.org/wesay/> (by the SIL International).
* [Project for Free Electronic Dictionaries](http://pfed.info/) Is a project for a java MIDlet for mobile phones - for indigenous language dictionaries.
* [Webonary](https://www.webonary.org/) Site which hosts digital dictionaries for single languages.

### Software

* [Tesseract.js](https://github.com/naptha/tesseract.js) ⭐ 38,667 | 🐛 47 | 🌐 JavaScript | 📅 2026-05-17 - Pure Javascript OCR for 62 Languages 📖🎉🖥 <http://tesseract.projectnaptha.com/>.
* [fastText](https://github.com/facebookresearch/fastText) ⚠️ Archived - Library for fast text representation and classification.
* [NLTK](https://github.com/nltk/nltk) ⭐ 14,702 | 🐛 232 | 🌐 Python | 📅 2026-08-25 - *Python* Natural Language Tool Kit. NLTK Source <http://www.nltk.org/>.
* [Natural](https://github.com/NaturalNode/natural) ⭐ 10,881 | 🐛 87 | 🌐 JavaScript | 📅 2026-02-22 - *Javascript* general natural language facilities for node.
* [wavesurfer.js](https://github.com/katspaugh/wavesurfer.js) ⭐ 10,384 | 🐛 36 | 🌐 TypeScript | 📅 2026-08-21 - Navigable waveform built on Web Audio and Canvas <https://wavesurfer-js.org/> (Also has an ELAN plugin).
* [Stanford CoreNLP](https://github.com/stanfordnlp/CoreNLP) ⭐ 10,102 | 🐛 182 | 🌐 Java | 📅 2026-08-25 - Stanford CoreNLP: A Java suite of core NLP tools. <https://stanfordnlp.github.io/CoreNLP/>.
* [stanza](https://github.com/stanfordnlp/stanza) ⭐ 7,867 | 🐛 92 | 🌐 Python | 📅 2026-08-25 - Stanford NLP group's shared Python tools.
* [Franc](https://github.com/wooorm/franc) ⭐ 4,411 | 🐛 6 | 🌐 JavaScript | 📅 2024-06-12 - Natural language detection <https://wooorm.com/franc/>.
* [hunspell](https://github.com/hunspell/hunspell) ⭐ 2,572 | 🐛 113 | 🌐 C++ | 📅 2026-08-16 - Spell checker and morphological analyzer library and program designed for languages with rich morphology and complex word compounding or character encoding.
* [langid.py](https://github.com/saffsd/langid.py) ⭐ 2,462 | 🐛 28 | 🌐 Python | 📅 2020-01-01 - Stand-alone language identification system.
* [Gaia](https://github.com/mozilla-b2g/gaia) ⚠️ Archived - Gaia is a HTML5-based Phone UI for the Boot 2 Gecko Project. NOTE: For details of what branches are used for what releases, see [the wiki](https://wiki.mozilla.org/B2G). If you're interested in setting up a keyboard in new language, see [this](https://developer.mozilla.org/en-US/docs/Archive/B2G_OS/Developing_Gaia/Customizing_the_keyboard).
* [mosesdecoder](https://github.com/moses-smt/mosesdecoder) ⭐ 1,624 | 🐛 7 | 🌐 Roff | 📅 2025-03-28 - Moses, the machine translation system.
* [OpenNLP](https://github.com/apache/opennlp) ⭐ 1,602 | 🐛 18 | 🌐 Java | 📅 2026-08-25 - The Apache OpenNLP library is a machine learning based toolkit for the processing of natural language text. [Website](https://opennlp.apache.org).
* [dataverse](https://github.com/IQSS/dataverse) ⭐ 1,069 | 🐛 1,003 | 🌐 Java | 📅 2026-08-25 - A data repository framework to share and publish research data.
* [l20n.js](https://github.com/l20n/l20n.js) ⚠️ Archived - L20n reinvents software localization. Users should be able to benefit from the entire expressive power of natural languages. L20n keeps simple things simple, and at the same time makes complex things possible. This is the JavaScript implementation of L20n. <http://l20n.org>.
* [epitran](https://github.com/dmort27/epitran) ⭐ 831 | 🐛 31 | 🌐 Python | 📅 2026-06-18 - Grapheme to Phoneme conversion (G2P) for many low-resource languages.
* [fast\_align](https://github.com/clab/fast_align) ⭐ 768 | 🐛 39 | 🌐 C++ | 📅 2022-07-19 - Simple, fast unsupervised word aligner.
* [Stanford CoreNLP Python](https://github.com/dasmith/stanford-corenlp-python) ⭐ 610 | 🐛 47 | 🌐 Python | 📅 2018-03-14 - Python wrapper for Stanford CoreNLP tools.
* [brown-cluster](https://github.com/percyliang/brown-cluster) ⭐ 426 | 🐛 15 | 🌐 C++ | 📅 2023-09-10 - C++ implementation of the Brown word clustering algorithm.
* [enchant](https://github.com/AbiWord/enchant) ⭐ 398 | 🐛 18 | 🌐 Vala | 📅 2026-08-25 - enchant spellchecking library <https://abiword.github.io/enchant/>.
* [wikipron](https://github.com/CUNY-CL/wikipron) ⭐ 373 | 🐛 7 | 🌐 Python | 📅 2026-07-23 -- retrives IPA pronunciations for Wiktionary entries
* [long-press](https://github.com/quentint/long-press) ⚠️ Archived - jQuery plugin to ease the writing of accented or rare characters. <http://toki-woki.net/lab/long-press/>.
* [UniversalDependencies docs](https://github.com/UniversalDependencies/docs) ⭐ 297 | 🐛 161 | 🌐 HTML | 📅 2026-08-25 - Universal Dependencies online documentation <http://universaldependencies.org/docs/>.
* [giza-pp](https://github.com/moses-smt/giza-pp) ⭐ 273 | 🐛 7 | 🌐 C++ | 📅 2025-11-18 - GIZA++ is a statistical machine translation toolkit that is used to train IBM Models 1-5 and an HMM word alignment model. This package also contains the source for the mkcls tool which generates the word classes necessary for training some of the alignment models.
* [xdxf\_makedict](https://github.com/soshial/xdxf_makedict) ⭐ 247 | 🐛 12 | 📅 2024-05-20 - XDXF dictionary format and "makedict" dictionary converting software (official repository).
* [UniversalDependencies tools](https://github.com/universaldependencies/tools) ⭐ 220 | 🐛 5 | 🌐 Perl | 📅 2026-08-25 - Various utilities for processing the data.
* [GlotLID](https://github.com/cisnlp/GlotLID) ⭐ 215 | 🐛 3 | 🌐 Python | 📅 2026-04-15 - Fasttext language identification with support for more than 2000 labels.
* [morfessor](https://github.com/aalto-speech/morfessor) ⭐ 208 | 🐛 1 | 🌐 Python | 📅 2020-10-06 - Morfessor is a tool for unsupervised and semi-supervised morphological segmentation.
* [jQuery.IME](https://github.com/wikimedia/jquery.ime) ⭐ 190 | 🐛 72 | 🌐 JavaScript | 📅 2026-08-21 - jQuery Input Method Editor used on Wikipedia
* [cdec](https://github.com/redpony/cdec) ⭐ 185 | 🐛 50 | 🌐 C++ | 📅 2020-05-26 - Decoder, aligner, and model optimizer for statistical machine translation and other structured prediction models based on (mostly) context-free formalisms.
* [mgiza](https://github.com/moses-smt/mgiza) ⭐ 167 | 🐛 8 | 🌐 C++ | 📅 2021-05-12 - A word alignment tool based on famous GIZA++, extended to support multi-threading, resume training and incremental training.
* [Lingpy](https://github.com/lingpy/lingpy) ⭐ 146 | 🐛 38 | 🌐 Python | 📅 2026-05-27 - LingPy: Python library for quantitative tasks in historical linguistics <http://lingpy.org>.
* [clam](https://github.com/proycon/clam) ⭐ 136 | 🐛 16 | 🌐 Python | 📅 2026-07-29 - Computational Linguistics Application Mediator -- Quickly turn NLP applications into RESTful webservices with a web-application front-end. You provide a specification of your command line application, its input, output and parameters, and CLAM wraps around your application to form a fully fledged RESTful webservice.
* [CorpusTools](https://github.com/PhonologicalCorpusTools/CorpusTools) ⭐ 123 | 🐛 118 | 🌐 Python | 📅 2025-05-24 - Phonological CorpusTools <http://phonologicalcorpustools.github.io/CorpusTools/>.
* [FieldWorks](https://github.com/sillsdev/FieldWorks) ⭐ 111 | 🐛 20 | 🌐 C# | 📅 2026-08-25 - FieldWorks is a suite of software tools for language and cultural data, with support for complex scripts. <https://software.sil.org/fieldworks/> FieldWorks Language Explorer (or FLEx, for short) is designed to help field linguists perform many common language documentation and analysis tasks. It can help you: elicit and record lexical information, create dictionaries, interlinearize texts, analyze discourse features, study morphology.
* [mukurtucms](https://github.com/MukurtuCMS/mukurtucms) ⭐ 95 | 🐛 108 | 🌐 PHP | 📅 2025-11-19 - The Mukurtu Content Management System (CMS) is an Internet- based platform designed to enable archiving of digital cultural resources
* [pyDelphin](https://github.com/delph-in/pydelphin) ⭐ 88 | 🐛 15 | 🌐 Python | 📅 2026-03-31 - Python libraries for DELPH-IN (Friendly Fork).
* [icu-dotnet](https://github.com/sillsdev/icu-dotnet) ⭐ 83 | 🐛 8 | 🌐 C# | 📅 2026-08-25 - C# wrapper for ICU4C.
* [liblevenshtein](https://github.com/universal-automata/liblevenshtein) ⭐ 68 | 🐛 13 | 📅 2020-10-19 - A library for generating Finite State Transducers based on Levenshtein Automata.
* [giellakbd-ios](https://github.com/divvun/giellakbd-ios) ⭐ 57 | 🐛 38 | 🌐 Swift | 📅 2026-06-30 - An open source reimplementation of Apple's native iOS keyboard with a specific focus on support for localised keyboards. Used by [kbdgen](https://github.com/divvun/kbdgen) ⭐ 24 | 🐛 16 | 🌐 Rust | 📅 2026-07-04 (see elsewhere on this page).
* [wikt2dict](https://github.com/juditacs/wikt2dict) ⭐ 54 | 🐛 5 | 🌐 Python | 📅 2022-08-17 - Wiktionary parser tool for many language editions.
* [discoursegraphs](https://github.com/arne-cl/discoursegraphs) ⭐ 51 | 🐛 49 | 🌐 Python | 📅 2025-11-14 - Python-based tool to convert and merge multilayer annotated linguistic data.
* [RBGParser](https://github.com/taolei87/RBGParser) ⭐ 47 | 🐛 1 | 🌐 Java | 📅 2016-01-25 - Graph-based Dependency Parser.
* [libpalaso](https://github.com/sillsdev/libpalaso) ⭐ 46 | 🐛 29 | 🌐 C# | 📅 2026-08-25 - Palaso Library: A set of .Net libraries useful for developers of Language Software.
* [mythes](https://github.com/hunspell/mythes) ⭐ 46 | 🐛 0 | 🌐 C++ | 📅 2026-05-17 - MyThes is a simple thesaurus that uses a structured text data file and an index file with binary search to lookup words and phrases and return information on part of speech, meanings, and synonyms.
* [SyllabiPy](https://github.com/henchc/syllabipy) ⭐ 45 | 🐛 1 | 🌐 Python | 📅 2022-12-25 - Python interface for universal syllabification algorithms
* [BloomDesktop](https://github.com/BloomBooks/BloomDesktop) ⭐ 44 | 🐛 52 | 🌐 C# | 📅 2026-08-25 - Bloom Desktop is a hybrid c#/javascript/html/css Windows application that dramatically "lowers the bar" for language communities who want books in their own languages. Bloom delivers a low-training, high-output system where mother tongue speakers and their advocates work together to foster both community authorship and access to external materia… <https://bloomlibrary.org/>.
* [4lang](https://github.com/kornai/4lang) ⭐ 42 | 🐛 52 | 🌐 Python | 📅 2024-04-04 - Concept dictionary using Eilenberg machines.
* [Machine](https://github.com/sillsdev/machine) ⭐ 29 | 🐛 17 | 🌐 C# | 📅 2026-08-25 - Machine is a natural language processing library for .NET that is focused on providing tools for processing resource-poor languages (used by FLEx).
* [pepper](https://github.com/korpling/pepper) ⭐ 25 | 🐛 38 | 🌐 XSLT | 📅 2025-01-03 - Pepper is a pluggable, Java-based, open source converter framework for linguistic data.
* [TECkit](https://github.com/silnrsi/teckit) ⭐ 25 | 🐛 3 | 🌐 C | 📅 2026-08-11 - A Text Encoding Conversion toolkit.
* [Cog](https://github.com/sillsdev/cog) ⭐ 24 | 🐛 29 | 🌐 C# | 📅 2023-10-13 - Cog is a tool for comparing languages using lexicostatistics and comparative linguistics techniques. It can be used to automate much of the process of comparing word lists from different language varieties. <http://sillsdev.github.io/cog/>.
* [hundict](https://github.com/zseder/hundict) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2014-07-03 - bilingual dictionary extractor from parallel corpora.
* [kbdgen](https://github.com/divvun/kbdgen) ⭐ 24 | 🐛 16 | 🌐 Rust | 📅 2026-07-04 - Generate keyboards and keyboard layouts for Windows, macOS, X11, iOS, Android and Chrome, from a single, simple yaml file. Also registers languages unknown to Windows, so that after installation, there is a correct and robust association between the designated BCP 47 code (including full support for ISO 639-3) and installed language tools such as keyboards, spelling checkers and other tools.
* [iLanguage](https://github.com/iLanguage/iLanguage) ⭐ 22 | 🐛 5 | 🌐 JavaScript | 📅 2017-11-28 - A semi-unsupervised language independent morphological analyzer useful for stemming unknown language text, or getting a rough estimate of possible parses for morphemes in a word. Input: a corpus. Uses compression, maximum entropy and fieldlinguistics.
* [norma](https://github.com/comphist/norma) ⭐ 22 | 🐛 10 | 🌐 C++ | 📅 2021-01-18 - A tool for automatic spelling normalization.
* [alignment-with-openfst](https://github.com/ldmt-muri/alignment-with-openfst) ⭐ 21 | 🐛 63 | 🌐 C++ | 📅 2016-12-09 - This is an implementation of the CRF autoencoder framework for four tasks: bitext word alignment, part-of-speech tagging, code switching, dependency parsing.
* [huntag](https://github.com/recski/HunTag) ⭐ 21 | 🐛 6 | 🌐 Python | 📅 2016-01-18 - a sequential tagger for NLP using Maximum Entropy Learning and Hidden Markov Models.
* [Lex4All](https://github.com/lex4all/lex4all) ⭐ 21 | 🐛 6 | 🌐 C# | 📅 2020-07-14 - pronunciation LEXicons for Any Low-resource Language <http://lex4all.github.io/lex4all/>.
* [nabu](https://github.com/nabu-catalog/nabu) ⭐ 21 | 🐛 5 | 🌐 Ruby | 📅 2026-08-20 - nabu is a digital media item management system that provides a catalog of audio and video items, metadata for these items, and information about the workflow status of the items. [www.paradisec.org.au](http://www.paradisec.org.au)
* [pressagio](https://github.com/cidles/pressagio) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2019-11-18 - Pressagio is a library that predicts text based on n-gram models. For example, you can send a string and the library will return the most likely word completions for the last token in the string.
* [CTK](https://github.com/LowResourceLanguages/champollion) ⭐ 18 | 🐛 0 | 🌐 Perl | 📅 2016-03-14 - Built around LDC's champollion sentence aligner kernel, Champollion Tool Kit (CTK) aims to providing ready-to-use parallel text sentence alignment tools for as many language pairs as possible. (Original project is on SourceForge: <http://champollion.sourceforge.net>).
* [bible-corpus-tools](https://github.com/christos-c/bible-corpus-tools) ⭐ 16 | 🐛 0 | 🌐 Java | 📅 2022-10-10 - A collection of tools for reading/processing the multilingual Bible corpus.
* [Gramadóir](https://github.com/kscanne/gramadoir) ⭐ 16 | 🐛 2 | 🌐 Perl | 📅 2026-03-30 - Grammar checking engine that is designed for the rapid development of grammar checkers for minority languages and other languages with limited computational resources.
* [dative](https://github.com/dativebase/dative) ⭐ 15 | 🐛 179 | 🌐 CoffeeScript | 📅 2023-04-01 - A single-page application that interacts with multiple linguistic fieldwork web service databases. [Website](http://www.dative.ca).
* [hfst-ospell](https://github.com/hfst/hfst-ospell) ⭐ 15 | 🐛 13 | 🌐 C++ | 📅 2024-02-20 - HFST spell checker library and command line tool.
* [Salt](https://github.com/korpling/salt) ⭐ 15 | 🐛 72 | 🌐 XSLT | 📅 2023-03-27 - A graph-based model to store and manipulate linguistic data.
* [twitter\_langid](https://github.com/ajaech/twitter_langid) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2017-01-18 - A hierarchical character-word neural network for language identification.
* [divvunspell](https://github.com/divvun/divvunspell) ⭐ 14 | 🐛 9 | 🌐 Rust | 📅 2026-08-24 - `hfst-ospell` (below) rewritten in Rust, for robust concurrency and memory management. Is in practical use about 10x faster than `hfst-ospell`. It uses the same zhfst files as `hfst-ospell`, which are available for all languages in the [GiellaLT](https://github.com/giellalt/) GitHub org (see below).
* [giellakbd-android](https://github.com/divvun/giellakbd-android) ⭐ 14 | 🐛 23 | 🌐 Java | 📅 2026-07-03 - A fork of LatinIME (by Google for Android), targeting marginalised languages that also deserve first-class status on mobile operating systems. Used by [kbdgen](https://github.com/divvun/kbdgen) ⭐ 24 | 🐛 16 | 🌐 Rust | 📅 2026-07-04 (see elsewhere on this page).
* [TexNLP](https://github.com/utcompling/texnlp) ⭐ 14 | 🐛 0 | 🌐 Java | 📅 2012-01-14 - TexNLP: Texas Natural Language Processing tools.
* [hfst-optimized-lookup](https://github.com/hfst/hfst-optimized-lookup) ⭐ 13 | 🐛 13 | 🌐 C++ | 📅 2018-02-27 - HFST optimized-lookup standalone library and command line tool.
* [nplm](https://github.com/moses-smt/nplm) ⭐ 13 | 🐛 0 | 🌐 C++ | 📅 2015-09-03 - Fork of <https://nlg.isi.edu/software/nplm/> with some efficiency tweaks and adaptation for use in mosesdecoder.
* [DLTK](https://github.com/alvations/DLTK) ⭐ 12 | 🐛 1 | 🌐 Perl | 📅 2015-08-31 - Deutsch Language Tool Kit. [More](https://htmlpreview.github.io/?https://github.com/alvations/DLTK/blob/master/docs/index.html).
* [Glottolog data](https://github.com/clld/glottolog-data) ⭐ 12 | 🐛 7 | 🌐 TeX | 📅 2017-11-23 - [Glottolog](https://glottolog.org) provides comprehensive reference information for the world's languages.
* [Secwepemc-Facebook](https://github.com/kscanne/secwepemc-facebook) ⭐ 12 | 🐛 0 | 🌐 Gettext Catalog | 📅 2015-03-11 - Translate Facebook into unsupported languages.
* [convertextract](https://github.com/roedoejet/convertextract) ⭐ 11 | 🐛 0 | 🌐 HTML | 📅 2023-09-08 - Convert Excel, Word and PowerPoint files with non-Unicode text (like text requiring SIL fonts) into Unicode, while preserving original file's formatting.
* [phonology-assistant](https://github.com/sillsdev/phonology-assistant) ⭐ 11 | 🐛 11 | 🌐 C# | 📅 2025-02-19 - Phonology Assistant is a discovery tool. Provided with a corpus of phonetic data, it automatically charts the sounds and through its searching capabilities, helps a user discover and test the rules of sound in a language.
* [salm](https://github.com/moses-smt/salm) ⭐ 11 | 🐛 1 | 🌐 C++ | 📅 2017-12-22 - SALM: Suffix Array and its Applications in Empirical Language Processing by Joy.
* [SeedLing](https://github.com/alvations/SeedLing) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2018-02-09 - Building and Using A Seed Corpus for the Human Language Project.
* [pdfdroplet](https://github.com/sillsdev/pdfdroplet) ⭐ 10 | 🐛 3 | 🌐 C# | 📅 2026-03-02 - Library and GUI for imposition of PDF pages (e.g. 2-up) <http://software.sil.org/pdfdroplet/>.
* [str2ipa](https://github.com/ytsvetko/str2ipa) ⭐ 10 | 🐛 0 | 🌐 Ruby | 📅 2015-10-29 - Pronunciation dictionaries for languages with close-to-phonetic writing systems.
* [divvun-gramcheck](https://github.com/divvun/libdivvun) ⭐ 9 | 🐛 20 | 🌐 C++ | 📅 2026-03-10 - This program does FST lookup on forms specified as Constraint Grammar format readings, and looks up error-tags in an XML file with human-readable messages. It is meant to be used as a late stage of a grammar checker pipeline.
* [low-resource-pos-tagging-2014](https://github.com/dhgarrette/low-resource-pos-tagging-2014/) ⭐ 9 | 🐛 1 | 🌐 Scala | 📅 2016-02-25 Low-Resource POS-Tagging: 2014
* [SegParser](https://github.com/yuanzh/SegParser) ⭐ 9 | 🐛 0 | 🌐 C++ | 📅 2015-11-29 - Randomized Greedy algorithm for joint segmentation, POS tagging and dependency parsing.
* [ToolsForFieldLinguistics](https://github.com/cesine/ToolsForFieldLinguistics) ⭐ 9 | 🐛 2 | 🌐 JavaScript | 📅 2026-07-23 - A collection of scripts and recipes for linguistics.
* [webcorpus](https://github.com/zseder/webcorpus) ⭐ 9 | 🐛 3 | 🌐 C++ | 📅 2015-03-30 - This project is a collection of scripts and programs for creating a webcorpus from crawled data.
* [divvun-keyboard](https://github.com/divvun/divvun-keyboard) ⭐ 8 | 🐛 8 | 📅 2026-07-04 - keyboard apps for iOS and Android with keyboard layouts for indigenous and minority languages
* [FwDocumentation](https://github.com/sillsdev/FwDocumentation) ⭐ 8 | 🐛 0 | 🌐 HTML | 📅 2026-08-13 - Developer documentation for FieldWorks (software tools for language and cultural data, with support for complex scripts).
* [gv-crawl](https://github.com/vchahun/gv-crawl) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2014-10-20 - Global Voices bitext crawler for creating parallel corpora.
* [old-pyramid](https://github.com/dativebase/old-pyramid) ⭐ 8 | 🐛 18 | 🌐 Python | 📅 2023-05-23 - Online Linguistic Database migrated to the Pyramid framework.
* [ops-devbox](https://github.com/sillsdev/ops-devbox) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2023-06-13 - Ansible playbook for a (linux) developer machine.
* [panlex-tools](https://github.com/longnow/panlex-tools) ⭐ 8 | 🐛 5 | 🌐 Python | 📅 2022-12-08 - This package contains scripts to transform lexical resources into a format suitable for importing into PanLex. Documentation may be found at <https://dev.panlex.org>.
* [exsite9](https://github.com/IntersectAustralia/exsite9) ⚠️ Archived - ExSite9 is a desktop application that was built to facilitate researchers easily and quickly tagging their data files with descriptive metadata and subsequently packaging their data files and associated metadata ready for submission to a repository. ExSite9 also allows for the structural organisation of said files within actually moving their physical location on your local file storage; allowing you to correctly organise your files and metadata ready for packaging.
* [MacVoikko](https://github.com/bnavetta/MacVoikko) ⭐ 7 | 🐛 0 | 🌐 Objective-C | 📅 2015-01-08 - An OS X spelling server based on Voikko.
* [pathway](https://github.com/sillsdev/pathway) ⭐ 7 | 🐛 6 | 🌐 HTML | 📅 2024-05-24 - Preparing language data for publication.
* [SayMore](https://software.sil.org/saymore/) - A tool for making common Language Documentation tasks such as keeping all the resulting files and meta data organized, converting files to archive formats, and transcription. [Source](https://github.com/sillsdev/saymore) ⭐ 7 | 🐛 9 | 🌐 C# | 📅 2026-08-25.
* [icu4c](https://github.com/sillsdev/icu4c) ⚠️ Archived - Mirror of svn project at <http://source.icu-project.org/repos/icu/icu/>. The FieldWorks branch has some FieldWorks specific enhancements.
* [node-panlex](https://github.com/longnow/node-panlex) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2019-04-23 - node.js client for PanLex.
* [TeraDict](https://github.com/longnow/TeraDict) ⭐ 6 | 🐛 1 | 🌐 JavaScript | 📅 2019-05-03 - Translate English words into hundreds of languages!.
* [Toney](https://github.com/langtech/toney) ⭐ 6 | 🐛 12 | 🌐 C++ | 📅 2014-09-21 - Tone Classification Software.
* [Tsammalex data](https://github.com/clld/tsammalex-data) ⭐ 6 | 🐛 12 | 🌐 TeX | 📅 2018-06-25 - [Tsammalex](https://tsammalex.clld.org) is a multilingual lexical database on plants and animals.
* [chorus](https://github.com/sillsdev/chorus) ⭐ 5 | 🐛 22 | 🌐 C# | 📅 2026-08-20 - A version control system designed to enable workflows appropriate for typical language development teams who are geographically distributed.
* [grind](https://github.com/sillsdev/grind) ⭐ 5 | 🐛 2 | 🌐 C++ | 📅 2020-07-09 - An InDesign 5.5 plug-in designed allow graphite enabled smart fonts to be used in Adobe InDesign. This project integrates SIL's Graphite 2 smart font technology with our own implementation of a paragraph composer plugin.
* [Make-extensions](https://github.com/kscanne/make-extensions) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2017-12-04 - Scripts for generating hunspell spellchecking extensions.
* [Skype in your language](https://github.com/akerbeltz/skypeinyourlanguage) ⭐ 5 | 🐛 0 | 🌐 Makefile | 📅 2015-12-02 - Translate Skype into unsupported languages.
* [BloomLibrary](https://github.com/BloomBooks/BloomLibrary) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2021-02-09 - Bloom Library Single Page App, using AngularJS & Bootstrap, Parse.com backend. <https://bloomlibrary.org/>.
* [Desmeme](https://github.com/jcgood/desmeme) ⭐ 4 | 🐛 9 | 🌐 Python | 📅 2026-06-05 - Database and tools for exploring linguistic templates.
* [ELDER: Endangered Language Data Electronic Repository](https://github.com/elderonline/ELDER) ⭐ 4 | 🐛 4 | 🌐 PHP | 📅 2011-12-12 - Endangered Language Data Electronic Repository: A web-based ontologically-compliant collaborative linguistic data cataloguing tool.
* [old-webapp](https://github.com/jrwdunham/old-webapp) ⭐ 4 | 🐛 26 | 🌐 Python | 📅 2014-12-29 - Online Linguistic Database --- software for creating web applications to collaboratively document languages.<http://www.onlinelinguisticdatabase.org>.
* [pdsc-collection-viewer](https://github.com/marcolarosa/pdsc-collection-viewer) ⚠️ Archived - Paradisec Collection Browser
* [LLM Proxy Babylon](https://github.com/tverney/llm-proxy-babylon) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-09 - An open-source proxy that bridges the quality gap for low-resource languages in LLMs by selectively pre-translating prompts to English at inference time. Measured quality improvements from 0.456 to 0.949 for Thai, with 70% token cost reduction. Supports AWS Bedrock and OpenAI.
* [FwSupportTools](https://github.com/sillsdev/FwSupportTools) ⭐ 3 | 🐛 0 | 🌐 Rich Text Format | 📅 2024-01-30 - Additional tools for FieldWorks development.
* [koreksyon](https://github.com/reokatoa/koreksyon) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2015-08-22 - Tools for developing and implementing spell-checking and grammar-checking capabilities in low-resource languages.
* [morpholm](https://github.com/ldmt-muri/morpholm) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2013-06-27 - Morphology-aware language models.
* [teny](https://github.com/vchahun/teny) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2012-10-17 - Tools for low-resource machine translation.
* [translitit-engine](https://github.com/gausby/translitit-engine) ⚠️ Archived - A transliteration engine written in JavaScript.
* [tweet2learn](https://github.com/kscanne/tweet2learn) ⭐ 3 | 🐛 0 | 🌐 Perl | 📅 2025-10-07 - An app to make it easier to use your native language on Twitter.
* [web-template](https://github.com/eddersko/web-template) ⭐ 3 | 🐛 0 | 🌐 PHP | 📅 2015-02-27 - This is a web-based template that may be used to present language learning resources to aid language revitalization efforts. It includes a talking dictionary, and a phrasicon, containing sentences and phrases.
* [Bristol Uni MT Morphology tools](https://github.com/LowResourceLanguages/bristol-mt-morphology) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2015-11-08 - This repo is a mirror of scripts previously available on <http://www.cs.bris.ac.uk/Research/MachineLearning/Morphology/resources.jsp>. Included: Ukwabelana - An open-source morphological Zulu corpus and EMMA: A Novel Evaluation Metric for Morphological Analysis.
* [LfMerge](https://github.com/sillsdev/LfMerge) ⭐ 2 | 🐛 30 | 🌐 C# | 📅 2026-08-25 - Send/Receive for languageforge.org.
* [lrl](https://github.com/RichardLitt/lrl) ⭐ 2 | 🐛 1 | 🌐 C | 📅 2013-06-07 - For work concerning low resource languages.
* [morph-test](https://github.com/divvun/morph-test) ⭐ 2 | 🐛 2 | 🌐 Python | 📅 2025-08-22 - A python script to run tests for generation and analysis of a morphological transducer built using the Giella infrastructure. Works with Hfst, Xerox' fst tools, and with Foma.
* [OdtXslt](https://github.com/sillsdev/OdtXslt) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2017-06-27 - Perform XSLT transform on contents of a package (such as ODT, Docx, etc.).
* [OmegaT-hfst-tokenizer](https://github.com/divvun/OmegaT-hfst-tokenizer) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2020-03-26 - OmegaT-hfst-tokenizer provides fst-based tokenisation in OmegaT.
* [sugali](https://github.com/alvations/sugali) ⭐ 2 | 🐛 5 | 🌐 Python | 📅 2022-07-19 - This is a legacy repository of the language identification project for many (many) languages project for the software project course, NLP projects for low-resource languages.
* [transcriber](https://github.com/langtech/transcriber/tree/dev) ⭐ 2 | 🐛 1 | 📅 2015-05-07 - An HTML5 transcription tool for Aikuma
* [ArtOfReading](https://github.com/sillsdev/ArtOfReading) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2020-01-14 - Index and processing scripts related to the Art Of Reading illustration collection.
* [brain](https://github.com/FieldDB/brain) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2014-03-10 - Neural networks in JavaScript.
* [cnminlangwebcollect](https://github.com/hyphenliu/cnminlangwebcollect) ⭐ 1 | 🐛 3 | 🌐 Python | 📅 2020-10-01 - Chinese minorities website languages detection and websites collection.
* [hermitcrab](https://github.com/sillsdev/hermitcrab) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2022-05-09 - HermitCrab.NET is a flexible morphological/phonological parser that takes an item-and-process approach.
* [myWorkSafe](https://github.com/sillsdev/myWorkSafe) ⭐ 1 | 🐛 1 | 🌐 C# | 📅 2018-09-17 - Smart & Simple Backup for Language Development Workers. <http://software.sil.org/myworksafe/>.
* [old](https://github.com/dativebase/old) ⭐ 1 | 🐛 86 | 🌐 Python | 📅 2020-08-28 - The Online Linguistic Database (OLD): software for linguistic fieldwork. <http://www.onlinelinguisticdatabase.org>.
* [paradigm](https://github.com/sillsdev/paradigm) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2026-07-14 - PARADIGM is a .Net (C#) implementation of Joseph E. Grimes' 1983 work entitled "Affix Positions and Cooccurrences: The PARADIGM Program".
* [PrimerPro](https://github.com/sillsdev/PrimerPro) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2018-10-08 - The purpose of PrimerPro is to assist the literacy worker in the development of primers for a given language.
* [solid](https://github.com/sillsdev/solid) ⭐ 1 | 🐛 5 | 🌐 C# | 📅 2025-03-13 - Solid is a software tool that can be used to check, clean up, and convert Standard Format (e.g. Toolbox) lexicon data.
* [SuGarLike](https://github.com/alvations/SuGarLike) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2014-07-24 - Language Identification for Low Resource Languages (by Susanne, Guy and Liling).
* [wordbyword](https://github.com/cidles/wordbyword) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2014-09-18 - WordByWord is a free, open source, easy-to-use multimedia vocabulary trainer developed by Vera Ferreira, Peter Bouda, and Ricardo Filipe at CIDLeS with the support of the Foundation for Endangered Languages.
* [ark-tweet-nlp](https://github.com/FieldDB/ark-tweet-nlp) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2012-08-16 - CMU ARK Twitter Part-of-Speech Tagger (*Fork*).
* [bayesline](https://github.com/alvations/bayesline) ⭐ 0 | 🐛 0 | 📅 2017-05-26 - A Multinomial Bayesian Classification for Language Identification.
* [DataTags](https://github.com/FieldDB/DataTags) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2014-11-11 - A system to assess the sensitivity and privacy risk of a dataset, and assign a tag to describe how the dataset must be transfered, stored and accessed. (*Fork*).
* [DeepLearnToolbox](https://github.com/FieldDB/DeepLearnToolbox) ⭐ 0 | 🐛 0 | 🌐 Matlab | 📅 2014-05-11 - Matlab/Octave toolbox for deep learning. Includes Deep Belief Nets, Stacked Autoencoders, Convolutional Neural Nets, Convolutional Autoencoders and vanilla Neural Nets. Each method has examples to get you started.
* [FwLocalizations](https://github.com/sillsdev/FwLocalizations) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2026-08-05 - Localizations for FieldWorks.
* [hfst-ospell-js](https://github.com/divvun/hfst-ospell-js) ⚠️ Archived - Node bindings for hfst-ospell.
* [ipa-help](https://github.com/sillsdev/ipa-help) ⭐ 0 | 🐛 0 | 🌐 Visual Basic | 📅 2017-12-27 - IPA Helps.
* [itweets-geodata](https://github.com/kscanne/itweets-geodata) ⭐ 0 | 🐛 0 | 📅 2021-03-08 - Geodata from Indigenous Tweets.
* [LEGO Unified Concepticon](https://github.com/jcgood/concepticon) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2013-07-17 - Material relating to the LEGO Unified Concepticon.
* [moz-l10n-tiers](https://github.com/kscanne/moz-l10n-tiers) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2013-11-22 - Creates a pseudo-locale to evaluate string prioritization for l10n.
* [octothorpe](https://github.com/FieldDB/octothorpe) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2013-05-03 - CouchDB-powered wiki thing.
* [Rosetta Pangloss](https://github.com/jcgood/rosetta-pangloss) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2015-03-13 - The Rosetta Project's Pangloss system.
* [StandardFormatLib](https://github.com/sillsdev/StandardFormatLib) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2015-04-16 - Standard Format Library.
* [Toolbox Scripts for ELAN](https://github.com/RichardLitt/toolbox-scripts) ⭐ 0 | 🐛 0 | 🌐 Perl | 📅 2015-01-08 - Mirror of Alexander Koenig's Toolbox Scripts <https://tla.mpi.nl/tools/tla-tools/elan/thirdparty/>.
* [WSI4URLang](https://github.com/mohammadnasiruddin/WSI4URLang) ⭐ 0 | 🐛 1 | 🌐 Java | 📅 2020-10-30 - Word Sense Induction (WSI) for Under-resourced Languages (URLang).
* [accentuate.us](https://sourceforge.net/p/lingala/code/HEAD/tree/) a.k.a. "charlifter". Statistical Unicodification of plain text for many languages
* [Apertium](https://sourceforge.net/projects/apertium/) Apertium is a toolbox to build open-source shallow-transfer machine translation systems, especially suitable for related language pairs: it includes the engine, maintenance tools, and open linguistic data for several language pairs.
* CasualCon CasualConc is a concordance program that runs natively on Mac OS X 10.5 Leopard or later. It was originally designed for casual use (preliminary analysis or non-research purposes), though \[the maintainer] has been using it for his own research (and may others have). It can generate kwic concordance lines, word clusters, collocation analysis, and word count. **\[unrecoverable]** <!-- https://sites.google.com/site/casualconc/Home -->
* [charlint](http://www.w3.org/International/charlint/) Charlint is a character normalization/checking tool written in Perl. Among else, it implements Normalization Form C of Unicode TR 15, as a test platform for Early Uniform Normalization in the W3C Character Model.
* [CMU Sphinx](https://sourceforge.net/projects/cmusphinx/) CMUSphinx is a speaker-independent large vocabulary continuous speech recognizer released under BSD style license. It is also a collection of open source tools and resources that allows researchers and developers to build speech recognition systems.
* [dictdb](https://web.archive.org/web/20180610235429/https://github.com/substack/dictdb) - dictionary database for language translation. **\[archived]**
* [Field Linguist's Toolbox](https://software.sil.org/toolbox/download/) - Toolbox is a data management and analysis tool for field linguists. It is especially useful for maintaining lexical data, and for parsing and interlinearizing text, but it can be used to manage virtually any kind of data.
* langtech A host of resources provided in SVN by the University of Tromsø. Details are [here](http://giellatekno.uit.no) and in English [here](http://giellatekno.uit.no/index.eng.html). **\[unrecoverable]** <!-- https://victorio.uit.no/langtech/trunk/ -->
* [lexdb](https://web.archive.org/web/20160408102737/https://bitbucket.org/evoling/lexdb) - LexDB is a lexical cognate tracking database. It stores the full provenance of all lexemes and cognate judgements, and allows export into a number of nexus dialects. The database is written in the flexible python/django web framework. **\[archived]**
* [LinGO Grammar Matrix](http://www.delph-in.net/matrix/) The LinGO Grammar Matrix is a framework for the development of broad-coverage, precision, implemented grammars for diverse languages.
* [Linguistica](http://people.cs.uchicago.edu/~jagoldsm/linguistica-site/) Linguistica is a program designed to explore the unsupervised learning of natural language, with primary focus on morphology (word-structure). It runs under Windows, Mac OS X and Linux, and is written in C++ within the Qt development framework. Its demands on memory depend on the size of the corpus analyzed.
* [Minority Translate](https://bitbucket.org/andrjus/minoritytranslate/) Minority Translate is a simple program for helping content generation on smaller sized Wikipedias (actually any sized) by giving pointers to existing articles in other language Wikipedias, so that the user can easily translate or adapt existing texts and thus increase the size and useability of their Wikipedia editions.
* [NIST 2008 Open Machine Translation Evalutation](https://catalog.ldc.upenn.edu/LDC2010T21)
* [OpenDataKit](https://opendatakit.org/software/) Open Data Kit (ODK) is an open-source suite of tools that helps organizations author, field, and manage mobile data collection solutions
* [SPHERE Conversion Tools](https://web.archive.org/web/20240930120400/https://www.ldc.upenn.edu/language-resources/tools/sphere-conversion-tools) Many LDC corpora contain speech files in NIST SPHERE format. The programs below convert SPHERE files to other formats. **\[archived]**
* [tasty-imitation-keyboard](https://web.archive.org/web/20180611021922/https://github.com/divvun/tasty-imitation-keyboard) - A custom keyboard for iOS8+ that serves as a tasty imitation of the default Apple keyboard. Built using Swift and the latest Apple technologies!. **\[archived]**
* [TiMBL](https://languagemachines.github.io/timbl/) TiMBL is an open source software package implementing several memory-based learning algorithms, among which IB1-IG, an implementation of k-nearest neighbor classification with feature weighting suitable for symbolic feature spaces, and IGTree, a decision-tree approximation of IB1-IG. All implemented algorithms have in common that they store some representation of the training set explicitly in memory. During testing, new cases are classified by extrapolation from the most similar stored cases.
* [VocBench](https://bitbucket.org/art-uniroma2/vocbench3) VocBench is a web-based, multilingual, editing and workflow tool that manages thesauri, authority lists and glossaries using SKOS-XL.
* [Word Generator](http://billposer.org/Software/WordGenerator.html) WordGenerator generates hypothetical words from specifications of their syllable structure.
* [WordBoundary](https://web.archive.org/web/20200703213217/https://github.com/eddersko/WordBoundary) - An experiment in the detection and segmentation of word boundaries. **\[archived]**

## Keyboard Layout Configuration Helpers

* [Keyboard](https://github.com/Mottie/Keyboard) ⭐ 1,801 | 🐛 113 | 🌐 JavaScript | 📅 2022-08-24 - Virtual Keyboard using jQuery \~ <https://mottie.github.io/Keyboard/>.
* [Keyboard layout editor](https://github.com/ijprest/keyboard-layout-editor) ⭐ 1,513 | 🐛 187 | 🌐 JavaScript | 📅 2024-09-17 - Keyboard Layout Editor <http://www.keyboard-layout-editor.com>
* [Keyman](https://github.com/keymanapp/keyman) ⭐ 529 | 🐛 1,173 | 🌐 Pascal | 📅 2026-08-25 - Keyman cross platform input methods. Keyman makes it possible for you to type in over 1,000 languages on Windows, iPhone, iPad, Android tablets and phones, and even instantly in your web browser. [Website](https://keyman.com/).
* [keyboardlayouteditor](https://github.com/simos/keyboardlayouteditor) ⭐ 257 | 🐛 39 | 🌐 Python | 📅 2022-06-17 - Keyboard Layout Editor <https://code.google.com/archive/p/keyboardlayouteditor/>.
* [Keyboards](https://github.com/keymanapp/keyboards) ⭐ 203 | 🐛 38 | 🌐 HTML | 📅 2026-08-25 - Open Source Keyman keyboards.
* [jQuery.IME](https://github.com/wikimedia/jquery.ime) ⭐ 190 | 🐛 72 | 🌐 JavaScript | 📅 2026-08-21 - jQuery Input Method Editor used on Wikipedia
* [kbdgen](https://github.com/divvun/kbdgen) ⭐ 24 | 🐛 16 | 🌐 Rust | 📅 2026-07-04 - Generate keyboards and keyboard layouts for Windows, macOS, X11, iOS, Android and Chrome, from a single, simple yaml file. Also registers languages unknown to Windows, so that after installation, there is a correct and robust association between the designated BCP 47 code (including full support for ISO 639-3) and installed language tools such as keyboards, spelling checkers and other tools.
* [lipika-ime](https://github.com/ratreya/lipika-ime) - Input Method Engine (IME) for Mac OS X with built-in support for all Indic Languages.
* [XKeyboardConfig](https://www.freedesktop.org/wiki/Software/XKeyboardConfig/) - The non-arch keyboard configuration database for X Window. The goal is to provide the consistent, well-structured, frequently released open source of X keyboard configuration data for X Window System implementations (free, open source and commercial). The project is targeted to XKB-based systems.

## Annotation

* [brat](https://github.com/nlplab/brat) ⭐ 1,879 | 🐛 493 | 🌐 Python | 📅 2024-07-03 - brat rapid annotation tool (brat) for online text annotation.
* [WebAnno](https://github.com/webanno/webanno) ⭐ 251 | 🐛 60 | 🌐 Java | 📅 2026-05-09 - Web-based annotation tool for a wide range of linguistic annotations including various layers of morphological, syntactical, and semantic annotations. Distributed under Apache 2.0.
* [FLAT - FoLia Linguistic Annotation Tool](https://github.com/proycon/flat) ⭐ 113 | 🐛 37 | 🌐 JavaScript | 📅 2025-01-24 - FLAT is a web-based linguistic annotation environment based around the FoLiA format (<http://proycon.github.io/folia/>), a rich XML-based format for linguistic annotation. FLAT allows users to view annotated FoLiA documents and enrich these documents with new annotations, a wide variety of linguistic annotation types is supported through the FoLiA paradigm. It is a document-centric tool that fully preserves and visualises document structure.
* [graf-python](https://github.com/cidles/graf-python) ⭐ 21 | 🐛 2 | 🌐 Python | 📅 2014-07-28 - The library graf-python is an open source Python implemenation to parse and write GrAF/XML files as described in ISO 24612. The parser of the library creates an annotation graph from the files. The user may then query the annotation graph via the API of graf-python.
* [poio-api](https://github.com/cidles/poio-api) ⭐ 18 | 🐛 6 | 🌐 Python | 📅 2018-05-18 - Poio API is a free and open source Python library to access and search data from language documentation in your linguistic analysis workflow. It converts file formats like Elan’s EAF, Toolbox files, Typecraft XML and others into annotation graphs as defined in ISO 24612. Those graphs, for which we use an implementation called “Graph Annotation F…
* [pyannotation](https://github.com/cidles/pyannotation) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2012-09-04 - PyAnnotation is a Python Library to access and manipulate linguistically annotated corpus files.
* [poio-analyzer](https://github.com/cidles/poio-analyzer) ⭐ 13 | 🐛 17 | 🌐 Python | 📅 2013-09-24 - Poio is a collection of software tools for linguists working in language documentation, descriptive linguistics and/or language typology. It allows linguists to manage and analyze their data. The Poio Interlinear Editor allows to add morpho-syntactic annotations to transcriptions. It supports various file formats for input, but will only output standardized XML defined by the Corpus Encoding Standard and the Text Encoding Initiative. Several tools for analyzing linguistic data will be made available to further process annotated data. Poio tools are written in Python and are based on PyQt.
* [eopas](https://github.com/eopas/eopas) ⭐ 9 | 🐛 15 | 🌐 Ruby | 📅 2023-05-30 - ETHNOER Online Presentation and Annotation System.
* [brendano/gfl\_syntax](https://github.com/brendano/gfl_syntax) ⭐ 8 | 🐛 7 | 🌐 Python | 📅 2015-07-02 - Graph Fragment Language for Easy Syntactic Annotation. [Website](https://www.cs.cmu.edu/~ark/FUDG/).
* [kwaras](https://github.com/ucsd-field-lab/kwaras) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-04-19 - Tools for ELAN corpus management.
* [LDC Word Aligner](https://github.com/RichardLitt/ldc-word-aligner) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2018-04-24 LDC Word Aligner is a software tool used for manual annotation of word alignment developed to support Arabic-English and Chinese-English word alignment tasks. It has a clean, easy-to-use interface. Since its development in 2009, LDC has used LDC Word Aligner to generate over 1,000,000 tokens of annotated word alignment data from a variety of genres including broadcast, newswire and web-based sources. [Website](https://www.ldc.upenn.edu/language-resources/tools/ldc-word-aligner).
* [AGTK](https://github.com/lowresourcelanguages/agtk) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2016-03-14 - AGTK is a suite of software components for building tools for annotating linguistic signals, time-series data which documents any kind of linguistic behavior (e.g. audio, video). The internal data structures are based on annotation graphs. (Original project is on SourceForge: <https://sourceforge.net/projects/agtk/>).
* [Annotation page](http://annotation.exmaralda.org/index.php/Tools) - Ethnographic tools for annotation.
* [CLAM](https://proycon.github.io/clam/) - Quickly and transparently transforms command-line NLP tools into RESTful webservices with an interface for human end-users.
* [FoLiA: Format for Linguistic Annotation](https://proycon.github.io/folia/) - A rich XML-based annotation format, suitable for the representation of linguistically annotated language resources.
* XTrans Trans is a next generation multi-platform, multilingual, multi-channel transcription tool that supports manual transcription and annotation of audio recordings. The XTrans toolkit provides new and efficient solutions to common transcription challenges and addresses critical gaps in existing tools.Designed with input from experienced human transcribers working with real world data, XTrans provides a flexible and intuitive graphical user interface for a multitude of speech annotation tasks including (virtual) segmentation of audio into smaller units like turns and sentences; speaker identification; orthographic transcription in any language; and labeling of structural elements of the transcript like topics. **\[unrecoverable]** <!-- https://www.ldc.upenn.edu/language-resources/tools/xtrans -->

## Format Specifications

* [xdxf\_makedict](https://github.com/soshial/xdxf_makedict) ⭐ 247 | 🐛 12 | 📅 2024-05-20 - XDXF dictionary format and "makedict" dictionary converting software (official repository).
* [FoLiA](https://github.com/proycon/folia/) ⭐ 66 | 🐛 24 | 🌐 Python | 📅 2025-12-09 FoLiA: Format for Linguistic Annotation - FoLiA is a rich XML-based annotation format for the representation of language resources (including corpora) with linguistic annotations. A wide variety of linguistic annotations are support, making FoLiA a useful format for NLP tasks and data interchange. <http://proycon.github.io/folia/>
* [spec](https://github.com/digitallinguistics/spec) ⭐ 21 | 🐛 37 | 🌐 JavaScript | 📅 2023-02-07 - The official specification for the DLx linguistic data format. <https://digitallinguistics.github.io/spec/>.

## i18n-related Repositories

* [Express-Lingua](https://github.com/akoenig/express-lingua) ⚠️ Archived - An i18n middleware for the Express.js framework.
* [Polyglot.js](https://airbnb.io/polyglot.js/) Give your JavaScript the ability to speak many languages.
* [Transifex](https://www.transifex.com/) - System for providing a nice, userfriendly/project oriented approach to translating `.po` files. Great for non-technical users, free for open-source projects, decent for minority languages; **however**, it can take a while to get a new language added to the Transifex system because the ticketing system Transifex uses results in them losing tickets sometimes. Provides translation memory, ability to appoint reviewers, etc. Transifex used to have an open source system that you could host on your own, but that seems to have disappeared.

## Audio automation

* [dejavu](https://github.com/worldveil/dejavu) ⭐ 6,782 | 🐛 132 | 🌐 Python | 📅 2024-04-22 - Audio fingerprinting and recognition in Python.
* [pyAudioAnalysis](https://github.com/tyiannak/pyAudioAnalysis) ⭐ 6,254 | 🐛 205 | 🌐 Python | 📅 2025-08-04 - Python Audio Analysis Library: Feature Extraction, Classification, Segmentation and Applications.
* [pocketsphinx](https://github.com/cmusphinx/pocketsphinx) ⭐ 4,333 | 🐛 58 | 🌐 C | 📅 2026-08-10 - PocketSphinx is a lightweight speech recognition engine, specifically tuned for handheld and mobile devices, though it works equally well on the desktop.
* [Montreal-Forced-Aligner](https://github.com/MontrealCorpusTools/Montreal-Forced-Aligner) ⭐ 1,872 | 🐛 287 | 🌐 Python | 📅 2026-08-20 - Python interface for forced text/speech alignment.
* [pocketsphinx.js](https://github.com/syl22-00/pocketsphinx.js) ⭐ 1,507 | 🐛 69 | 🌐 JavaScript | 📅 2020-04-05 - Speech recognition in JavaScript.
* [sphinx4](https://github.com/cmusphinx/sphinx4) ⭐ 1,437 | 🐛 29 | 🌐 Java | 📅 2022-10-18 - Pure Java speech recognition library.
* [sphinxbase](https://github.com/cmusphinx/sphinxbase) ⚠️ Archived
* [Prosodylab-Aligner](https://github.com/prosodylab/Prosodylab-Aligner) ⭐ 351 | 🐛 6 | 🌐 Python | 📅 2020-06-28 - Python interface for forced audio alignment using HTK and SoX.
* [pocketsphinx-python](https://github.com/cmusphinx/pocketsphinx-python) ⚠️ Archived - Python module installed with setup.py.
* [node-pocketsphinx](https://github.com/cmusphinx/node-pocketsphinx) ⭐ 241 | 🐛 7 | 🌐 CMake | 📅 2019-03-12
* [html5-audio-read-along](https://github.com/westonruter/html5-audio-read-along) ⚠️ Archived - HTML5 Audio Read-Along.
* [sphinxtrain](https://github.com/cmusphinx/sphinxtrain) ⭐ 189 | 🐛 17 | 🌐 Roff | 📅 2026-08-17
* [ipa-chart](https://github.com/westonruter/ipa-chart) ⭐ 140 | 🐛 8 | 🌐 HTML | 📅 2021-04-28 - International Phonetic Alphabet (IPA) Unicode Chart and Character Picker.
* [esv-text-audio-aligner](https://github.com/westonruter/esv-text-audio-aligner) ⚠️ Archived - ESV Text/Audio Aligner to programmatically obtain the timings for each word in the corresponding audio.
* [pocketsphinx-ios-demo](https://github.com/cmusphinx/pocketsphinx-ios-demo) ⭐ 75 | 🐛 5 | 🌐 Shell | 📅 2018-07-14 - Simple demo for iOS.
* [AuToBI](https://github.com/AndrewRosenberg/AuToBI) ⭐ 66 | 🐛 6 | 🌐 Java | 📅 2019-04-18 - Automatic prosodic annotation tool written in Java.
* [Praat-Scripts](https://github.com/FieldDB/Praat-Scripts) ⭐ 58 | 🐛 3 | 🌐 JavaScript | 📅 2021-12-14 - Mietta's Scripts.
* [PraatontheWeb](https://github.com/monikaUPF/PraatontheWeb) ⭐ 42 | 🐛 1 | 🌐 JavaScript | 📅 2021-09-22 - Web implementation of Praat. Source code, running demo scripts on web, samples and documentation.
* [pocketsphinx-wp-demo](https://github.com/cmusphinx/pocketsphinx-wp-demo) ⭐ 21 | 🐛 0 | 🌐 C | 📅 2016-03-04 - Demo to run pocketsphinx on WP8 platform.
* [kaldi-svn-archive](https://github.com/kaldi-asr/kaldi-svn-archive) ⭐ 19 | 🐛 0 | 🌐 C++ | 📅 2015-07-29 - An read-only archive of the original Kaldi SVN repository (mainly to keep sandboxes available).
* [PraatTextGridJS](https://github.com/FieldDB/PraatTextGridJS) ⭐ 15 | 🐛 4 | 🌐 JavaScript | 📅 2021-12-14 - A small library which can parse TextGrid into json and json into TextGrid.
* [TLSphinx](https://github.com/cmusphinx/TLSphinx) ⭐ 15 | 🐛 0 | 🌐 C | 📅 2019-01-04 - Swift wrapper around Pocketsphinx.
* [prosodylab.alignertools](https://github.com/prosodylab/prosodylab.alignertools) ⭐ 14 | 🐛 5 | 🌐 Python | 📅 2015-04-29
* [pocketsphinx-ruby](https://github.com/cmusphinx/pocketsphinx-ruby) ⭐ 13 | 🐛 0 | 🌐 Ruby | 📅 2015-05-14 - Ruby speech recognition with Pocketsphinx.
* [opensauce](https://github.com/voicesauce/opensauce) ⭐ 5 | 🐛 1 | 🌐 Matlab | 📅 2017-06-30 - GNU Octave-compatible version of VoiceSauce.
* [AudioWebService](https://github.com/FieldDB/AudioWebService) ⭐ 4 | 🐛 5 | 🌐 JavaScript | 📅 2023-03-05 - a simple nodejs server which accepts upload of audio and runs it through praat.
* [prosodicParsing](https://github.com/jpate/prosodicParsing) ⭐ 2 | 🐛 0 | 🌐 Scala | 📅 2012-05-08 - different kinds of HMMs to use for incorporating prosody into basic parsing.
* [Recordmp3js](https://github.com/FieldDB/Recordmp3js) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2015-08-12 - Record MP3 files directly from the browser using JS and HTML.
* [arctic-prompts](https://github.com/psibre/arctic-prompts) ⭐ 1 | 🐛 0 | 📅 2016-04-09 - Generate prompts PDF for CMU ARCTIC dataset.
* [lex4all](https://github.com/FieldDB/lex4all) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2014-06-24 - pronunciation LEXicons for Any Low-resource Language (*Fork* of a student project).
* [BashScriptsForPhonetics](https://github.com/FieldDB/BashScriptsForPhonetics) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2013-10-09 - (*Fork* of a dormant project).
* [praat-py](https://github.com/FieldDB/praat-py) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2012-12-12 - From my PhD days: Praat-Py is a custom build of Praat, the computer program used by linguists for doing phonetic analysis on sound files, to allow for scripts to be written in the Python programming language, rather than in Praat's built-in language. (*Fork* of a dormant project).
* [Audacity](http://audacity.sourceforge.net/) - Free, open source, cross-platform software for recording and editing sounds.
* [CMU Sphinx](https://cmusphinx.github.io/) - Open source toolkit for speech recognition. PocketSphinx, SphinxTrain, Sphinx4, and sphinxbase.
* [ELAN](https://web.archive.org/web/20200307094533/https://tla.mpi.nl/tools/tla-tools/elan/) ELAN is a professional tool for the creation of complex annotations on video and audio resources. **\[archived]**
* [Praat](http://www.fon.hum.uva.nl/praat/) - Praat: doing Phonetics by Computer.
* Recordmp3js - Record MP3 files directly from the browser using JS and HTML (original project). **\[unrecoverable]** <!-- https://github.com/nicklarosa/Recordmp3js -->
* [SoX](http://sox.sourceforge.net/) - SoX, the Swiss Army knife of sound processing programs.
* [WaveSurfer](http://www.speech.kth.se/wavesurfer/) - An open source tool for sound visualization and manipulation.

## Text-to-Speech (TTS)

* [MARY TTS](https://github.com/marytts/marytts) ⭐ 2,583 | 🐛 134 | 🌐 Java | 📅 2025-01-17 - MARY TTS -- an open-source, multilingual text-to-speech synthesis system written in pure java <http://mary.dfki.de>.
* [Indic-TTS](https://github.com/AI4Bharat/Indic-TTS) ⭐ 390 | 🐛 42 | 🌐 Jupyter Notebook | 📅 2024-11-08 - Open-source text-to-speech models for 13 Indian languages including Assamese, Bengali, Hindi, Kannada, Malayalam, Tamil, and Telugu.
* [espeak](http://espeak.sourceforge.net/) - eSpeak is a compact open source software speech synthesizer for English and other languages, for Linux and Windows. <http://espeak.sourceforge.net>.
* [Festival Text to Speech](http://www.festvox.org/festival/) - A general multi-lingual speech synthesis system.
* [Ossian](https://web.archive.org/web/20200221010523/http://homepages.inf.ed.ac.uk/owatts/ossian/html/index.html) - Ossian is a collection of Python code for building text-to-speech (TTS) systems, with an emphasis on easing research into building TTS systems with minimal expert supervision. **\[archived]**

## Automatic Speech Recognition (ASR)

* [kaldi](https://github.com/kaldi-asr/kaldi) ⭐ 15,468 | 🐛 261 | 🌐 Shell | 📅 2025-09-22 - This is now the official location of the Kaldi project.
* [Elpis](https://github.com/CoEDL/elpis) ⭐ 161 | 🐛 77 | 🌐 Python | 📅 2024-06-02 - Elpis is software for creating speech recognition models and applying them to the transcription of audio. As of 2022, it gives access to Kaldi and Huggingface Transformers.
* [Persephone](https://github.com/persephone-tools/persephone) ⭐ 159 | 🐛 91 | 🌐 Python | 📅 2023-04-18 - Persephone aims to make state-of-the-art phonemic transcription accessible to people involved in language documentation, who have a training corpus of about one to four hours of transcribed speech. As of 2022, Persephone is superseded by Elpis.

## Text automation

* [clld](https://github.com/clld/clld) ⭐ 73 | 🐛 4 | 🌐 Python | 📅 2026-07-08 - Cross Linguistic Linked Data python library.
* [LaTeX2HTML5](https://github.com/pyramation/LaTeX2HTML5) ⭐ 60 | 🐛 8 | 📅 2022-05-16 - LaTeX web components.
* [SeedLing](https://github.com/FieldDB/SeedLing) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2014-06-26 - Building and Using A Seed Corpus for the Human Language Project (*Fork* of a student project).
* [MultilingualCorporaExtractor](https://github.com/FieldDB/MultilingualCorporaExtractor) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2013-06-14 - Node io Spider for extracting multilingual corpora (*Fork* of a student project).
* [L3XDG](http://web.archive.org/web/20140703214405/http://code.google.com/p/hltdi-l3/) - Extensible Dependency Grammar (Debusmann, 2007) for translation.

## Experimentation

* [OpenSesame](https://github.com/smathot/OpenSesame) ⭐ 279 | 🐛 86 | 🌐 Python | 📅 2026-07-28 - Graphical experiment builder for the social sciences.
* [experigen](https://github.com/tlozoot/experigen) ⭐ 36 | 🐛 3 | 🌐 HTML | 📅 2020-08-18 - A framework for creating linguistic experiments.
* [PsychScript](https://github.com/EoinTravers/PsychScript) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2014-11-17 - A HTML5/Javascript library for running behavioural experiments online.
* [GamifyPsycholinguisticsExperiments](https://github.com/FieldDB/GamifyPsycholinguisticsExperiments) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2012-05-10 - A simple node server to gamify linguistics experiments, runs offline on a laptop for small scale experiements and online on a server for large scale experiments. Data is sent to a Google spreadsheet. (*Fork* of a dormant project).
* [OPrime](https://github.com/FieldDB/OPrime) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2014-10-15 - Open Source Experimentation Libraries - Online and Offline for Android and HTML5.
* [psychopyMegProsody](https://github.com/FieldDB/psychopyMegProsody) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2013-01-03 - Runs MegProsody using PsychoPy.

## Flashcards

* [Anki](https://github.com/dae/anki) ⭐ 30,036 | 🐛 436 | 🌐 Rust | 📅 2026-08-25 - Anki is a program to make and share flaschard decks (including audio) for any language or writing system. <https://apps.ankiweb.net/>.
* [awesome-anki](https://github.com/tianshanghong/awesome-anki) ⭐ 2,082 | 🐛 10 | 📅 2026-01-02 - A curated list of awesome Anki add-ons, decks and resources.
* [VocabLift](https://github.com/somelinguist/VocabLift) ⭐ 3 | 🐛 3 | 🌐 JavaScript | 📅 2014-06-27 - Language-learning tool that uses vocabulary from LIFT-format dictionaries produced by programs such as Fieldworks Language Explorer and WeSay.

## Natural language generation

* [OpenCCG](https://github.com/OpenCCG/openccg) ⭐ 220 | 🐛 13 | 🌐 Java | 📅 2021-02-03 - OpenCCG library for parsing and realization with CCG. Includes mini-grammars for Inuit, Nezperce, Basque and others.

## Computing systems

* [Common Language Resources and Technology Infrastructure Norway / Clarino](https://clarin.w.uib.no/about/) - One of their projects (not clearly listed here) is about providing an online system for language analysis, so users can connect resources visually, dump in text, and get a result. Kind of like the Yahoo! Pipes but for language processing. Uses the [ABEL](https://www.uio.no/english/services/it/research/hpc/abel/) cluster.

## Android Applications

* [pocketsphinx-android-demo](https://github.com/cmusphinx/pocketsphinx-android-demo) ⭐ 561 | 🐛 12 | 🌐 Java | 📅 2018-11-08
* [pocketsphinx-android](https://github.com/cmusphinx/pocketsphinx-android) ⭐ 239 | 🐛 18 | 🌐 Java | 📅 2020-01-11 - pocketsphinx build for Android.
* [Aikuma](https://github.com/aikuma/aikuma) ⚠️ Archived - Android software for recording and translation.
* [AndroidLanguageLessons](https://github.com/FieldDB/AndroidLanguageLessons) ⭐ 4 | 🐛 2 | 🌐 Java | 📅 2018-11-18 - Lets heritage speakers create self designed language lessons.
* [Bevara](https://github.com/KentonMurray/bevara) ⭐ 4 | 🐛 2 | 🌐 Java | 📅 2013-11-04 - Android Phone Application designed for Linguistic Fieldwork to help preserve, maintain, and save endangered languages.
* [Android Speech Recognition Trainer](https://github.com/FieldDB/AndroidSpeechRecognitionTrainer) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2018-11-18 - Speech recognition training app for low resource languages which interfaces with FieldDB corpora.
* [AndroidFieldDB](https://github.com/FieldDB/AndroidFieldDB) ⭐ 3 | 🐛 1 | 🌐 Java | 📅 2019-06-16 - An Android app which lets the user build a custom visual and auditory vocabulary, useful for guided anomia treatment and self designed language lessons by heritage speakers.
* [AndroidFieldDBElicitationRecorder](https://github.com/FieldDB/AndroidFieldDBElicitationRecorder) ⭐ 3 | 🐛 8 | 🌐 Java | 📅 2013-11-04 - A general purpose video recording tool.
* [android-template](https://github.com/eddersko/android-template) ⭐ 0 | 🐛 1 | 🌐 Java | 📅 2015-02-18 - This is a template of an Android word-learning app that may be used a way to introduce a language. It includes a quiz. For the documentation, go to <http://eddersko.github.io/android-template/>.
* [AndroidProductionExperiment](https://github.com/FieldDB/AndroidProductionExperiment) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2013-10-01 - Android App to run perception experiments.
* [ojoVoz](http://sautiyawakulima.net/ojovoz/) - A mobile app for sending georeferenced image and voice recordings from an Adroid phone to an email address. <!-- used to exist on https://github.com/ojovoz/ojoVoz_mobile -->

## Chrome Extensions

* [babelfrog](https://github.com/dergachev/babelfrog) ⭐ 16 | 🐛 11 | 🌐 JavaScript | 📅 2019-04-23 - Chrome extension to help learn languages as you browse.
* [DictionaryChromeExtension](https://github.com/FieldDB/DictionaryChromeExtension) ⭐ 6 | 🐛 5 | 🌐 JavaScript | 📅 2015-03-02 - Dictionary for websites in low-resource languages. App and codebase which connects to a Wiktionary to provide definitions of any term on any website (current languages Cherokee 194,426 entries, Inuktitut 251 entries, Kartuli 7,363 entries, Plains Cree (incubation) 0 entries) [use](https://chrome.google.com/webstore/detail/my-dictionary/jfmpeiicncingobdejgmmcamknndpbbi).

## FieldDB

*FieldDB* is actively worked on by the [FieldDB (Formally known as OpenSourceFieldlinguistics)](https://github.com/FieldDB) group. These repos explicitly work with it but could be repurposed for other projects.

* [FieldDB](https://github.com/FieldDB/FieldDB) ⭐ 82 | 🐛 55 | 🌐 JavaScript | 📅 2026-01-26 - An offline/online field database which adapts to its user's terminology and I-Language, has plugins for various data automation routines along the process of primary data collection to cleaning to publication and archival. [use](https://wwwdev.lingsync.org/).

### FieldDB Webservices/Components/Plugins

* [fielddb-spreadsheet-sikuli](https://github.com/FieldDB/fielddb-spreadsheet-sikuli) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2015-01-19 - sikuli tests for the spreadsheet module [use](https://www.youtube.com/watch?v=pPN8e1m6RBU\&feature=youtu.be).
* [LexiconWebServiceSample](https://github.com/FieldDB/LexiconWebServiceSample) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2012-05-24 - A node.js web server which implements the fieldlinguist's lexicon API for the FieldDB project.
* [AndroidLanguageLearningClientForFieldDB-sikuli](https://github.com/FieldDB/AndroidLanguageLearningClientForFieldDB-sikuli) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2014-09-30 - Sikuli tests for AndroidLanguageLearningClientForFieldDB.
* [AuthenticationWebService](https://github.com/FieldDB/AuthenticationWebService) ⭐ 0 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-25 - A node.js web service which mananges users and corpora creation and authentication.
* [bower-fielddb-angular](https://github.com/FieldDB/bower-fielddb-angular) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2015-08-04 - A bower repository which hosts fielddb-angular components, bower install fielddb-angular --save.
* [bower-fielddb](https://github.com/FieldDB/bower-fielddb) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2020-07-11 - A bower repository which hosts fielddb core components, bower install fielddb --save.
* [FieldDBActivityFeed](https://github.com/FieldDB/FieldDBActivityFeed) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2015-03-01 - A fielddb activity feed widget which can be embedded in other codebases, websites etc [use](https://chrome.google.com/webstore/detail/lingsync-prototype/eeipnabdeimobhlkfaiohienhibfcfpa).
* [FieldDBGlosser](https://github.com/FieldDB/FieldDBGlosser) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2017-03-12 - A semi-unsupervised language independent morphological analyzer useful for stemming unknown language text, or getting a rough estimate of possible parses for morphemes in a word. bower install fielddb-glosser --save.
* [FieldDBLexicon](https://github.com/FieldDB/FieldDBLexicon) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2017-11-19 - A lexicon browser/editor web widget for FieldDB databases.
* [LanguageClassDashboard](https://github.com/FieldDB/LanguageClassDashboard) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2014-09-08 - App which provides a view of FieldDB corpora for language teachers [use](http://app.phophlo.ca/).
* [LexiconWebService](https://github.com/FieldDB/LexiconWebService) ⭐ 0 | 🐛 1 | 🌐 JavaScript | 📅 2020-07-17 - A node.js ElasticSearch wrapper for indexing/training lexicons from corpora.

## Academic Research Paper-Specific Repositories

* [Gargantua](https://github.com/braunefe/Gargantua) ⭐ 12 | 🐛 1 | 🌐 C++ | 📅 2015-12-09 - Fast Unsupervised Sentence Aligner described in "Improved unsupervised sentence alignment for symmetrical and asymmetrical parallel corpora", COLING 2010.
* [low-resource-pos-tagging-2014](https://github.com/dhgarrette/low-resource-pos-tagging-2014) ⭐ 9 | 🐛 1 | 🌐 Scala | 📅 2016-02-25 and [low-resource-pos-tagging-2014](https://github.com/dhgarrette/low-resource-pos-tagging-2014) ⭐ 9 | 🐛 1 | 🌐 Scala | 📅 2016-02-25 Published in: Learning a Part-of-Speech Tagger from Two Hours of Annotation. *Dan Garrette and Jason Baldridge*. In Proceedings of NAACL 2013. And in: Real-World Semi-Supervised Learning of POS-Taggers for Low-Resource Languages. *Dan Garrette, Jason Mielens, and Jason Baldridge*. In Proceedings of ACL 2013. <!-- ell:ignore -->
* [orthotree](https://github.com/kscanne/orthotree) ⭐ 9 | 🐛 0 | 🌐 Perl | 📅 2015-02-15 - Linguistic family tree based on orthographic distance.
* [type-supervised-tagging-2012emnlp](https://github.com/dhgarrette/type-supervised-tagging-2012emnlp) ⭐ 1 | 🐛 0 | 🌐 Scala | 📅 2016-02-25 This repository contains the code, scripts, and instructions needed to reproduce the results in the paper: Type-Supervised Hidden Markov Models for Part-of-Speech Tagging with Incomplete Tag Dictionaries. *Dan Garrette and Jason Baldridge*. In Proceedings of EMNLP 2012. This code is frozen as of the version used to obtain the results in the paper. It will not be maintained. To see the updated code, visit [nlp](https://github.com/dhgarrette/nlp) ⭐ 0 | 🐛 0 | 🌐 Scala | 📅 2015-07-21 <!-- ell:ignore -->
* [visualizing-language](https://github.com/RichardLitt/visualizing-language) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2012-03-15 - For visualizations of WALS and other typological databases.
* [ldc-kiy](https://github.com/krismyu/ldc-kiy) ⭐ 0 | 🐛 0 | 🌐 OpenEdge ABL | 📅 2013-07-02 - Materials for: The experimental state of mind in elicitation: illustrations from tonal fieldwork. Dubmitted to Language Documentation & Conservation, *How to study a tone language*.
* [WALS-APiCS](https://github.com/jcgood/complexity) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2015-01-12 - Code for working with WALS-APiCS (Atlas of Pidgin and Creole Language Structures) complexity metrics.
* [Learning to map into a Univerisal POS tagset](http://groups.csail.mit.edu/rbg/code/unitag/) Yuan Zhang, Roi Reichart, Regina Barzilay and Amir Globerson

## Example Repositories

*These are repositories that are generally only interesting for training purposes or seeing how something is done.*

* [CorporaForFieldLinguistics](https://github.com/cesine/CorporaForFieldLinguistics) ⭐ 3 | 🐛 0 | 🌐 HTML | 📅 2017-07-11 - Small corpora from diverse language typologies, useful for testing scripts.
* [CorpusWebService](https://github.com/FieldDB/CorpusWebService) ⭐ 0 | 🐛 3 | 🌐 JavaScript | 📅 2022-02-20 - über-simple node.js-Proxy to enable CORS request for couchdb.
* [startR](https://github.com/FieldDB/startR) ⭐ 0 | 🐛 0 | 🌐 R | 📅 2012-11-18
* [lucenerevolution-2013](https://github.com/FieldDB/lucenerevolution-2013) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2013-05-01 - Demo examples for linguistics in Lucene and Solr.
* [berlin-buzzwords-2013](https://github.com/FieldDB/berlin-buzzwords-2013) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2013-06-04 - Demo examples for Lucene, Solr, ElasticSearch and OpenNLP from Berlin Buzzwords 2013 talk.

## Fonts

* [Noto Fonts](https://github.com/googlei18n/noto-fonts) ⚠️ Archived - Noto is Google’s free font family that aims to support all the world’s scripts. Its design goal is to achieve visual harmonization across languages. Noto fonts are under Apache License 2.0.
* [fontinline](https://github.com/sillsdev/fontinline) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2018-08-08 - Make inline stroke paths from an outline font.
* [Unicodify](https://www.lancaster.ac.uk/staff/hardiea/unicodify.htm) Unicodify is a suite of programs for converting text in a variety of 8-bit encodings to Unicode (using the UTF-16 encoding). Unicodify was particularly designed to handle HTML-based text using non-ISCII 8-bit fonts to render South Asian scripts. However, elements of the suite can map other types of non-ASCII 8-bit encodings, such as Latin-2, ISCII and PASCII.

## Corpora

These corpora are useful for working with tools on endangered languages. Monolingual corpora that are more for archival efforts should most likely not be included here.

* [bible-corpus](https://github.com/christos-c/bible-corpus) ⭐ 197 | 🐛 3 | 📅 2025-05-19 - A multilingual parallel corpus created from translations of the Bible.
* [Common Crawl — web-languages](https://github.com/commoncrawl/web-languages) ⭐ 71 | 🐛 7 | 📅 2026-08-24 - Crowd-sourced URL lists to steer the Common Crawl crawler toward under-resourced languages.
* [poio-corpus](https://github.com/cidles/poio-corpus) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2024-12-10 - The Poio Corpus is a freely available collection of language resources for the lesser-used languages. The data is extracted from free sources like Wikipedia, dictionaries, documents, websites and others.
* [Common Crawl — web-languages-code](https://github.com/commoncrawl/web-languages-code) ⭐ 2 | 🐛 2 | 🌐 Python | 📅 2026-06-10 - Code and tooling for the Common Crawl web-languages project.
* [OLDI — Open Language Data Initiative](https://oldi.org/languages) - Curated multilingual datasets (FLORES+, OLDI-Seed) covering \~400 language-script combinations for NLP research.
* [WaxalNLP](https://huggingface.co/datasets/google/WaxalNLP) - Large-scale multilingual speech corpus covering 29 African languages for ASR and TTS research, created by Google.

## Organizations

### On GitHub

* [AI4Bharat](https://github.com/AI4Bharat) - Open-source datasets, tools, and models for Indian languages from IIT Madras, including IndicTrans2 (translation), Indic-TTS, IndicLID (language identification), and IndicVoices.
* [batumi](https://github.com/batumi) - Speech recognition and natural language processing for low-resource languages
* [BloomBooks](https://github.com/BloomBooks)
* [unicode-cldr](https://github.com/unicode-cldr) - Unicode Common Locale Data Repository (CLDR) Project <http://cldr.unicode.org>
* [cmusphinx](https://github.com/cmusphinx) - Mirror of the SourceForge repositories
* [dativebase](https://github.com/dativebase) - Tools for working with OLD.
* [divvun](https://github.com/divvun) - The Divvun group at UiT develops proofing tools, keyboard apps and other language technology solutions for indigenous and minority languages, especially the Sámi languages. [Website](http://divvun.no).
* [FieldDB](https://github.com/FieldDB)
* [GiellaLT](https://github.com/giellalt) - home for keyboard layouts, lexicons and morphologies for indigenous and minority languages, especially for morphologically complex languages, using mainly rule-based techonlogies. The resources are used by Divvun (above) and Giellatekno (below) to build a number of tools for the language communities. Almost everything is open source.
* [HFST](https://github.com/hfst) - Helsinki Finite-State Technology. [Website](http://hfst.github.io/).
* [hunspell](https://github.com/hunspell)
* [keymanapp](https://github.com/keymanapp) - [Website](https://keyman.com/).
* [langtech](https://github.com/langtech) - Language Technology Group, University of Melbourne
* [lex4all](https://github.com/lex4all)
* [longnow](https://github.com/longnow)
* [MontrealCorpusTools](https://github.com/MontrealCorpusTools)
* [moses-smt](https://github.com/moses-smt) - Statistical Machine Translation.
* [mukurtucms](https://github.com/MukurtuCMS)
* [NLTK](https://github.com/nltk) - Natural Language Toolkit.
* [PhonologicalCorpusTools)](https://github.com/PhonologicalCorpusTools)
* [Projet de recherche sur l'écriture](https://github.com/projetDeRechercheSurLecriture/) - Crowdsourcing or conducting large scale psycholinguistics experiments (or statistically significant field linguistics).
* [prosodylab](https://github.com/prosodylab) - Prosodylab at McGill University, Canada
* [SIL International (Dev)](https://github.com/sillsdev) [SIL International](https://www.sil.org/)- Another SIL organization, with many repositories.
* [SIL International](https://github.com/silinternational) - SIL (originally known as the Summer Institute of Linguistics, Inc.) is probably the leading organization which provides software and tools tailored for use by field linguists and lexicographers working on endangered languages. A little known fact is that much of it's code is open sourced on GitHub and SIL is happy to recieve open source contributions and collaborate on open source projects.
* [SIL NRSI](https://github.com/silnrsi) - SIL Non-Roman Script Initiative. The NRSI is a department of SIL International, whose task is to provide assistance, research and development for SIL International and its partners to support the use of non-Roman and complex scripts in language development.
* [StanfordNLP](https://github.com/stanfordnlp) <https://nlp.stanford.edu>
* [ucsd-field-lab](https://github.com/ucsd-field-lab) - University of California, San Diego
* [UniversalDependencies](https://github.com/UniversalDependencies) - Universal Dependencies (UD) is a project that is developing cross-linguistically consistent treebank annotation for many languages, with the goal of facilitating multilingual parser development, cross-lingual learning, and parsing research from a language typology perspective. The annotation scheme is based on an evolution of (universal) Stanford dependencies (de Marneffe et al., 2006, 2008, 2014), Google universal part-of-speech tags (Petrov et al., 2012), and the Interset interlingua for morphosyntactic tagsets (Zeman, 2008). The general philosophy is to provide a universal inventory of categories and guidelines to facilitate consistent annotation of similar constructions across languages, while allowing language-specific extensions when necessary.
* [utcompling](https://github.com/utcompling) - The University of Texas at Austin's Computational Linguistics Lab. [Website](http://www.utcompling.com).

### Other OSS Organizations

* [African Languages Lab](https://www.africanlanguageslab.com/) - Develops enterprise-grade language AI models (including Mansa LLM) supporting 30+ African languages for translation, transcription, and NLP.
* [7000 Languages](https://www.7000.org/) - Creates free online language learning courses and materials in partnership with Indigenous, minority, and refugee communities.
* [Giellatekno](http://giellatekno.uit.no/index.eng.html) - Giellatekno combines cutting-edge linguistic and computational research into the analysis of Saami and other morphologically-rich languages, with the development of practical applications. We focus on deep linguistic modeling and on highly efficient and robust computational analysis with a wide empirical coverage. They use svn for their code: all of it can be found [here](https://victorio.uit.no/langtech/trunk/langs/), sorted by language.
* [Gnani AI](https://www.gnani.ai/) - Voice AI platform with speech-to-text (Vachana STT) and voice models supporting 15+ Indian languages, funded under the IndiaAI Mission.
* [Invisible Languages Project](https://theinvisiblelab.org/) - University of Amsterdam research project studying the representation and visibility of the world's languages in LLMs and on the internet.
* [LOWLANDS](https://bitbucket.org/lowlands/) - LOWLANDS – Parsing low-resource languages and domains <https://ccc.ku.dk/research/lowlands/>
* [LTRC: Language Technologies Research Center IIIT Hyderabad](http://ltrc.iiit.ac.in/) LTRC addresses the complex problem of understanding and processing natural languages in both speech and text mode. LTRC conducts research on both basic and applied aspects of language technology. It is the largest academic centre of speech and language technology in South Asia. LTRC carries out its work through four labs, which work in synergy with each other, as listed above.
* [Sarvam AI](https://www.sarvam.ai/models/) - Open-source Indian language LLMs (Sarvam-1, 30B, 105B) supporting 22 scheduled Indian languages, available on [HuggingFace](https://huggingface.co/sarvamai) and [GitHub](https://github.com/sarvamai).
* [SILICON Stanford](https://silicon.stanford.edu/) - Stanford Initiative on Language Inclusion and Conservation in Old and New Media, advancing digital inclusion for underrepresented and endangered languages.
* [Soket AI](https://soket.ai/) - Open-source Indian language models including Pragna-1B (4 Indian languages) and the Bhasha dataset series for training Indian language models.
* [The Language Archive](https://tla.mpi.nl/tools/tla-tools/) Part of the MPI
* [Vakyansh / EkStep](https://github.com/Open-Speech-EkStep/vakyansh-models) ⭐ 328 | 🐛 8 | 📅 2022-09-16 - Open-source speech-to-text models for Indic languages with 10,000+ hours of training data across 23 languages.
* [Wikitongues](https://wikitongues.org/) - Nonprofit preserving linguistic diversity through a language archive of 700+ languages and grants for endangered language revitalization projects.

## Tutorials

* [How to Write a Spelling Corrector](http://norvig.com/spell-correct.html) by [Peter Norvig](http://norvig.com/).

## Language Specific Projects

For each language, we include the [ISO 639-3 code](https://en.wikipedia.org/wiki/ISO_639-3), and the main autonym for that language.

### Afrikaans

*afr :: Afrikaans*

* [Afrikaanse rekenaarlinguïstiek (Afrikaans computational linguistics)](https://web.archive.org/web/20211025200827/http://xixona.dlsi.ua.es/~fran/afrikaans/index.old.html) — wordlists, corpora, morphological analyser, tagger, word decompounder. Available upon email. **\[archived]**

### Albanian

*sqi :: shqip*

* [Apertium rules for Albanian](https://sourceforge.net/p/apertium/svn/41266/tree/incubator/apertium-mk-sq/) - Machine Translation rules
* [out-of-copyright-albanian-authors](https://web.archive.org/web/20200910215835/https://github.com/substack/out-of-copyright-albanian-authors) - authors scraped from the albanian language wikipedia who are out of copyright. **\[archived]**
* [Plis keyboard](http://plisi.org/tastiera/) - The Plis keyboard is a keyboard or computer keyboard layout for the Albanian language.
* [spell checking](http://www.shkenca.org/k6i/index.html) - Here you find a collection of Albanian words and information about them. Aspell, Ispell, and MySpell are included.

### Alutiiq

*ems :: sugpiaq*

* [wiinaq](https://github.com/futurulus/wiinaq) ⭐ 2 | 🐛 2 | 🌐 Python | 📅 2023-04-21 - Word Wiinaq is a [Kodiak Alutiiq](http://www.alutiiqlanguage.org/) dictionary web application with automatically generated ending tables and souped-up search capabilities. It is written in Python using Django.

### Amharic

*amh :: Amarigna / አማርኛ*

* [HornMorpho](https://github.com/LowResourceLanguages/hltdi-morphology) ⭐ 5 | 🐛 0 | 📅 2015-04-17 - morphological analysis and generation of Amharic and Oromo verbs and nouns and Tigrinya verbs.

### Basque

*eus :: euskara*

* [Matxin](http://matxin.sourceforge.net/) - An open-source transfer machine translation engine. Linguistic information for the translation from Spanish and Basque (es-eu) is included.

### Belarusian

*bel :: беларуская мова*

* [belmorph](https://github.com/alesdrobysh/belmorph) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-11 - Zero-dependency morphological analyzer for Belarusian (JavaScript/TypeScript).

### Bengali

*ben :: Bangla / বাংলা*

* [Bengali Writer](https://github.com/LowResourceLanguages/bwedit) ⭐ 1 | 🐛 0 | 🌐 Tcl | 📅 2016-03-14 - \`Bengali Writer' is a set of utilities for computerized editing and typesetting in Bengali, a language of India and Bangladesh. It comprises a set of fonts for Bengali in several formats (METAFONT, BDF, PS), a text editor with spell-cheking, export, and more. (Original project is on SourceForge: <https://sourceforge.net/projects/bengaliwriter/>).
* [Lekho](https://github.com/LowResourceLanguages/lekho) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2016-03-14 - A collection of tools and resources for using bangla on computers (Original project is on SourceForge: <https://sourceforge.net/projects/lekho/>).
* [Bangla-অঙ্কুর for Mac](https://sourceforge.net/projects/onkur/) This project aims to develop a phonetic based Bangla typing system for Macintosh computer which can be developed into a transliteration technique in the future.
* [Ekushey](https://sourceforge.net/projects/ekushey/) Bangla Computing and Localization Project for the Bangla speaking people.

### Chichewa

*nya :: Chicheŵa*

* [Chichewa](https://github.com/kscanne/chichewa) ⭐ 11 | 🐛 1 | 🌐 Makefile | 📅 2021-04-03 - NLP resources for Chichewa.

### Galician

*glg :: galego*

* [Linguakit](https://github.com/citiususc/Linguakit) ⭐ 63 | 🐛 4 | 🌐 Perl | 📅 2024-02-24 - Multilingual toolkit for NLP: dependency parser, PoS tagger, NERC, multiword extractor, sentiment analysis, etc.
* [DepPattern](https://github.com/gamallo/DepPattern) ⭐ 10 | 🐛 0 | 🌐 Perl | 📅 2018-06-07 - Dependency Syntactic Parsing for Portuguese, Spanish, English, and Galician, including MetaRomance parser
* [CitiusSentiment](https://github.com/gamallo/CitiusSentiment) ⭐ 7 | 🐛 0 | 🌐 Perl | 📅 2016-05-06 - Sentiment analysis (opinion mining) for Portuguese, English, Spanish, and Galician
* [UD\_Galician-TreeGal](https://github.com/UniversalDependencies/UD_Galician-TreeGal) ⭐ 6 | 🐛 0 | 📅 2026-05-06 - The Galician-TreeGal is a treebank for Galician developed at LyS Group (Universidade da Coruña).
* [javagalician-java6](https://github.com/javagalician/javagalician-java6) ⚠️ Archived - The Java Galician Locale is an implementation of Java localization SPIs which will allow the Java VM to use the Galician Language (locales "gl" and "gl\_ES"), one of the official languages of Spain, which is not included in Sun's JVM distribution.
* [an-metri-gal](https://github.com/juliojgd/an-metri-gal) ⭐ 3 | 🐛 3 | 🌐 OCaml | 📅 2026-05-31 - Análise métrico de texto en verso en lingua galega (Galician language) gl-ES
* [android\_gl\_dict](https://github.com/chavaone/android_gl_dict) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2013-01-23 - Android Galician (gl\_ES) Keyboard Dictionary
* [corpora](https://github.com/bertez/corpora) ⭐ 2 | 🐛 0 | 📅 2016-01-08 - This is a collection of corpus of Galician (or related to Galicia) words / Colección de corpus de palabras en galego (ou relacionadas con Galicia)
* [galeXtra](https://github.com/gamallo/galeXtra) ⭐ 2 | 🐛 0 | 🌐 Perl | 📅 2024-12-30 - Multiword Extractor for Portuguese, English, Spanish, Galician, French
* [aspell-gl](https://github.com/pld-linux/aspell-gl) ⭐ 1 | 🐛 0 | 📅 2026-02-22 - Galician dictionary for aspell
* [elFinder-language](https://github.com/Rubarez/elFinder-Language) ⭐ 1 | 🐛 0 | 📅 2016-09-23 - Galician - Gallego / language for elFinder
* [EuroWordNetLemon](https://github.com/martavillegas/EuroWordNetLemon) ⭐ 1 | 🐛 2 | 📅 2015-09-09 - EuroWordNet lemon lexicons generated from the LMF versions of the Multilingual Central Repository (MCR) EuroWordNet lexicons. It includes lexicons for Spanish, Catalan, Basque & Galician.
* [Galician-Dependency-Treebank](https://github.com/paulomalvar/Galician-Dependency-Treebank) ⭐ 1 | 🐛 0 | 📅 2016-10-10 - This Galician Dependency Treebank has been developed by transliterating and adapting lexically the Portuguese part (Bosque 7.3 by the Floresta sintá(c)tica project) of the CONLL-X 2006.
* [Galician-Fuzzy-Text-watch](https://github.com/pfsq/Galician-Fuzzy-Text-watch) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2015-12-31 - Based on Fuzzy Text International by Jesse Hallett, uses the galician language to display time.
* [galician-locale-for-mac](https://github.com/vaites/galician-locale-for-mac) ⚠️ Archived - Galician locale for Mac OS X
* [gl-syllabler](https://github.com/bertez/gl-syllabler) ⭐ 1 | 🐛 2 | 🌐 JavaScript | 📅 2016-01-10 - Split galician language words into syllables
* [gl](https://github.com/OmegaT-L10N/gl) ⭐ 1 | 🐛 0 | 📅 2025-12-28- Galician OmegaT Localisation
* [hunspell-gl](https://github.com/gooselinux/hunspell-gl) ⚠️ Archived - Galician hunspell dictionaries
* [hyphen-gl](https://github.com/gooselinux/hyphen-gl) ⚠️ Archived - Galician hyphenation rules
* [poss-gl](https://github.com/nosolosw/poss-gl) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2011-07-20 - Galician translation of Producing Open Source Software, by Karl Fogel
* [rima](https://github.com/bertez/rima) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2016-02-01 - Find rhyming words in galician language.
* [stopwords-gl](https://github.com/stopwords-iso/stopwords-gl) ⭐ 1 | 🐛 0 | 📅 2016-10-10 - Galician stopwords collection
* [texlive-babel-galician](https://github.com/OpenMandrivaAssociation/texlive-babel-galician) ⭐ 1 | 🐛 0 | 📅 2026-07-11 - TeXLive babel-galician package
* [UD\_Galician-CTG](https://github.com/UniversalDependencies/UD_Galician-CTG) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2026-05-06 - The Galician UD treebank is based on the automatic parsing of the Galician Technical Corpus created at the University of Vigo by the the TALG NLP research group.
* [DOGA\_scraper](https://github.com/jjelosua/DOGA_scraper) ⭐ 0 | 🐛 0 | 🌐 Ruby | 📅 2014-09-13 - Galician Official journal scraper
* [hunspell-gl-ciencias](https://github.com/mglbranco/hunspell-gl-ciencias) ⭐ 0 | 🐛 0 | 📅 2013-08-04 - Project oriented into developing a science and maths Galician language Hunspell dictionary
* [ParlamentoGalicia](https://github.com/jjelosua/ParlamentoGalicia) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2013-04-14 - Project based on the information extracted from the transcriptions of the sessions held in the Galician Parlament
* [UL\_Galician-TreeGal](https://github.com/conllul/UL_Galician-TreeGal) ⭐ 0 | 🐛 0 | 📅 2018-05-08 - CoNLL-UL Repository for UD\_Galician-TreeGal
* [CitiusTagger](https://gramatica.usc.es/pln/tools/CitiusTools.html) - A PoS-Tagger and Named Entity Classification tool for Portuguese, English, Galician, and Spanish
* [Conshuga](https://gramatica.usc.es/pln/tools/conjugador/download.html) - Galician verb conjugator
* [GalegoDroid](https://web.archive.org/web/20180610234243/https://github.com/amsqr/GalegoDroid) - Galician Translator for Android **\[archived]**

#### Apertium

* [apertium-cat-glg](https://github.com/apertium/apertium-cat-glg) ⭐ 1 | 🐛 0 | 🌐 XML | 📅 2022-07-16 - Apertium translation pair for Catalan and Galician
* [apertium-dict-en-gl](https://github.com/pld-linux/apertium-dict-en-gl) ⭐ 1 | 🐛 0 | 📅 2026-04-05 - English-Galician language pair for Apertium
* [apertium-dict-es-gl](https://github.com/pld-linux/apertium-dict-es-gl) ⭐ 1 | 🐛 0 | 📅 2026-02-20 - Spanish-Galician language pair for Apertium
* [apertium-dict-pt-gl](https://github.com/pld-linux/apertium-dict-pt-gl) ⭐ 1 | 🐛 0 | 📅 2026-04-05 - Portuguese-Galician language pair for Apertium
* [apertium-es-gl](https://github.com/apertium/apertium-es-gl) ⭐ 1 | 🐛 2 | 🌐 XML | 📅 2021-07-19 - Apertium translation pair for Spanish and Galician
* [apertium-en-gl](https://github.com/apertium/apertium-en-gl) ⭐ 0 | 🐛 2 | 🌐 XML | 📅 2022-05-08 - Apertium translation pair for English and Galician
* [apertium-glg](https://github.com/apertium/apertium-glg) ⭐ 0 | 🐛 0 | 🌐 XML | 📅 2022-08-12 - Apertium linguistic data for Galician
* [Apertium-pt-gl.pt-gl-LMF](https://github.com/apertium-lmf/Apertium-pt-gl.pt-gl-LMF) ⭐ 0 | 🐛 0 | 📅 2014-07-31 - This is the LMF version of the Apertium bilingual ditionary for Portugues and Galician languages
* [apertium-pt-gl](https://github.com/apertium/apertium-pt-gl) ⭐ 0 | 🐛 1 | 🌐 XML | 📅 2021-07-20 - Apertium translation pair for Portuguese and Galician

### Georgian

*kat :: Kartuli / ქართული*

* [awesome-georgia](https://github.com/Stichoza/awesome-georgia) ⭐ 94 | 🐛 0 | 📅 2024-12-22 - A curated list of awesome libraries and packages specific/related to Georgia (country).
* [GeoWordsDatabase](https://github.com/bumbeishvili/GeoWordsDatabase) ⭐ 73 | 🐛 0 | 📅 2017-12-09 - Around 310 000 unique Georgian words <https://bumbeishvili.github.io/GeoWordsDatabase/>.
* [Kartuli Speech Recognition](https://github.com/batumi/KartuliSpeechRecognition) ⭐ 4 | 🐛 11 | 🌐 C | 📅 2017-12-21 - ანდროიდის ქართველი მომხმარებლებისთვის სიტყვის ამოცნობის სისტემის შექმნა. Codebase to turn any webpage from any alphabet into another alphabet, the default is to turn latin letters into Kartuli. [use](https://chrome.google.com/webstore/detail/kartuli-glasses/ccmledaklimnhjchkcgideafpglhejja) "Do your friends keep commenting on Facebook with English keyboards (either because they forgot to switch, or because they didn't/can't install a Georgian keyboard)? Now you can read the web through კართული eyes.".
* [translitit-latin-to-mkhedruli-georgian](https://github.com/batumi/translitit-latin-to-mkhedruli-georgian) ⭐ 4 | 🐛 1 | 🌐 JavaScript | 📅 2017-03-27 - A Latin to ქართული (Mkhedruli Georgian) transliteration function written in JavaScript.
* [Declensions](https://github.com/opinion-mining-south-caucasus/declensions) ⭐ 2 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-11-07 - Methods to generate declensions for Georgian language
* [Gadatsqvetilebebi](https://github.com/batumi/Gadatsqvetilebebi) ⭐ 1 | 🐛 3 | 🌐 JavaScript | 📅 2017-03-27 - გადაწყვეტილებები; Web spider and corpora importer for public legal decisions.
* [KartuliChromeExtension](https://github.com/batumi/KartuliChromeExtension) ⭐ 1 | 🐛 1 | 🌐 JavaScript | 📅 2014-04-19 - Chrome აპლიკაცია, რომელიც ყველა ინგლისურ ასო-ბგერას აჩვენებს ქართულ ასო-ბგერად.
* [QartuliDaBunebismetkveleba](https://github.com/aiSaba/QartuliDaBunebismetkveleba) ⭐ 1 | 🐛 4 | 🌐 ActionScript | 📅 2013-12-15 - მათემატიკისა და ბუნებისმეტყველების ინტერაქტიული სახელმძღვანელო მე-2 - მე-3 კლასის მოსწავლეებისათვის.
* [translitit-mkhedruli-georgian-to-ipa](https://github.com/batumi/translitit-mkhedruli-georgian-to-ipa) ⭐ 1 | 🐛 1 | 🌐 JavaScript | 📅 2017-03-27 - A Latin to ქართული (Mkhedruli Georgian) transliteration function written in JavaScript.
* [SakartvelosUzenaesiSasamartloSarke](https://github.com/batumi/SakartvelosUzenaesiSasamartloSarke) ⭐ 0 | 🐛 0 | 📅 2014-05-20 - საქართველოს უზენაესი სასამართლო სარკე.
* [SamartlosSakonstitutsioSasamartdoSarke](https://github.com/batumi/SamartlosSakonstitutsioSasamartdoSarke) ⭐ 0 | 🐛 0 | 📅 2017-03-26 - სამართლოს საკონსტიტუციო სასამართდო სარკე.

#### Fonts

* [Stichoza/font-larisome](https://github.com/Stichoza/font-larisome) ⭐ 39 | 🐛 0 | 🌐 SCSS | 📅 2025-07-18 - Iconic font for Georgian currency inspired by Font-Awesome (CSS).
* [thecotne/georgian-webfonts](https://github.com/thecotne/georgian-webfonts) ⚠️ Archived - Package for georgian fonts (CSS).
* [Lotuashvili/BPGNateli](https://github.com/Lotuashvili/BPGNateli) ⭐ 0 | 🐛 0 | 🌐 CSS | 📅 2015-09-01 - Bower package for BPG Nateli font (CSS).

#### Internationalization and Localization (i18n/l10n)

* [moment/moment](https://github.com/moment/moment) ⭐ 47,916 | 🐛 106 | 🌐 JavaScript | 📅 2026-08-23 - A lightweight date library (JavaScript).
* [wenzhixin/bootstrap-table](https://github.com/wenzhixin/bootstrap-table) ⭐ 11,809 | 🐛 202 | 🌐 JavaScript | 📅 2026-08-25 - Bootstrap table with extra features. l10n by [@Lotuashvili](https://github.com/Lotuashvili) and [@Stichoza](https://github.com/Stichoza).
* [ioseb/geokbd](https://github.com/ioseb/geokbd) ⭐ 57 | 🐛 1 | 🌐 JavaScript | 📅 2009-11-29 - Georgian keyboard library (JavaScript).
* [Landish/Laravel-Ka](https://github.com/Landish/Laravel-KA) ⚠️ Archived - [Laravel](https://laravel.com/) Georgian Language Pack.
* [Stichoza/money-num-to-string](https://github.com/Stichoza/money-num-to-string) ⭐ 7 | 🐛 0 | 🌐 PHP | 📅 2024-01-04 - Convert a number/money to localized string (PHP, JavaScript).
* [dimakura/ka.js](https://github.com/dimakura/ka.js) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2014-09-09 - Georgian language support for node and browser (JavaScript).
* [akalongman/kautilities](https://github.com/akalongman/kautilities) ⭐ 4 | 🐛 0 | 🌐 PHP | 📅 2016-06-23 - Convert Georgian letters to Latin and vice-versa (PHP).
* [natchkebiailia/NumberToWord](https://github.com/natchkebiailia/NumberToWord) ⭐ 3 | 🐛 1 | 🌐 JavaScript | 📅 2017-10-27 - Convert numbers to localized strings (JavaScript).
* [d0ragon/number-to-words-ka](https://github.com/d0ragon/number-to-words-ka) ⭐ 3 | 🐛 0 | 🌐 PHP | 📅 2014-06-03 - Convert numbers to localized strings (PHP).
* [dimakura/ka](https://github.com/dimakura/ka) ⭐ 0 | 🐛 0 | 🌐 Ruby | 📅 2013-11-09 - Common functionality for georgian projects (Ruby).
* [Landish/RedactorJS-GE](https://web.archive.org/web/20230101042541/https://github.com/Landish/RedactorJS-GE) - Redactor WYSIWYG HTML Editor Georgian Language Pack (JavaScript). **\[archived]**

### Guarani

*grn :: Guarani*

* [ParaMorfo](https://github.com/LowResourceLanguages/hltdi-morphology) ⭐ 5 | 🐛 0 | 📅 2015-04-17 - morphological analysis and generation of Spanish and Guarani verbs, nouns, and adjectives.

### Hausa

*hau :: Hausa / هَرْشَن هَوْسَ*

* [Hausa](https://github.com/amir-zeldes/hausa) ⭐ 6 | 🐛 0 | 📅 2015-08-25 - Repository for Hausa NLP tools.

### Hindi

*hin :: Hindi / हिन्दी*

* [hindi-morph](https://github.com/FieldDB/hindi-morph) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2013-05-01 - An open source morphological analyzer for Hindi.

### Høgnorsk

*nno :: Høgnorsk*

* hunspell-hn\_NO - A beginning to a spellchecking tool for Høgnorsk, a conservative variant of Norwegian Nynorsk, based on a set of corpuses. **\[unrecoverable]** <!-- https://github.com/rtxanson/hunspell-hn_NO -->

### Icelandic

*isl :: Íslenska*

* [IceNLP](https://github.com/hrafnl/icenlp) ⭐ 22 | 🐛 0 | 🌐 Lex | 📅 2024-02-23 - IceNLP is an open source Natural Language Processing (NLP) toolkit for analyzing and processing Icelandic text. The toolkit is implemented in Java.

### Inuktitut

*iku :: Inuktitut*

* [InuktitutComputing](https://github.com/LowResourceLanguages/InuktitutComputing) ⭐ 10 | 🐛 0 | 🌐 Java | 📅 2015-08-02 - Inuktitut Morphological Analyser, transcoder, transliterator, corpus tools, and lexical lists for working with Inuktitut. Usable online at <http://inuktitutcomputing.ca/index.php>.
* [InuktitutAlignerData](https://github.com/cmesher/InuktitutAlignerData) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2012-06-11 - Scripts for alignment of laboratory speech production data.

### Irish

*gle :: Gaeilge*

* [caighdean](https://github.com/kscanne/caighdean) ⭐ 21 | 🐛 0 | 🌐 Perl | 📅 2024-09-14 - Code for standardizing Irish language text.
* [GaelSpell](https://github.com/kscanne/gaelspell) ⭐ 21 | 🐛 0 | 🌐 HTML | 📅 2024-11-22 - Sources for an Irish language spell checker.
* [tesseract-gle-uncial](https://github.com/kscanne/tesseract-gle-uncial) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2015-04-27 - OCR for old Irish fonts.
* [fleiscin](https://github.com/hyphenation/fleiscin) ⭐ 1 | 🐛 0 | 🌐 HTML | 📅 2020-11-08 - Irish hyphenation patterns for TeX <https://cadhan.com/fleiscin/>.
* [aimsigh](https://github.com/kscanne/aimsigh) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2023-09-15 - Source for the now-defunct aimsigh.com Irish search engine.

### Kinyarwanda

*kin :: Ikinyarwanda*

* [kin-morph-fst](https://github.com/ldmt-muri/kin-morph-fst) ⭐ 6 | 🐛 0 | 🌐 Java | 📅 2013-08-26 - Kinyarwanda morphological analyzer.
* [TurboTagger & TurboParser for Kinyarwanda (download)](https://web.archive.org/web/*/http://www.ark.cs.cmu.edu/TurboParser/nasmith_models/kin-turbo-v1.0.tgz) TurboTagger & TurboParser for Kinyarwanda

### Kurdish

*kur :: Kurdî*

* [kurmanji-stemmer](https://github.com/adelra/kurmanji-stemmer) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2015-08-26 - NLTK based kurmanji stemmer
* [kurlex](https://gitlab.inria.fr/almanach/alexina/kurlex) - Morphological analyser and lexicon, written in the Alexina framework, licensed under the LGPL-LR.

### Lingala

*lin :: Lingála*

* [Lingala NLP](https://sourceforge.net/projects/lingala/) NLP tools and resources for Lingala

### Lushootseed

*lut :: Lushootseed*

* [Lushootseed](https://github.com/LowResourceLanguages/lushootseed) ⭐ 0 | 🐛 0 | 📅 2016-05-23 - Joshua Crowgey's work on Lushootseed <http://students.washington.edu/jcrowgey/lushootseed/>.

### Malay

*msa :: Bahasa Melayu*

* [MorfoMelayu](https://github.com/LowResourceLanguages/hltdi-morphology) ⭐ 5 | 🐛 0 | 📅 2015-04-17 - morphological analysis of Malay words.

### Malagasy

*mlg :: Malagasy*

* [Global Voices Malagasy Project](http://www.cs.cmu.edu/~ark/global-voices/) This page provides a link to a corpus of parallel news articles in Malagasy and English from the Global Voices project. This corpus was collected and aligned at the sentence level by Victor Chahuneau.

### Manx

*glv :: Gaelg*

* [gaelg](https://github.com/kscanne/gaelg) ⭐ 3 | 🐛 5 | 🌐 Perl | 📅 2024-08-27 - NLP resources for Manx Gaelic, mainly in support of the gv2ga MT engine.
* [aspell-gv](https://github.com/pld-linux/aspell-gv) ⭐ 1 | 🐛 0 | 📅 2026-02-22 - Manx Gaelic dictionary for aspell.

### Migmaq

*mic :: Mi'kmaq*

* [migmaq-lessons](https://github.com/FieldDB/migmaq-lessons) ⭐ 1 | 🐛 4 | 🌐 CSS | 📅 2015-06-03 - Repository for website building Mi'gmaq language lessons.

### Minderico

*drc :: Piação do Ninhou*

* [fredericajordarzambarino](https://github.com/cidles/fredericajordarzambarino) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2014-09-04 - A web based game for mobile devices in minderico based in the "Who Wants to be a Millionaire" TV show.

### Nishnaabe

*oji :: Ojibwe, Oddawa, Chippewa, Anishinaabemowin, ᐊᓂᔑᓈᐯᒧᐎᓐ*

* [OjibwayMap](https://github.com/LowResourceLanguages/OjibwayMap) ⭐ 3 | 🐛 0 | 🌐 Objective-C | 📅 2015-08-02 - An iPhone app with audio and images for learning Ojibway language and culture.
* [Ojibway-iphone-app](https://github.com/LowResourceLanguages/Ojibway-iphone-app) ⭐ 1 | 🐛 0 | 🌐 Objective-C | 📅 2015-08-01 - An iPhone app with audio and images for learning the Ojibway language.
* [nishanimate](https://github.com/jpmontano/nishanimate) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2015-07-21 - A desktop app to facilitate Nishnaabe-language acquisition via animations produced by the natural language processing of audio-accompanied text.

### Oromo

*orm :: Oromo*

* [HornMorpho](https://github.com/LowResourceLanguages/hltdi-morphology) ⭐ 5 | 🐛 0 | 📅 2015-04-17 - morphological analysis and generation of Amharic and Oromo verbs and nouns and Tigrinya verbs.

### Quechua

*que :: Runa Simi*

* [AntiMorfo](https://github.com/LowResourceLanguages/hltdi-morphology) ⭐ 5 | 🐛 0 | 📅 2015-04-17 - morphological analysis and generation of Quechua nouns, adjectives, and verbs and Spanish verbs.
* [Morphology, spellchecker](https://pub.cl.uzh.ch/projects/squoia/normalizer.html) - XFST and FOMA, plus OpenOffice plugin.

### Sami

*sma :: Sámi/Saami*

* [divvun-webdemo](https://github.com/divvun/divvun-webdemo) ⭐ 2 | 🐛 3 | 🌐 JavaScript | 📅 2023-07-12 - simple webdemo for divvun grammar checker. [Website](https://gtweb.uit.no/gc/).
* [Giellatekno](http://giellatekno.uit.no/) A host of Sámi tools.
  * Mobile keyboards (iOS and Android), learning apps, dictionaries, morphologies, syntax disambiguators, some amount of project collaboration with Apertium on shallow translation between Saami languages, and
* [Oahpa!](http://oahpa.no) - A learning portal for Saami languages. Includes WordPress based, media rich lesson-based learning, and morphological and syntactic exercizes generated from the morphological and syntactic tools
* [Neahttadigisánit](https://sanit.oahpa.no/about/) - A morphologically sensitive dictionary, with modes for 'social media input' (which allows users to type a 'relaxed' version of the orthography (*acdnstz* will be recognized also as *áčđŋšŧz̄*), and also includes a JavaScript bookmarklet to offer click-to-read dictionary lookup functionality. Also available for [other Uralic, and non-Uralic languages](http://dicts.uit.no/index.eng.html).

Giellatekno also supports many other minority Uralic and non-Uralic languages:

* Saami languages: North Saami, Lule Saami, South Saami, Inari Saami, Kildin Saami, Pite Saami, Skolt Saami.
* Other Uralic languages: Erzya, Finnish, Hill Mari, Ingrian, Khanty, Kven, Komi, Livonian, Meadow Mari, Moksha, Nenets, Nganasan, Olonetsian, Udmurt, Veps.
* Other languages: Buriat, Cornish, Faroese, Greenlandic, Inupiaq, Northern Haida, Ojibwe, Plains Cree, Russian.

### Scottish Gaelic

*gla :: Gàidhlig*

* [hunspell-gd](https://github.com/kscanne/hunspell-gd) ⭐ 10 | 🐛 0 | 🌐 Makefile | 📅 2023-02-20 - Files for building Scottish Gaelic spell checkers.
* [gdbank](https://github.com/colinbatchelor/gdbank) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2025-02-03 - Some tools and resources for natural language processing of Scottish Gaelic. <https://www.tantallon.org.uk/cggblog/>.
* [gaidhlig](https://github.com/kscanne/gaidhlig) ⭐ 3 | 🐛 0 | 🌐 Perl | 📅 2025-09-05 - NLP resources for Scottish Gaelic, mainly in support of gd2ga/ga2gd MT engines.
* [gd-fcfg](https://github.com/wojtekdz/gd-fcfg) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2012-03-27 - Context-free feature-based grammar of Scottish Gaelic in the NLTK format.
* [briathrachan](https://github.com/tobiasbayer/briathrachan) ⭐ 2 | 🐛 0 | 🌐 Objective-C | 📅 2016-10-24 - This is the source code to Briathrachan, a Gaelic-English dictionary app for iOS.
* [aspell-gd](https://github.com/pld-linux/aspell-gd) ⭐ 1 | 🐛 0 | 📅 2026-02-22 - Scottish Gaelic dictionary for aspell.

### Secwepemctsin

*shs :: Secwepemctsín*

* [secwepemctsnem](https://github.com/neskie/secwepemctsnem) ⭐ 2 | 🐛 0 | 🌐 ActionScript | 📅 2010-10-28 - A project to help people learn Secwepemctsín.

### Somali

*som :: Soomaaliga*

* [qaamuus.net](http://qaamuus.net/) morphologically aware dictionary based on lexical resources found online, and the somali morphology.
* somorph - Somali morphological and syntactic analyzers and generators built on XFST and VISL-CG Constraint Grammar. Up to date version checked in on [Giellatekno's](http://giellatekno.uit.no) repository. **\[unrecoverable]** <!-- https://github.com/rtxanson/somorph -->

### Tigrinya

*tir :: Tigrinya / ትግርኛ*

* [HornMorpho](https://github.com/LowResourceLanguages/hltdi-morphology) ⭐ 5 | 🐛 0 | 📅 2015-04-17 - morphological analysis and generation of Amharic and Oromo verbs and nouns and Tigrinya verbs.

### Uralic

*urj :: Uralic languages*

* [UralicNLP](https://github.com/mikahama/uralicNLP) ⭐ 100 | 🐛 0 | 🌐 Python | 📅 2026-03-12 - A Python library for processing Uralic languages (Finnish, Skolt Sami, Erzya, Moksha, Komi-Zyrian and so on). The library provides an easy programmatic access to Giellatekno resources such as FST morphology and CG disambiguators. Other functionalities include UD parser, API for the [Online Dictionary of Uralic Languages](https://akusanat.com) and interface to SemFi and SemUr semantic databases. The library is under active development and new features are added from time to time.

### Zulu

*zul :: Zulu*

* [Ukwabelana](http://www.cs.bris.ac.uk/Research/MachineLearning/Morphology/resources.jsp#corpus) An open-source morphological Zulu corpus

> **\[archived]** = link replaced with archived copy via [Wayback Machine](https://web.archive.org) ·
> **\[unrecoverable]** = link no longer available, kept for reference

## License

[![License: CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/). Original content by Richard Littauer, 2014-2017.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-25._
