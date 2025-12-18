roject Overview

This project demonstrates how to scrape news headlines, paragraphs  from websites using Python.
It is designed for absolute beginners with no prior coding experience.

The script downloads a webpage, parses its HTML structure, and extracts headlines in a readable format.

What This Project Does

Downloads a webpage from the internet

Parses the HTML content

Extracts news headlines (h1, h2, h3 tags)
EXtracts paragraphs(p tags)

Prints the extracted headlines

Libraries Used and Why
requests

Purpose: Download the webpage
Reason: Websites exist on the internet. This library fetches the raw HTML content.

beautifulsoup4

Purpose: Extract data from HTML
Reason: HTML is unstructured and complex. Beautiful Soup makes it searchable.

html.parser

Purpose: Parse HTML structure
Reason: Helps Beautiful Soup understand the hierarchy of HTML elements.
