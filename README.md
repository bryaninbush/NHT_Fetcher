# NHT_Fetcher
# Python Enma Manga Downloader & Analyzer

A tool to download and analyze manga metadata using the Enma library. Features include:
- Download manga by ID(6-digit God's Language)
- Auto-build structured metadata (English and Japanese support)
- Visualization and statistical analysis of your preference
- JSON-based persistent storage

## Setup

```bash
python -m venv .venv
source .venv/bin/activate  # Mac/Linux
.\.venv\Scripts\activate   # Windows
pip install -r requirements.txt
```
## Usage

```bash
python fetch.py
python visualize.py
