# :bookmark: The Indic NLP Catalog
_A Collaborative Catalog of Resources for Indic Language NLP_

The **Indic NLP Catalog** repository is an attempt to **collaboratively** build the **most comprehensive** catalog of NLP datasets, models and other resources for all languages of the Indian subcontinent.

_Please suggest any other resources you may be aware of. Raise a pull request or an issue to add more resources to the catalog. Put the proposed entry in the following format:_

  [Wikipedia Dumps](https://dumps.wikimedia.org)

_Add a small, informative description of the dataset and provide links to any paper/article/site documenting the resource. Mention your name too. We would like to acknowlege your contribution to building this catalog in the [CONTRIBUTORS](CONTRIBUTORS.md) list._

## :+1: Featured Resources

Indian language NLP has come a long way. We feature a few resources that are illustrative of the trends in recent times along various axes and point to a bright future.  
 
- [Universal Language Contribution API (ULCA)](https://bhashini.gov.in/ulca): **ULCA** is a standard API and open scalable data platform (supporting various types of datasets) for Indian language datasets and models. ULCA is part of the [Bhasini mission](https://bhashini.gov.in). You can upload, discover models, datasets and benchmarks here. This is one repository we really need and hope to see this evolving into a standard, large-scale platform for resource discovery and dissemination.
- We are seeing the rise of large-scale datasets across many tasks like **IndicCorp** (text corpus/9 billion tokens), **Samanantar** (parallel corpus/50 million sentence pairs), **Naamapadam** (named entity/5.7 million sentences), **HiNER** (named entity/100k sentences), **Aksharantar** (transliteration/26 million pairs) , _etc_. These are being built using either large-scale mining of web-resource or large human annotation efforts or both. 
- As we aim higher, the datasets and models are achieving higher language coverage. While earlier datasets would be available for only a handful of Indian languages, then for 10-12 languages - we are now reaching the next frontier where we are creating resources like **Aksharantar** (transliteration/21 languages), **FLORES-200** (translation/27 languages), **IndoWordNet** (wordnet/18 languages) spanning almost all languages listed in the Indian constitution and more.  Datasets and models spanning a large number of languages. 
- Particularly, we are seeing datasets getting created for extremely low-resourced languages or languages not yet covered in any dataset like **Bodo**, **Kangri**, **Khasi**, _etc_.
- From a handful of institutes who pioneered the development of NLP in India, we now have an increasing number of institutes/interest groups and passionate volunteers like **AI4Bharat**, **BUET CSE NLP**, **KMI**, **L3Cube**, **iNLTK**, **IIT Patna**, _etc_. who are contributing to building resources for Indian languages.

## Browse the entire catalog...

:raising_hand:**Note**: Many known resources have not yet been classified into the catalog. They can be found as open issues in the repo.
	
* [Major Indic Language NLP Repositories](#MajorIndicLanguageNLPRepositories)
* [Libraries and Tools](#Libraries)
* [Evaluation Benchmarks](#Benchmarks)
* [Standards](#Standards)
	* [Unicode Standard](#UnicodeStandard)
* [Text Corpora](#TextCorpora)
	* [Monolingual Corpus](#MonolingualCorpus)
	* [Language Identification](#LanguageIdentification)	
	* [Lexical Resources](#LexicalResources)
	* [NER Corpora](#NERCorpora)
	* [Parallel Translation Corpus](#ParallelTranslationCorpus)
	* [MT Evaluation](#MTEvaluation)
	* [Parallel Transliteration Corpus](#ParallelTransliterationCorpus)
	* [Text Classification](#TextualClassification)
	* [Textual Entailment/Natural Language Inference](#TextualEntailment)
	* [Paraphrase](#Paraphrase)
	* [Sentiment, Sarcasm, Emotion  Analysis](#SentimentAnalysis)
	* [Hate Speech and Offensive Comments](#HateSpeech)
	* [Question Answering](#QuestionAnswering)
	* [Dialog](#Dialog)
	* [Discourse](#Discourse)
	* [Information Extraction](#InformationExtraction)
	* [POS Tagged corpus](#POSTaggedcorpus)
	* [Chunk Corpus](#ChunkCorpus)
	* [Dependency Parse Corpus](#DependencyParseCorpus)
	* [Co-reference Corpus](#CoreferenceCorpus)
	* [Summarization](#Summarization)
	* [Data to Text](#DatatoText)
* [Models](#Models)
	* [Word Embeddings](#WordEmbeddings)
	* [Pre-trained Language Models](#PreTrainedLanguageModels)
	* [Multilingual Word Embeddings](#MultilingualWordEmbeddings)
	* [Morphanalyzers](#Morphanalyzers)
	* [Translation Models](#TranslationModels)
	* [Speech Models](#SpeechModels)
	* [NER](#NER)
* [Speech Corpora](#SpeechCorpora)
* [OCR Corpora](#OCRCorpora)
* [Multimodal Corpora](#MultimodalCorpora)
* [Language Specific Catalogs](#LanguageSpecificCatalogs)	


## <a name='MajorIndicLanguageNLPRepositories'></a>Major Indic Language NLP Repositories
- [Universal Language Contribution API (ULCA)](https://bhashini.gov.in/ulca)
- [Technology Development for Indian Languages (TDIL)](http://tdil-dc.in)
- [Center for Indian Language Technology (CFILT)](http://www.cfilt.iitb.ac.in/)
- [Language Technologies Research Center (LTRC)](https://ltrc.iiit.ac.in/download.php)
- [AI4Bharat](https://ai4bharat.iitm.ac.in)
- [Linguistic Data Consortium For Indian Languages (LDCIL)](https://data.ldcil.org)
- [University of Hyderabad - Sanskrit NLP](http://sanskrit.uohyd.ac.in/scl)
- [National Platform for Language Technology](https://nplt.in/demo/index.php?route=product/category&path=75_59&limit=100)
- [BUET CSE NLP Group](https://csebuetnlp.github.io)
- [KMI Linguistics](https://github.com/kmi-linguistics)
- [L3Cube](https://github.com/l3cube-pune/MarathiNLP)
- [IIT Patna](https://www.iitp.ac.in/~ai-nlp-ml/resources.html)


## <a name='Libraries'></a>Libraries and Tools

- [Indic NLP Library](https://github.com/anoopkunchukuttan/indic_nlp_library): Python Library for various Indian language NLP tasks like tokenization, sentence splitting, normalization, script conversion, transliteration, _etc_
	- [Devnagri to Roman transliteration](https://github.com/ritwikmishra/devanagari-to-roman-script-transliteration) using hand-crafted rules and lexicons.
- [pyiwn](https://github.com/riteshpanjwani/pyiwn): Python Interface to IndoWordNet
- [Indic-OCR](https://indic-ocr.github.io/) : OCR for Indic Scripts
- [CLTK](https://github.com/cltk/cltk/tree/master/cltk): Toolkit for many of the world's classical languages. Support for Sanskrit. Some parts of the Sanskrit library are forked from the Indic NLP Library.
- [iNLTK](https://github.com/goru001/inltk): iNLTK aims to provide out of the box support for various NLP tasks that an application developer might need for Indic languages.
- [Sanskrit Coders Indic Transliteration](https://github.com/sanskrit-coders/indic_transliteration): Script conversion and romanization for Indian languages.
- [Smart Sanskirt Annotator](https://github.com/iamdsc/smart-sanskrit-annotator): Annotation tool for Sanskrit [paper](http://www.lrec-conf.org/proceedings/lrec2020/pdf/2020.lrec-1.874.pdf)
- [BNLP](https://github.com/sagorbrur/bnlp): Bengali language processing toolkit with tokenization, embedding, POS tagging, NER suppport
- [CodeSwitch](https://github.com/sagorbrur/codeswitch): Language identification, POS Tagging, NER, sentiment analysis support for code mixed data including Hindi and Nepali language
- [IndIE](https://github.com/ritwikmishra/IndIE): An Open Information Extraction tool (triple extractor) in Hindi. It is conjectured to work for Tamil, Telugu, and Urdu as well.
- [Hindi-BenchIE](https://github.com/ritwikmishra/hindi-benchie): A triple evaluation tool for 112 Hindi sentences.
- [Kannada RAG Agent](https://github.com/Amruth011/kannada-rag-agent): An end-to-end RAG system for Kannada literature featuring OCR, multilingual Q&A, and TTS support. Contributed by [Amruth Kumar M](https://github.com/Amruth011).

## <a name='Benchmarks'></a>Evaluation Benchmarks

Benchmarks spanning multiple tasks.

- [AI4Bharat IndicGLUE](https://ai4bharat.iitm.ac.in/indic-glue): NLU benchmark for 11 languages.
- [AI4Bharat IndicNLG Suite](https://ai4bharat.iitm.ac.in/indic-nlg-suite): NLG benchmark for 11 languages spanning 5 generation tasks: biography generation, sentence summarization, headline generation, paraphrase generation and question generation.
- [GLUECoS](https://microsoft.github.io/GLUECoS): For Hindi-English code-mixed benchmark containing the following tasks - Language Identification (LID), POS Tagging (POS), Named Entity Recognition (NER), Sentiment Analysis (SA), Question Answering (QA), Natural Language Inference (NLI).
- [AI4Bharat Text Classification](https://github.com/ai4bharat/indicnlp_corpus#publicly-available-classification-datasets): A compilation of classification datasets for 10 languages.
- [WAT 2021 Translation Dataset](http://lotus.kuee.kyoto-u.ac.jp/WAT/indic-multilingual): Standard train and test sets for translation between English and 10 Indian languages.

## <a name='Standards'></a>Standards

- Unicode Standard for Indic Scripts
   - [An Introduction to Indic Scripts](https://www.w3.org/2002/Talks/09-ri-indic/indic-paper.pdf)
   - [Unicode Standard for South Asian Scripts](http://www.unicode.org/versions/Unicode12.1.0/ch12.pdf)

## <a name='TextCorpora'></a>Text Corpora

### <a name='MonolingualCorpus'></a>Monolingual Corpus

- [AIBharat IndicCorp]: Text corpora for Indian languages
  - [v1](https://github.com/AI4Bharat/indicnlp_suite/blob/master/README.md#indiccorp): contains 8.9 billion tokens from 12 Indian languages (including Indian English). [[paper](https://aclanthology.org/2020.findings-emnlp.445)]
  - [v2](https://github.com/AI4Bharat/IndicBERT?tab=readme-ov-file#indiccorp-v2): contains 20 billion tokens from 22 Indian languages (including Indian English). [[paper](https://aclanthology.org/2023.acl-long.693/)]
- [Wikipedia Dumps](https://dumps.wikimedia.org)
- Common Crawl
	- [OSCAR Corpus](https://traces1.inria.fr/oscar): Released in 2019, large-scaled processed CommonCrawl.	
	- [WMT Common Crawl Dumps](http://data.statmt.org/ngrams/raw): Crawls between 2012 and 2016. Noisy text, needs to be filtered.
	- [CC-100 Corpus](): Facebook CommonCrawl extracted data. They provide scripts for processing CommonCrawl. StatMT has built a replica of the CC-100 corpus using these scripts. You can find it [HERE](http://data.statmt.org/cc-100). This corpus also has romanized corpora for some Indian languages.
- [WMT NEWS Crawl](http://data.statmt.org/news-crawl)
- [LDCIL Monolingual Corpus](https://data.ldcil.org)
- [Charles University Hindi Monolingual Corpus](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0023-625F-0)
- [Charles University Urdu Monolingual Corpus](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0023-65A9-5)
- [IIT Bombay Hindi Monolingual Corpus](http://www.cfilt.iitb.ac.in/iitb_parallel/iitb_corpus_download/monolingual.hi.tgz)
- [EMILLE Corpus (multiple Indian languages)](https://www.lancaster.ac.uk/fass/projects/corpus/emille/)
- [Janmabhumi Malayalam Corpus](https://github.com/ABHISHEKVALSAN/Malayalam-Newspaper-Article-Dataset)
- [Leipzig Corpus](http://wortschatz.uni-leipzig.de/en/download/)
- [Sanskrit Monolingual and Sandhi-split Corpus](http://sanskrit.uohyd.ac.in/Corpus/)
- [Lot Of Indic Tweets Corpus](https://github.com/bedapudi6788/LOIT): Large twitter datasets for telugu (7.9 million) and hindi (17.6 million) and fasttext skipgram and cbow word vectors for the same.
- [CMU Romanized Hinglish Corpus](https://github.com/khyathiraghavi/multi_task_code_switched_language_modeling/tree/master/hinglishData): See [THIS PAPER](https://www.aclweb.org/anthology/W18-3211.pdf) for details. 
- [JNU-BHLTR Bhojpuri Corpus](https://github.com/shashwatup9k/bho-resources/tree/master/mono-bho-corpus): Bhojpuri corpus of 45k sentences.
- [KMI Magahi Corpus](https://github.com/kmi-linguistics/magahi): 
- [KMI Awadhi Corpus](https://github.com/kmi-linguistics/awadhi): 
- [KMI Linguistics Bodo](https://github.com/kmi-linguistics/bodo): Contains the Bodo corpus and the frequency-ordered word and punctuation list.
- [SMC Malayalam text corpus](https://gitlab.com/smc/corpus)
- [DNLP-Tel Telugu Corpus](https://drive.google.com/drive/folders/1fEt7aIzYWGQKto3Nt51M5CdjtzxMqdCz?usp=sharing): Telugu corpus of 280M tokens and 23M sentences along with skip-gram model trained with word2vec.
- [Ema-lon Manipuri Corpus](http://catalog.elra.info/en-us/repository/browse/ELRA-W0316/): The first comparable corpus built for the Manipuri (mni)-English (eng) language pair with the monolingual data comprising of 1,034,715 Manipuri sentences and 846,796 English sentences in version 1 and 1,880,035 Manipuri sentences and 1,450,053 English sentences in version 2.
- [SinMin Corpus](https://osf.io/a5quv/): Contains texts of different genres and styles of the modern and old Sinhala language.
- [Kangri_corpus](https://github.com/chauhanshweta/Kangri_corpus): Monolingual corpus of Himachali low resource endangered language, Kangri comprising of 1,81,552 sentences. Described in [this paper](https://arxiv.org/abs/2103.11596).
- [Sanskrit-Hindi-MT](https://github.com/priyanshu2103/Sanskrit-Hindi-Machine-Translation): The Sanskrit Monolingual Data is available [here](https://drive.google.com/file/d/1_qclc7unNLvToiDK8t2scIgj5oxJDEGm/view?usp=sharing).
- [FacebookDecadeCorpora](https://github.com/samithaj/FacebookDecadeCorpora): Contains two language corpora of colloquial Sinhala content extracted from Facebook using the Crowdtangle platform. The larger corpus contains 28,825,820 to 29,549,672 words of text, mostly in Sinhala, English and Tamil and the smaller corpus amounts to 5,402,76 words of only Sinhala text extracted from Corpus-Alpha. Described in [this paper](https://arxiv.org/ftp/arxiv/papers/2007/2007.07884.pdf).
- [Nepali National corpus](http://catalog.elra.info/product_info.php?products_id=1216): The Nepali Monolingual written corpus comprises the core corpus containing 802,000 words and the general corpus containing 1,400,000 words. Described [here](https://www.sketchengine.eu/nepali-national-corpus/).

### <a name='LanguageIdentification'></a>Language Identification

- [VarDial 2018 Language Identification Dataset](https://github.com/kmi-linguistics/vardial2018): 5 languages - Hindi, Braj, Awadhi, Bhojpuri, Magahi.

### <a name='LexicalResources'></a>Lexical Resources and Semantic Similarity

- [IndoWordNet](http://www.cfilt.iitb.ac.in/indowordnet/)
- [IIIT-Hyderabad Word Similarity Database](https://github.com/syedsarfarazakhtar/Word-Similarity-Datasets-for-Indian-Languages): 7 Indian languages
- [Facebook Hindi Analogy Dataset](https://dl.fbaipublicfiles.com/fasttext/word-analogies/questions-words-hi.txt)
- [MGAD Hindi Analogy dataset](https://github.com/rutrastone/MGAD)
- [AI4Bharat Word Frequency Lists](https://github.com/AI4Bharat/indicnlp_corpus#text-corpora): Tokens and their frequencies from the AI4Bharat corpus, a large monolingual corpus.
- [Hindi RG-63](https://github.com/ashwinivd/similarity_hindi): Hindi version of the Rubenstein and Goodenough (RG-65) word similarity dataset
- [IITB Cognate Datasets](https://github.com/dipteshkanojia/challengeCognateFF): Dataset of Cognates and False Friend Pairs for 12 Indian Languages. [(Paper)](https://aclanthology.org/2020.lrec-1.378.pdf)
- [AI4Bharat Cross-lingual Semantic Textual Similarity](https://storage.googleapis.com/samanantar-public/human_annotations.tsv): 10 sentences across 11 en-Indic language pairs annotated on a scale of 0-5 as per SemEval cross-lingual STS guidelines.
- [Toxicity-200](https://github.com/facebookresearch/flores/blob/main/toxicity): Toxicity Lists for 200 languages including 27 Indian languages.
- [FacebookDecadeCorpora](https://github.com/samithaj/FacebookDecadeCorpora): Contains a list of algorithmically derived stopwords extracted from Corpus-Sinhala-Redux. Described in [this paper](https://arxiv.org/ftp/arxiv/papers/2007/2007.07884.pdf).

### <a name='NERCorpora'></a>NER Corpora

- [FIRE 2013 AUKBC NER Corpus](http://au-kbc.org/nlp/NER-FIRE2013)
- [FIRE 2014 AUKBC NER Corpus](http://www.au-kbc.org/nlp/NER-FIRE2014/)
- [IIT Bombay Marathi NER Corpus](http://www.cfilt.iitb.ac.in/ner/download_data.html)
- [WikiAnn NER Corpus](https://elisa-ie.github.io/wikiann) (_Noisy_)  [DOWNLOAD](https://drive.google.com/drive/folders/1Q-xdT99SeaCghihGa7nRkcXGwRGUIsKN?usp=sharing)  (Old broken [LINK](http://nlp.cs.rpi.edu))
- [IJCNLP 200 NER Corpus](http://ltrc.iiit.ac.in/ner-ssea-08/index.cgi?topic=5): NER corpora for hi, bn, or, te, ur.
- [a-mma NER data](https://github.com/a-mma/NER_Open_Data)
- [AI4Bharat Naamapadam](https://huggingface.co/datasets/ai4bharat/naamapadam): NER dataset for 11 Indic languages.
- [AsNER](https://arxiv.org/ftp/arxiv/papers/2207/2207.03422.pdf): A named entity annotation dataset for low resource Assamese language containing 99k tokens.
- [L3Cube-MahaNER](https://github.com/l3cube-pune/MarathiNLP/tree/main/L3Cube-MahaNER): The first major gold standard named entity recognition dataset in Marathi consisting of 25,000 sentences in Marathi language. Described in [this paper](http://www.lrec-conf.org/proceedings/lrec2022/workshops/WILDRE6/pdf/2022.wildre6-1.6.pdf).
- [CFILT HiNER](https://github.com/cfiltnlp/hiner): A large Hindi NER dataset containing 109,146 sentences and 2,220,856 tokens. Described in [this paper](https://arxiv.org/abs/2204.13743).
- [MultiCoNER](https://multiconer.github.io/): A multilingual complex Named Entity Recognition dataset composed of 2.3 million instances for 11 languages(including dataset for Indic languages Hindi and Bangla) representing three domains(wiki sentences, questions, and search queries) plus multilingual and code-mixed subsets.The NER tag-set consists of six classes viz.: PER,LOC,CORP,GRP,PROD and CW. Described in [this paper](https://aclanthology.org/2022.semeval-1.196.pdf).

### <a name='ParallelTranslationCorpus'></a>Parallel Translation Corpus

- [BPCC Parallel Corpus](https://github.com/ai4bharat/IndicTrans2/?tab=readme-ov-file#data): Largest parallel corpus for English and 22 Indian languages (as of Jan 2024). It comprises 230 million sentence pairs between English-Indian languages. A subset of this corpus is the BPCC-Human Corpus containing 2.2 English-Indic pairs for 22 Indic languages. 
- [Samanantar Parallel Corpus](https://ai4bharat.iitm.ac.in/samanantar): Largest parallel corpus for English and 11 Indian languages (as of 2021). It comprises 46m sentence pairs between English-Indian languages and 82m sentence  pairs between Indian languages.
- [FLORES-101](https://github.com/facebookresearch/flores): Human translated evaluation sets for 101 languages released by Facebook. It includes 14 Indic languages. The testsets are n-way parallel. 
- [FLORES-200](https://github.com/facebookresearch/flores/tree/main/flores200): Human translated evaluation sets for 200 languages released by Facebook. It includes 24 Indic languages. The testsets are n-way parallel. 
- [IIT Bombay English-Hindi Parallel Corpus](http://www.cfilt.iitb.ac.in/iitb_parallel): Largest en-hi parallel corpora in public domain (about 1.5 million segments)
- [CVIT-IIITH PIB Multilingual Corpus](http://preon.iiit.ac.in/~jerin/resources/datasets/pib-v0.tar): Mined from Press Information Bureau for many Indian languages. Contains both English-IL and IL-IL corpora (IL=Indian language).
- [CVIT-IIITH Mann ki Baat Corpus](
