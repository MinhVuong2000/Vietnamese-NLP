# Table of Contents
1. [Corpus](#Corpus)
2. [Vocabs - Tokens - Stopword -Dictionary](#Vocabs---Tokens---Stopword---Dictionary)
3. [Part of Speech Tagging](#Part-of-Speech-Tagging)
4. [Named Entity Recognition](#Named-Entity-Recognition)
5. [Automatic Speech Recognition (ASR) & Text-To-Speech (TTS)](#Automatic-Speech-Recognition-(ASR)--Text-To-Speech-(TTS))
6. [Summarization](#Summarization)
7. [Question Answering](#Question-Answering)
8. [Spelling Correction](#Spelling-Correction)

## Corpus
- [VNTC](https://github.com/duyvuleo/VNTC)
- [Binhvq News Corpus](https://github.com/binhvq/news-corpus)
- [Common Crawl](https://commoncrawl.org/): web crawl data.
- [WikiDumps](https://dumps.wikimedia.org/): Download via scripts from [viwik18](https://github.com/NTT123/viwik18), [viwik19](https://github.com/NTT123/viwik19)
- [VNESEcorpus](http://viet.jnlp.org/download-du-lieu-tu-vung-corpus): 650.000 sentences from vietnamnet.vn, dantri.com.vn, nhandan.com.vn.
- [VNTQcorpus(samll)](http://viet.jnlp.org/download-du-lieu-tu-vung-corpus): 300.000 sentences from vnthuquan.net.
- [VNTQcorpus(big)](http://viet.jnlp.org/download-du-lieu-tu-vung-corpus): 1.750.000 sentences from vnthuquan.net.
- [OSCAR](https://oscar-corpus.com/): 68GB of text data with 12.036.845.359 words

## Vocabs - Tokens - Stopword - Dictionary
- Danh sách các từ thông dụng tiếng Việt: [Vietnamese word list](https://www.informatik.uni-leipzig.de/~duc/software/misc/wordlist.html?trk=public_post_comment-text)
- Stopword: [Vietnamese Stopwords](https://github.com/stopwords/vietnamese-stopwords)
- Từ điển: [Vietnamese Dictionary](https://www.informatik.uni-leipzig.de/~duc/Dict/)

## Part of Speech Tagging
- Phân nhóm các từ loại khác nhau theo chủ đề: [vietnamese-wordnet](https://github.com/zeloru/vietnamese-wordnet) 
```
vi-wordnet.tar.xz
│──verb.animal.csv
│──noun.animal.csv
│──adj.animal.csv
│──verb.animal.csv
│──adj.animal.csv
│──interj.csv
│──adj.csv
│──prep.csv
│──pron.csv
│── ...
```
- [word_tokenize](https://github.com/jackNhat/word_tokenize/tree/master/data)
```
data/
│──jvnsegmenter_data
│──viettreebank
│──vlsp2013
│──vlsp2016
```

## Named Entity Recognition
- 10 loại thực thể [COVID-19 Named Entity Recognition for Vietnamese](https://github.com/VinAIResearch/PhoNER_COVID19)


## Automatic Speech Recognition (ASR) & Text-To-Speech (TTS)
Name |	Source |	Hours
--- | --- | ---
VLSP 2020 | [VinBigdata-VLSP2020-100h](https://drive.google.com/u/0/uc?id=1vUSxdORDxk-ePUt-bUVDahpoXiqKchMx&export=download) | 100h
InfoRe Technology 2 (used in VLSP2019) | [InfoRe2](https://files.huylenguyen.com/audiobooks.zip) (passwd: BroughtToYouByInfoRe) | 415h
InfoRe Technology 1 | [InfoRe1](https://files.huylenguyen.com/25hours.zip) (passwd: BroughtToYouByInfoRe) | 25h
InfoRe Technology 1 (denoised & aligned version) | [denoised & aligned InfoRe1](https://github.com/NTT123/vietTTS) | 25h
"Vu Trong Phung"'s novels and short stories | [book](https://github.com/NTT123/Vietnamese-Text-To-Speech-Dataset) | 35.9h
Vivos | https://zenodo.org/record/7068130 | 15h
Common Voice | https://commonvoice.mozilla.org/en/datasets | 17h
FPT Open Speech Dataset | https://data.mendeley.com/datasets/k9sxg2twv4/4 | 30h


## Summarization
Name |	Source
--- | ---
wikilingua | https://drive.google.com/drive/folders/1PFvXUOsW_KSEzFm5ixB8J8BDB8zRRfHW
vietnews | https://github.com/ThanhChinhBK/vietnews
ViMs | https://github.com/CLC-HCMUS/ViMs-Dataset/blob/master/ViMs.zip
XLsum | https://github.com/csebuetnlp/xl-sum

You can also translate English Dataset to Vietnamese to use through googletrans library & huggingface (python)


## Question Answering
Name |	Source
--- | ---
MultiLingual Question Answering (vietnamese) | https://github.com/facebookresearch/MLQA
Squad (vietnamese) | https://github.com/deepmind/xquad/blob/master/xquad.vi.json
UIT-ViQuAD | https://aclanthology.org/2020.coling-main.233/
mailong25 | https://github.com/mailong25/bert-vietnamese-question-answering/tree/master/dataset
QA_viuit | https://github.com/vietnguyen012/QA_viuit (training, test & trial)

## Spelling Correction

Name |	Source
--- | ---
Viwiki-spelling | https://github.com/heraclex12/Viwiki-spelling
VSEC | https://github.com/VSEC2021/VSEC/tree/main/Dataset
