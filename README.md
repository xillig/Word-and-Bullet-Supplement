# Word-and-Bullet-Supplement
Supplement Material and Code to the Paper: "The Word and the Bullet: Out-Grouping and Threat Framing as Predictors of Terrorist Targeting by ISIS, 2015-2019"

The repository only consists of the final pipeline used to train the LDA Model and the subsequent analysis. The pipeline makes firstly use of "far_near_enemy_pagewise.ipynb" and then of "far_near_enemy_pagewise_5_topic_estimation.ipynb". Files that are loaded into notebooks, like "most_occurring_words_modified.txt", can be provided on request. Additional material, like the "Alittihad News Corpora" or ISIS "Al-Naba" Magazine issues can not be provided due to file size or legal restrictions.

The Granger Causality test and the associated data preparation can be found in "granger_causality.ipynb". The results of the tests are provided in the corresponding txt-files. Please note, that only test results for significant topics / variables are provided.

The Spearman-Correlation analysis has been implemented using STATA. The Do-File code is presented in "Do file 20230515.pdf".

A detailed explaination on the technical implementations of the NLP-Pipeline can be found in "Technical_Annex_on__The_Word_and_the_Bullet__Out_Grouping_and_Threat_Framing_as_Predictors_of_Terrorist_Targeting_by_ISIS__2015_2019_.pdf"
