# DATASETS

## Vocabs - Tokens
- Danh sách các từ thông dụng tiếng Việt: [Vietnamese word list](https://www.informatik.uni-leipzig.de/~duc/software/misc/wordlist.html?trk=public_post_comment-text)

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


## Spelling Correction
