# WGU Chip - Computer Science Career Guidance Chatbot

WGU Chip is an AIML-based career guidance chatbot designed to help computer science students explore potential career paths based on their interests and work preferences.

![image](https://github.com/user-attachments/assets/bf9c4ce0-9778-494b-b615-69231b6560b9)


## Overview

The chatbot uses a questionnaire-based approach to match students with potential career paths in computer science. Through a series of five targeted questions, it evaluates student preferences and provides compatibility scores for different tech careers.

### Features

- Interactive career assessment quiz
- Personalized career matching algorithm
- Detailed information about 5 key tech careers:
  - Software Engineering
  - UX Design
  - Data Science
  - Cybersecurity Analysis
  - Database Administration
- Dynamic scoring system that recognizes overlapping career interests

![image](https://github.com/user-attachments/assets/212478e3-32df-47c3-8f06-b66fefc57007)


## Implementation

The chatbot is implemented using AIML (Artificial Intelligence Markup Language) and hosted on the Pandorabots platform. The implementation consists of several key files:

- `UDC.AIML`: Default category handling
- `MAIN.AIML`: Core chatbot initialization and basic interactions
- `QUESTIONS.AIML`: Quiz implementation and scoring logic
- `CAREERS.AIML`: Career information and results handling
- `MATH.MAP`: Mathematical operations mapping

## Usage

The chatbot can be accessed through the Pandorabots platform:
1. Visit https://home.pandorabots.com/home/sign-in
2. Create an account or log in
3. Navigate to https://home.pandorabots.com/dash/bot-directory
4. Search for "WGU Chip Chatbot"

## Technical Details

### Scoring System

The chatbot uses a weighted scoring system where:
- Primary career matches receive 8 points
- Secondary matches receive 4 points
- Final scores are converted to percentages (score/40 * 2.5)

### Career Information

Each career profile includes:
- Core responsibilities
- Required skills
- Salary ranges
- Education requirements
- Career progression paths
- Key tools and technologies
- Industry focus

## Development

This project was developed as part of WGU's Introduction to Artificial Intelligence course (C951). It demonstrates the practical application of AIML in creating an educational guidance tool.
