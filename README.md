# AI-Web-Scraper
It uses beautifulsoup to scrape websites and then use ollama models to get details

## Features

- **Streamlit UI**: A user-friendly interface to input URLs and view results.
- **BeautifulSoup**: Efficiently parse and clean HTML content.
- **Ollama Integration**: Utilize the Ollama language model for precise data extraction based on user-defined criteria.
- **Session Management**: Store and manage DOM content using Streamlit's session state.

## Getting Started

Follow these steps to set up and run the AI-Web-Scraper:

### Prerequisites

- Python 3.x
- pip (Python package manager)

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/sandeep-chakraborty/AI-Web-Scraper.git
   cd AI-Web-Scraper
   ```

2. **Install Dependencies:**

   Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

3. **Configure the Model:**

   Update the model to your preferred version of Llama. Open your terminal and run:

   ```bash
   ollama:latest
   ```

   Then, specify the version of Llama you wish to use in ```parse.py```

### Running the Application

Start the Streamlit application to begin scraping:

```bash
streamlit run main.py
```

## Usage

1. **Enter Website URL**: Input the URL of the website you wish to scrape.
2. **Scrape Website**: Click the "Scrape Website" button to fetch and display the website's DOM content.
3. **Parse Content**: Describe the information you want to extract and click "Parse Content" to retrieve the data using Ollama.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests to enhance the project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.