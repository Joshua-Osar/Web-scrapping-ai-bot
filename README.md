# AI Web Scraper

AI Web Scraper is an advanced tool that combines web scraping capabilities with AI-powered content parsing. This project allows users to extract specific information from websites based on natural language descriptions.

## Features

- Web scraping with captcha solving capabilities
- AI-powered content parsing using Ollama LLM
- User-friendly interface built with Streamlit
- Modular design for easy extensibility

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.7+
- [Ollama](https://ollama.ai/) installed and running locally

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/ai-web-scraper.git
   cd ai-web-scraper
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

3. Set up your environment variables:
   Create a `.env` file in the root directory and add the following:
   ```
   SBR_WEBDRIVER=your_scraping_browser_webdriver_url
   ```

## Usage

1. Start the Streamlit app:
   ```
   streamlit run main.py
   ```

2. Open your web browser and navigate to the URL provided by Streamlit (usually `http://localhost:8501`).

3. Enter the URL of the website you want to scrape in the text input field.

4. Click "Scrape Website" to extract the content.

5. Once the content is scraped, you can view the DOM content in the expandable text box.

6. In the "Describe what you want to parse" text area, enter a natural language description of the information you want to extract.

7. Click "Parse Content" to process the scraped data using the AI model.

8. The parsed results will be displayed on the page.


![Screenshot (59)](https://github.com/user-attachments/assets/910045e1-b7cb-4c51-a0b0-47f4c5272f19)
![Screenshot (65)](https://github.com/user-attachments/assets/5892fb39-0f2b-4196-a4d6-6ffb8a87d0d5)

## Result
![Screenshot (63)](https://github.com/user-attachments/assets/ccce0b77-6473-4ca8-8f8e-36c07778f473)
![Screenshot (64)](https://github.com/user-attachments/assets/603909c2-147f-4995-9d19-38febe235bed)






## Project Structure

- `main.py`: Contains the Streamlit UI and orchestrates the scraping and parsing processes.
- `scrape.py`: Handles web scraping functionality, including captcha solving and content extraction.
- `parse.py`: Manages the AI-powered parsing using the Ollama LLM.
- `requirements.txt`: Lists all Python dependencies.

## Contributing

Contributions to the AI Web Scraper project are welcome. Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Submit a pull request.

## Acknowledgments

- [Streamlit](https://streamlit.io/) for the user interface framework
- [Langchain](https://python.langchain.com/) for AI integration
- [Ollama](https://ollama.ai/) for the local LLM
- [Selenium](https://www.selenium.dev/) for web scraping
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/) for HTML parsing

## Contact

If you have any questions or feedback, please open an issue on the GitHub repository.
 
