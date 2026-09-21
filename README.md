[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

# A list of Romanian NLP Datasets
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
   * [Questions and Answering](#questions-and-answers)
   * [Spelling, Dictionaries and Gramatical Errors](#spelling-and-gramatical-errors)
   * [Automatic Speech Recognition (ASR)](#automatic-speech-recognition)

<!--te-->

## Unlabeled text Corpora


* [❄️FuLG dataset ❄️](https://huggingface.co/datasets/faur-ai/fulg)
>     The FuLG dataset is a comprehensive Romanian language corpus comprising
>     150 billion tokens, carefully extracted from Common Crawl. 
[![arXiv](https://img.shields.io/badge/arXiv-2004.06165-f9f107.svg)](https://arxiv.org/abs/2407.13657)

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

* [COVIDSentiRO](https://github.com/Alegzandra/KES-2023/tree/main/datasets/COVIDSentiRO)
>    A corpus of Romanian tweets related to COVID and vaccination against COVID, created and
>    collected between January 2021 and February 2022. It contains 19319 tweets.

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

* [⚖️ Law Domain Corpus ⚖️](https://elrc-share.eu/repository/browse/monolingual-romanian-corpus-in-the-law-domain/ee9f6b0289f611e6bfe700155d0205029e7b188412ab4e56bf6fd1d7d9e8b033/)
>    Monolingual (ron) corpus, containing 38063991 tokens and 854096 lexical types in the law domain.

* [🏢 Public Administration Domain Corpus 🏢](https://elrc-share.eu/repository/browse/monolingual-romanian-corpus-in-the-public-administration-domain-processed/32b0c234327311e8b7d400155d026706afa147904c554dd1bad4764bd4a7aaed/)
>    Monolingual Romanian corpus, containing 360833 sentences (9064764 words) in the public administration domain.
  
* [📋 New Civil Procedure Code 📋](https://elrc-share.eu/repository/browse/romanian-new-civil-procedure-code-processed/e4d8e13046ff11e8b7d400155d026706010657f248274e6286aeb6488d8a2ee6/)
>    The New Civil Procedure Code in Romanian (monolingual) comprising 297888 words.

* [⚖️ New Criminal Code ⚖️](https://elrc-share.eu/repository/browse/noul-cod-penal/100b7e38d25111ea913100155d0267066e48d760d0d24b39a4900b2b09864a02/)
>     The Romanian updated criminal code: text with law content.

* [📰 Romanian News Articles Dataset 📰](https://github.com/mhakan20/RomanianNewsArticlesDataset)
>   news articles dataset from romanian newssites
>   title, summary and article

* [📰 Old Newspapers 📰](https://www.kaggle.com/datasets/alvations/old-newspapers)
>   multi-language corpus from online available news sources.
>   It contains also 43mil words in Romanian language from Twitter, Blogs and Newspapers

[![Homepage](https://img.shields.io/badge/hc%20corpora%20homepage-6ca1f0)](http://corpora.epizy.com/corpora.html?i=1)

* [📚 ELTeC-Rom 📚](https://github.com/COST-ELTeC/ELTeC-rom)
>   The Romanian novel collection for ELTeC, the European Literary Text Collection
>   Sources: Biblioteca Metropolitana din Bucuresti, Biblioteca Universitara "Mihai Eminescu" din Iasi,
>   Biblioteca Judeteana din Botosani, personal micro-collections uploaded on Zenodo
>   under the following labels: "Hajduks Library"; "RomanianNovel Library"; "CityMysteries Library"; "BibliotecaDHL_Iasi" 
  
* [📧 RO Business Emails 📧](https://huggingface.co/datasets/readerbench/ro-business-emails)
>   Public dataset of 1447 manually annotated Romanian business-oriented emails.
>   The corpus is annotated with 5 token-related labels, as well as 5 sequence-related classes

[![MDPI](https://img.shields.io/badge/MDPI-Information-00813E.svg)](https://www.mdpi.com/2078-2489/14/6/321)


* [📖RO-Stories📖](https://huggingface.co/datasets/readerbench/ro-stories)
>  The corpus consists of texts written by Romanian authors between 19th century and present, representing stories, short-stories, fairy tales and sketches.
>  The current version contains 19 authors, 1263 full texts and 12516 paragraphs of around 200 words each, preserving paragraphs integrity.

* [📕ROST📕](https://www.kaggle.com/datasets/sandamariaavram/rost-romanian-stories-and-other-texts)
>  A dataset containing 400 Romanian texts written by 10 authors
>  The dataset contains stories, short stories, fairy tales, novels, articles, and sketches written by Ion Creangă,
>  Barbu Ştefănescu Delavrancea, Mihai Eminescu, Nicolae Filimon, Emil Gârleanu, Petre Ispirescu, Mihai Oltean, Emilia Plugaru, Liviu Rebreanu, Ioan Slavici.

[![MDPI](https://img.shields.io/badge/MDPI-Information-00813E.svg)](https://www.mdpi.com/2227-7390/10/23/4589)

* [🍳Romanian Cooking Recipes🍳](https://huggingface.co/datasets/BlackKakapo/recipes-ro)
>  891 Cooking Recipes in Romanian Language

* [🌐 FineWeb2-Ro 🌐](https://github.com/VladNegoita/FineWeb2-Ro)
>   A large-scale Romanian pretraining corpus derived from web data through quality and diversity filtering,
>   totalling billions of tokens. Public releases include fineweb2-ro-llm and fineweb2-ro-bert,
>   providing large-scale corpora for training Romanian language models.

[![ACL](https://img.shields.io/badge/ACL%20Anthology-ed1c24.svg)](https://aclanthology.org/2026.loreslm-1.13.pdf)
[![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-datasets-yellow)](https://huggingface.co/datasets/OpenLLM-Ro/fineweb2-ro-llm)

* [🏛️ CROL 🏛️](https://github.com/craciuncg/GRAF)
>   A temporally-aware Romanian legal corpus, part of the GRAF package (alongside JuRO and Law-RoG).
>   Designed for legal reasoning and retrieval tasks, covering Romanian legislation with temporal metadata.

[![ACL](https://img.shields.io/badge/ACL%20Anthology-ed1c24.svg)](https://aclanthology.org/2025.findings-acl.659/)

## Semantic Textual Similarity / Paraphrasing

* [🔗 RO-STS 🔗](https://huggingface.co/datasets/ro_sts)
>   Semantic Textual Similarity dataset for the Romanian language
>   RO-STS contains 8,628 sentence pairs with their similarity scores

[![NeurIPS](https://img.shields.io/badge/NeurIPS-ed1c24.svg)](https://datasets-benchmarks-proceedings.neurips.cc/paper/2021/hash/5f93f983524def3dca464469d2cf9f3e-Abstract-round1.html)

* [📖 Romanian Bible Paraphrase Corpus 📖](https://huggingface.co/datasets/andyP/ro-paraphrase-bible)
>   A paraphrase corpus created from 10 different Romanian language Bible versions.
>   The final dataset contains 904,815 similar records and 218,977 non matching records, totaling 1,123,927


* [🔄 Romanian paraphrase dataset 🔄](https://huggingface.co/datasets/BlackKakapo/paraphrase-ro)
>  Around ~100k examples of paraphrases. No clear explanation on how the dataset was built

* [🌐 TaPaCo 🌐](https://huggingface.co/datasets/tapaco/viewer/ro/train)
>    A multi-language paraphrase corpus for 73 languages extracted from the Tatoeba database.
>    It has ~ 2000 romanian phrases totaling 941 paraphrase groups. 

[![ACL](https://img.shields.io/badge/ACL%20Anthology-ed1c24.svg)](https://aclanthology.org/2020.lrec-1.848/)
[![Homepage](https://img.shields.io/badge/cc-100%20homepage-6ca1f0)](https://zenodo.org/record/3707949)

## Natural Language Inference

* [🧠 RONLI 🧠](https://github.com/Eduard6421/RONLI)
>   We introduce the first Romanian NLI corpus (RoNLI) comprising 58K training sentence pairs, which are obtained via distant supervision, and 6K validation and test sentence pairs, which are manually annotated with the correct labels.
[![ACL](https://img.shields.io/badge/ACL%20Anthology-ed1c24.svg)](https://aclanthology.org/2024.acl-long.15/)



* [~RO-NLI~](https://github.com/dumitrescustefan/RO-NLI)
>  The repository seems to be just an attempt at starting to build the dataset


## Summarization
* [📝 RO Text Summarization 📝](https://huggingface.co/datasets/readerbench/ro-text-summarization)
>   Around ~72k Full texts and their summary. Source seems to be news websites.
>   No description or explanation available

* [📰 RoLargeSum 📰](https://github.com/avramandrei/rolargesum)
>   A large-scale Romanian news dataset with 615k+ articles for summarization, headline generation,
>   and keyword extraction. Includes rich metadata such as summaries, topics, and dialect labels
>   distinguishing Romania vs Moldova text.

[![ACL](https://img.shields.io/badge/ACL%20Anthology-ed1c24.svg)](https://aclanthology.org/2025.coling-main.140/)
[![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-datasets-yellow)](https://huggingface.co/datasets/avramandrei/rolargesum)

## Dialect and regional speech identification
* [🗣️ RoDia 🗣️](https://github.com/codrut2/RoDia)
> varied compilation of speech samples from five distinct regions of Romania, covering both urban and rural environments.
> Around 2800 records labeled with age, gender and type of dialect

[![arXiv](https://img.shields.io/badge/arXiv-2309.03378-f9f107.svg)](https://arxiv.org/abs/2309.03378)

* [🌍 MOROCO 🌍](https://github.com/butnaruandrei/MOROCO)
> MOROCO: The Moldavian and Romanian Dialectal Corpus
> The MOROCO data set contains Moldavian and Romanian samples of text collected from the news domain.
> The samples belong to one of the following six topics: culture, finance, politics, science, sports, tech
> totaling over 32.000 labeled records

[![arXiv](https://img.shields.io/badge/arXiv-1901.06543-f9f107.svg)](https://arxiv.org/abs/1901.06543)

* [🗣️ MoRoVoc 🗣️](https://huggingface.co/datasets/avramandrei/morovoc)
>   A speech dataset for Romanian dialect identification containing over 93 hours of audio and ~88k samples
>   across Romania and Moldova. Captures intra-language variation rather than multilingual diversity,
>   making it ideal for ASR robustness and dialect modeling.

[![ACL](https://img.shields.io/badge/ACL%20Anthology-ed1c24.svg)](https://aclanthology.org/2025.findings-emnlp.653/)

  
## Named Entity Recognition (NER)

* [⚖️ LegalNERo ⚖️](https://huggingface.co/datasets/joelito/legalnero)
* [🏷️ RONEC 🏷️](https://huggingface.co/datasets/ronec)
* [🌐 WikiAnn 🌐](https://huggingface.co/datasets/wikiann)
* [🏛️ SiMoNERo 🏛️](https://github.com/UniversalDependencies/UD_Romanian-SiMoNERo)
* [📜 HistNERo 📜]()
> The dataset contains 323k tokens of text, covering more than half of the 19th century
> (i.e., 1817) until the late part of the 20th century (i.e., 1990).
> The samples belong to one of the following four historical regions of Romania,
> namely Bessarabia, Moldavia, Transylvania, and Wallachia.

[![arXiv](https://img.shields.io/badge/arXiv-2405.00155-f9f107.svg)](https://arxiv.org/abs/2405.00155v1)



## Autorship Attribution

* [📚 ROST 📚](https://www.kaggle.com/datasets/sandamariaavram/rost-romanian-stories-and-other-texts)


## Sentiment Analysis

* [😊 RO_Sent 😊](https://huggingface.co/datasets/ro_sent)
* [📖 Senti_Lex 📖](https://huggingface.co/datasets/senti_lex)
* [🎭 LaROSeDa 🎭](https://huggingface.co/datasets/laroseda)
* [🎬 SART 🎬](https://github.com/Alegzandra/KES-2023/tree/main/datasets/SART)
* [❤️ RED ❤️](https://github.com/Alegzandra/RED-Romanian-Emotions-Dataset)
* [🌐 Romanian Categorized Web Dataset 🌐](https://github.com/bogsio/RomanianCategorizedWebDataset)
* [🎬 Romanian Sentiment Movie Reviews 🎬](https://www.kaggle.com/datasets/gringoandy/romanian-sentiment-movie-reviews)


## Dependency Parsing

* [🌳 CoNLL 2017 & 2018 🌳](https://www.conll.org/previous-tasks)
* [🔗 Deep Universal Dependencies 🔗](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-3720)
* [📚 Curlicat Romanian Corpus 📚](https://elrc-share.eu/repository/browse/curlicat-romanian-corpus/8b6c8dca58ea11ed9c1a00155d026706fb03ef8b4c1847cfbe9cea869a82731e/)
* [🌲 HamleDT 🌲](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-1508)
* [📖 RoWordNet 📖](https://github.com/dumitrescustefan/RoWordNet)
* [🌳 RoRefTrees 🌳](https://github.com/UniversalDependencies/UD_Romanian-RRT)

## Diacritics Restoration / Grammar Correction

* [✍️ Corpus for training and evaluating diacritics restoration systems ✍️](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-2607)
* [✏️ RONACC ✏️](https://nextcloud.readerbench.com/index.php/s/9pwymesT5sycxoM)

## Fake News / Clickbait / Satirical News

* [❌ Fakerom ❌](https://www.tagtog.com/fakerom/fakerom)
* [🎣 Clickbait dataset on Romanian SciTech News 🎣](https://github.com/ralucaginga/ClickbaitSciTechRO)
* [😂 SaRoCo 😂](https://github.com/MihaelaGaman/SaRoCo)

## Offensive Language

* [🚫 RO-Offense 🚫](https://huggingface.co/datasets/readerbench/ro-offense)
  
* [📰 News RO-Offense 📰](https://huggingface.co/datasets/readerbench/news-ro-offense)
> manually annotated 4,052 comments on a Romanian local news website
> into one of the following classes: non-offensive, targeted insults,
> racist, homophobic, and sexist.

[![arXiv](https://img.shields.io/badge/UTCluj-RoCHI-ac2820.svg)](http://rochi.utcluj.ro/articole/10/RoCHI2022-Cojocaru-A.pdf)

* [📱 FB RO-Offense 📱](https://huggingface.co/datasets/readerbench/ro-fb-offense)
> 4455 organic generated comments from Facebook live broadcasts
> annotated not binary offensive language detection tasks and for fine-grained offensive language detection

[![IEEE](https://img.shields.io/badge/IEEE-xplore-14303e.svg)](https://ieeexplore.ieee.org/document/10130824)

* [🔍 RO-Offense-Sequences 🔍](https://huggingface.co/datasets/readerbench/ro-offense-sequences)
> 4800 Romanian comments annotated with offensive text spans
> Offensive span detection

[![MDPI](https://img.shields.io/badge/MDPI-Information-00813e.svg)](https://www.mdpi.com/2078-2489/15/1/8)

* [💢 Hate Speech RO 💢](https://github.com/andra-pumnea/hate-speech-ro)
> 3860 labeled hate speech records
  
* [🐦 ROFF 🐦](https://github.com/guzimanis/ROFF)
> Dataset consists of 5000 tweets, from which 924 were labeled as offensive (18.48 %)
> and 4076 tweets as non-offensive.

[![ACL](https://img.shields.io/badge/ACL%20Anthology-ed1c24.svg)](https://aclanthology.org/2021.ranlp-1.102.pdf)
  
* [⚠️ CoRoSeOf ⚠️](https://github.com/DianaHoefels/CoRoSeOf)
> The corpus contains 39 245 tweets, annotated by multiple annotators, following the sexist label set of a recent study.

[![ACL](https://img.shields.io/badge/ACL%20Anthology-ed1c24.svg)](https://aclanthology.org/2022.lrec-1.243.pdf)

## Questions and Answers

* [🧮 GSM8K RO 🧮](https://huggingface.co/datasets/BlackKakapo/gsm8k-ro)
>   This dataset is just the translation of the [gsm8k](https://huggingface.co/datasets/gsm8k) dataset.
>   GSM8K (Grade School Math 8K) is a dataset of 8.5K high quality linguistically diverse grade school math word problems.
>   There is no information on the quality of the translation

* [💻 ROCODE 💻](https://huggingface.co/datasets/cosmadrian/rocode)
>   RoCode, a competitive programming dataset, consisting of 2,642 problems written in Romanian,
>  11k solutions in C, C++ and Python and comprehensive testing suites for each problem. The purpose of RoCode
>  is to provide a benchmark for evaluating the code intelligence of language models trained on
>  Romanian / multilingual text as well as a fine-tuning set for pretrained Romanian models.

[![arXiv](https://img.shields.io/badge/arXiv-2005.06012-f9f107.svg)](https://arxiv.org/abs/2402.13222)

* [💻 RoITD 💻](https://huggingface.co/datasets/dragosnicolae555/RoITD)
> Romanian IT Dataset (RoITD) resembling SQuAD 1.1.
> RoITD consists of 9575 Romanian QA pairs formulated by crowd workers. QA pairs are based on 5043 articles from Romanian Wikipedia articles describing IT and household products.
> Of the total number of questions, 5103 are possible (i.e. the correct answer can be found within the paragraph) and 4472 are not possible (i.e. the given answer is a "plausible answer" and not correct)

* [🩺 RoMedQA 🩺](https://github.com/ana-rogoz/MedQARo)
> The dataset comprises 102,646 high-quality QA pairs from real-world clinical records of 1,011 oncology patients (796 patients with breast cancer and 215 patients with lung cancer).
> The QA pairs are the results of a manual annotation process carried out by physicians specialized in oncology and radiotherapy
> RoMedQA includes 76,416 QA pairs about breast cancer patients and 26,230 about lung cancer patients, with questions grounded in medical case summaries (epicrises).

[![arXiv](https://img.shields.io/badge/arXiv-2508.16390-f9f107.svg)](https://arxiv.org/abs/2508.16390v1)

* [⚖️ JurRO ⚖️](https://github.com/craciuncg/GRAF)
> Romanian legal MCQA dataset, comprising 10,836 questions from three examinations.
>  Each entry essentially consists of a body in which a theoretical question is posed regarding
> a legal aspect, along with three possible answer choices labeled A, B, and C,
> out of which at mosttwo answers are correct.

[![ACL](https://img.shields.io/badge/ACL%20Anthology-ed1c24.svg)](https://aclanthology.org/2025.findings-acl.659/)


* [🧬 RoBiologyDataChoiceQA 🧬](https://huggingface.co/datasets/RoLLMHub/RoBiologyDataChoiceQA)
>   A domain-specific multiple-choice QA dataset with ~14k biology questions in Romanian,
>   designed for evaluating and fine-tuning LLMs in educational contexts aligned with the national curriculum.

[![ACL](https://img.shields.io/badge/ACL%20Anthology-ed1c24.svg)](https://aclanthology.org/2025.mrl-main.37/)

* [🚗 RoD-TAL 🚗](https://github.com/vladman-25/RoD-TAL)
>   A multimodal Romanian benchmark for driving-license exam reasoning, combining text, images, and legal references.
>   Includes over 1,100 questions across tasks like QA, visual QA, and retrieval.

[![ACL](https://img.shields.io/badge/ACL%20Anthology-ed1c24.svg)](https://aclanthology.org/2026.findings-eacl.295/)
[![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-datasets-yellow)](https://huggingface.co/datasets/unstpb-nlp/RoD-TAL)

* [🧮 RoMathExam 🧮](https://github.com/badea-codrut-cti/proiect-ai-in-educatie)
>   A longitudinal dataset of Romanian math exams spanning 1895–2025, with over 10k problems and 600+ exam sets.
>   Supports educational AI, retrieval, and reasoning tasks with rare historical depth.

[![arXiv](https://img.shields.io/badge/arXiv-2604.16392-f9f107.svg)](https://arxiv.org/abs/2604.16392)
[![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-datasets-yellow)](https://huggingface.co/datasets/RoMathExam/RoMathExam)


## Spelling, Dictionaries and Gramatical Errors

* [✏️ Grammar-RO ✏️](https://huggingface.co/datasets/BlackKakapo/grammar-ro)
>  Synthetic dataset with ~1.9M records. Altered and correct statement as columns

* [📖 RoAcReL 📖](https://huggingface.co/datasets/fmi-unibuc/RoAcReL)
>  Romanian Archaisms Regionalisms Lexicon containing ~ 1940 Word definitions

* [🗺️ RoRuDi 🗺️](https://huggingface.co/datasets/fmi-unibuc/RoRuDi)
> Romanian Rules for Dialects - 1940 regionalisms, meanings and the region of provenience

* [📚 RoLEX 📚](https://github.com/adrianastan/rolex)
> The dataset was developed mainly for speech processing applications, yet its applicability
> extends beyond this domain. RoLEX includes over 330,000 curated entries with information
> regarding lemma, morphosyntactic description, syllabification, lexical stress and phonemic transcription.

[![Cambridge](https://img.shields.io/badge/Cambridge-Core-ef4135.svg)](https://adrianastan.com/papers/2022_NLE.pdf)

* [⚖️ RoLegalGEC ⚖️](https://huggingface.co/datasets/MirceaT/RoLegalGEC)
>   The first Romanian legal-domain grammatical error correction dataset with ~350k annotated sentence pairs.
>   Enables research in correction, normalization, and document processing for Romanian legal text.

[![arXiv](https://img.shields.io/badge/arXiv-2604.19593-f9f107.svg)](https://arxiv.org/abs/2604.19593)

## Automatic Speech Recognition

* [🗣️ USPDATRO 🗣️](https://zenodo.org/records/7898233)
> Underrepresented Speech Dataset from Open Data. Duration of the dataset is 4h 18m 55s.
> Distribution according to platforms: 83% of the content comes from YouTube, 12% from SoundCloud, and 5% from Vimeo
> Dataset covers primarily under-represented speech groups (outside the 19–29 male category)

[![MDPI](https://img.shields.io/badge/MDPI-Information-00813E.svg)](https://www.mdpi.com/2076-3417/14/19/9043)
