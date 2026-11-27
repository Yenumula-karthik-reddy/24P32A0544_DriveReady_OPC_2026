About the Project
-----------------
This is a simple AI-powered chatbot built for Sweet Crumbs Home Bakery using Python, LangChain, and Groq API.

The chatbot helps customers get basic information about the bakery, such as cake prices, eggless options, and ordering requirements.

Technologies Used
-----------------
Python
LangChain
Groq API
Google Colab

Features
--------
Answers customer questions about cakes.
Provides basic bakery information.
Supports eggless cake queries.
Informs customers about the 24-hour advance order requirement.
Uses AI to generate polite responses.
Includes a Prompt Guard model to detect unsafe prompts.

Installation
------------
Install the required library:
!pip install langchain_groq

API Setup
---------
Create a Groq API key.
Add the API key to Google Colab Secrets.
Set the secret name as groq-demo.
Run the notebook cells.

Example
-------
Question: What is the price of chocolate cake?

Response: Our chocolate cake starts at $XX for a 6-inch, with options for size and decorations.
