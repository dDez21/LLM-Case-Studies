# LLMs Case Studies

Large Language Models (LLMs) comparison project developed as part of my Bachelor's internship and thesis.

This repository contains the material collected during an experimental evaluation of four state-of-the-art Large Language Models — **ChatGPT, Claude, DeepSeek and Gemini** — through two independent case studies focused on **text generation** and **code generation**.

---

## Project Objectives

The goal of this project was to evaluate how different LLMs perform when solving increasingly complex tasks through iterative prompting.

The comparison focuses on two practical scenarios:

- **Text Generation** – adapting a recipe to progressively stricter nutritional and dietary constraints while preserving its culinary identity.
- **Code Generation** – developing a complete desktop application through multiple prompt iterations, refining the software after each interaction.

---

## Case Study 1 — Text Generation

Starting from the recipe of an Italian *Pizza Capricciosa*, each model received a sequence of progressively more challenging requests involving dietary restrictions such as allergies, intolerances, vegetarian and vegan adaptations, gluten-free variants and calorie limits.

For every iteration, the generated recipe was evaluated considering:

- Compliance with the requested constraints
- Preservation of the original recipe identity
- Culinary coherence
- Nutritional consistency

The documents contained in the `LLM/` folder include the conversation links together with a detailed analysis of each response.

---

## Case Study 2 — Code Generation

Each LLM was tasked with developing a complete desktop application in Python through iterative prompting.

The application calculates the nutritional values of recipes using:

- a local food database;
- the USDA FoodData Central API;
- a graphical interface built with **CustomTkinter**.

The repository preserves every development stage, from the initial prototype (based on a static food dictionary) to the final application integrating the USDA API.

This approach allowed the comparison of the models in terms of:

- Requirement understanding
- Code quality
- Debugging capabilities
- Software evolution
- Ability to refine previous implementations

---

## Technologies

- Python
- CustomTkinter
- USDA FoodData Central API
- REST APIs
- Large Language Models (ChatGPT, Claude, DeepSeek, Gemini)

---

## Project Outcomes

The collected material was used to compare the strengths and weaknesses of each model throughout the entire development process, highlighting differences in:

- reasoning capabilities;
- software engineering skills;
- prompt interpretation;
- consistency across multiple iterations;
- quality of generated text and code.

The complete analysis is presented in my Bachelor's Thesis.

---

## Author

**Davide Mariotti**

Bachelor's Degree in Computer Engineering  
Università Politecnica delle Marche
