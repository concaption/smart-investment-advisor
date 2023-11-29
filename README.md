# Smart Investment Advisor

This project is a smart investment advisor application built using Python, Streamlit, OpenAI, and yfinance. It uses OpenAI's GPT-3 model to answer user queries and provide investment advice based on the latest stock prices fetched using yfinance.
![Custom GPT](/screenshot.png)

## Features

- Fetches the latest stock prices using yfinance.
- Uses OpenAI's GPT-3 model to answer user queries.
- Provides a chat interface for user interaction.
- Stores chat history in session state.

## Installation

1. Clone the repository.
2. Install the required Python packages using pip:

```bash
make setup
```

3. Clone the `.env.example` file and rename it to `.env`. Then, replace the values with your own.

```bash
cp .env.example .env
```

## Usage

1. Run the Streamlit app:

```bash
make run
```

2. Open the provided local URL in your web browser.
3. Enter your OpenAI API key in the sidebar.
4. Click "Start Chat" to begin interacting with the smart investment advisor.

## How It Works
![](/worflow.png)

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the terms of the MIT license.

## Disclaimer

This application is for informational purposes only. It is not intended to provide any investment advice. Always do your own research before making any investment decisions.