# LIC2019_Knowledge-driven-dialogue
[2019 Language and Intelligence Challenge -- Knowledge-driven Dialogue task](http://lic2019.ccf.org.cn/talk)

**Knowledge-driven Dialogue:** This is a human-machine dialogue task, which requires machines to have conversations with humans based upon a given knowledge graph. It aims to equip machines with the ability to simulate human conversations.

This code is from the **7th team: sysu-wholly**.

## Requirements

* cuda=9.0
* cudnn=7.0
* python=3.6
* pytorch=1.0.1
* numpy
* nltk
* scikit-learn

## Interact
Start the conversation server
```
python conversation_server.py
```
Start the conversation client. For example,
```
python conversation_client.py sample.txt
```
