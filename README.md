


The simple idea here is to pull together a list of live events that people could
tune-in for a short time during lockdown. "Taking part" and "knowing that they
are contributing to a wider discussion" might give a sense of togetherness and
shared community. These spaces could be anything from playing a game/quiz
online, doing a online Cult-fit session together, learning courses with friends
online, or watching ramayana on TV. I'm particularly interested in list of
current and recurring online events that happen through the day.


Instructions to use

1) pip install instagram-scraper

2) Open terminal and type
instagram-scraper <channel_name> -t none --media-metadata --maximum 30
e.g., instagram-scraper aalaap_concepts -t none --media-metadata --maximum 30

This will retrieve the meta-information about the last 30 posts from the
instagram channel and store in a folder called "aalaap_concepts" as data JSON
file. Change the number 30 for more posts.

1) Python environment:
Setup the python envrionment with python 3.

2) Fire up jupyter notebook
3) Run the attached Python code. (insta-parsing-text)
3) Execute all the cells in the code
4) The code dumps the json information string in  "database.json" stored in the
same folder as python code.
