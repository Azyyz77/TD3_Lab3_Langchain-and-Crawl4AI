# 🧰 Python Requirements for Async Web Crawler Project

This project uses an asynchronous web crawler to scrape and process content from the [Pydantic AI documentation](https://ai.pydantic.dev). Below are the required Python packages and their purposes.

---

## 📦 Required Packages

| Package     | Purpose                                                                 |
|-------------|-------------------------------------------------------------------------|
| `crawl4ai`  | Main asynchronous web crawling library used to extract markdown content |
| `psutil`    | Used to monitor memory usage during crawling tasks                      |
| `requests`  | Fetches the sitemap XML for URLs                                        |

---

## 🛠️ Installation

Install all dependencies with the following command:

```bash
pip install crawl4ai psutil requests
