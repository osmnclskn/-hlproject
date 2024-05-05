# Chat with MySQL

This is a simple MySQL chat application. Users can connect to a MySQL database and interact with an SQL assistant by asking questions or making queries.

## Features

- **Database Connection**: Users can enter MySQL database credentials (host, port, username, password, and database name) and establish a connection.
  
- **Interactive Chat Interface**: Users can interact with the SQL assistant by typing messages in the chat interface.
  
- **SQL Assistant**: The SQL assistant generates responses to user queries based on chat history and database schema.

## Installation

To run the application locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies with `pip install -r requirements.txt`.
3. Ensure MySQL is installed and running.
4. Create your MySQL database and schema.
5. Create a `.env` file in the project directory and add your MySQL database credentials.
6. Run the application with the command `streamlit run app.py`.
7. Access the application through your web browser.

## Usage

1. Enter your MySQL database credentials in the sidebar and click the "Connect" button to establish the connection.
2. Start typing messages in the chat interface to interact with the SQL assistant.
3. The SQL assistant will generate SQL queries based on chat history and the database schema.
4. View the SQL responses provided by the SQL assistant in the chat interface.


