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
├── data                               % folder with our data 
│   ├── doc_topic_dist_2.npy                    % different price scale wines
│   ├── doc_topic_dist_3.npy                    % wide vintage range for LivEx wines
│   ├── doc_topic_dist_4.npy                    % bourgogne wines 
│   ├── doc_topic_dist_5.npy                    % same vintage, different regions
│   ├── doc_topic_dist_6.npy                    % same vintage, different regions
│   ├── doc_topic_dist_7.npy                    % same vintage, different regions
│   ├── doc_topic_dist_8.npy                    % livex 2000-2015
│   ├── doc_topic_dist_10.npy                   % livex sold in France
│   ├── doc_topic_dist_12.npy                   % livex sold in Switzerland
│   ├── doc_topic_dist_15.npy                   % Smith Haut Laffite
│   ├── doc_topic_dist_17.npy                   % Smith Haut Laffite
│   ├── doc_topic_dist_20.npy                   % Smith Haut Laffite
│   ├── doc_topic_dist_25.npy                   % Smith Haut Laffite
│   ├── doc_topic_dist_30.npy                   % Smith Haut Laffite
│   ├── softeng1000.csv                         % Smith Haut Laffite
│   ├── software_engineering_depth1.csv         % Smith Haut Laffite
│   ├── software_engineering_depth1.json        % Smith Haut Laffite
│   ├── sports_depth1.csv                       % Smith Haut Laffite
│   ├── sports_depth1.json                      % Smith Haut Laffite
│   ├── sports1000.csv                          % Smith Haut Laffite
│   ├── tfidf_mat.npy                           % Smith Haut Laffite
│   ├── doc_topic_dist_30.npy                   % Smith Haut Laffite
│   └── wikiArticles_preprocessed.csv  
└── src                                % data visualization and analysis notebooks
    ├── 1 - wikiArticle_collection.ipynb        % notebook for data collection
    ├── 2 - NLP.ipynb                           % notebook for text processing
    └── 3 - Classification.ipynb                % notebook for classificaions
```
