# Transferbot
Experiment in conversational banking to learn about interaction using natural language.

A demo can be found at https://seriousme.github.io/transferbot/

The transferbot is composed of 3 parts:
- the AI, provided by https://api.ai  (two instances: one English version and one Dutch version)
- the (very simplistic) banking backend hosted at https://firebase.google.com/ to maintain balances
- the web frontend hosted using gitHub pages, including voice recognition when using Chrome using the selected language

The frontend can be easily replaced by other [channels](https://docs.api.ai/docs/integrations) an example being the [default API.ai web agent](https://bot.api.ai/transferbot) and the [Dutch API.ai web agent](https://bot.api.ai/transferbotNL)
