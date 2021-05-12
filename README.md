# Rasa chatbot

This project is a part of a student thesis done at Blekinge Institute of Technology, testing two open source chatbots and their NLPs.

[Botpress chatbot](https://github.com/Lioo19/chatbotThesis)

## Prerequisites

You need can install Rasa using pip (requires Python 3.6, 3.7 or 3.8). See [Rasa documentation](https://rasa.com/docs/rasa/installation/) for more information.

```
pip3 install -U pip
pip3 install rasa
```

## Download chatbot repo

```
git clone https://github.com/heidipatja/thesis-rasa-chatbot
```

## Commands for testing
**Traning phase 1**
```
rasa shell -m models/phase1.tar.gz --debug
```

**Traning phase 2**
```
rasa shell -m models/phase2.tar.gz --debug
```

**Traning phase 3**
```
rasa shell -m models/phase3.tar.gz --debug
```
