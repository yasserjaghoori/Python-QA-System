# QA System – Wikipedia-Based Question Answering
This project implements a Question Answering (QA) system in Python using a Jupyter Notebook. It answers Who, What, When, and Where questions by retrieving and parsing content from Wikipedia.

## Features
Accepts natural language input from users

Answers factual "Who", "What", "When", and "Where" questions

Uses spaCy for Named Entity Recognition (NER)

Searches Wikipedia using both wikipediaapi and wikipedia libraries

Logs each question and answer for auditing

Simple logging for traceability

## How It Works
User Input: The user types a question into the input prompt.

NER & Question Type Detection: The system determines the type of question (Who, What, When, Where).

Wikipedia Search:

It searches Wikipedia for relevant articles using the topic from the question.

Retrieves and parses the content.

Answer Extraction:

Named Entities or relevant sentences are selected using spaCy.

Display Answer: The most relevant response is shown.

## Technologies Used
Python 3

Jupyter Notebook

spaCy – Natural Language Processing

wikipedia & wikipediaapi – Wikipedia content retrieval

re / json / sys – Standard Python utilities for text parsing and logging

## Example
Question: Who is the CEO of Nvidia?
Answer: Jensen Huang

## Authors
Yasser Jaghoori
Andrej Paskalov
Yaseen Trombati
George Mason University 
