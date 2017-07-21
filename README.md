# Kijiji Scraper

Yet another Kijiji scraper based on Selenium


# Usage

## Quick Start

Following command will scrap first page of results:

```bash
python3 kijiji-scraper.py [URL]
```

While *[URL]* should be substituted with the relevant search URL.

> Note that URL should not represent a specific page, script handles pages.


## Advanced Usage

Use built-in help to learn about optional arguments:

```bash
python3 kijiji-scraper.py -h
```

### Pages

By default only first page is scraped, you can increase this value up to 100:

```bash
python3 kijiji-scraper.py [URL] -p [PAGES]
```

## Mail Results

If you wish the results to be emailed to you:

```bash
python3 kijiji-scraper.py [URL] -m --smtp-server [SERVER] --smtp-server-port [PORT] --smtp-server-username [USERNAME] --smtp-server-password [PASSWORD] -r [RECIPIENT_1] [RECIPIENT_2] ...
```

You should substitute placeholders in square brackets with real values.
