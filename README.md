# Text to SQL Query Generator 🤖

This Streamlit application allows users to generate SQL queries from natural language prompts with ease.

## Overview

This tool utilizes the GenerativeAI API to translate natural language queries into SQL queries. It provides a simple interface for users to input their queries and generate corresponding SQL code. Additionally, the tool generates sample expected outputs and explanations for the generated SQL queries.

## Features

- Input natural language queries and generate SQL queries.
- View sample expected outputs based on the generated SQL queries.
- Receive explanations for the generated SQL queries.
- Simple and intuitive user interface.

## Getting Started

To run this application locally, follow these steps:

1. Clone this repository to your local machine.
   
    ```
    git clone https://github.com/your_username/your_repository.git
    ```

2. Navigate to the project directory.

    ```
    cd your_repository
    ```

3. Install the required dependencies.

    ```
    pip install -r requirements.txt
    ```

4. Set up your environment variables. Make sure to obtain an API key for the GenerativeAI API from Google and set it in a `.env` file.

    ```dotenv
    GOOGLE_API_KEY=your_api_key_here
    ```

5. Run the Streamlit application.

    ```
    streamlit run app.py
    ```

6. Access the application in your web browser at `http://localhost:8501`.

## Usage

1. Enter your natural language query into the text area provided.
2. Click the "Generate SQL Query" button to generate the corresponding SQL code.
3. View the generated SQL query, sample expected output, and explanation provided by the model.

## Dependencies

- Streamlit
- GenerativeAI
- python-dotenv

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- This project utilizes the GenerativeAI API from Google.
- Special thanks to Streamlit for providing an excellent framework for building interactive web applications with Python.
