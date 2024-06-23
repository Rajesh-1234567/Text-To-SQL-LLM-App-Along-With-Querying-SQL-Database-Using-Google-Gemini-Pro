# Text to SQL Query Retrieval

## Overview

This project leverages the Google Gemini Pro LLM model to convert natural language queries into SQL queries. It enables users to interactively retrieve data from a SQLite database through a web application built with Streamlit.

## Technology Stack

- **Google Gemini Pro LLM**
- **Python**
- **SQLite**
- **Streamlit**

## Features

- Converts natural language queries into SQL queries
- Retrieves data in real-time from a SQLite database
- Interactive web interface for inputting queries and displaying results
- Handles errors for invalid queries and database issues

## Usage

1. **Input Natural Language Query**: Users enter a query in natural language.
2. **Conversion to SQL**: The query is processed and converted into an SQL query using the Google Gemini Pro LLM model.
3. **Database Query Execution**: The SQL query is executed against a SQLite database.
4. **Result Display**: The results are displayed in the Streamlit web application.

## Future Enhancements

- Support for complex queries involving joins and subqueries
- Integration with additional database systems
- Improved natural language understanding for more accurate query conversion
- User authentication and session management for personalized query history

## License

This project is licensed under the MIT License.
