# Utilizing-Cognitive-Signals-to-Improve-Keyphrase-Extraction

#Dataset（Because the data set is too large, it cannot be uploaded to the GitHub project）
- Keyphrase Extraction Dataset
 The Election-Trec dataset is sourced and modified from https://trec.nist.gov/data/tweets/, and the final dataset is formed through integration and modification.
 The General-Twitter dataset was developed by (Zhang et al., 2016) and uses hashtags as keywords for each tweet. The project data set was finally completed through modifications
- Cognitive Signal Dataset
 The cognitive signal data set was extracted from https://osf.io/2urht/#!, and was modified to form the project data set.
 
BERT_1 and BERT_1 mainly compare the model performance capabilities of different models after adding EEG and ET cognitive signals.

BERT_EEG_1 and BERT_EEG_2 mainly compare the model performance capabilities of different models after adding only EEG cognitive signals.

BERT_ET_1 and BERT_ET_2 mainly compare the model performance capabilities of different models after adding only ET cognitive signals.

BERT_without_1 and BERT_without_2 mainly compare the model performance capabilities of different models after only adding cognitive signals without adding cognitive signals.

Different feature combinations of EEG1 mainly compare the impact of a single EEG signal band and adjacent EEG signal bands on model performance.

RoBERTa_1 and RoBERTa_2 compare the performance of the RoBERTa model under different cognitive signal combinations.
