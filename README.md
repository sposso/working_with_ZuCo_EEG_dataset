# working_with_ZuCo_EEG_dataset
This tutorial explains the preprocessing steps applied to EEG data in the studies “[ZuCo](https://www.nature.com/articles/sdata2018291): A Simultaneous EEG and Eye-Tracking Resource for Natural Sentence Reading, and "[ZuCo 2.0](https://arxiv.org/abs/1912.00903): A dataset of physiological recordings during natural reading and annotation". 

ZuCo v.1 is a dataset combining EEG and eye-tracking recordings from subjects reading natural sentences. Eye-tracking makes it possible to mark the exact boundaries of each word as a subject reads a sentence, which in turn allows precise extraction of the corresponding EEG signals for every word.
Main features:
1. Subjects: 12 healthy adult native speakers
2. Schematic overview of the three tasks in  the study design. [Source](https://www.nature.com/articles/sdata2018291)
![Schematic overview of the three tasks in  the study design](schematic_overview.png)
The reading materials contain sentences from movie reviews from the Stanford Sentiment Treebank and biographical sentences about notable people from the Wikipedia relation extraction corpus.
- Sentences from the Stanford Sentiment Treebank: 123 neutral, 137 negative, and 140 positive sentences. Total sentences: 400
- Sentences from the Wikipedia relation extraction dataset for the Normal Reading (NR) task: 300
- Sentences from the Wikipedia relation extraction dataset for the task-specific relation task: 407
4. Procedure: The sentences were presented to the subjects in a naturalistic reading scenario, where the complete sentence was presented on the screen and the subjects read each sentence at their own speed. 

   
   




