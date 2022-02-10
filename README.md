# Hindi-Chatbot-RASA
Hindi version of the RASA Mood Bot

## Install dependencies

```sh
apt-get update && apt-get install libffi-dev libxml2-dev libxmlsec1-dev libxmlsec1-openssl python3-dev
```

## Install Rasa dependecies (inside virtual environment)

```
pip install --upgrade pip setuptools wheel
pip install rasa[full]
pip install rasa-x --extra-index-url https://pypi.rasa.com/simple
```
