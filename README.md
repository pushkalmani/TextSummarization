
# Text Summarization

### List of contents

- [Introduction](#introduction)
- [Working](#working)
- [Installation](#installation)
- [Running](#running)


## Introduction
---
[(Back to top)](#list-of-contents)

The given program collects text from website url given by user and generates it's summary .

## Working
---
[(Back to top)](#list-of-contents)

The step-by-step procedure of the Project:

+ Data in form is collected from website url using urrlib.request , BeautifulSoup python packages .


+ Preparing text for summarization

1. Text is cleaned using re library of python .
2. Tokination of sentences and stopwords using nltk library 
3. Count is maintained for every word left by number of time that word appears .
4. Every Sentence score is generated and sentence with more than 100 words are removed.

+  Summary is generated using heapq the sentences with top scores will be generated .






 

## Installation
---
[(Back to top)](#list-of-contents)

Following Python Libraries need to be installed for the successful completion of project.
- [lxml](https://lxml.de/)
- [beautifulsoup4](https://pypi.org/project/beautifulsoup4/)
- [urllib](https://docs.python.org/3/library/urllib.html)
- [nltk](https://www.nltk.org/)
- [re](https://docs.python.org/3/library/re.html)
- [heapq](https://docs.python.org/3/library/heapq.html)


Install above required packages using pip or any other method.


## Running


- some snapshots from working program.
![img](https://imgur.com/53FpAS0.png)

![img](https://imgur.com/hBAw2LQ.png)

- generating text summary
![img](https://imgur.com/TLD0bKH.png)



