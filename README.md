# MCQ Generator with LangChain and Streamlit

This project leverages the power of LangChain and Streamlit to create an interactive application that generates multiple-choice questions (MCQs) from the input text. It's designed to help educators, content creators, and anyone interested in generating quizzes or tests efficiently.

## Features
Upload Text or PDF: Easily upload your content in text or PDF format.
Customizable MCQ Generation: Specify the number of MCQs, subject, and complexity level.
Interactive Web Application: Built with Streamlit, offering a user-friendly interface.

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

## Installation
pip install -r requirements.txt
or
python setup.py install

## Run Application
streamlit run Streamlitapp.py

### Streamlit web Interface:
File Upload: Users can upload a text or PDF file (up to 200MB) that contains the content for generating MCQs.

Number of MCQs: Users can specify the desired number of MCQs to generate.

Subject: Users have the option to insert the subject related to the content.

Complexity Level: Users can select the complexity level of the questions, such as 'Simple', 'Intermediate', or 'Advanced'.

![image](https://github.com/lasyaMundrathi/MCQgen/assets/98383338/98b00f56-94b0-4872-a448-0d310fa70ae5)

### Output:
Running the Streamlit application using **streamlit run Streamlitapp.py** initiates the MCQ generation process.

![image](https://github.com/lasyaMundrathi/MCQgen/assets/98383338/214fe1ca-5e82-4cec-8579-498e4f1026b0)

 Upon completion, the terminal will display a summary of the LangChain operation, which includes token usage and the associated cost. Here's an example of the expected terminal output:
 
![image](https://github.com/lasyaMundrathi/MCQgen/assets/98383338/28957573-2536-4cba-9763-e9748ad77d5c)




