# Topic-Modeling
Topic Modelling to segregate news report data to different topics using Gensim, NLTK, Spacy.


Topic modelling as the name suggests, it is a process to automatically identify topics present in a text object and to derive hidden patterns exhibited by a text corpus. Thus, assisting better decision making.
Topic Modelling is different from rule-based text mining approaches that use regular expressions or dictionary-based keyword searching techniques. It is an unsupervised approach used for finding and observing the bunch of words (called “topics”) in large clusters of texts.
Topics can be defined as “a repeating pattern of co-occurring terms in a corpus”. A good topic model should result in – “health”, “doctor”, “patient”, “hospital” for a topic – Healthcare, and “farm”, “crops”, “wheat” for a topic – “Farming”.
We have a dataset which consists of News articles and our task is to assign topics to those articles.
We will do a simple LSI and lastly a LDA method to figure out the topics


Why solve it
Solving it will help you apply the following skills:

- Topic Modelling
- Understanding Topic classification

Task consist of :
1. <b>Loading the data</b>
2. <b>Clean the Data</b> <br>
Transforming text into something an algorithm can digest it a complicated process. We cannot feed the data as it is, some preprocessing needs to be done. In this task we will be doing some preprocessing to convert our data in a form that we can feed our model with.
3. <b>Handling the Stop-words</b><br>
Text may contain stop words like ‘the’, ‘is’, ‘are’. Stop words can be filtered from the text to be processed. There is no universal list of stop words in nlp research, however the nltk module contains a list of stop words. We will remove these stopwords in this task.
4. <b>Lemmatization</b>
5. <b>TF-IDF Vectorization</b><br>
Apart from Count vectorizer an alternative to calculate word frequencies , and by far the most popular method is called TF-IDF. This is an acronym than stands for “Term Frequency – Inverse Document” Frequency which are the components of the resulting scores assigned to each word.
6. <b>Topic modelling using LSA</b><br>
Latent Semantic Analysis, or LSA, is one of the foundational techniques in topic modeling. The core idea is to take a matrix of what we have — documents and terms — and decompose it into a separate document-topic matrix and a topic-term matrix.
7. <b>Topic Modelling using Gensim's LDA</b><br>
One of the drawbacks of LSA is that though it is really fast, its effectiveness in finding good topics is not great. One assumption that LSA makes is that the topics are orthogonal to each other, while Latent Dirichlet Allocation (LDA) relaxes this assumption. Moreover, LDA generalizes the way the documents are generated and this modelling assumption leads to better topics. Let us first understand intuitively how LDA works.
