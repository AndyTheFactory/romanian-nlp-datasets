# A list of Romanian NL Datasets
A curated list of open source and open access Romanian Language NLP Datasets.
For the moment we don't add parallel copora to the list.

For additions or any other changes please submit a pull request.

Table of contents
=================

<!--ts-->
   * [Unlabeled text Corpora](#unlabeled-text-corpora)
   * [Semantic Textual Similarity / Paraphrasing](#semantic-textual-similarity--paraphrasing)
   * [Natural Language Inference](#natural-language-inference)
   * [Summarization](#summarization)
   * [Dialect and regional speech identification](#dialect-and-regional-speech-identification)
   * [Named Entity Recognition (NER)](#named-entity-recognition-ner)
   * [Autorship Attribution](#autorship-attribution)
   * [Sentiment Analysis](#sentiment-analysis)
   * [Dependency Parsing](#dependency-parsing)
   * [Diacritics Restoration / Grammar Correction](#diacritics-restoration--grammar-correction)
   * [Fake News / Clickbait / Satirical News](#fake-news--clickbait--satirical-news)
   * [Offensive Language](#offensive-language)

<!--te-->

## Unlabeled text Corpora

* [🌐 Oscar Common Crawl dataset 🌐](https://huggingface.co/datasets/oscar-corpus/OSCAR-2201)
>     Part of a large multilanguage corpus originated from Common Crawl.
>     It's a raw, unannotated corpus. It has roughly 50 GB of Romanian text
>     in 4.5 million documnets. For details check its homepage 
>     and the paper
 
[![arXiv](https://img.shields.io/badge/arXiv-2004.06165-f9f107.svg)](https://arxiv.org/abs/2004.06165)
[![Homepage](https://img.shields.io/badge/oscar%20homepage-6ca1f0)](https://oscar-project.org/)

* [📚 CC-100 📚](https://data.statmt.org/cc-100/)
>      Similar to Oscar, part of a multilanguage corpus also based on Common Crawl
>      from 2018. Romanian text is 16GB large

[![arXiv](https://img.shields.io/badge/arXiv-1911.00359-f9f107.svg)](https://arxiv.org/abs/1911.00359)
[![Homepage](https://img.shields.io/badge/cc-100%20homepage-6ca1f0)](https://data.statmt.org/cc-100/)

* [🌍 Wikipedia Corpus 🌍](https://dumps.wikimedia.org/rowiki/)
>       Romanian language wikipedia dump. 
  
* [📰⚖️ RoTex Collection 📰⚖️](https://github.com/aleris/ReadME-RoTex-Corpus-Builder)
>       A collection of varoius unannotated corpora collected around 2018-2019.
>       Includes books, scraped newspapers and juridical documents  
> 
* [📖 Romanian Language Repository 📖](https://github.com/lmidriganciochina/romaniancorpus)
>       A collection of written and spoken text from various
>       sources: Articles, Fairy tales, Fiction, History, Theatre, News
 
* [🏛️ MARCELL Legislative Corpus 🏛️](https://elrc-share.eu/repository/browse/marcell-romanian-legislative-subcorpus-v2/2da548428b9d11eb9c1a00155d026706ce94a6b59ffc4b0e9fb5cd9cebe6889e/)
>      Romanian national legilation from  1881 to 2021. The corpus
>      includes mainly: governmental decisions, ministerial orders,
>      decisions, decrees and laws.
>      Automatically annotated for Named Entities

[![ACL](https://img.shields.io/badge/ACL%20Anthology-ed1c24.svg)](http://www.lrec-conf.org/proceedings/lrec2020/pdf/2020.lrec-1.464.pdf)
[![Homepage](https://img.shields.io/badge/marcell%20homepage-6ca1f0)](https://marcell-project.eu/)

* [🦠 COVID-19 Tweets 🐦](https://github.com/UBC-NLP/megacov)
>    Mega-COV is a billion-scale dataset from Twitter for studying COVID-19. It is
>    available in over 100+ languages, Romanian being one of them. Tweets need
>    to be rehydrated

[![arXiv](https://img.shields.io/badge/arXiv-2005.06012-f9f107.svg)](https://arxiv.org/abs/2005.06012)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://mumageed.medium.com/billion-scale-investigation-of-covid-19-impact-on-human-communication-in-104-languages-874b5a37beac)


  
* [📜 Minutes of the Sittings of the Chamber of Deputies of Romania 📜](https://elrc-share.eu/repository/browse/monolingual-corpus-from-minutes-of-the-sittings-of-the-chamber-of-deputies-of-romania-2016-2018-processed/759806e22e1311e9a4d400155d02670657928f90efa64c9dab1b177c2186bf6c/)
>     Minutes of the Sittings of the Chamber of Deputies of Romania (2016-2018)
>     Unannotated corpus
  
* [🔊 Minutes of the Sittings of the Romanian Parliament 🔊](https://elrc-share.eu/repository/browse/romanian-parliament-transcripts-1996-2018-processed/779b85aee4de11e9913100155d026706ac0a5e38c6824010a537363b37b6bd0f/)
>     contains 500k+ instances of speech from the parliament podium from
>     1996 to 2018. Sentence splitting and deduplication onm sentence level
>     have been applied as processing steps
>     Unannotated corpus
  
* [🗣️ Romanian Presidential Discourses 🗣️](https://github.com/grrrrah/RomanianPresidentialDiscourses)
>     Romanian presidential discouses (1990-2020) split in 4 files
>     one for each president. Unannotated corpus
  
  
* [🎭 Culture Domain Corpus 🎭](https://elrc-share.eu/repository/browse/monolingual-romanian-corpus-in-the-culture-domain-processed/a1d6c98e1d5911e9b7d400155d026706fd71a90bf1df4bacb3f174edccb6e9b9/)
>     Monolingual Romanian corpus, including content from public websites related to culture

* [Law Domain Corpus](https://elrc-share.eu/repository/browse/monolingual-romanian-corpus-in-the-law-domain/ee9f6b0289f611e6bfe700155d0205029e7b188412ab4e56bf6fd1d7d9e8b033/)
>    Monolingual (ron) corpus, containing 38063991 tokens and 854096 lexical types in the law domain.

* [Public Administration Domain Corpus](https://elrc-share.eu/repository/browse/monolingual-romanian-corpus-in-the-public-administration-domain-processed/32b0c234327311e8b7d400155d026706afa147904c554dd1bad4764bd4a7aaed/)
>    Monolingual Romanian corpus, containing 360833 sentences (9064764 words) in the public administration domain.
  
* [New Civil Procedure Code](https://elrc-share.eu/repository/browse/romanian-new-civil-procedure-code-processed/e4d8e13046ff11e8b7d400155d026706010657f248274e6286aeb6488d8a2ee6/)
>    The New Civil Procedure Code in Romanian (monolingual) comprising 297888 words.

* [New Criminal Code](https://elrc-share.eu/repository/browse/noul-cod-penal/100b7e38d25111ea913100155d0267066e48d760d0d24b39a4900b2b09864a02/)
>     The Romanian updated criminal code: text with law content.

* [Romanian News Articles Dataset](https://github.com/mhakan20/RomanianNewsArticlesDataset)
>   news articles dataset from romanian newssites
>   title, summary and article

* [Old Newspapers](https://www.kaggle.com/datasets/alvations/old-newspapers)
>   multi-language corpus from online available news sources.
>   It contains also 43mil words in Romanian language from Twitter, Blogs and Newspapers

[![Homepage](https://img.shields.io/badge/hc%20corpora%20homepage-6ca1f0)](http://corpora.epizy.com/corpora.html?i=1)

* [ELTeC-Rom](https://github.com/COST-ELTeC/ELTeC-rom)
>   The Romanian novel collection for ELTeC, the European Literary Text Collection
>   Sources: Biblioteca Metropolitana din Bucuresti, Biblioteca Universitara "Mihai Eminescu" din Iasi,
>   Biblioteca Judeteana din Botosani, personal micro-collections uploaded on Zenodo
>   under the following labels: "Hajduks Library"; "RomanianNovel Library"; "CityMysteries Library"; "BibliotecaDHL_Iasi" 
  
* [RO Business Emails](https://huggingface.co/datasets/readerbench/ro-business-emails)
>   Public dataset of 1447 manually annotated Romanian business-oriented emails.
>   The corpus is annotated with 5 token-related labels, as well as 5 sequence-related classes

[![MDPI](https://img.shields.io/badge/MDPI-Information-00813E.svg)](https://www.mdpi.com/2078-2489/14/6/321)

## Semantic Textual Similarity / Paraphrasing

* [RO-STS](https://huggingface.co/datasets/ro_sts)
* [Romanian paraphrase dataset](https://huggingface.co/datasets/BlackKakapo/paraphrase-ro)
* [TaPaCo](https://huggingface.co/datasets/tapaco/viewer/ro/train)
>    A multi-language paraphrase corpus for 73 languages extracted from the Tatoeba database.
>    It has ~ 2000 romanian phrases totaling 941 paraphrase groups. 

[![ACL](https://img.shields.io/badge/ACL%20Anthology-ed1c24.svg)](https://aclanthology.org/2020.lrec-1.848/)
[![Homepage](https://img.shields.io/badge/cc-100%20homepage-6ca1f0)](https://zenodo.org/record/3707949)

* [Romanian Bible Paraphrase Corpus](https://huggingface.co/datasets/andyP/ro-paraphrase-bible)

## Natural Language Inference

* [RO-NLI](https://github.com/dumitrescustefan/RO-NLI)

## Summarization
* [RO Text Summarization](https://huggingface.co/datasets/readerbench/ro-text-summarization)

## Dialect and regional speech identification
* [RoDia](https://github.com/codrut2/RoDia)
* [MOROCO](https://github.com/butnaruandrei/MOROCO)
    
## Named Entity Recognition (NER)

* [LegalNERo](https://huggingface.co/datasets/joelito/legalnero)
* [RONEC](https://huggingface.co/datasets/ronec)
* [WikiAnn](https://huggingface.co/datasets/wikiann)
* [SiMoNERo](https://github.com/UniversalDependencies/UD_Romanian-SiMoNERo)

## Autorship Attribution

* [ROST](https://www.kaggle.com/datasets/sandamariaavram/rost-romanian-stories-and-other-texts)


## Sentiment Analysis

* [RO_Sent](https://huggingface.co/datasets/ro_sent)
* [Senti_Lex](https://huggingface.co/datasets/senti_lex)
* [LaROSeDa](https://huggingface.co/datasets/laroseda)
* [RED](https://github.com/Alegzandra/RED-Romanian-Emotions-Dataset)
* [Romanian Categorized Web Dataset](https://github.com/bogsio/RomanianCategorizedWebDataset)
* [Romanian Sentiment Movie Reviews](https://www.kaggle.com/datasets/gringoandy/romanian-sentiment-movie-reviews)


## Dependency Parsing

* [CoNLL 2017 & 2018](https://www.conll.org/previous-tasks)
* [Deep Universal Dependencies](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-3720)
* [Curlicat Romanian Corpus](https://elrc-share.eu/repository/browse/curlicat-romanian-corpus/8b6c8dca58ea11ed9c1a00155d026706fb03ef8b4c1847cfbe9cea869a82731e/)
* [HamleDT](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-1508)
* [RoWordNet](https://github.com/dumitrescustefan/RoWordNet)
* [RoRefTrees](https://github.com/UniversalDependencies/UD_Romanian-RRT)

## Diacritics Restoration / Grammar Correction

* [Corpus for training and evaluating diacritics restoration systems](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-2607)
* [RONACC](https://nextcloud.readerbench.com/index.php/s/9pwymesT5sycxoM)

## Fake News / Clickbait / Satirical News

* [Fakerom](https://www.tagtog.com/fakerom/fakerom)
* [Clickbait dataset on Romanian SciTech News](https://github.com/ralucaginga/ClickbaitSciTechRO)
* [SaRoCo](https://github.com/MihaelaGaman/SaRoCo)

## Offensive Language

* [RO-Offense](https://huggingface.co/datasets/readerbench/ro-offense)
* [News RO-Offense](https://huggingface.co/datasets/readerbench/news-ro-offense)
* [FB RO-Offense](https://huggingface.co/datasets/readerbench/ro-fb-offense)
* [RO-Offense-Sequences](https://huggingface.co/datasets/readerbench/ro-offense-sequences)
* [Hate Speech RO](https://github.com/andra-pumnea/hate-speech-ro)
* [ROFF](https://github.com/guzimanis/ROFF)
* [CoRoSeOf](https://github.com/DianaHoefels/CoRoSeOf)

