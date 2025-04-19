# WebScraping-using-LLM
This project is a brochure generator that scrapes company websites and uses Ollama (a local large language model) to generate company brochures in markdown format. It automates the process of gathering information from a company's landing page and other relevant pages and compiles it into a concise and structured brochure.

Features:

1.Web Scraping: Scrapes essential details like the homepage, about us, and other relevant links from a company’s website.

2.LLM Integration: Uses Ollama’s local language model to analyze the scraped content and generate a professional brochure.

3.Markdown Output: Outputs the brochure in markdown format for easy customization and use.

Key Components:

1.Web Scraping: Utilizes Python libraries like requests, beautifulsoup4, and custom logic to fetch and clean data from a website.

2.Ollama LLM: Interacts with Ollama to process the scraped content and generate human-readable content for the brochure.

3.JSON Parsing: Extracts the relevant JSON data from Ollama’s responses for seamless integration into the final brochure.

4.Error Handling: Implements robust error handling and cleaning mechanisms to deal with unexpected response formats.

Usage
1.Clone this repository to your local machine.

2.Install the required dependencies from requirements.txt.

3.Set up your local Ollama instance to process the content.

4.Call the main function create_brochure(company_name, url) to generate the brochure for any company.


Contributions
Feel free to fork this repository and submit pull requests with bug fixes, improvements, or feature additions!

License
This project is licensed under the MIT License - see the LICENSE file for details.
