Project Description: Climate Change Chatbot
Overview
This project aims to develop an AI-powered chatbot that provides informed and accurate information on climate change. The bot is designed to assist users in understanding complex climate-related topics, leveraging data from various authoritative sources.

Data Sources
The foundation of this project is built upon a meticulously curated set of data sources, including academic research papers and data from the Global Environmental Outlook. The data collection process, while essential, is not the focus of this documentation and thus is not detailed here.

Data Preprocessing
Given the complexity and diversity of the data, a significant portion of the project was dedicated to manual preprocessing. A large volume of the data was in PDF format, requiring specialized handling to remove formatting artifacts and convert it into a text format suitable for further processing. This critical step ensured the data's readiness for integration into the AI model. The specific methodologies and tools used for this phase are outlined in [placeholder_notebook_name].

Data Summarization and Question Generation
To refine the data further, I employed the GPT-3.5 API for two crucial tasks:

Summarization: Each paragraph of the pre-processed data was summarized using GPT-3.5. This step was aimed at distilling the essence of the information, focusing on general climate change concepts rather than text-specific details. This approach helps prevent the model from overfitting on particular texts and formulations.
Question Generation: Again using GPT-3.5, I generated a series of questions based on the summarized data. This creative use of AI not only enhanced the diversity of the dataset but also contributed to a more robust and varied question-answer pair collection.
Model Training and Fine-Tuning
The project progressed to the model training phase, where a pre-trained Zephyr7b model was fine-tuned using the [placeholder number] question-answer pairs generated. This step was pivotal in tailoring the model specifically to the domain of climate change, enabling it to provide informative and contextually relevant responses.

Current Status and Next Steps
As of now, the chatbot has undergone initial training and is in the early stages of testing. The next phases of the project will involve rigorous evaluation, iterative improvements, and possibly the integration of additional data sources to broaden the bot's knowledge base.

Project Goals
The ultimate goal of this project is to create an accessible and reliable resource for individuals seeking to understand climate change better. By leveraging advanced AI technologies, this chatbot aims to make complex environmental information more digestible and engaging for a wide audience.
