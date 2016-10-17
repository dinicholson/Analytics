Analytics
=========

*ln 19:*
##this is the most important line:##
from gensim import models 
lda = models.LdaModel(corpus, num_topics=3, id2word=dictionary, update_every=5, chunksize=10000, passes=100)

