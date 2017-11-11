# PDM Assignment

## Guideline
The exercise consists in getting some Wikipedia articles and building a binary classifier for them – in the next two weeks.
* Pick two Wikipedia categories (e.g. Computer Science and Sports)
* Download 1000 articles of each category.
* Train a classifier that is able to distinguish between the two categories using the plain text of an article (classification algorithm of your choice). Please use at least 5 classifiers, and at least one neural net.
* Test the classifier on 100 articles of each class (unseen during training) and report the results. Discuss the results, plot them nicely – this is the most important part.

## Deadline
Sunday 12th November (9 days)
## Content

```
.  
├── data                                    % folder with our data 
│   ├── doc_topic_dist_2.npy                    % 2 topics extracted with lda
│   ├── doc_topic_dist_3.npy                    % 3 topics extracted with lda
│   ├── doc_topic_dist_4.npy                    % 4 topics extracted with lda 
│   ├── doc_topic_dist_5.npy                    % 5 topics extracted with lda
│   ├── doc_topic_dist_6.npy                    % 6 topics extracted with lda
│   ├── doc_topic_dist_7.npy                    % 7 topics extracted with lda
│   ├── doc_topic_dist_8.npy                    % 8 topics extracted with lda
│   ├── doc_topic_dist_10.npy                   % 10 topics extracted with lda
│   ├── doc_topic_dist_12.npy                   % 12 topics extracted with lda
│   ├── doc_topic_dist_15.npy                   % 15 topics extracted with lda
│   ├── doc_topic_dist_17.npy                   % 17 topics extracted with lda
│   ├── doc_topic_dist_20.npy                   % 20 topics extracted with lda
│   ├── doc_topic_dist_25.npy                   % 25 topics extracted with lda
│   ├── doc_topic_dist_30.npy                   % 30 topics extracted with lda
│   ├── softeng1000.csv                         % 1000 articles of Category: Sofware Engineering
│   ├── software_engineering_depth1.csv         % Category: Sofware Engineering from PetScan
│   ├── software_engineering_depth1.json        % Category: Sofware Engineering from PetScan
│   ├── sports_depth1.csv                       % Category: Sports from PetScan
│   ├── sports_depth1.json                      % Category: Sports from PetScan
│   ├── sports1000.csv                          % 1000 articles of Category: Sport 
│   ├── tfidf_mat.npy                           % TF-IDF matrix
│   └── wikiArticles_preprocessed.csv           % Prepocessed articles contents (2000 articles)
├── 1 - wikiArticle_collection.ipynb        % notebook for data collection
├── 2 - NLP.ipynb                           % notebook for text processing
└── 3 - Classification.ipynb                % notebook for classificaions
```

