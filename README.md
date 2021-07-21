# German Hate Speech Corpus
This repository contains several German text instances from different sources (facebook comments, tweets etc.; see section [references](#References)), which are **manually re-annotated** as either hate speech (hs), offensive/problematic language (p) or non-hate (n). All files are tab-separated CSV files. **The corpus is currently under construction and is prone to change.**

## Content

### HASOC

The HASOC dataset includes 818 German tweets as well as German facebook comments classified as either hate or non-hate. The comments were gathered with a keyword based approach in [1]. As the corpus predominantly contains non-hate, we again sampled from the corpus to obtain a (preliminary) equal ratio of hate and non-hate in this dataset.

### Hatr
The Hatr dataset contains 432 text instances that were extracted from [hatr.org](http://hatr.org/), a website that collects German hate posts from various German blogs.

### German refugees

This dataset contains 469 text instances from Ross et al. [2], which is a [corpus on offensive tweets](https://github.com/UCSM-DUE/IWG_hatespeech_public) about the refugee crisis. The tweets were gathered with a keyword based approach, the keywords all being hashtags in this case.

### GermEval 2018

This dataset contains 2871 text instances from the [tweet corpus](https://github.com/uds-lsv/GermEval-2018-Data) described in [3], created as part of the GermEval 2018 Task on the Identification of Offensive Language. For this project, we only included the tweets that were classified as 'OFFENSE'. 

### POLLY

The POLLY corpus originally contains political 125.000 German tweets around the time of the German federal election in 2017 [4]. Here, we only re-annotated a sample of tweets (around 4.500) that were previously annotated as "hateful" to maintain a balanced dataset overall.

## Acknowledgements

The German hate speech project at the University of Würzburg, including the creation of the hate speech dataset presented here, was made possible with funding from the [Mapara Stiftung](https://stiftungen.bayern.de/stiftung/5827;jsessionid=9DCACF4D2F31F155E6EA1BC2782EF2FC).

Many thanks also go to Lukas Weimer, who previously supervised the project.

## References

<a id="1">[1]</a> 
Mandl, Thomas, Sandip  Modha, Prasenjit  Majumder, Daksh  Patel, Mohana  Dave, Chintak  Mandlia, and Aditya  Patel. "Overview of the HASOC track at FIRE 2019: Hate Speech and Offensive Content Identification in Indo-European Languages."
*FIRE '19: Proceedings of the 11th Forum for Information Retrieval Evaluation*, 2019. 14–17.

<a id="1">[2]</a> 
Ross, Björn, Michael Rist, Guillermo Carbonell, Benjamin Cabrera, Nils Kurowsky, and Michael Wojatzki. "Measuring the Reliability of Hate Speech Annotations: The Case of the European Refugee Crisis." *Proceedings of NLP4CMC III: 3rd Workshop on Natural Language Processing for Computer-Mediated Communication*, 2016. 6-9.

<a id="1">[3]</a> 
Wiegand, Michael, Melanie Siegel, and Josef Ruppenhofer. "Overview of the GermEval 2018 Shared Task on the Identification of Offensive Language."
*Proceedings of GermEval 2018, 14th Conference on Natural Language Processing (KONVENS 2018)*, 2018. 1-10.

<a id="1">[4]</a> 
De Smedt, Tom, and Sylvia Jaki. "The Polly corpus: Online political debate in Germany." *Proceedings of the 6th Conference on Computer-Mediated Communication (CMC) and Social Media Corpora (CMC-corpora 2018)*. 2018.
