# Scrapy Quotes Tutorial Example

A small Scrapy exercise that extracts quote text, authors and tags and follows pagination.

## Scope

Although the package is named `carrefour`, the spider targets the quotes.toscrape.com tutorial site. The implementation follows the standard quotes tutorial pattern; it is not a Carrefour data integration or an original scraping framework. Spider placement in `__init__.py` should be checked before relying on CLI discovery.

## Technology / Material

Python · Scrapy

## Repository guide

- [carrefour/__init__.py](carrefour/__init__.py)
- [carrefour/spiders/__init__.py](carrefour/spiders/__init__.py)
- [carrefour/settings.py](carrefour/settings.py)
- [scrapy.cfg](scrapy.cfg)

## Getting started / Reproducibility

Review the spider module layout and Scrapy settings in a compatible Python environment. CLI discovery and a live crawl were not verified in this documentation review.
