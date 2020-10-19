## NLTK 

is specialized on gathering and classifying unstructured texts. If you need e.g. a POS-tagger, lemmatizer, dependeny-analyzer, etc, you'll find them there, 
and sometimes nowhere else. It offers a quit broad range of tools developped mainly in academic research. But: most often it is not very well optimized 
-involving NLTK libraries often means to accept a huge performance loss. If you do text-gathering or -preprocessing, its fine to begin with - until you 
found some faster alternatives.

## SKLEARN 

offers a very systematic, efficient framework for machine-learning, analyzing, ensemble methods, evaluation and validation, and hyper-parameter optimization. 
It is very well documented (with a lot of ready to use recipes and examples), well optimized, and covers a broad range of ‘state of the art’ machine learning and 
statistical methods, the latter especially for evaluation purposes. Due to its integrity, it is ideal to start learning ‘machine learning’.

## GENSIM 

is a very well optimized, but also highly specialized, library for doing jobs in the periphery of "WORD2VEC". That is: it offers an easy, surpringly 
well working and swift AI-approach to unstructured raw texts, based on a shallow neural network. If you are interested in prodution, or in getting 
deeper insights into neural networks, you might also have a look on TensorFlow, which offers a mathematically more generalized model, yet to be paid 
by some ‘unpolished’ performance and scalability issues by now.

## My conclusion 

Although considerably overlapping, I personally prefer using NLTK for the pre-processing of natural text (i.e., gathering, wrangling, stemming, 
POS-tagging, filtering and ‘noise’-reduction), GENSIM as kind of base platform (for autoencoding, semantic (topics) and syntactic (sequence) pattern- and 
as such for similiarity- recognition, dimensionality reduction, and for multilabel classification), and SKLEARN, which easily can be mixed up with NLTK and GENSIM, 
for third step evaluation / ensembling / optimizing / processing issues.
