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
