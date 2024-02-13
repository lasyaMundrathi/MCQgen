# MCQ Generator with LangChain and Streamlit 🦜⛓️

This project harnesses LangChain and Streamlit to create a dynamic application for generating multiple-choice questions. It's tailored for educators and content creators who need to produce quizzes or tests with ease.

## Features

**Upload Text or PDF**: Accepts text or PDF input.
- **Customizable MCQ Generation**: Allows specification of quantity, subject, and complexity.
- **Interactive Web Application**: User-friendly interface powered by Streamlit.

## Project Structure

- `src/mcqgenerator`: Core logic for MCQ generation.
  - `MCQGenerator.py`: Generates the MCQs.
  - `utils.py`: Assists with file operations and data handling.
  - `logger.py`: Manages logging.
- `Streamlitapp.py`: Interface of the Streamlit app.
- `requirements.txt`: Lists dependencies.
- `setup.py`: Installs the project.
- `data.txt`: Provides sample data.
- `Response.json`: Manages LangChain callbacks.

## Installation

To install the project dependencies:

```bash
pip install -r requirements.txt
# or
python setup.py install
```
## Running the Application
To run the Streamlit application:
```bash
streamlit run Streamlitapp.py
```
Streamlit Web Interface
Input your data through the Streamlit interface:

- `File Upload`: Users can upload a text or PDF file.
- `Number of MCQs`: Specify the number of MCQs to generate.
- `Subject`: Insert the subject of content.
- `Complexity Level`: Choose the complexity level of questions.
![image](https://github.com/lasyaMundrathi/MCQgen/assets/98383338/98b00f56-94b0-4872-a448-0d310fa70ae5)

## Terminal Output
Running the Streamlit application using **streamlit run Streamlitapp.py** initiates the MCQ generation process.

![image](https://github.com/lasyaMundrathi/MCQgen/assets/98383338/214fe1ca-5e82-4cec-8579-498e4f1026b0)

 Upon completion, the terminal will display a summary of the LangChain operation, which includes token usage and the associated cost.
 
 Here's an example of the expected terminal output:
 
![image](https://github.com/lasyaMundrathi/MCQgen/assets/98383338/28957573-2536-4cba-9763-e9748ad77d5c)
