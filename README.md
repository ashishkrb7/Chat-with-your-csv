# Chat with csv

This project is a chat application that utilizes Azure OpenAI, Langchain, and Streamlit. The application allows users to interact with a language model powered by Azure OpenAI and perform operations on CSV files using Langchain. The user interface is built using Streamlit, making it easy to navigate and use the application.

## Features

- Chat with a language model: Users can engage in conversations with the language model powered by Azure OpenAI. The language model can understand and generate text based on user inputs.
- CSV operations: Users can perform various operations on CSV files, such as reading, writing, updating, and analyzing data. The Langchain library is used to handle these CSV operations efficiently.
- User-friendly interface: The application provides a streamlined and intuitive user interface built using Streamlit. It enables users to interact with the chatbot and perform CSV operations seamlessly.

## Prerequisites

Before running the project, make sure you have the following dependencies installed:

- Python 3.7 or above
- Azure OpenAI package and credentials
- Langchain package
- Streamlit package

## Configuration

Before running the application, you need to configure your Azure OpenAI credentials. Create `.env` file in the project root and add the following environment variables:

```txt
api_type = ""
api_base = ""
api_version = ""
OPENAI_API_KEY = 
```

## Sample dataset

Dataset is doenloaded from [Kaggle](https://www.kaggle.com/datasets/swatikhedekar/price-prediction-of-diamond)

## Getting Started

1. Clone the repository:

```shell
git clone https://github.com/ashishkrb7/Chat-with-your-csv.git
```

2. Change to the project directory:

```shell
cd Chat-with-your-csv
```

3. Install the project dependencies (if not installed already):

```shell
pip install -r requirements.txt
```

4. Run the Streamlit application:

```shell
streamlit run app.py
```

5. The application will be accessible in your browser at `http://localhost:8501`. Open the URL to start using the chat with CSV application.

## Usage

Once the application is up and running, you can use the chatbot and perform CSV operations through the user interface provided by Streamlit. The chatbot will respond to your queries and generate responses based on the conversation history.

To perform CSV operations, simply provide the appropriate commands and parameters to interact with the Langchain library. The application will execute the requested operations on the CSV files.

## Contributing

Contributions to the project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code for personal or commercial purposes.
