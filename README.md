# NLP Model Translation

## Project Overview

This project focuses on developing a machine learning-based translation system for converting text between English and Thai. It supports both translation directions—English to Thai and Thai to English. The model is optimized for translating basic sentences, though it faces challenges with more intricate phrases due to training limitations.

## Topics

**ENG-THA/THA-ENG Machine Translation**

**Objective:** Develop a machine translation system for [English to Thai] & [Thai to English]
translation.

**Dataset:** Sentence pairs in English and Thai languages from AI Research Thailand.

**Description:** You will build a transformer model (e.g., Transformer, BART) to translate sentences between English and Thai languages. The model should accurately translate text from one language to another while preserving meaning and context.

## Usage Instructions

**- Input:** Provide a sentence in either English or Thai.

**- Select Translation Direction:** Choose [1] for English to Thai or [2] for Thai to English.

**- Output:** The model returns the translated text based on your selection. 

## Model Training Details

**- Training Sessions:** Conducted in four iterations, using checkpoints to incrementally improve the model without starting from scratch.

**- Simplified Configuration:** Due to resource limitations, training was done with basic settings to showcase the translation capabilities while minimizing time and memory requirements.

## Features

**- Dual Translation Options:**
    - [1] English to Thai (EN-TH)
    - [2] Thai to English (TH-EN)
    
**- Basic Sentence Handling:** Translates straightforward sentences with relative ease.

**- Custom Deep Learning Model:** Specifically designed for the English-Thai language pair, trained on a custom dataset.
