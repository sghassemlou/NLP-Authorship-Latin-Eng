# NLP-Authorship-Latin-Eng
Does Latin-English translation impact authorship attribution?

## Checklist
-  [x] LSTM RNN as they are adept at capturing sequential information. 
    - [x] make la and en model with the same architecture
    - [x] 1 layer LSTM
    - [x] accuracy scoring
    - [x] F1 Scoring
    - [ ] remove personal paths
-  [ ] Bag-of-N with SVM using a varying N since SVMs are made for multi-class classification.
-  [x] Character Level CNNs as they can capture morphological details and are less sensitive to misspellings or variations in word forms.
    -  [x] 1 conv layer
    -  [ ] try switching models?
    -  [x] F1 scoring?
-  [x] Multilingual BERT + linear classifier.
### Write up checklist
- [x] Abstract: A short overview of the paper.
- [x] Introduction:What is the motivation behind the project? In general terms, what is the hypothesis that you test and how do you go about doing so?
- [ ] Related work: Summarize previous work in the area that you have found. I don't expect you to give a complete and fully up-to-date survey of related work in the area. Instead, aim to cite and discuss at least 3-5 relevant papers, with a focus on how your work differs from theirs.
- [x] Method: Describe the model that you implement, the data set that you use, and any other materials. There should be sufficient details that another researcher is able to more or less replicate your experiment with some effort.
- [ ] Results: Report the results of your experiment, and any general trends that you see. If the evaluation measure used is not a standard one, be sure to define that as well.
- [ ] Discussion and conclusion: What conclusions can be drawn from your experiments? Was your initial hypothesis verified? What are the limitations of your work, and how could it be extended?
- [x] Statement of contributions
