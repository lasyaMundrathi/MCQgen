# MCQ Generator with LangChain and Streamlit

This project leverages the power of LangChain and Streamlit to create an interactive application that generates multiple-choice questions (MCQs) from the input text. It's designed to help educators, content creators, and anyone interested in generating quizzes or tests efficiently.

## Features
Upload Text or PDF: Easily upload your content in text or PDF format.
Customizable MCQ Generation: Specify the number of MCQs, subject, and complexity level.
Interactive Web Application: Built with Streamlit, offering a user-friendly interface.

## Installation
pip install -r requirements.txt
or
python setup.py install

## Run Application
streamlit run Streamlitapp.py

### Project structure 
1) src/mcqgenerator: Contains the core logic for MCQ generation.
2) MCQGenerator.py: The main script for generating MCQs.
3) utils.py: Helper functions for file reading and data manipulation.
4) logger.py: Logging configurations.
5) Streamlitapp.py: The Streamlit application interface.
6) requirements.txt: Required Python libraries.
7) setup.py: Setup script for installing the project.
8) data.txt: Sample data for testing.
9) Response.json: Configuration for LangChain callbacks.

