# CSC649 - Setup and First Python Experiment

**Student ID:** 2024405456
**Date:** 9.11.2001  

## Description
A Python program that prompts the user for a text sentence, verifies that it is not blank, and computes both the total word count and character count (including spaces).

## Requirements & Environment
- Python 3.12
- PyCharm Community Edition
- Git

## How to Run
1. Open the project in PyCharm.
2. Ensure the virtual environment (`.venv`) with Python 3.12 is selected.
3. Right-click `main.py` and choose **Run 'main'** (or run `python main.py` in the terminal).

## Test Results
- **Test 1 (Normal input):**
  - Input: `Hello world from Python`
  - Output: `Word count: 4`, `Character count (including spaces): 23`
- **Test 2 (Empty input):**
  - Input: `   ` (spaces only or Enter)
  - Output: `You did not enter a sentence.`
- **Test 3 (Extra spaces):**
  - Input: `   Data   structures   and   algorithms   `
  - Output: `Word count: 4`, `Character count (including spaces): 45`

## Limitation
The program counts all characters including punctuation and whitespace, and words are split purely on whitespace (hyphenated words or contractions like `don't` are counted as a single word).