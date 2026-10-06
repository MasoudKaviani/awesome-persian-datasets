# Awesome Persian Datasets

<div dir="rtl">
مجموعه‌ای از مجموعه‌داده‌های زبان فارسی موجود در سراسر اینترنت
</div>

A comprehensive, categorized collection of Persian (Farsi) datasets available across GitHub, Hugging Face, Kaggle, and other platforms — for NLP, speech, computer vision, and beyond.

---

## Table of Contents

- [Text Corpora & Raw Text](#text-corpora--raw-text)
- [Sentiment Analysis & Emotion Detection](#sentiment-analysis--emotion-detection)
- [Question Answering](#question-answering)
- [Machine Translation & Parallel Corpora](#machine-translation--parallel-corpora)
- [Named Entity Recognition (NER)](#named-entity-recognition-ner)
- [Text Summarization](#text-summarization)
- [Natural Language Inference (NLI) & Entailment](#natural-language-inference-nli--entailment)
- [Spell Checking & Correction](#spell-checking--correction)
- [Part-of-Speech Tagging & Dependency Parsing](#part-of-speech-tagging--dependency-parsing)
- [Irony & Sarcasm Detection](#irony--sarcasm-detection)
- [Text Classification](#text-classification)
- [Instruction Tuning & LLM Datasets](#instruction-tuning--llm-datasets)
- [Speech & Audio — ASR](#speech--audio--asr)
- [Speech & Audio — TTS](#speech--audio--tts)
- [Computer Vision](#computer-vision)
- [OCR](#ocr)
- [Names & Demographics](#names--demographics)
- [Poetry & Literature](#poetry--literature)
- [News & Social Media](#news--social-media)
- [Fact-Checking & Information Verification](#fact-checking--information-verification)
- [Contributing](#contributing)
- [License](#license)

---

## Text Corpora & Raw Text

| Dataset | Description | Source |
|---|---|---|
| [Persian Wikipedia Dataset](https://www.kaggle.com/datasets/miladfa7/persian-wikipedia-dataset) | Persian (Farsi) Wikipedia corpus | Kaggle |
| [Farsi Wiki Dataset](https://github.com/mallahyari/Farsi-datasets/tree/master/farsi_wiki) | Farsi Wikipedia extracted text | GitHub |
| [Farsi News Dataset](https://github.com/mallahyari/Farsi-datasets/tree/master/farsi_news) | Collection of Farsi news articles | GitHub |
| [community-datasets/farsi_news](https://huggingface.co/datasets/community-datasets/farsi_news) | Persian news articles on Hugging Face | Hugging Face |
| [ali619/corpus-dataset-normalized-for-persian-farsi](https://huggingface.co/datasets/ali619/corpus-dataset-normalized-for-persian-farsi) | Normalized Persian/Farsi text corpus | Hugging Face |
| [m522t/farsi_dataset](https://huggingface.co/datasets/m522t/farsi_dataset) | General Farsi text dataset | Hugging Face |
| [PersianWikiText](https://github.com/roshansh/PerWikiText) | Large-scale Persian Wikipedia text extraction | GitHub |
| [Persian Text Corpus (BijanKhan)](https://github.com/ BijanKhan/Persian-Text-Corpus) | Persian text corpus compiled by Bijan Khan | GitHub |

## Sentiment Analysis & Emotion Detection

| Dataset | Description | Source |
|---|---|---|
| [Persian Sentiment Analysis Datasets](https://github.com/Keramatfar/Persian_NLP_Datasets) | Comprehensive reference of Persian sentiment & emotion datasets with loaders | GitHub |
| [SentiPers](https://github.com/phosariyoon/SentiPers) | Sentiment analysis corpus for Persian with polarity labels | GitHub |
| [PerSent](https://github.com/RezaGooner/PerSent) | Persian sentiment dataset with labeled reviews | GitHub |
| [hezarai/sentiment-dksf](https://huggingface.co/datasets/hezarai/sentiment-dksf) | Digikala product sentiment dataset | Hugging Face |
| [Persian Twitter Sentiment](https://www.kaggle.com/datasets/mohammadalimkh/persian-twitter-dataset-sentiment-analysis) | Persian tweets with sentiment labels | Kaggle |
| [ArmanEmo](https://github.com/FatemehAskari/Sentiment-analysis-in-Persian-text-using-deep-learning) | Emotion dataset from Persian tweets, Instagram comments, and customer reviews | GitHub |
| [ShortPersianEmo](https://github.com/vkiani/ShortPersianEmo) | Short Persian emotion classification (5 emotions, 5,472 samples) | GitHub |
| [JAMFA](https://github.com/Azadsee/JAMFA) | Deep emotion detection in Persian literary text (4 emotions, 2,241 samples) | GitHub |
| [Persian Tweets Emotional Dataset](https://www.kaggle.com/datasets/behdadkarimi/persian-tweets-emotional-dataset) | 113,829 Persian tweets labeled with 6 emotions | Kaggle |
| [Persian Sentiment Corpus - Product](https://huggingface.co/datasets/HooshvareLab/sentiment-dksf) | 62,321 user comments on digital products | Hugging Face |
| [Colloquial Persian Sentiment (Mazoochi 2023)](https://arxiv.org/abs/2306.12679) | Colloquial Persian sentiment dataset with 3 polarities | arXiv |
| [Donya/subjective-tasks-farsi](https://huggingface.co/datasets/Donya/subjective-tasks-farsi) | Subjective NLP tasks in Farsi including sentiment | Hugging Face |

## Question Answering

| Dataset | Description | Source |
|---|---|---|
| [PersianQA](https://github.com/sajjjadayobi/PersianQA) | Persian reading comprehension dataset (9,000+ entries, SQuAD-style) | GitHub |
| [PersianQuAD / PerAnSel](https://www.kaggle.com/datasets/jamshidjdmy/peransel) | ~100,000 QA pairs on Persian Wikipedia; native answer selection dataset | Kaggle |
| [ParsiNLU Reading Comprehension](https://huggingface.co/datasets/persiannlp/parsinlu_reading_comprehension) | Persian reading comprehension from ParsiNLU suite | Hugging Face |
| [PersianQA (Kaggle)](https://www.kaggle.com/datasets/sajjjadayobi/persianqa) | Persian question answering dataset on Kaggle | Kaggle |

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
| [Persian-English Wikipedia Parallel](https://arxiv.org/abs/1711.00681) | Parallel sentences extracted from English-Persian Wikipedia | arXiv |
| [Shiraz Corpus](http://wwwusers.di.uniroma1.it/~pilehvar/pubs/CICLING_2011_Pilehvars_Faili.pdf) | 3,000 Persian-English sentence pairs from Hamshahri newspaper | Web |

## Named Entity Recognition (NER)

| Dataset | Description | Source |
|---|---|---|
| [ArmanNER](https://github.com/HooshvareLab/ArmanPersoNERCorpus) | Persian named entity recognition corpus with 3 levels (7,682 tagged tokens) | GitHub |
| [hezarai/arman-ner](https://huggingface.co/datasets/hezarai/arman-ner) | Arman NER dataset on Hugging Face | Hugging Face |
| [PEYNER](https://github.com/RahaProjects/peyner) | Persian NER corpus with 9 entity types | GitHub |
| [hezarai/parstwiner](https://huggingface.co/datasets/hezarai/parstwiner) | Persian twin NER dataset | Hugging Face |

## Text Summarization

| Dataset | Description | Source |
|---|---|---|
| [HooshvareLab/pn_summary](https://huggingface.co/datasets/HooshvareLab/pn_summary) | Persian news summarization dataset | Hugging Face |
| [PasSum](https://github.com/hooshvare/pasport) | Persian summarization dataset with extractive and abstractive summaries | GitHub |

## Natural Language Inference (NLI) & Entailment

| Dataset | Description | Source |
|---|---|---|
| [ParsiNLU Entailment](https://huggingface.co/datasets/persiannlp/parsinlu_entailment) | Persian natural language inference / textual entailment dataset | Hugging Face |
| [ParsiNLU Multiple Choice](https://huggingface.co/datasets/persiannlp/parsinlu_multiple_choice) | Persian multiple-choice reading comprehension | Hugging Face |
| [ParsiNLU Query Paraphrasing](https://huggingface.co/datasets/persiannlp/parsinlu_query_paraphrasing) | Persian query paraphrasing / QQP dataset | Hugging Face |

## Spell Checking & Correction

| Dataset | Description | Source |
|---|---|---|
| [FAspell](https://www.kaggle.com/datasets/rtatman/faspell) | Misspelled Persian words and their corrections (similar to ASpell for English) | Kaggle |
| [Persian Spell Correction Dataset](https://github.com/olomix/persian-spell-checker) | Persian spell checker dataset with word-level corrections | GitHub |

## Part-of-Speech Tagging & Dependency Parsing

| Dataset | Description | Source |
|---|---|---|
| [hezarai/lscp-pos-500k](https://huggingface.co/datasets/hezarai/lscp-pos-500k) | 500K Persian sentences with POS tags (LSCP) | Hugging Face |
| [PerDT (Persian Dependency Treebank)](https://github.com/PerDT/PerDT) | Persian dependency parsing treebank | GitHub |
| [BijanKhan POS Tagged Corpus](https://github.com/persian-nlp/persian-pos) | POS-tagged Persian corpus | GitHub |

## Irony & Sarcasm Detection

| Dataset | Description | Source |
|---|---|---|
| [Persian Irony Detection Dataset](https://nlpdataset.ir/farsi/irony_detection.html) | Persian irony detection dataset listing | Web |
| [Persian Sarcasm Dataset](https://github.com/AmirGahreman/sarcasm_persian) | Persian sarcasm detection dataset from social media | GitHub |

## Text Classification

| Dataset | Description | Source |
|---|---|---|
| [Persian Text Classification Datasets](https://nlpdataset.ir/farsi/text_classification.html) | Listing of Persian text classification datasets | Web |
| [Digikala Product Comments](https://www.kaggle.com/datasets/sobhanmh/persian-digikala-comments) | Persian product reviews from Digikala for classification | Kaggle |

## Instruction Tuning & LLM Datasets

| Dataset | Description | Source |
|---|---|---|
| [mshojaei77/alpaca_persian_telegram](https://huggingface.co/datasets/mshojaei77/alpaca_persian_telegram) | Persian Alpaca-style instruction dataset from Telegram | Hugging Face |
| [mshojaei77/merged_persian_alpaca](https://huggingface.co/datasets/mshojaei77/merged_persian_alpaca) | Merged Persian Alpaca instruction-tuning dataset | Hugging Face |
| [xmanii/persian-alpaca-chat-2k](https://huggingface.co/datasets/xmanii/persian-alpaca-chat-2k) | 2K Persian Alpaca chat-format instructions | Hugging Face |
| [xmanii/persian-alpaca-completion-2k](https://huggingface.co/datasets/xmanii/persian-alpaca-completion-2k) | 2K Persian Alpaca completion-format instructions | Hugging Face |
| [ParsiAI/FarsInstruct](https://huggingface.co/datasets/ParsiAI/FarsInstruct) | Persian instruction-tuning dataset | Hugging Face |
| [taesiri/TinyStories-Farsi](https://huggingface.co/datasets/taesiri/TinyStories-Farsi) | Persian translation of TinyStories for LLM training | Hugging Face |
| [BaSalam/entity-attribute-sft-dataset](https://huggingface.co/datasets/BaSalam/entity-attribute-sft-dataset-GPT-4.0-generated-v1) | Persian SFT dataset with entity-attribute pairs | Hugging Face |
| [MaralGPT/persian_blogs](https://huggingface.co/datasets/MaralGPT/persian_blogs) | Persian blog posts for LLM training | Hugging Face |
| [mshojaei77/SCED](https://huggingface.co/datasets/mshojaei77/SCED) | Persian conversational and educational dataset | Hugging Face |
| [mshojaei77/PersianTelegramChannels](https://huggingface.co/datasets/mshojaei77/PersianTelegramChannels) | Persian text scraped from Telegram channels | Hugging Face |

## Speech & Audio — ASR

| Dataset | Description | Source |
|---|---|---|
| [Common Voice 17 (Persian)](https://huggingface.co/datasets/mozilla-foundation/common_voice_17_0) | Mozilla Common Voice Persian subset — crowdsourced ASR data | Hugging Face |
| [hezarai/common-voice-13-fa](https://huggingface.co/datasets/hezarai/common-voice-13-fa) | Common Voice 13 Persian subset processed by Hezar | Hugging Face |
| [pourmand1376/asr-farsi-youtube-chunked](https://huggingface.co/datasets/pourmand1376/asr-farsi-youtube-chunked-10-seconds) | Persian ASR data from YouTube, chunked into 10-second segments | Hugging Face |
| [DeepMine](https://github.com/deepmine/ds/) | 480+ hours of Persian ASR data from 1,850+ speakers (restricted license) | GitHub |
| [FarsSpon](https://github.com/farsspon) | 530+ hours of Persian speech from 5,300+ speakers | GitHub |
| [SmartGitiCorp/persian_tts](https://huggingface.co/datasets/SmartGitiCorp/persian_tts) | Persian speech dataset (also usable for ASR) | Hugging Face |

## Speech & Audio — TTS

| Dataset | Description | Source |
|---|---|---|
| [ParsVoice](https://huggingface.co/datasets/ParsVoice/ParsVoice) | 1,804 hours, 470+ speakers — large-scale multi-speaker Persian TTS corpus | Hugging Face |
| [Thomcles/Persian-Farsi-Speech](https://huggingface.co/datasets/Thomcles/Persian-Farsi-Speech) | 417 hours of cleaned Persian TTS data (109K samples after filtering) | Hugging Face |
| [ManaTTS](https://github.com/mana-show/ManaTTS) | 86 hours of single-speaker Persian TTS data | GitHub |
| [ArmanTTS](https://github.com/ArmanTTS/ArmanTTS) | 9 hours of single-speaker Persian TTS data | GitHub |
| [ParsiGoo](https://github.com/azsa22/ParsiGoo) | Multi-speaker Persian TTS dataset (6 speakers) | GitHub |
| [AmerAndish TTS](https://github.com/AmerAndish/persian-tts) | 21 hours of single-speaker Persian TTS data | GitHub |
| [Persian TTS (Coqui)](https://github.com/karim23657/Persian-tts-coqui) | Persian/Farsi TTS training using Coqui TTS | GitHub |

## Computer Vision

| Dataset | Description | Source |
|---|---|---|
| [hezarai/persian-license-plate-v1](https://huggingface.co/datasets/hezarai/persian-license-plate-v1) | Persian license plate detection dataset with Farsi digits, letters, and symbols | Hugging Face |
| [Persian License Plate Dataset](https://github.com/mut-deep/Persian-License-Plate-Detection) | Iranian license plates for object detection and classification | GitHub |
| [CLIPfa](https://github.com/sajjjadayobi/CLIPfa) | Connecting Farsi text and images — Persian CLIP training dataset | GitHub |
| [hezarai/flickr30k-fa](https://huggingface.co/datasets/hezarai/flickr30k-fa) | Flickr30k image captions translated to Persian | Hugging Face |
| [hezarai/coco-flickr-fa](https://huggingface.co/datasets/hezarai/coco-flickr-fa) | COCO + Flickr image captions in Persian | Hugging Face |
| [BaSalam/vision-catalogs-llava-format](https://huggingface.co/datasets/BaSalam/vision-catalogs-llava-format-v3) | Persian visual catalog dataset in LLaVA format | Hugging Face |
| [Persian Word Handwritten Dataset](https://www.kaggle.com/datasets/shahmoradi/persian-word-handwritten-dataset) | Handwritten Persian words for recognition | Kaggle |

## OCR

| Dataset | Description | Source |
|---|---|---|
| [hezarai/parsynth-ocr-200k](https://huggingface.co/datasets/hezarai/parsynth-ocr-200k) | 200K synthetic Persian OCR samples | Hugging Face |
| [Persian OCR Dataset](https://github.com/zh Clausen/persian-ocr) | Persian printed text images for OCR training | GitHub |

## Names & Demographics

| Dataset | Description | Source |
|---|---|---|
| [Persian Gender by Name](https://github.com/farbodbj/persian-gender-by-name) | Dataset for determining gender from Persian names with English representations | GitHub |
| [Iranian Surname Frequencies](https://github.com/farbodbj/iranian-surname-frequencies) | 100,000+ Persian surnames with frequencies from 10M+ records | GitHub |

## Poetry & Literature

| Dataset | Description | Source |
|---|---|---|
| [Ganjoor Persian Poetry Corpus](https://github.com/ganjoor/persian-poetry-corpus) | Classical Persian poetry curated from Ganjoor.net for NLP and literary research | GitHub |
| [RezaGooner/PerPoetry](https://github.com/RezaGooner/PerPoetry) | Comprehensive repository of classical Persian poetry for ML applications | GitHub |
| [MaralGPT/persian_quotes](https://huggingface.co/datasets/MaralGPT/persian_quotes) | Collection of Persian quotes | Hugging Face |

## News & Social Media

| Dataset | Description | Source |
|---|---|---|
| [Asriran News Dataset](https://www.kaggle.com/datasets/amirpourmand/asriran-news) | 330,000+ Persian news articles from asriran.com (2005–2022) | Kaggle |
| [Persian Twitter Dataset](https://www.kaggle.com/datasets/mohammadalimkh/persian-twitter-dataset-sentiment-analysis) | Persian tweets from X (Twitter) with sentiment labels | Kaggle |
| [Persian Telegram Channels](https://huggingface.co/datasets/mshojaei77/PersianTelegramChannels) | Large-scale Persian text from Telegram channels | Hugging Face |

## Fact-Checking & Information Verification

| Dataset | Description | Source |
|---|---|---|
| [ParsFEVER](https://github.com/Zarharan/ParsFEVER) | First dataset for Farsi fact extraction and verification | GitHub |

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
