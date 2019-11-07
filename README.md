# NLU Training Data
Crowd-sourced training data for the development and testing of Rasa NLU models. 

---

## About this repository 

<img align="right" height="200" src="https://i.imgur.com/YR7ziAx.png">

This is an experiment with the goal of providing basic training data for developing chatbots, therefore, this repository is open for contributions!

We need your help to create an open source dataset to empower chatbot makers and conversational AI enthusiasts alike, and we very much appreciate your support in expanding the collection of data available to the community.

## How do I contribute?

Each category should contain a list of multiple intents, consider if the set of training data you're contributing could fit within an existing category before creating a new one.

### To contribute via pull request, follow these steps:

1. Create an issue describing the training data you would like to contribute. 

2. Create a new file with a category title and a `NLU.md` file, or contribute to an existing category.  

3. In the `NLU.md` file, format your training data using markdown, and title each section with the intent types e.g.`intent:mood_happy` or `intent:mood_unhappy`

4. Update the `README.md` file, include a list of the intent types added. 

5. Create a pull request describing your changes. 

Your pull request will be reviewed by a maintainer, who will get back to you about any necessary changes or questions. You will also be asked to sign a Contributor License Agreement.

### How should I label my intents?

Please always put the domain at the end of each intent. For example: `ask_transport`

### What do I do if multi-intent utterences? 

If you would like to contribute multi-intent utterences, please add a `+` to indicate an additional intent, for example: `affirm+ask_transport`

### Where do I put intents that fall into multiple domains?

## Categories 

* [Banking](https://github.com/RasaHQ/rasa-training-data/tree/master/banking)
* [Small Talk](https://github.com/RasaHQ/rasa-training-data/tree/master/generic)
* [Mood](https://github.com/RasaHQ/rasa-training-data/tree/master/mood)
* [Weather](https://github.com/RasaHQ/rasa-training-data/tree/master/weather)

---  

## About Rasa

- **What does Rasa do? 🤔**
  [Check out our Website](https://rasa.com/)

- **I'm new to Rasa 😄**
  [Get Started with Rasa](https://rasa.com/docs/getting-started/)

- **I'd like to read the detailed docs 🤓**
  [Read The Docs](https://rasa.com/docs/)

- **I'm ready to install Rasa 🚀**
  [Installation](https://rasa.com/docs/rasa/user-guide/installation/)

- **I want to learn how to use Rasa 🚀**
  [Tutorial](https://rasa.com/docs/rasa/user-guide/rasa-tutorial/)

- **I have a question ❓**
  [Rasa Community Forum](https://forum.rasa.com/)

- **I would like to contribute 🤗**
  [How to Contribute](#how-to-contribute)
