# Hindi-Chatbot-RASA
Hindi version of the RASA Mood Bot

## Install dependencies

```sh
apt-get update && apt-get install libffi-dev libxml2-dev libxmlsec1-dev libxmlsec1-openssl python3-dev
```

## Install Rasa dependecies (inside virtual environment)

```sh
pip install --upgrade pip setuptools wheel
pip install rasa[full]
pip install rasa-x --extra-index-url https://pypi.rasa.com/simple
```
## Train the bot

```sh
rasa train
```

## Run the bot on Rasa X 
(need to accept license for first time run on machine)

```sh
rasa x
```

## Setup fasttext's Hindi vectors for RASA
<a href="https://fasttext.cc/docs/en/crawl-vectors.html" target="_blank">Full list here</a>

```sh
sh scripts/hindi_setup_full.sh
```