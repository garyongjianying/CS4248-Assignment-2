# CS4248-Assignment-2
Assignment 2 for Manual Feature Engineeering on baseline models (NB/LR/SVC)


Preprocessing Technique	Worked/Did not work
Casefolding & Data Normalization (MinMaxScaler)	Worked, helped with improving LogisticRegression (tfidf) f1_score from 0.79682 to 0.8153
Removal of duplicates and clipping of data with contradicting labels to minority class of 0	Worked, helped model generalization of LogisticRegression (tfidf) from 0.8153 to 0.82531.
Lemmatization (considering POS tags)	Did not work
Removal of stopwords & punctuations	Did not work


Feature Engineering
Type of Feature	Worked/Did not work
Text Subjectivity / Text Polarity	Did not work, 
Counts of different types of Part-of-Speech (POS) tags within a sentence	Worked, improved test f1 score from 0.82531 to 0.84159 for LogisticRegression (tfidf)
Dialog & Narrative parser	Worked
Unique words in sentence ratio	Worked, improved test f1 score from 0.84159 to 0.85446
Stopwords in sentence ratio	Worked, improved test f1 score from 0.84159 to 0.85446
Count of punctuations within the sentence	Did not work
