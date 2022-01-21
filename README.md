# Romance or Thriller?

## About the project

The aim of this project is to implement and analyse supervised Machine Learning algorithms that identify the genre of a movie given features including audio, visual and metadata features. 

## Background

As video-based contents are spread, companies which provide video entertainment services, such as Netflix, YouTube, try to offer recommendation lists to attract more users. One way to recommend a content is based on its genre. A person who likes action movies is highly likely to search for similar movies. A previous study, [1] presented a movie-genre classifier using audio and visual features, yet the model performance was too poor to be practical. Here I implement a competitive recommendation system with more informative features which is text-based information provided by human annotators. 

## Datasets

The dataset consists of metadata, audio, visual features and genre labels. It is retrieved from [1-2]. Metadata provides movie title, year of release and tags which are created by human annotators. Audio and visual features involve continuous numerical values from the movie trailer. These are not interpretable. Details are as follows:

• `train features.tsv` - features of 5240 training instances <br>
• `train labels.tsv` - a genre label for each training instance <br>
• `valid features.tsv` - features of 299 validation instances <br>
• `valid labels.tsv` - a genre label for each validation instance <br>

Each movie with a unique movieID is provided with three different types of features. Details are as follows:

• Metadata features - a title, year of release, and a list of tags (like ‘predictable’, ‘boring’, or ‘based on a book’)<br>
• Visual features - 107 pre-computed visual features from the movie trailer; each feature takes a continuous floating point value<br>
• Audio features - 20 pre-computed audio features from the movie trailer; each feature takes a continuous value<br>


Movies are labelled as one of 18 different genres; Action, Adventure, Animation, Children, Comedy, Crime, Documentary, Drama, Fantasy, Film noir, Horror, Musical, Mystery, Romance, Sci fi, Thriller, War, and Western

## Implemented models 

ZeroR (baseline)<br>
Multilayer Perceptron
  
## Version 

Python 3.7.11<br>
Numpy 1.19.5<br>
scikit-learn 0.23.1<br>
matplotlib 3.2.2<br>
Pandas 1.0.5<br>
NLTK 3.6.7


## References 
[1] Yashar Deldjoo, Mihai Gabriel Constantin, Markus Schedl, Bogdan Ionescu, and Paolo Cremonesi. 2018. Mmtf-14k: A multifaceted movie trailer feature dataset for recommendation and retrieval. Proceedings of the 9th ACM Multimedia Systems Conference, MMSys 2018(1):11-21. 

[2] F. Maxwell Harper and Joseph A. Konstan. 2015. The movielens datasets: History and context. ACM Transactions on Interactive
Intelligent Systems (TiiS), 5(4):19.

----

Have fun! 🍿🎥 <br>🧟? 🦸‍♀️? 💑🏽?
