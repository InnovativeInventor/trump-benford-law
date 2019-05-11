## Trump's tweets compared to Benford's Law

![](https://raw.githubusercontent.com/InnovativeInventor/trump-benford-law/master/trump-benford-law.png)

Benford's Law is a phenomenon that shows that the first digit of numbers in real datasets will follow log base 10 of (1 + 1/d) where d is the leading digit (GitHub READMEs are bad at rendering math). 

Benford's Law is commonly used to detect fraud and has been used in court cases to help prove the falsification of numbers. Because Trump is widely known [to make up statistics](http://wapo.st/trumpclaimsdb), I expected his tweets to not obey Benford's Law and was rather suprised at the results.

All analysis was done in a Jupyter Notebook (`trump-tweet-analysis.ipynb`).

## Data sources
- https://github.com/bpb27/trump_tweet_data_archive
