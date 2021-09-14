##### The repository with the data and everything is **PRIVATE**, just send me an email at [axel@stoiclab.com](stoiclab.com) or open an issue. 😁🤞🏾
# Osheng | Oshiwambo - English Translation
# All contributers are welcome

This project aims to develop an Oshiwambo-English language dataset and translation model.

## Dictionary book
#### Data collection and cleaning
  - This involves extracting text from open source Oshiwambo <-> English Translation dictionary, online blog entries, online newspaper entries etc.
  - Then format the text into a .txt file, where for each row: "Onde mu adha megumbo." then a translated sentence in english is entered "I found him in the house.".
  - Word, phrase and complete sentence (defined by full stop) qualify.

## Bible
#### Data collection and cleaning

##### Scraping text from [bible.com](bible.com)
- English https://my.bible.com/bible/1713/GEN.1.CSB
- Oshindonga https://my.bible.com/bible/372/GEN.1.ONDB
- Oshikwanyama https://my.bible.com/bible/469/GEN.1.okyb

#### Neural Machine Translation
- This tensoflow tutorial [Neural machine translation with attention](https://www.tensorflow.org/text/tutorials/nmt_with_attention) helped out a lot 
- Also [A Must-Read NLP Tutorial on Neural Machine Translation – The Technique Powering Google Translate](https://www.analyticsvidhya.com/blog/2019/01/neural-machine-translation-keras/), [Github](https://github.com/prateekjoshi565/machine_translation/blob/master/german_to_english.ipynb)
- Read this paper [Effective Approaches to Attention-based Neural Machine Translation, 2015](https://arxiv.org/pdf/1508.04025v5.pdf)
- [Attention Is All You Need](https://arxiv.org/pdf/1706.03762.pdf) Paper with a great tutorial/explanation [here](https://jalammar.github.io/illustrated-transformer/)
