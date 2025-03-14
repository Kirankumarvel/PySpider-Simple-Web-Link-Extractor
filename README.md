
# PySpider-Simple-Web-Link-Extractor
🕷️PySpider: Simple Web Link Extractor

Python Web Crawler - Simple Link Extractor. This Python program extracts all hyperlinks from a given webpage using `urllib` and `BeautifulSoup`.

## Features
- ✅ Fetches web pages using `urllib.request`
- ✅ Parses HTML using `BeautifulSoup`
- ✅ Extracts and prints all anchor (`<a>`) tag links
- ✅ Ignores SSL certificate errors

## Project Structure
```
web-crawler/
│── src/
│   ├── main.py  # Main script to extract links
│── README.md    # Documentation
│── requirements.txt  # Dependencies (BeautifulSoup4)
```

## Installation

Clone the repository:
```sh
git clone https://github.com/your-username/web-crawler.git
cd web-crawler
```

Install dependencies:
```sh
pip install -r requirements.txt
```

## Usage

Run the script and enter a URL:
```sh
python src/main.py
```

Example:
```sh
Enter - https://example.com
```

Output:
```sh
https://example.com/link1
https://example.com/link2
...
```

## Disclaimer

This script is intended for educational purposes only. Scraping websites without permission may violate their terms of service. Always ensure you have proper authorization before using this tool.

## License

MIT License
```

