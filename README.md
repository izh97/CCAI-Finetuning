# The Climate Change AIctivist

## Overview
This project aims to develop an AI-powered chatbot providing informed and accurate information on climate change. The bot aims to assist users in understanding complex climate-related topics, leveraging data from various authoritative sources.

## Data Sources
The foundation of this project is built upon a meticulously curated set of data sources, including academic research papers and data from the Global Environmental Outlook.

## Data Preprocessing
Significant effort was dedicated to manual preprocessing of data, mostly in PDF format. This involved removing formatting artifacts and converting data into a text format suitable for AI processing. Details can be found in [Clean_pdf_data_example.ipynb].

## Data Summarization and Question Generation 
Utilizing the GPT-3.5 API, the project involved:
1. **Summarization** [Generate_questions_gpt3.5.ipynb]: Summarizing each paragraph to distill essential information, focusing on general climate change concepts.
2. **Question Generation** [Generate_summary_gpt3.5.ipynb]: Generating questions based on the summarized data to create a diverse question-answer pair collection.

## Model Training and Fine-Tuning
The project is based on a pre-trained quantized Zephyr7b model, which was fine-tuned on over 27000 question-answer pairs. The preliminary fine-tuning results and hyperparameter configuration can be found in [Fine-tune_zephyr7b.ipynb]

## Current Status and Next Steps
The chatbot has undergone initial training and is in early testing stages. Future work includes evaluation, expanding the knowledge base, and a small-scale deployment.
