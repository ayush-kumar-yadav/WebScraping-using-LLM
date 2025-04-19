# WebScraping-using-LLM
This project is a brochure generator that scrapes company websites and uses Ollama (a local large language model) to generate company brochures in markdown format. It automates the process of gathering information from a company's landing page and other relevant pages and compiles it into a concise and structured brochure.
Features:
Web Scraping: Scrapes essential details like the homepage, about us, and other relevant links from a company’s website.

LLM Integration: Uses Ollama’s local language model to analyze the scraped content and generate a professional brochure.

Markdown Output: Outputs the brochure in markdown format for easy customization and use.

Key Components:
Web Scraping: Utilizes Python libraries like requests, beautifulsoup4, and custom logic to fetch and clean data from a website.

Ollama LLM: Interacts with Ollama to process the scraped content and generate human-readable content for the brochure.

JSON Parsing: Extracts the relevant JSON data from Ollama’s responses for seamless integration into the final brochure.

Error Handling: Implements robust error handling and cleaning mechanisms to deal with unexpected response formats.

Usage
Clone this repository to your local machine.

Install the required dependencies from requirements.txt.

Set up your local Ollama instance to process the content.

Call the main function create_brochure(company_name, url) to generate the brochure for any company.

Example:
python
Copy
Edit
create_brochure("HuggingFace", "https://huggingface.co")
This will scrape data from Hugging Face's website and generate a brochure using Ollama’s language model.

Installation
bash
Copy
Edit
pip install -r requirements.txt
Contributions
Feel free to fork this repository and submit pull requests with bug fixes, improvements, or feature additions!

License
This project is licensed under the MIT License - see the LICENSE file for details.
