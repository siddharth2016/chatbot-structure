# chatbot-structure

A Simple Chatbot Structure using RASA Framework. Just add your intents, entity and actions, train it and see it working !

## Steps

1. Create virtual env - `python3 -m venv venv`
2. Install dependencies

**Make sure to install these dependencies in your virtual env**

To use virtual env

`source venv/bin/activate`

Then

`pip3 install -r requirements.txt`

If this does not seem to work, then

`pip3 install rasa==2.1.3`

`pip3 install spacy==2.3.4`

3. Download en_core in venv

`python -m spacy download en-core-web-md`
