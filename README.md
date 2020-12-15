# chatbot-structure

A Simple Chatbot Structure using RASA Framework. Just add your intents, entity and actions, train it and see it working !

This project features a simple easy to use chatbot that I did for some weekend activity. The task was to have chatbot create a Jira ticket and do some minor tasks like update logs and update its status.

It was just for fun activity kind of thing.

Please use this chatbot foundation to build further bots using Rasa framework.

Below are the steps for installation of rasa framework and getting the bot working !

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

4. Train Model

`rasa train`

Run this command in terminal, where the venv is activated and all dependencies are installed.


