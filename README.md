Analytics
=========

####ln 19:####
*this is the most important line:*
from gensim import models 
lda = models.LdaModel(corpus, num_topics=3, id2word=dictionary, update_every=5, chunksize=10000, passes=100)

we are asking for 3 topic clusters
then we are printing those words as they are gropued into topics

*tip:* don't show more than 6 clusters

