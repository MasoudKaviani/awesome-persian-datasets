# Awesome Persian Datasets

<div dir="rtl">
مجموعه‌ای از مجموعه‌داده‌های زبان فارسی موجود در سراسر اینترنت
</div>

A comprehensive, categorized collection of Persian (Farsi) datasets available across GitHub, Hugging Face, Kaggle, Zenodo, Mendeley, and other platforms — for NLP, speech, computer vision, and beyond.

---

## Table of Contents

- [Text Corpora & Raw Text](#text-corpora--raw-text)
- [Sentiment Analysis](#sentiment-analysis)
- [Emotion Detection](#emotion-detection)
- [Hate Speech & Offensive Language Detection](#hate-speech--offensive-language-detection)
- [Aspect-Based Sentiment Analysis (ABSA)](#aspect-based-sentiment-analysis-absa)
- [Question Answering](#question-answering)
- [Machine Translation & Parallel Corpora](#machine-translation--parallel-corpora)
- [Named Entity Recognition (NER)](#named-entity-recognition-ner)
- [Text Summarization](#text-summarization)
- [Natural Language Inference (NLI) & Entailment](#natural-language-inference-nli--entailment)
- [Spell Checking & Correction](#spell-checking--correction)
- [Part-of-Speech Tagging & Dependency Parsing](#part-of-speech-tagging--dependency-parsing)
- [Irony & Sarcasm Detection](#irony--sarcasm-detection)
- [Text Classification](#text-classification)
- [Punctuation Restoration](#punctuation-restoration)
- [Conversation & Dialogue](#conversation--dialogue)
- [Instruction Tuning & LLM Datasets](#instruction-tuning--llm-datasets)
- [Math & Reasoning Datasets](#math--reasoning-datasets)
- [Benchmarks](#benchmarks)
- [Pre-trained Word Embeddings](#pre-trained-word-embeddings)
- [Code-Mixing & Transliteration (Finglish)](#code-mixing--transliteration-finglish)
- [Speech & Audio — ASR](#speech--audio--asr)
- [Speech & Audio — TTS](#speech--audio--tts)
- [Speech — Other](#speech--other)
- [Computer Vision & Image Captioning](#computer-vision--image-captioning)
- [Visual Question Answering (VQA)](#visual-question-answering-vqa)
- [OCR & Scene Text Recognition](#ocr--scene-text-recognition)
- [Handwriting Recognition](#handwriting-recognition)
- [License Plate Recognition](#license-plate-recognition)
- [Face Recognition & Attributes](#face-recognition--attributes)
- [Names & Demographics](#names--demographics)
- [Poetry & Literature](#poetry--literature)
- [News & Social Media](#news--social-media)
- [Medical & Clinical](#medical--clinical)
- [Legal Documents](#legal-documents)
- [Fact-Checking & Information Verification](#fact-checking--information-verification)
- [Metaphor & Stylistic Analysis](#metaphor--stylistic-analysis)
- [Job & Economic Data](#job--economic-data)
- [Grapheme-to-Phoneme (G2P)](#grapheme-to-phoneme-g2p)
- [Informal-Formal Text Normalization](#informal-formal-text-normalization)
- [Contributing](#contributing)
- [License](#license)

---

## Text Corpora & Raw Text

| Dataset | Description | Source |
|---|---|---|
| [Naab](https://huggingface.co/datasets/SLPL/naab) | ~130GB of data, 250M paragraphs, 15B words — the largest Persian raw text corpus | Hugging Face |
| [Persian Raw Text (persiannlp)](https://github.com/persiannlp/persian-raw-text) | ~80GB Persian raw text from CommonCrawl and other sources | GitHub |
| [Persian Wikipedia Corpus (Text-Mining)](https://github.com/Text-Mining/Persian-Wikipedia-Corpus) | Complete Persian Wikipedia dump (1,160,676 articles) in plain text JSON format | GitHub |
| [Persian Wikipedia Dataset (Kaggle)](https://www.kaggle.com/datasets/miladfa7/persian-wikipedia-dataset) | Persian (Farsi) Wikipedia corpus | Kaggle |
| [MirasText](https://github.com/miras-tech/MirasText) | 2.8M+ articles from 250+ Persian news websites, 1.4B+ content words | GitHub |
| [Farsi Wiki Dataset](https://github.com/mallahyari/Farsi-datasets/tree/master/farsi_wiki) | Farsi Wikipedia extracted text | GitHub |
| [Farsi News Dataset](https://github.com/mallahyari/Farsi-datasets/tree/master/farsi_news) | Persian news from Hamshahri and RadioFarda RSS feeds | GitHub |
| [community-datasets/farsi_news](https://huggingface.co/datasets/community-datasets/farsi_news) | Persian news articles on Hugging Face | Hugging Face |
| [ali619/corpus-dataset-normalized-for-persian-farsi](https://huggingface.co/datasets/ali619/corpus-dataset-normalized-for-persian-farsi) | Normalized Persian/Farsi text corpus | Hugging Face |
| [m522t/farsi_dataset](https://huggingface.co/datasets/m522t/farsi_dataset) | General Farsi text dataset | Hugging Face |
| [Persian Text Corpus (BijanKhan)](https://github.com/BijanKhan/Persian-Text-Corpus) | Large Persian text corpus compiled by Bijan Khan | GitHub |
| [PersianML/persian-document-corpus](https://huggingface.co/datasets/PersianML/persian-document-corpus) | Persian document corpus for language modeling | Hugging Face |
| [HuggingFaceFW/finepdfs](https://huggingface.co/datasets/HuggingFaceFW/finepdfs) | Fine-grained PDF documents including Persian | Hugging Face |
| [Hamshahri Corpus](http://www.dadmatech.ir/dadmatech-corpora/) | Large-scale Persian news corpus from Hamshahri newspaper | Web |
| [VOA Corpus](https://jon.dehdari.org/corpora/#persian) | 7.9M words from Voice of America Persian broadcasts (2003–2008) | Web |
| [dotIR Collection](https://dbrg.ut.ac.ir/webir-dotir/) | Standard Persian web test collection for IR evaluation, XML format | Web |
| [irBlogs](https://dbrg.ut.ac.ir/irblogs/) | 5M+ Persian blog posts from 600K+ weblogs with relations graph | Web |
| [Bijankhan Corpus](https://www.peykaregan.ir/dataset/0b88a5c4-b1c3-4c3a-ba39-5c6eebdf814f) | Annotated Persian corpus with 2.6M tokens | Peykaregan |
| [W2C Persian Corpus](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0022-6133-9) | Web-to-corpus automatically collected Persian text | LINDAT |

## Sentiment Analysis

| Dataset | Description | Source |
|---|---|---|
| [Persian Sentiment Analysis Datasets](https://github.com/Keramatfar/Persian_NLP_Datasets) | Comprehensive reference of Persian sentiment & emotion datasets with data loaders | GitHub |
| [SentiPers](https://github.com/phosariyoon/SentiPers) | Sentiment analysis corpus for Persian with polarity labels | GitHub |
| [DeepSentiPers](https://github.com/JoyeBright/DeepSentiPers) | Augmented Persian sentiment corpus (19,550 samples, 5 polarity levels) | GitHub |
| [MirasOpinion](https://github.com/miras-tech/MirasText/tree/master/MirasOpinion) | 1M labeled Digikala comments (positive/negative/neutral) via crowdsourcing | GitHub |
| [PerSent](https://www.gelbukh.com/resources/persent/) | Real-valued polarity labels (-1 to 1) for thousands of Persian words and expressions | Web |
| [LexiPers](https://github.com/phosseini/lexipers) | Ontology-based sentiment lexicon for Persian | GitHub |
| [hezarai/sentiment-dksf](https://huggingface.co/datasets/hezarai/sentiment-dksf) | Digikala product sentiment dataset (62,321 comments) | Hugging Face |
| [HooshvareLab/sentiment-dksf](https://huggingface.co/datasets/HooshvareLab/sentiment-dksf) | 62,321 user comments on digital products | Hugging Face |
| [Persian Twitter Sentiment](https://www.kaggle.com/datasets/mohammadalimkh/persian-twitter-dataset-sentiment-analysis) | Persian tweets with sentiment labels | Kaggle |
| [Snappfood Sentiment Analysis](https://www.kaggle.com/datasets/soheiltehranipour/snappfood-persian-sentiment-analysis) | 70,000 Snappfood customer comments with sentiment labels | Kaggle |
| [Digikala Product Comments](https://www.kaggle.com/datasets/sobhanmh/persian-digikala-comments) | Persian product reviews from Digikala for classification | Kaggle |
| [Persian Stock Market Tweets](https://github.com/Keramatfar/Persian_NLP_Datasets) | 12,055 tweets about stock market with sentiment labels | GitHub |
| [Hotel Reviews Dataset](https://github.com/Keramatfar/Persian_NLP_Datasets) | 3,600 hotel reviews from Hellokish with sentiment labels | GitHub |
| [Sahamyab Sentiment](https://github.com/Keramatfar/Persian_NLP_Datasets) | 8,373 comments from Sahamyab (stock exchange) with sentiment | GitHub |
| [LSCP](https://iasbs.ac.ir/~ansari/lscp/) | 27M casual Persian tweets with sentiment polarity, POS tags, derivation trees, and parallel sentences | Web |
| [Colloquial Persian Sentiment (Mazoochi 2023)](https://arxiv.org/abs/2306.12679) | Colloquial Persian sentiment dataset with 3 polarities | arXiv |
| [Donya/subjective-tasks-farsi](https://huggingface.co/datasets/Donya/subjective-tasks-farsi) | Subjective NLP tasks in Farsi including sentiment | Hugging Face |

## Emotion Detection

| Dataset | Description | Source |
|---|---|---|
| [ShortPersianEmo](https://github.com/vkiani/ShortPersianEmo) | Short Persian emotion classification (5 emotions, 5,472 samples) | GitHub |
| [JAMFA](https://github.com/Azadsee/JAMFA) | Deep emotion detection in Persian literary text (4 emotions, 2,241 samples) | GitHub |
| [ArmanEmo](https://github.com/arman-rayan-sharif/arman-text-emotion) | 7 emotions from Twitter, Instagram, and Digikala (7,308 samples) | GitHub |
| [EmoPars](https://github.com/nazaninsbr/persian-emotion-detection) | 6 emotions from Persian tweets (29,997 samples) | GitHub |
| [Persian Tweets Emotional Dataset](https://www.kaggle.com/datasets/behdadkarimi/persian-tweets-emotional-dataset) | 113,829 Persian tweets labeled with 6 emotions | Kaggle |

## Hate Speech & Offensive Language Detection

| Dataset | Description | Source |
|---|---|---|
| [AlirezaFzp/persian-abusive-words](https://huggingface.co/datasets/AlirezaFzp/persian-abusive-words) | Persian abusive and offensive words list | Hugging Face |
| [Pars-OFF](https://github.com/KamyarDarvishi/Pars-OFF) | First Farsi offensive language detection dataset — 3-level hierarchical annotation, ~12K tweets | GitHub |
| [PHATE](https://github.com/phate-dataset/phate) | Persian multi-label hate speech dataset with 7,000+ annotated tweets and annotator rationales | GitHub |
| [Pars-HaO](https://www.techrxiv.org/doi/10.36227/techrxiv.24106617) | Hate and offensive language detection on Persian social media | TechRxiv |

## Aspect-Based Sentiment Analysis (ABSA)

| Dataset | Description | Source |
|---|---|---|
| [Pars-ABSA](https://github.com/Titowak/Pars-ABSA) | Manually annotated aspect-based sentiment benchmark on Farsi product reviews (10,002 samples) | GitHub |
| [universitytehran/ParsiNLU_ABSA](https://huggingface.co/datasets/universitytehran/ParsiNLU_ABSA) | ParsiNLU aspect-based sentiment analysis dataset | Hugging Face |

## Question Answering

| Dataset | Description | Source |
|---|---|---|
| [PersianQA](https://github.com/sajjjadayobi/PersianQA) | Persian reading comprehension dataset (9,000+ entries, SQuAD-style with unanswerable questions) | GitHub |
| [PersianQuAD / PerAnSel](https://www.kaggle.com/datasets/jamshidjdmy/peransel) | ~100,000 QA pairs on Persian Wikipedia; native answer selection dataset | Kaggle |
| [ParsiNLU Reading Comprehension](https://huggingface.co/datasets/persiannlp/parsinlu_reading_comprehension) | Persian reading comprehension from ParsiNLU suite | Hugging Face |
| [PersianQA (Kaggle)](https://www.kaggle.com/datasets/sajjjadayobi/persianqa) | Persian question answering dataset on Kaggle | Kaggle |
| [PerSQuAD (Machine Translated)](https://github.com/m-ostadi/persquad) | Machine-translated Persian SQuAD 2.0 for question answering | GitHub |
| [ParsiNLU Multiple Choice (MCQA)](https://huggingface.co/datasets/universitytehran/ParsiNLU_MCQA) | Persian multiple-choice question answering | Hugging Face |
| [PersianMedQA](https://huggingface.co/datasets/MohammadJRanjbar/PersianMedQA) | Persian medical question answering dataset | Hugging Face |

## Machine Translation & Parallel Corpora

| Dataset | Description | Source |
|---|---|---|
| [TEP: Tehran English-Persian Parallel Corpus](https://huggingface.co/datasets/Helsinki-NLP/tep_en_fa_para) | First free English-Persian parallel corpus from movie subtitles | Hugging Face |
| [MIZĀN Corpus](https://github.com/omidmn/Mizan) | 1M+ Persian-English sentence pairs from literary masterpieces | GitHub |
| [PEPC: Parallel English-Persian Corpus](https://nlpdataset.ir/farsi/parallel_corpora.html) | ~1M sentence pairs from literature | Web |
| [Esposito Corpus](https://aclanthology.org/2024.lrec-main.557.pdf) | 3.5M English-Persian parallel sentence pairs from scientific publications | ACL Anthology |
| [ParsiNLU Translation (fa→en)](https://huggingface.co/datasets/persiannlp/parsinlu_translation_fa_en) | Persian-to-English translation dataset | Hugging Face |
| [ParsiNLU Translation (en→fa)](https://huggingface.co/datasets/persiannlp/parsinlu_translation_en_fa) | English-to-Persian translation dataset | Hugging Face |
| [OPUS English-Persian](https://opus.nlpl.eu/) | Multiple open parallel corpora for English-Farsi (21 corpora) | OPUS |
| [JW300 (Persian)](https://opus.nlpl.eu/JW300.php) | ~1.2M Persian-English parallel sentences from religious texts | OPUS |
| [Tatoeba (Persian)](https://tatoeba.org/) | ~50K community-contributed Persian-English sentence pairs | Tatoeba |
| [OPUS OpenSubtitles (Persian)](https://opus.nlpl.eu/OpenSubtitles.php) | ~200K Persian-English parallel sentences from movie subtitles | OPUS |
| [CCMatrix (Persian)](https://github.com/facebookresearch/CCMatrix) | ~50M web-crawled Persian-English sentence pairs (noisy but very large) | GitHub |
| [mC4 (Persian)](https://www.tensorflow.org/datasets/community_catalog/huggingface/mc4) | Multilingual Common Crawl — Persian subset for MT | TFDS |
| [Persian-English Wikipedia Parallel](https://arxiv.org/abs/1711.00681) | Parallel sentences extracted from English-Persian Wikipedia | arXiv |
| [Shiraz Corpus](http://wwwusers.di.uniroma1.it/~pilehvar/pubs/CICLING_2011_Pilehvars_Faili.pdf) | 3,000 Persian-English sentence pairs from Hamshahri newspaper | Web |
| [universitytehran/NLLB](https://huggingface.co/datasets/universitytehran/NLLB) | NLLB Persian translation dataset | Hugging Face |
| [universitytehran/TED2020](https://huggingface.co/datasets/universitytehran/TED2020) | TED2020 Persian translation dataset | Hugging Face |
| [Bijankhan Parallel Corpus](http://www.dadmatech.ir/dadmatech-corpora/) | Persian-English parallel corpus from Dadmatech | Web |
| [Targoman/TLPC](https://huggingface.co/datasets/Targoman/TLPC) | Targoman Large Persian Corpus for translation | Hugging Face |

## Named Entity Recognition (NER)

| Dataset | Description | Source |
|---|---|---|
| [ArmanNER](https://github.com/HooshvareLab/ArmanPersoNERCorpus) | Persian NER corpus with 3 levels (7,682 tagged tokens) | GitHub |
| [hezarai/arman-ner](https://huggingface.co/datasets/hezarai/arman-ner) | Arman NER dataset on Hugging Face | Hugging Face |
| [PEYNER](https://github.com/RahaProjects/peyner) | Persian NER corpus with 9 entity types | GitHub |
| [hezarai/parstwiner](https://huggingface.co/datasets/hezarai/parstwiner) | Persian twin NER dataset | Hugging Face |
| [Persian-NER (Text-Mining)](https://github.com/Text-Mining/Persian-NER) | ~25M tokens (~1M sentences) from Persian Wikipedia, 5 entity types (PER, ORG, LOC, EVT, DAT) | GitHub |
| [XTREME PAN-X NER (Persian)](https://github.com/google-research/xtreme) | Persian subset of WikiAnn — 40K samples, 3 entity types | GitHub |
| [NSURL-Persian-NER](https://github.com/nasrin-taghizadeh/NSURL-Persian-NER) | Persian NER dataset from the NSURL project | GitHub |

## Text Summarization

| Dataset | Description | Source |
|---|---|---|
| [HooshvareLab/pn_summary](https://huggingface.co/datasets/HooshvareLab/pn_summary) | Persian news summarization dataset | Hugging Face |
| [PasSum](https://github.com/hooshvare/pasport) | Persian summarization dataset with extractive and abstractive summaries | GitHub |
| [Farsinstract](https://github.com/Hojjat-Mokhtarabadi/FarsInstruct) | 9.3M train / 1.3M test Persian scientific abstracts for summarization and instruction tuning | GitHub |
| [universitytehran/Race](https://huggingface.co/datasets/universitytehran/Race) | Race dataset adapted for Persian | Hugging Face |

## Natural Language Inference (NLI) & Entailment

| Dataset | Description | Source |
|---|---|---|
| [FarsTail](https://github.com/dml-qom/FarsTail) | First large-scale Persian NLI dataset — 10,367 samples (entailment/contradiction/neutral) | GitHub |
| [ParsiNLU Entailment](https://huggingface.co/datasets/persiannlp/parsinlu_entailment) | Persian natural language inference / textual entailment dataset | Hugging Face |
| [ParsiNLU Multiple Choice](https://huggingface.co/datasets/persiannlp/parsinlu_multiple_choice) | Persian multiple-choice reading comprehension | Hugging Face |
| [ParsiNLU Query Paraphrasing (Para)](https://huggingface.co/datasets/universitytehran/ParsiNLU_Para) | Persian query paraphrasing / QQP dataset | Hugging Face |

## Spell Checking & Correction

| Dataset | Description | Source |
|---|---|---|
| [FAspell](https://www.kaggle.com/datasets/rtatman/faspell) | Misspelled Persian words and their corrections (similar to ASpell for English) | Kaggle |
| [Persian Spell Correction Dataset](https://github.com/olomix/persian-spell-checker) | Persian spell checker dataset with word-level corrections | GitHub |
| [Persian Clinical Spell Correction](https://pmc.ncbi.nlm.nih.gov/articles/PMC11299402) | Spelling correction dataset for Persian clinical text | PMC |

## Part-of-Speech Tagging & Dependency Parsing

| Dataset | Description | Source |
|---|---|---|
| [hezarai/lscp-pos-500k](https://huggingface.co/datasets/hezarai/lscp-pos-500k) | 500K Persian sentences with POS tags (LSCP) | Hugging Face |
| [PerUDT (Persian Universal Dependency Treebank)](https://github.com/UniversalDependencies/UD_Persian-PerDT) | 29K sentences converted to UD format with manual corrections (news, fiction, academic, web, blog) | GitHub |
| [PerDT (Persian Dependency Treebank)](https://github.com/PerDT/PerDT) | Persian dependency parsing treebank | GitHub |
| [BijanKhan POS Tagged Corpus](https://github.com/persian-nlp/persian-pos) | POS-tagged Persian corpus | GitHub |
| [Uppsala Persian Dependency Treebank](https://github.com/UniversalDependencies/Persian) | Universal Dependencies for Persian | GitHub |

## Irony & Sarcasm Detection

| Dataset | Description | Source |
|---|---|---|
| [Persian Irony Detection Dataset](https://nlpdataset.ir/farsi/irony_detection.html) | Persian irony detection dataset listing | Web |
| [Persian Sarcasm Dataset](https://github.com/AmirGahreman/sarcasm_persian) | Persian sarcasm detection dataset from social media | GitHub |
| [PersianIrony](https://github.com/soheil-tirgar/Persian_Irony_Detection) | Persian irony detection from Twitter | GitHub |

## Text Classification

| Dataset | Description | Source |
|---|---|---|
| [Persian Text Classification Datasets](https://nlpdataset.ir/farsi/text_classification.html) | Listing of Persian text classification datasets | Web |
| [Digikala Product Comments](https://www.kaggle.com/datasets/sobhanmh/persian-digikala-comments) | Persian product reviews from Digikala for classification | Kaggle |
| [Persian News Category Dataset](https://www.kaggle.com/datasets/amirpourmand/asriran-news) | 330,000+ Persian news articles with categories from asriran.com | Kaggle |

## Punctuation Restoration

| Dataset | Description | Source |
|---|---|---|
| [PersianPunc](https://huggingface.co/datasets/MohammadJRanjbar/PersianPunc) | ~100K–1M text pairs for restoring punctuation in Persian transcripts (ASR post-processing) | Hugging Face |

## Conversation & Dialogue

| Dataset | Description | Source |
|---|---|---|
| [Kamtera/Persian-conversational-dataset](https://huggingface.co/datasets/Kamtera/Persian-conversational-dataset) | 100K–1M Persian conversational text generation dataset | Hugging Face |
| [xmanii/Maux-Persian-SFT-30k](https://huggingface.co/datasets/xmanii/Maux-Persian-SFT-30k) | ~30K conversational samples for Persian chatbots and assistants | Hugging Face |
| [xmanii/Mauxi-SFT-Persian](https://huggingface.co/datasets/xmanii/Mauxi-SFT-Persian) | ~5K conversation threads for lightweight Persian chat models | Hugging Face |
| [xmanii/mauxitalk-persian](https://huggingface.co/datasets/xmanii/mauxitalk-persian) | ~10K informal open-domain conversational samples for Persian chatbots | Hugging Face |
| [HamRaz](https://aclanthology.org/2025.lm4dh-1.1) | Culturally adapted Persian mental health support conversation dataset grounded in Person-Centered Therapy | ACL Anthology |
| [Corpus of Conversational Persian Transcripts](https://catalog.ldc.upenn.edu/LDC2019T11) | ~20 hours of naturally occurring informal Tehrani Persian conversations (transcripts only) | LDC |
| [PeQa](https://www.youtube.com/watch?v=qYjLhF9OvDU) | Massive Persian question-answering and chatbot dataset | Web |
| [Persian Speech Corpus (ELRA)](https://catalog.elra.info/en-us/repository/browse/ELRA-S0415) | 31.5 hours of Persian scripted monologue and dialogue from 89 speakers | ELRA |

## Instruction Tuning & LLM Datasets

| Dataset | Description | Source |
|---|---|---|
| [mshojaei77/alpaca_persian_telegram](https://huggingface.co/datasets/mshojaei77/alpaca_persian_telegram) | Persian Alpaca-style instruction dataset from Telegram | Hugging Face |
| [mshojaei77/merged_persian_alpaca](https://huggingface.co/datasets/mshojaei77/merged_persian_alpaca) | Merged Persian Alpaca instruction-tuning dataset | Hugging Face |
| [xmanii/persian-alpaca-chat-2k](https://huggingface.co/datasets/xmanii/persian-alpaca-chat-2k) | 2K Persian Alpaca chat-format instructions | Hugging Face |
| [xmanii/persian-alpaca-completion-2k](https://huggingface.co/datasets/xmanii/persian-alpaca-completion-2k) | 2K Persian Alpaca completion-format instructions | Hugging Face |
| [xmanii/maux-gte-2k-public](https://huggingface.co/datasets/xmanii/maux-gte-2k-public) | Persian MAUX GTE dataset for embedding and retrieval | Hugging Face |
| [ParsiAI/FarsInstruct](https://huggingface.co/datasets/ParsiAI/FarsInstruct) | Persian instruction-tuning dataset | Hugging Face |
| [taesiri/TinyStories-Farsi](https://huggingface.co/datasets/taesiri/TinyStories-Farsi) | Persian translation of TinyStories for LLM training | Hugging Face |
| [BaSalam/entity-attribute-sft-dataset](https://huggingface.co/datasets/BaSalam/entity-attribute-sft-dataset-GPT-4.0-generated-v1) | Persian SFT dataset with entity-attribute pairs (GPT-4 generated) | Hugging Face |
| [BaSalam/entity-attribute-dataset-gpt35](https://huggingface.co/datasets/BaSalam/entity-attribute-dataset-GPT-3.5-generated-v1) | Persian SFT dataset with entity-attribute pairs (GPT-3.5 generated) | Hugging Face |
| [BaSalam/vision-catalogs-llava-format](https://huggingface.co/datasets/BaSalam/vision-catalogs-llava-format-v3) | Persian visual catalog dataset in LLaVA format | Hugging Face |
| [MaralGPT/persian_blogs](https://huggingface.co/datasets/MaralGPT/persian_blogs) | Persian blog posts for LLM training | Hugging Face |
| [MaralGPT/persian_quotes](https://huggingface.co/datasets/MaralGPT/persian_quotes) | Collection of Persian quotes for LLM training | Hugging Face |
| [mshojaei77/SCED](https://huggingface.co/datasets/mshojaei77/SCED) | Persian conversational and educational dataset | Hugging Face |
| [mshojaei77/PersianTelegramChannels](https://huggingface.co/datasets/mshojaei77/PersianTelegramChannels) | Persian text scraped from Telegram channels | Hugging Face |
| [universitytehran/OrcaMath](https://huggingface.co/datasets/universitytehran/OrcaMath) | OrcaMath adapted for Persian | Hugging Face |
| [universitytehran/SlimOrca](https://huggingface.co/datasets/universitytehran/SlimOrca) | SlimOrca adapted for Persian | Hugging Face |
| [universitytehran/Capybara](https://huggingface.co/datasets/universitytehran/Capybara) | Capybara dataset adapted for Persian | Hugging Face |
| [universitytehran/Proverb](https://huggingface.co/datasets/universitytehran/Proverb) | Persian proverb dataset for LLM training | Hugging Face |
| [persian-alpaca-reasoning-v1](https://huggingface.co/datasets/hosseinhimself/persian-alpaca-reasoning-v1) | ~20K instruction-output pairs with reasoning for reasoning-augmented fine-tuning | Hugging Face |
| [sinarashidi/alpaca-persian](https://huggingface.co/datasets/sinarashidi/alpaca-persian) | ~35K Persian Stanford Alpaca instruction-response pairs | Hugging Face |
| [North_fa_llama3_Dataset](https://huggingface.co/datasets/payamvha/North_fa_llama3_Dataset) | 15,281 instruction-output pairs with categories for Persian LLM training | Hugging Face |
| [Persian_instruct_dataset](https://github.com/mostafaamiri/Persian_instruct_dataset) | 4,864 semi-Alpaca style instruction-output pairs (products, books, QA) | GitHub |
| [MatinaAI/instruction_tuning_datasets](https://huggingface.co/datasets/MatinaAI/instruction_tuning_datasets) | Persian instruction tuning datasets from Matina AI | Hugging Face |
| [Persian-Math-SFT](https://huggingface.co/datasets/xmanii/Persian-Math-SFT) | ~2K Persian math Q&A pairs for educational tutoring | Hugging Face |

## Math & Reasoning Datasets

| Dataset | Description | Source |
|---|---|---|
| [Persian-Math-SFT](https://huggingface.co/datasets/xmanii/Persian-Math-SFT) | ~2K Persian math Q&A pairs for STEM education | Hugging Face |
| [universitytehran/OrcaMath](https://huggingface.co/datasets/universitytehran/OrcaMath) | Math reasoning dataset adapted for Persian | Hugging Face |
| [persian-alpaca-reasoning-v1](https://huggingface.co/datasets/hosseinhimself/persian-alpaca-reasoning-v1) | ~20K instruction-output pairs with reasoning/explanation outputs | Hugging Face |

## Benchmarks

| Dataset | Description | Source |
|---|---|---|
| [ParsiNLU](https://github.com/persiannlp/parsinlu) | Suite of 6 Persian NLU tasks: reading comprehension (1,300), MC-QA (2,460), sentiment (2,423), entailment (2,700), paraphrasing (4,644), MT (47,745 pairs) | GitHub |
| [PARSA-Bench](https://huggingface.co/datasets/MohammadJRanjbar/PARSA-Bench) | Persian benchmark for ASR and speech processing | Hugging Face |

## Pre-trained Word Embeddings

| Dataset | Description | Source |
|---|---|---|
| [fastText Pre-trained Persian Word Vectors](https://fasttext.cc/docs/en/crawl-vectors.html) | 300-dimensional word vectors trained on Common Crawl and Wikipedia using fastText | fastText |
| [fastText Persian Word Vectors (Kaggle)](https://www.kaggle.com/datasets/javadhelali/fasttext-pretrained-persian-word-vectors) | Pre-trained fastText Persian word vectors ready for download | Kaggle |
| [Persian FastText](https://github.com/MohammadHeydari/Persian_FastText) | Pre-trained FastText embeddings for Persian with t-SNE visualization | GitHub |
| [Persian Word2Vec (Spark NLP)](https://sparknlp.org/2020/12/05/persian_w2v_cc_300d_fa.html) | 300D word2vec embeddings trained on Common Crawl and Wikipedia | Spark NLP |
| [Pre-trained Embeddings Listing](https://nlpdataset.ir/farsi/pre-trained_embeddings.html) | Comprehensive listing of Persian pre-trained word embeddings | Web |

## Code-Mixing & Transliteration (Finglish)

| Dataset | Description | Source |
|---|---|---|
| [Arshia82sbn/Finglish-To-Persian-Dataset-Large](https://huggingface.co/datasets/Arshia82sbn/Finglish-To-Persian-Dataset-Large) | 9.8M Finglish (Latin-script Persian) to Persian script transliteration sentence pairs | Hugging Face |
| [PinLID](https://www.researchgate.net/publication/386536143_PinLID_a_dataset_for_Pinglish_language_identiftcation_based_on_code-mixing_sentence_on_unstructured_resources) | Pinglish language identification dataset from Persian-English code-mixed tweets | ResearchGate |
| [Persian-English Code-mixed Sentiment](https://github.com/nazaninsbr/Persian-English-Code-mixed-Sentiment-Analysis) | 3,640 Persian-English code-mixed tweets labeled with sentiment (positive/negative/neutral) | GitHub |

## Speech & Audio — ASR

| Dataset | Description | Source |
|---|---|---|
| [Common Voice 17 (Persian)](https://huggingface.co/datasets/mozilla-foundation/common_voice_17_0) | Mozilla Common Voice Persian subset — crowdsourced ASR data | Hugging Face |
| [hezarai/common-voice-13-fa](https://huggingface.co/datasets/hezarai/common-voice-13-fa) | Common Voice 13 Persian subset processed by Hezar | Hugging Face |
| [PersianVox](https://huggingface.co/datasets/saeedzou/persianvox_all) | 625K high-quality Persian utterances mined from in-the-wild data with dual-ASR agreement filtering | Hugging Face |
| [PersianVox-All](https://huggingface.co/datasets/saeedzou/persianvox_all) | 1M+ Persian utterances (less filtered than PersianVox) with language and MOS quality filtering | Hugging Face |
| [PersianVox v1 1K](https://huggingface.co/datasets/saeedzou/PersianVox_v1_1k) | 1K-sample subset of PersianVox for quick testing | Hugging Face |
| [pourmand1376/asr-farsi-youtube-chunked](https://huggingface.co/datasets/pourmand1376/asr-farsi-youtube-chunked-10-seconds) | Persian ASR data from YouTube, chunked into 10-second segments | Hugging Face |
| [Persian Speech to Text (Zenodo)](https://zenodo.org/records/7486182) | Open-source Persian speech-to-text dataset for ASR training | Zenodo |
| [Neyshekar](https://zenodo.org/records/18073633) | Open community-driven Persian speech dataset for TTS and ASR | Zenodo |
| [DeepMine](https://github.com/deepmine/ds/) | 480+ hours of Persian ASR data from 1,850+ speakers (restricted license) | GitHub |
| [FarsSpon](https://github.com/farsspon) | 530+ hours of Persian speech from 5,300+ speakers | GitHub |
| [SmartGitiCorp/persian_tts](https://huggingface.co/datasets/SmartGitiCorp/persian_tts) | Persian speech dataset (also usable for ASR) | Hugging Face |
| [vhdm/persian-voice-v1](https://huggingface.co/datasets/vhdm/persian-voice-v1) | Persian voice dataset for ASR | Hugging Face |

## Speech & Audio — TTS

| Dataset | Description | Source |
|---|---|---|
| [ParsVoice](https://huggingface.co/datasets/MohammadJRanjbar/ParsVoice) | 1,804 hours, 470+ speakers — large-scale multi-speaker Persian TTS corpus from audiobooks | Hugging Face |
| [Thomcles/Persian-Farsi-Speech](https://huggingface.co/datasets/Thomcles/Persian-Farsi-Speech) | 417 hours of cleaned Persian TTS data (109K samples after denoising and filtering) | Hugging Face |
| [Mana-TTS](https://huggingface.co/datasets/MahtaFetrat/Mana-TTS) | ~114 hours single-speaker Persian magazine narration TTS (largest public single-speaker corpus) | Hugging Face |
| [ManaTTS (GitHub)](https://github.com/mana-show/ManaTTS) | 86 hours of single-speaker Persian TTS data with open pipeline | GitHub |
| [ArmanTTS](https://github.com/ArmanTTS/ArmanTTS) | 9 hours of single-speaker Persian TTS data | GitHub |
| [ParsiGoo](https://github.com/azsa22/ParsiGoo) | Multi-speaker Persian TTS dataset (6 speakers) | GitHub |
| [AmerAndish TTS](https://github.com/AmerAndish/persian-tts) | 21 hours of single-speaker Persian TTS data | GitHub |
| [Persian TTS (Coqui)](https://github.com/karim23657/Persian-tts-coqui) | Persian/Farsi TTS training using Coqui TTS | GitHub |
| [DeepMine Multi-TTS](https://github.com/deepmine/ds/) | 120 hours of multi-speaker Persian TTS data (67 speakers, restricted) | GitHub |

## Speech — Other

| Dataset | Description | Source |
|---|---|---|
| [MahtaFetrat/HomoRich-G2P-Persian](https://huggingface.co/datasets/MahtaFetrat/HomoRich-G2P-Persian) | Persian grapheme-to-phoneme dataset for speech processing | Hugging Face |

## Computer Vision & Image Captioning

| Dataset | Description | Source |
|---|---|---|
| [CLIPfa](https://github.com/sajjjadayobi/CLIPfa) | Connecting Farsi text and images — Persian CLIP training dataset | GitHub |
| [hezarai/flickr30k-fa](https://huggingface.co/datasets/hezarai/flickr30k-fa) | Flickr30k image captions translated to Persian | Hugging Face |
| [hezarai/coco-flickr-fa](https://huggingface.co/datasets/hezarai/coco-flickr-fa) | COCO + Flickr image captions in Persian | Hugging Face |
| [BaSalam/vision-catalogs-llava-format](https://huggingface.co/datasets/BaSalam/vision-catalogs-llava-format-v3) | Persian visual catalog dataset in LLaVA format | Hugging Face |
| [Persian Font Recognition (Persis)](https://github.com/mehrdad-dev/persis) | Persian font recognition pipeline using CNNs | GitHub |
| [Persian Image Captioning Dataset](https://www.kaggle.com/datasets/malekzadeharman/persian-image-captioning-dataset) | ~1,500 image–caption pairs from Tasnim News Agency | Kaggle |

## Visual Question Answering (VQA)

| Dataset | Description | Source |
|---|---|---|
| [ParsVQA-Caps](https://www.kaggle.com/datasets/maryamsadathashemi/parsvqacaps) | First Persian VQA & image captioning benchmark — ~7.5K images, ~9K human-written captions | Kaggle |

## OCR & Scene Text Recognition

| Dataset | Description | Source |
|---|---|---|
| [hezarai/parsynth-ocr-200k](https://huggingface.co/datasets/hezarai/parsynth-ocr-200k) | 200K synthetic Persian OCR samples | Hugging Face |
| [Persian OCR Garshasp](https://huggingface.co/datasets/AliShafiee2003/persian-ocr-garshasp-70c) | 2.6M synthetic Persian text images (48×640, 13 styles with blur/noise/distortion) for OCR and scene text recognition | Hugging Face |
| [Persian Scene Text Dataset (Part DP)](https://partdp.ai/blog/wp-content/uploads/2025/03/A-Comprehensive-Dataset-of-Real-scene-Images-for-.pdf) | Comprehensive real-scene image dataset for Persian text detection and recognition | Web |

## Handwriting Recognition

| Dataset | Description | Source |
|---|---|---|
| [HODA (Persian Handwritten Digits)](https://github.com/Foroozani/ImageProcessing) | 102,352 binary images of handwritten Persian digits from 12,000 forms | GitHub |
| [Sadri Persian Handwritten Database](https://users.encs.concordia.ca/~j_sadri/PersianDatabase.htm) | 3,500 forms from 500 writers — digits, letters, words, free texts, symbols with metadata | Web |
| [Khayyam Offline Persian Handwriting Dataset](https://arxiv.org/abs/2406.1025) | 7,271 binary images of 1,080 Iranian handwritten city names (44K words, 60K letters, 6K digits) | arXiv |
| [PHTD (Persian Handwritten Text Dataset)](https://www.academia.edu/3138273/A_New_Dataset_of_Persian_Handwritten_Documents_and_Its_Segmentation) | 140 handwritten documents from 40 individuals (1,787 text-lines, 27,073 words) | Academia |
| [PHCWT (Persian Handwritten Characters, Words & Text)](https://www.semanticscholar.org/paper/PHCWT%3A-A-Persian-Handwritten-Characters%2C-Words-and-Montazeri-Kiani/573db8bf58bfb338c1f03f9e5f3006ce580733f0) | First extensive integrated collection of Persian handwritten characters, words, and texts | Semantic Scholar |
| [Persian Word Handwritten Dataset](https://www.kaggle.com/datasets/shahmoradi/persian-word-handwritten-dataset) | Handwritten Persian words for recognition | Kaggle |
| [Iranshahr Dataset](https://dl.acm.org/doi/abs/10.1007/s10032-021-00368-2) | Persian handwritten digits and characters dataset | ACM |
| [PHDD (Persian Handwritten Digits & Symbols)](https://data.mendeley.com/datasets/8993swvpjx) | 40,214 Persian handwritten digits and mathematical symbols (28×28, with noise reduction filters) | Mendeley Data |
| [PHDD (Zenodo)](https://zenodo.org/records/17914718) | 40,214 Persian handwritten digits and symbols dataset | Zenodo |

## License Plate Recognition

| Dataset | Description | Source |
|---|---|---|
| [hezarai/persian-license-plate-v1](https://huggingface.co/datasets/hezarai/persian-license-plate-v1) | Persian license plate detection dataset with Farsi digits, letters, and symbols | Hugging Face |
| [Iranis Dataset](https://github.com/alitourani/Iranis-dataset) | 83,844 cropped images of 28 Farsi license plate character classes (10 digits + 17 letters + 1 symbol) | GitHub |
| [Persian License Plate Dataset](https://github.com/mut-deep/Persian-License-Plate-Detection) | Iranian license plates for object detection and classification | GitHub |

## Face Recognition & Attributes

| Dataset | Description | Source |
|---|---|---|
| [ParsFace](https://github.com/Amirnoroozi/parsface) | ~6,000 Iranian personalities with face images, names (Persian & English), ages, professions, gender | GitHub |
| [Iranian-author-names-based-on-gender](https://github.com/MohRafiee/Iranian-author-names-based-on-gender.-) | Gender-labeled Persian author names from SID.ir academic database | GitHub |

## Names & Demographics

| Dataset | Description | Source |
|---|---|---|
| [Persian Gender by Name](https://github.com/farbodbj/persian-gender-by-name) | Dataset for determining gender from Persian names with English representations (26K samples) | GitHub |
| [farbodbij/persian-gender-by-name (HF)](https://huggingface.co/datasets/farbodbij/persian-gender-by-name) | 26K Persian names with gender labels and English transliterations (PNGT-26K) | Hugging Face |
| [Iranian Surname Frequencies](https://github.com/farbodbj/iranian-surname-frequencies) | 100,000+ Persian surnames with frequencies from 10M+ records | GitHub |

## Poetry & Literature

| Dataset | Description | Source |
|---|---|---|
| [Ganjoor Persian Poetry Corpus](https://github.com/ganjoor/persian-poetry-corpus) | Classical Persian poetry curated from Ganjoor.net for NLP and literary research | GitHub |
| [ganjoor-tex](https://github.com/ganjoor/ganjoor-tex) | Text documents for 12 Persian poets crawled from ganjoor.net | GitHub |
| [Persian Poems Corpus](https://github.com/amnghd/Persian_poems_corpus) | 48 Persian poets, 1.2M mesras, 8.1M words — original, normalized, and stop-words-removed formats | GitHub |
| [RezaGooner/PerPoetry](https://github.com/RezaGooner/PerPoetry) | Comprehensive repository of classical Persian poetry for ML applications | GitHub |
| [MaralGPT/persian_quotes](https://huggingface.co/datasets/MaralGPT/persian_quotes) | Collection of Persian quotes | Hugging Face |
| [universitytehran/Proverb](https://huggingface.co/datasets/universitytehran/Proverb) | Persian proverbs dataset | Hugging Face |

## News & Social Media

| Dataset | Description | Source |
|---|---|---|
| [Asriran News Dataset](https://www.kaggle.com/datasets/amirpourmand/asriran-news) | 330,000+ Persian news articles from asriran.com (2005–2022) | Kaggle |
| [MirasText](https://github.com/miras-tech/MirasText) | 2.8M+ articles from 250+ Persian news websites | GitHub |
| [Persian Twitter Dataset](https://www.kaggle.com/datasets/mohammadalimkh/persian-twitter-dataset-sentiment-analysis) | Persian tweets from X (Twitter) with sentiment labels | Kaggle |
| [Persian Telegram Channels](https://huggingface.co/datasets/mshojaei77/PersianTelegramChannels) | Large-scale Persian text from Telegram channels | Hugging Face |
| [Hamshahri News Corpus](http://www.dadmatech.ir/dadmatech-corpora/) | Large Persian news corpus from Hamshahri newspaper | Web |
| [VOA Persian Corpus](https://jon.dehdari.org/corpora/#persian) | 7.9M words from VOA Persian broadcasts (2003–2008) | Web |

## Medical & Clinical

| Dataset | Description | Source |
|---|---|---|
| [PersianMedQA](https://huggingface.co/datasets/MohammadJRanjbar/PersianMedQA) | Persian medical question answering dataset | Hugging Face |
| [Persian Clinical Spell Correction](https://pmc.ncbi.nlm.nih.gov/articles/PMC11299402) | Spelling correction dataset for Persian clinical text with medical reports | PMC |

## Legal Documents

| Dataset | Description | Source |
|---|---|---|
| [Targoman/TLPC](https://huggingface.co/datasets/Targoman/TLPC) | Targoman Large Persian Corpus — includes legal and official document texts | Hugging Face |

## Fact-Checking & Information Verification

| Dataset | Description | Source |
|---|---|---|
| [ParsFEVER](https://github.com/Zarharan/ParsFEVER) | First dataset for Farsi fact extraction and verification | GitHub |

## Metaphor & Stylistic Analysis

| Dataset | Description | Source |
|---|---|---|
| [PerMet](https://github.com/ms-miri/PerMet) | Metaphor-annotated corpus for Persian | GitHub |

## Job & Economic Data

| Dataset | Description | Source |
|---|---|---|
| [JobVision/JobVision_Jobposts_Dataset](https://huggingface.co/datasets/JobVision/JobVision_Jobposts_Dataset) | Persian job postings dataset from JobVision platform | Hugging Face |

## Grapheme-to-Phoneme (G2P)

| Dataset | Description | Source |
|---|---|---|
| [MahtaFetrat/HomoRich-G2P-Persian](https://huggingface.co/datasets/MahtaFetrat/HomoRich-G2P-Persian) | Persian grapheme-to-phoneme conversion dataset for speech processing | Hugging Face |

## Informal-Formal Text Normalization

| Dataset | Description | Source |
|---|---|---|
| [sbunlp/ParsMap](https://huggingface.co/datasets/sbunlp/ParsMap) | Informal-to-formal Persian text corpus for normalization tasks | Hugging Face |

---

## Contributing

Contributions are welcome! If you know of a Persian dataset that should be listed here:

1. Check that it is not already included.
2. Ensure the link points directly to the dataset itself (not to another "awesome list" or aggregator).
3. Open a pull request adding it to the appropriate category in the table format above.

**Guidelines:**
- Link directly to the dataset, not to a blog post or intermediary page.
- Include a concise description and the hosting platform.
- Place the dataset in the most specific category available.
- Do not link to other awesome-lists or dataset aggregation repos.

## License

[MIT](./LICENSE)
