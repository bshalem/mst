# What is MST?
MST is a hight-quality and sustainable movie review dataset we constructed to study automatic
spoiler detection in social media posts.

The data was scraped from unsolicited tweets and paired with a title caption and meta-data 
we extracted from the rich Internet Movie Database (IMDb).

The dataset is formatted as a pair of collections of movie and tweet json objects, respectively.

# Download MST
The dataset comprises the movies [sa_movies.json](sa_movies.json) and tweets [sa_tweets.json](sa_tweets.json) files.

# Paper
More details on the collecting of the data is available in our companion paper:

- Avi Bleiweiss. *Finding Spoiler Bias in Tweets by Zero-shot Learning and Knowledge Distilling from Neural Text Simplification*. In LTEDI/EACL 2021.

### Citation
If you use the MST dataset as part of your work, please cite:

    @inproceedings{bleiweiss-2021-finding,
      title = "Finding Spoiler Bias in Tweets by Zero-shot Learning and Knowledge Distilling from Neural Text   Simplification",
      author = "Bleiweiss, Avi",
      booktitle = "Proceedings of the First Workshop on Language Technology for Equality, Diversity and Inclusion",
      month = apr,
      year = "2021",
      address = "Kyiv",
      publisher = "Association for Computational Linguistics",
      url = "https://www.aclweb.org/anthology/2021.ltedi-1.7",
      pages = "51--60",
    }
    
