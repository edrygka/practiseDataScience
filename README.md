# practiseDataScience

homework 2:
CountVectorizer(stop_words='english')

CV score for class toxic is 0.9511152860174915
CV score for class severe_toxic is 0.9557955066523144
CV score for class obscene is 0.9621081334629311
CV score for class threat is 0.95123654817994
CV score for class insult is 0.9430304072682705
CV score for class identity_hate is 0.9119961594738827
Total score is 0.945880340175805
CPU times: user 3min 24s, sys: 1.78 s, total: 3min 26s
Wall time: 3min 27s

LogisticRegression(class_weight='balanced')
CountVectorizer(stop_words='english')

Регуляризация - 0.5
Total score is 0.954723079249353

0.75
Total score is 0.954174586412591

1
Total score is 0.9534784282778883

1.25
Total score is 0.9540908854680779

1.5
Total score is 0.953534602848463

___________________________________
TfidfVectorizer(analyzer='word', # token = word
                    ngram_range=(1,1), # only unigrams are used, (1,2) - unigrams/bigrams, ..., etc.
                    stop_words='english', # or stop_words='english'
                    vocabulary=None, # or vocabulary=your_own_dictionary
                    max_df=1.0, # don't filter words by their frequency
                    smooth_idf=True,
                    norm='l2' # euclidean norm is used by default
                    )
Total score is 0.9778229641473549

c = 0.9
Total score is 0.9778623978854962

c = 0.8
Total score is 0.9778882851359153

c = 0.7
Total score is 0.9778932545817983 

c = 0.6
Total score is 0.9778655028155786

c = 0.4
Total score is 0.9776301607098844


0.978735893237438 with cv = 5 - MAX
