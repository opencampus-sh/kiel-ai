# Motivation - Things you can do with NLP

This is a brief overview of use cases of NLP. The goal is to show you what is possible with current NLP techniques and inspire you to use some of these applications for your own. This guide does not attempt to be comprehensive, so if you know of other  interesting application we would be happy to tell us about them

### 1. Automatic text summarisation

Take one or more text documents and create a summary that represents the most important/relevant information from the original text. These summaries can either be “generic” (a general overview of the original text) or “query relevant” (a summary that only focuses on the text that is relevant to a picked topic). The summarisation process is either extractive (directly reproducing parts of the source text word-for-word) or abstractive (forming an internal semantic representation of the original content and using this to write the summary from scratch).

You can play around with a demo bot for this:

{% embed url="https://www.summarizebot.com/text_api_demo.html" %}

### 2. Question answering

This are tools that can answer questions asked in normal (natural) language.

It replies based on either text it saw during training or on some text you provide to it at the same time as asking the question. As with text summarisation, the answering process can either be extractive (directly quoting the source text) or abstractive (writing the answer based on an internal semantic representation of the original content).

{% embed url="https://twitter.com/paraschopra/status/1284801028676653060?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1284801028676653060%7Ctwgr%5Eshare_3&ref_url=https%3A%2F%2Fhuwwalters.com%2Fblog%2Fwhat-you-can-do-with-NLP%2F" %}

### 3. Information extraction

The task of automatically extracting structured information from text documents.

Information extraction can facilitate further computation to be done on the previously unstructured data. There are two main types of information extraction: Named entity recognition and Relation extraction.

Named entity recognition allows you to identify all entities of a predefined category (e.g. Extract all cities; or extract all company names).

Relation extraction builds on top of named entity recognition. In addition to finding the entities, it allows you to detect the semantic relationships between them (e.g. Extract all countries and their capital cities; or extract all companies and the year they were founded in).

{% embed url="https://twitter.com/itsyashdani/status/1285695850300219392?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1285695850300219392%7Ctwgr%5Eshare_3&ref_url=https%3A%2F%2Fhuwwalters.com%2Fblog%2Fwhat-you-can-do-with-NLP%2F" %}

Here is a demo website where you can enter your text and see what subjects are extracted

{% embed url="https://explosion.ai/demos/displacy-ent" %}

### 4. Chat bots

Normal chatbots can hold conversations, answer your questions and carry out simple tasks  (e.g. changing a setting in your account, placing an order or scheduling a meeting for you).

### 5. Text classification

The process of sorting pieces of text into one or more predefined categories. Examples of how this can be used include:

* Text sentiment classification;
* Spam filters;
* Determining whether the author is making a claim or not - as the first step in fact-checking;
* Analysing trends in social media monitoring.

{% embed url="https://dandelion.eu/semantic-text/text-classification-demo" %}

### 6. Machine Translation

Translate from one language to another or let your text be rewritten.

{% embed url="https://twitter.com/michaeltefula/status/1285505897108832257?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1285505897108832257%7Ctwgr%5Eshare_3&ref_url=https%3A%2F%2Fhuwwalters.com%2Fblog%2Fwhat-you-can-do-with-NLP%2F" %}

Check out:

{% embed url="https://www.deepl.com" %}

### 7. Write Code using natural language

Describe what you are trying to achieve, and let the AI draft the code for you (e.g. HTML, CSS, SQL query and Linux commands).

At present the tools that can do this are imperfect and can only really be used to write a first draft that you would need to review

{% embed url="https://twitter.com/sharifshameem/status/1282676454690451457?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1282676454690451457%7Ctwgr%5Eshare_3&ref_url=https%3A%2F%2Fhuwwalters.com%2Fblog%2Fwhat-you-can-do-with-NLP%2F" %}



&#x20;

