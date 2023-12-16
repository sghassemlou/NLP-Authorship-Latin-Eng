# NLP-Authorship-Latin-Eng
Does Latin-English translation impact authorship attribution?

## Checklist
-  [ ] LSTM RNN as they are adept at capturing sequential information. 
    - [x] make la and en model with the same architecture
    - [x] 1 layer LSTM
    - [ ] multi-layer LSTM
    - [x] accuracy scoring
    - [ ] F1 Scoring, confusion matrix
-  [ ] Bag-of-N with SVM using a varying N since SVMs are made for multi-class classification.
-  [ ] Character Level CNNs as they can capture morphological details and are less sensitive to misspellings or variations in word forms.
-  [x] Latin BERT, a pre-trained contextual language model for the Latin language, trained on 642.7 million words from a variety of sources spanning the Classical era to the 21st century
