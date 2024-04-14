# Open Phrasebank

Building your own phrasebank.
  
```bash
pip install openphrasebank
```

- This lib provides open accessible phrasebank, which is a collection of frequent phrases that can be used for e.g. auto-complement function of IDE (This lib does not provide IDE or auto-complete function but ready-for-used phrasebank)
- This repository also contains features building a phrasebank from a given text or open corpus, so that the users can have personal phrasebank.

## Why Phrase Bank
  
### Case 1 - Typing in Flow


Using phrasebank in an IDE. 

gif - Positive phrasebank

### Case 2 - Academic Writing

You can be further customized the phrasebank according your needs, e.g. for certain discipline, for certain style (descriptive, analytical, persuasive and critical), for certain sections (abstract, body text).

The difference of word tree between STEM and ...



## Open Accessible Phrase Bank


| No. | Phrasebank                                                                                                            | Source                                                                                                          | N-gram Length | Lines  | Comments                                                                                     |
| --- | --------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- | ------------- | ------ | -------------------------------------------------------------------------------------------- |
| 1   | [academic_phrasebank.md](https://github.com/liuh886/open_phrasebank/blob/main/academic_phrasebank.md)                 | Book - [Academic Phrasebank](https://github.com/liuh886/open_phrasebank/blob/main/data/Academic_Phrasebank.pdf) | 2-5           | 2,190  | Extract from pdf (Zhihao, 2024)                                                              |
| 2   | elsevier_phrasebank.md                                                                                                | Corpus - Elsevier                                                                                               | 2-6           |        | Extract by n-gram frequency (Zhihao, 2024)                                                   |
| 3   | bawe_1000.md                                                                                                          | Corpus - [British Academic Written English](https://app.sketchengine.eu/#dashboard?corpname=preloaded%2Fbawe2)  | 2-6           | 1,000  | Due to inaccessible, only most frequent used 1000 n-grams (n: 2-6) list here. (Zhihao, 2024) |
| 4   | [google-10000-english.txt](https://github.com/first20hours/google-10000-english/blob/master/google-10000-english.txt) |                                                                                                                 | 1             | 10,000 | The 10,000 most common English words from Google Books Corpus                                |
| 5   | academic_word_list                                                                                                    | [Academic Word List Coxhead (2000)](https://www.uefap.com/vocab/select/awl.htm)                                 | 1             | 570    | The 570 word for academic English (exclude frequent 2000 words of English)   (Coxhead, 2000) |
| 6   | elsevier_academic_word_list                                                                                           |                                                                                                                 | 2-6           |        | The elsevier phrasebank that contains  AWL                                                   |

  


## How to get a self-define Phrasebank

  
  ![](https://i.imgur.com/if1BdNw.png)
  
``` python
import openphrasebank as opb

opb.get_phrasebank ('academic_phrasebank.md')
```


The notebook phrasebank_pdf.ipynb gave an example to extract phrasebank from pdf.

The notebook phrasebank_pdf.ipynb gave an example to extract phrasebank from pdf.

  

