# lyrics information retrieval

a little search engine that searches for a song using it's lyrics

## features:
* literal search
* search with lemma and removing the stopwords
* rank search
* wild card search

## how to run it:
* install ide that support jupyter notebook
* install python 3
* install recommended libraries
* import and run "lyrics web crawler.ipynb" to create lyrics.json file, the lyrics.json file will contain 100 songs lyrics from https://www.lyrics.com, if you want to change it, put x whatever number you like so it will look for x songs lyrics temp.run(x)
* import and run "irs project.ipynb" after it and run B.search("lyrics you want") to get the song that have that specific lyrics

## recommeneded libraries:
* pandas
* numpy
* collections
* re
* nltk
* json
* sci-learn
* string
* urllib
* requests
* bs4
* extruct
* time

## example of use:

<h4> Query:</h4>

* B.search("amazing series")

<h4> Outputs:</h4>

* Keith Sweat: Til the Morning
* Tom Odell: Grow Old with Me

