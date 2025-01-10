# Building a Simple Chatbot from Scratch in Python (using NLTK)

![Alt text](https://cdn-images-1.medium.com/max/800/1*pPcVfZ7i-gLMabUol3zezA.gif)

History of chatbots dates back to 1966 when a computer program called ELIZA was invented by Weizenbaum. It imitated the language of a psychotherapist from only 200 lines of code. You can still converse with it here: [Eliza](http://psych.fullerton.edu/mbirnbaum/psych101/Eliza.htm?utm_source=ubisend.com&utm_medium=blog-link&utm_campaign=ubisend). 

On similar lines let's create a very basic chatbot utlising the Python's NLTK library.It's a very simple bot with hardly any cognitive skills,but still a good way to get into NLP and get to know about chatbots.

Chatbots play a crucial role in modern businesses as they possess the capability to efficiently address customer inquiries and provide information without causing delays. By automating various procedures, they significantly reduce the workload on customer support teams. Achieving this level of automation is made possible through the implementation of Machine Learning, Artificial Intelligence, and Data Science techniques. Chatbots operate by analyzing the input provided by customers and generating appropriate responses based on predefined mappings. To train a chatbot, Recurrent Neural Networks can be employed along with intention datasets in JSON format, while the implementation can be carried out using the Python programming language. The nature of the chatbot, whether it is specific to a particular domain or caters to a wide range of topics, depends on the desired objective.

# Outline
* [Motivation](#motivation)
* [Pre-requisites](#pre-requisites)
* [How to run](#how-to-run)


## Motivation for developing this project
The idea of this project was not to create some SOTA chatbot with exceptional cognitive skills but just to utilise and test my Python skills.

## BlogPost
Underdevelopment currently


### Installation of NLTK
```
pip install nltk
```
### Installing required packages
After NLTK has been downloaded, install required packages
```
import nltk
from nltk.stem import WordNetLemmatizer
nltk.download('popular', quiet=True) # for downloading popular packages
nltk.download('punkt') 
nltk.download('wordnet') 
```



You can run the [chatbot.ipynb](https://github.com/parulnith/Building-a-Simple-Chatbot-in-Python-using-NLTK/blob/master/Chatbot.ipynb) which also includes step by step instructions.
* Through Terminal
```
python chatbot.py
```
