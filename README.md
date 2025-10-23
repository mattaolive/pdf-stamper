# PDF Stamper

A simple web application to stamp and combine multiple PDF files with custom codes and dates.

## Features

- Upload multiple PDF files at once
- Add unique codes to each PDF
- Automatically stamp the first page of each PDF
- Combine all PDFs into a single output file
- Custom date selection

## Usage

1. Select a date (defaults to today)
2. Upload one or more PDF files
3. Enter a code for each PDF
4. Click "Generate Combined PDF"
5. Download your stamped and combined PDF

## Files

- `index.html` - Main application
- `stamp pci.jpg` - Stamp image template

## Deployment

This app is deployed on Netlify and can be accessed at your deployed URL.

## Local Development

To run locally:
```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

