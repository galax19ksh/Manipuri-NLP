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
9. [Machine Translation](#machine-translation)
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


### Machine Translation
| Author & Date | Paper | Summary | 
|:-----------:|:------------:|:------------|
| Doren et al.,2010 | [Manipuri-English Example Based Machine Translation System](https://www.gelbukh.com/ijcla/2010-1-2/Manipuri-English%20Example.pdf)   | The paper presents a Manipuri-English example-based machine translation system, utilizing parallel corpus alignment techniques including POS tagging, morphological analysis, NER, and chunking, achieving BLEU and NIST scores of 0.137 and 3.361 respectively, outperforming a baseline SMT system with the same training and test data.   | 
| Doren et al.,2010    | [Statistical Machine Translation of English-Manipuri using Morpho-syntactic and Semantic Information](https://aclanthology.org/2010.amta-srw.1/)    |The paper introduces a factored Statistical Machine Translation (SMT) system for the English-Manipuri language pair, highlighting the significance of suffixes, dependency relations, and case markers in translation, resulting in improved translation quality, as evidenced by both BLEU score and subjective evaluation.  | 
| Doren et al.,2010    | [Manipuri-English Bidirectional Statistical Machine Translation Systems using Morphology and Dependency Relations](https://aclanthology.org/W10-3811/)     | The paper presents the development of bidirectional Manipuri-English statistical machine translation systems, highlighting the importance of suffixes, dependency relations, and case markers, with factored BLEU scores improved from 13.045 to 16.873 for English-Manipuri and from 13.452 to 17.573 for Manipuri-English translations, alongside subjective evaluation showing enhanced fluency and adequacy compared to baseline systems. | 
|Doren et al.,2011     | [Integration of Reduplicated Multiword Expressions and Named Entities in a Phrase Based Statistical Machine Translation System](https://aclanthology.org/I11-1146/)     |The paper presents the integration of reduplicated multiword expressions (RMWEs) and Multiword Named Entities (MNEs) into a Manipuri-English Phrase Based Statistical Machine Translation (PBSMT) system, utilizing SVM-based machine learning and GIZA++ alignment techniques, resulting in improved BLEU and NIST scores over baseline systems, as well as subjective evaluation indicating enhanced adequacy  | 
| Doren et al.,2012   | [Addressing some Issues of Data Sparsity towards Improving English-Manipuri SMT using Morphological Information](https://www.academia.edu/2973911/Addressing_some_Issues_of_Data_Sparsity_towards_Improving_English_Manipuri_SMT_using_Morphological_Information)     |The paper explores enriching parallel corpora resources for morphologically rich languages like Manipuri, enhancing SMT system performance in terms of both automatic scoring and subjective evaluation over baseline systems through mapping from source to target side using a factored model.    |
| Doren et al.,2013     | [Taste of Two Different Flavours: Which Manipuri Script Works Better for English-Manipuri Language Pair SMT Systems?](https://aclanthology.org/W13-0802.pdf)     |The paper compares the performance of phrase-based statistical machine translation (PBSMT) systems for the English-Manipuri language pair using Bengali script and transliterated Meitei Mayek script, showing that the Bengali script-based PBSMT outperforms in terms of BLEU and NIST scores, despite slight variations in subjective evaluation against automatic scores. | 
| Islam et al.,2017     | [A Review on  Electronic Dictionary and Machine Translation System Developed in North-East India](https://www.computerscijournal.org/vol10no2/a-review-on-electronic-dictionary-and-machine-translation-system-developed-in-north-east-india/)     |The paper discusses the importance and approaches of Electronic Dictionary (E-dictionary) and Machine Translation (MT) systems, highlighting their significance in Natural Language Processing (NLP), particularly in multilingual regions like North-East (NE) India, where few such systems have been developed, underscoring the growing demand for research in this area. | 
| Michael et al.,2020     | [Unsupervised Neural Machine Translation for English and Manipuri](https://aclanthology.org/2020.loresmt-1.10/)   |The paper introduces an unsupervised neural machine translation (UNMT) system for the low-resource English-Manipuri language pair, achieving BLEU scores of 3.1 for en → mni and 2.7 for mni → en translations, with subjective evaluation yielding encouraging results on the translated output.   |
| Meetei et al.,2020    | [English to Manipuri and Mizo Post-Editing Effort and its Impact on Low Resource Machine Translation](https://aclanthology.org/2020.icon-main.7/)     |The paper presents a study on post-editing effort in building a parallel dataset for English-Manipuri and English-Mizo, revealing positive correlations between technical effort and function words for both language pairs, and negative correlations between technical effort and noun words for English-Mizo, with an increase in HBLEU of up to 4.6 for English-Manipuri when using the post-edited dataset for incremental training.  |
| Huidrom et al.,2020     | [Zero-shot translation among Indian languages](https://aclanthology.org/2020.loresmt-1.7)  |The paper explores zero-shot translation on low-resource Indian languages, achieving an increase in translation accuracy, with a balanced data settings score multiplied by 7 for Manipuri to Hindi during Round-III of zero-shot translation.  |
| Laitonjam et al.,2021    | [Manipuri-English Machine Translation using Comparable Corpus](https://aclanthology.org/2021.mtsummit-loresmt.8/)     |The paper explores the effectiveness of unsupervised Machine Translation (MT) models over a Manipuri-English comparable corpus, demonstrating feasibility and identifying future directions for developing effective MT for the Manipuri-English language pair under unsupervised scenarios.   |
| Rahul et al.,2021 | [Statistical and Neural Machine Translation for Manipuri-English on Intelligence Domain](https://link.springer.com/chapter/10.1007/978-981-33-6987-0_21)     |The paper presents the development and outcomes of a Manipuri-English machine translation system in an intelligence domain, utilizing 56,678 parallel corpora from open-source intelligence (OSINT) sources, with statistical machine translation (SMT) achieving a BLEU score of 23.91 and neural machine translation (NMT) outperforming with a BLEU score of 40.67. Additionally, language-specific morphological analysis, particularly focusing on suffixes, yields further improvements, with SMT achieving a BLEU score of 25.03 and NMT achieving a BLEU score of 44. |
| Michael et al.,2022    | [Low resource machine translation of english–manipuri: A semi-supervised approach](https://www.sciencedirect.com/science/article/abs/pii/S0957417422013513)     |This paper introduces a semi-supervised neural machine translation system for English-Manipuri, employing self-training and back-translation techniques, yielding a +0.9 BLEU score improvement with external noise introduction, and outperforming supervised and mBART baselines by up to +4.5 and +1.2 BLEU improvements respectively. |
| Michael et al.,2022   | [An empirical study of low-resource neural machine translation of manipuri in multilingual settings](https://link.springer.com/article/10.1007/s00521-022-07337-8)     |This paper presents a multilingual LSTM-based neural machine translation system for Manipuri and English, incorporating cross-lingual features, which demonstrates improvement over vanilla multilingual and bilingual baselines, with enhanced performance across Manipuri-English and other Indian language-English translation tasks, including zero-shot translation evaluations. |
|Huidrom et al.,2022   | [Introducing EM-FT for Manipuri-English Neural Machine Translation](https://aclanthology.org/2022.wildre-1.1/)   |This paper employs pretrained fastText word embeddings for Manipuri, enhancing machine translation experiments using neural network models, where the Transformer architecture with fastText word embedding model EM-FT consistently outperforms alternatives, while noting a negative impact on translation accuracy with additional training data from a different domain.  |
|Devi et al.,2022 | [An Analysis of Phrase based SMT for English to Manipuri Language](https://aircconline.com/csit/papers/vol12/csit121904.pdf) |This paper presents a phrase-based Statistical Machine Translation (SMT) system from English to Manipuri, leveraging the Moses toolkit and Bengali script, and evaluates its performance using the BLEU metric on tourism, agriculture, and entertainment corpora. |
|Devi et al.,2023    |[An Exploratory Study of SMT Versus NMT for the Resource Constraint English to Manipuri Translation](https://link.springer.com/chapter/10.1007/978-981-99-3761-5_31)   |This study investigates and compares the performance of Statistical Machine Translation (SMT) and Neural Machine Translation (NMT) methods for English-to-Manipuri translation using BLEU, Meteor, TER, and F-measure scores as well as expert evaluation, to determine the most suitable approach for low-resource language pairs. |
| Singh et al.,2023    | [Subwords to Word Back Composition for Morphologically Rich Languages in Neural Machine Translation](https://aclanthology.org/2023.paclic-1.69/)     | This paper proposes a novel approach for neural machine translation (NMT) in morphologically rich languages, segmenting words into morphemes and composing word representations from them, showing improved translation accuracy over baseline subword models in Manipuri-English, Tamil-English, and Marathi-English translation tasks, highlighting the importance of leveraging word boundary information and interrelationships between word morphemes in NMT. |
|Lalrempuii et al.,2023     | [Low-Resource Indic Languages Translation Using Multilingual Approaches](https://link.springer.com/chapter/10.1007/978-981-99-6690-5_27)   |This study explores the effectiveness of multilingual pre-trained transformers—mBART and mT5—on low-resource Indic languages, including Hindi, Bengali, Assamese, Manipuri, and Mizo, comparing their performance with multiway multilingual translation trained from scratch using a one-to-many and many-to-one approach, highlighting the scalability of multilingual neural machine translation (MNMT) and its potential for improving translation quality in low-resource language settings.  |
|Pal et al.,2023   | [Findings of the WMT 2023 Shared Task on Low-Resource Indic Language](https://aclanthology.org/2023.wmt-1.56.pdf)    |This paper outlines the outcomes of the low-resource Indic language translation task conducted alongside the Eighth Conference on Machine Translation (WMT) 2023, where participants were tasked with developing machine translation systems for English-Assamese, English-Mizo, English-Khasi, and English-Manipuri language pairs. The evaluation of these systems will include both automatic metrics (BLEU, TER, RIBES, COMET, ChrF) and human assessment, utilizing the IndicNE-Corp1.0 dataset, comprising parallel and monolingual corpora for northeastern Indic languages like Assamese, Mizo, Khasi, and Manipuri.  |
|Singh et al.,2023     | [NITS-CNLP Low-Resource Neural Machine Translation Systems of English-Manipuri Language Pair](https://aclanthology.org/2023.wmt-1.92.pdf)     | This paper presents a transformer-based Neural Machine Translation (NMT) system developed by NITS-CNLP for the English-Manipuri language pair, achieving BLEU scores of 22.75 for English to Manipuri and 26.92 for Manipuri to English translations, along with character level n-gram F-score (chrF), RIBES, TER, and COMET evaluations.  |
|Agrawal et al.,2023     | [Neural Machine Translation for English - Manipuri and English - Assamese](https://aclanthology.org/2023.wmt-1.86.pdf)  |In the WMT23 shared task: low resource Indic language translation challenge, our team, ATULYA-NITS, utilized the NMT transformer model for English to/from Assamese and English to/from Manipuri language translation, achieving BLEU scores of 15.02 and 18.7 for English to Manipuri and Manipuri to English translations respectively, as well as 5.47 for English to Assamese and 8.5 for Assamese to English translations.  |
