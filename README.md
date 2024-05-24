# Advancements-in-Manipuri-NLP
My repo "Advancements in Manipuri NLP" will provide a comprehensive study of research papers regarding Natural Language Processing (NLP) applications and developments of Manipuri language

## Introduction
Manipuri (Meiteilon), a language of Tibo-Burman origin is the official language and lingua franca of the northeast Indian state of Manipur. Despite its status as one of India's 22 Scheduled languages and a communication tool for over 1.5 million speakers across states like Manipur, Assam and Tripura, Manipuri remains a low resource language, impeded by sparse annotated data and technological advancements. While Manipuri boasts a rich morphology, complex agglutinative structure, and unique SOV word order, it also presents a thrilling challenge for NLP researchers. This is further compounded by its monosyllabic and compounding nature. Despite these complexities, researchers have made commendable strides in NLP applications like Part-of-Speech tagging, Name Entity Recognition, and machine translation. 

Interestingly, Manipuri uses two writing systems: the borrowed Bengali script and its own indigenous Meitei Mayek. While most research has focused on Bengali script, Meitei Mayek holds immense potential for future exploration. It's clear that significant progress is needed for both scripts to unlock the full potential of Manipuri NLP. This github repo will serve as the ultimate destination for the analysis of the NLP applications, approaches, challenges and future directions of Manipuri. I will post all papers and updates there has been in this realm with a summary and analysis.

## Index
1. [Morphological Analysis](#morphological-analysis)
2. [Syllabification, Stemming, Chunking](#)
3. [POS Tagging](#)
4. [Named Entity Recognition](#)
5. [Word Sense Disambiguation](#)
6. [RMWE](#)
7. [Corpus Creation and E-Dictionary](#)
8. [Parsing](#)
9. [Machine Translation](#)
10. [Transliteration](#)
11. [Sentiment Analysis](#)
12. [Speech Technologies](#)



### Morphological Analysis

| Author & Date | Paper | Summary | 
|:-----------:|:------------:|:------------| 
| Choudhury et al.,2004   | [Morphological Analyzer for Manipuri: Design and Implementation](https://link.springer.com/chapter/10.1007/978-3-540-30176-9_16)    | implements a Manipuri morphological analyzer by employing Morphographemics and Morphotactics, alongside a model addressing orthographic variations and morphosyntactic feature combinations.    
| Singh et al.,2005     | [Manipuri Morphological Analyzer](https://www.academia.edu/1150157/Manipuri_Morphological_Analyzer)    | utilizes a Manipuri-English dictionary for identifying word morphemes and an affix dictionary for categorizing affix types.
| Singh et al.,2006 | [Word Class and Sentence Type Identification in Manipuri Morophological Analyzer](https://www.academia.edu/1150153/Word_Class_and_Sentence_Type_Identification_in_Manipuri_Morophological_Analyzer)     | The developed Manipuri Morphological Analyzer, utilizing a Manipuri-English dictionary for root words and an affix dictionary for affix types, yields surface-level word analysis aiding in the development of a Manipuri-English machine translation system, showcasing promising results.     |
| Nongmeikapam et al.,2012     | [Manipuri Morpheme Identification](https://aclanthology.org/W12-5008.pdf) | This approach used involves segmenting Manipuri words into syllables and employing 2-gram analysis with Standard Deviation technique for morpheme identification, achieving recall of 59.80%, precision of 83.02%, and an f-score of 69.52%.   |
| Singha et al.,2012     | [Morphological Analysis for Manipuri Nominal Category Words with Finite State Techniques](https://research.ijcaonline.org/volume58/number15/pxc3883688.pdf) | The paper proposes a suffix stripping approach for analyzing nominal category Manipuri words, utilizing finite state machines to model morphotactics and converting non-deterministic finite automata to deterministic finite automata, facilitating morphological analysis without a lexicon. | 
| Singha et al.,2013    | [Morphotactics of Manipuri Adjectives: A FiniteState Approach](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=4aaa66c6f90c51a9feb8ddc9629548b7d7c3c500)     |This paper presents a constrained finite-state model to represent the morphotactic rule of Manipuri adjective word forms, which are derived from verb roots using specific affixes, with rules composed to describe their simple agglutinative morphology and more complex structures, resulting in a system capable of analyzing and recognizing adjectives through finite-state networks, utilizing a root lexicon and an affix dictionary.  |
| Devi et al.,2015     | [Manipuri morphological generator](https://ieeexplore.ieee.org/abstract/document/7377324/similar#similar)     | The paper presents a morphological generator for Manipuri, focusing on inflecting root words to cater to the complex morphology of Manipuri nouns and verbs, with coverage directly tied to the size of the root list. | 
|  Bablu et al.,2017     | [Morphological Analysis of Manipuri Language](https://www.caeaccess.org/archives/volume6/number8/bablu-2017-cae-652527.pdf)     | The Morphological Analyzer for Manipuri applies computational morphology principles to analyze Manipuri word forms, achieving an 80\% accuracy rate when tested on 3500 Manipuri words in Shakti Standard format using Meitei Mayek script as a source.  | 
| Devi et al.,2020     | [Morphotactics of Manipuri Verbs: A Finite State Approach](https://www.researchgate.net/publication/339709527_Morphotactics_of_Manipuri_Verbs_A_Finite_State_Approach)     | The paper investigates the morphotactics of Manipuri verbs using a Finite State Approach, crucial for understanding word formation in this language, where verbs serve as the main morphology and all other word forms are derived from them through affixation, providing essential insights for Natural Language Processing applications  | 
| Bablu et al.,2020     | [Manipuri Morphological Analysis](https://trp.org.in/wp-content/uploads/2021/01/AJCST-Vol.9-No.2-July-December-2020-pp.-4-10.pdf)    |The Morphological Analyzer for Manipuri language, tested on 4500 Manipuri lexicons using Meitei Mayek Unicode as a source, achieves an 84% accuracy rate, providing valuable grammatical information associated with the lexicon for Natural Language Processing applications. |
| Devi et al.,2022    | [Allomorphs in Meeteilon (Manipuri) Morphology](https://www.nepjol.info/index.php/lsnj/article/view/46557)  | The paper focuses on studying the distribution of phonologically conditioned allomorphs in Meeteilon morphology to understand its morphosyntactic nature, facilitating morpheme segmentation, identification, and parts of speech tagging for natural language processing, alongside an introduction to an optimality theory approach for syllable final devoicing |
