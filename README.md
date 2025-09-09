# Fandom Scraper
A simple AI (span-marker) powered fandom scraper, written in python and using fandom-py and huggingface span-marker.

## Usage
The 
```python
from fandom_scraper import scrape_fandom
in_path = Path("./witcher_json")
out_path = Path("./async_fandom")
instruct_path = Path("./async_fandom_instruct")

scrape_fandom(in_path, out_path, instruct_path)
```