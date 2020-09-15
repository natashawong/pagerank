# pagerank
PageRank assignment

I've completed both portions of the assignment:
- the program successfully runs the power method, returning the correct order of urls according to their rank
- the program is able to make a personalization vector and have that return again the correct order of urls according to their rank

Data sets provided from https://www.lawfareblog.com.

This program accepts data sets, search queries, different values of alpha, and a filter ratio as parameters to output the rankings of urls in the data set based off Google's PageRank algorithm.

Another parameter is to use the personalization vectory query instead of the usual search query. 

Example commands are below:
$ python3 pagerank.py --data=./lawfareblog.csv.gz --verbose 
$ python3 pagerank.py --data=./lawfareblog.csv.gz --filter_ratio=0.2 --personalization_vector_query='corona'
$ python3 pagerank.py --data=./lawfareblog.csv.gz --verbose --alpha=0.99999
$ python3 pagerank.py --data=./lawfareblog.csv.gz --verbose --filter_ratio=0.2
$ python3 pagerank.py --data=./lawfareblog.csv.gz --verbose --filter_ratio=0.2 --alpha=0.99999

Please allow time for the commands to output.