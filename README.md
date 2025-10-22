# Cadence Design Systems Shares Outstanding Data Viewer

A lightweight client-side web application to fetch, process, and display the share outstanding data for Cadence Design Systems or any other company specified via URL parameter. It retrieves data from the SEC's API, processes the JSON to find maximum and minimum shares outstanding for fiscal years after 2020, and updates the webpage dynamically.

## Features

- Fetches data from SEC API with a custom User-Agent as per SEC guidance.
- Supports ?CIK= query parameter to specify different companies.
- Stores and processes `data.json` locally for efficiency.
- Displays the entity name, maximum, and minimum share counts with fiscal years.
- Responsive and styled with Bootstrap 5.3.3 or fallback CSS.

## Usage

Open `index.html` in a browser. To view data for a different CIK, append `?CIK=XXXXXXXXXX` to the URL.

## Notes

- The application validates inputs and handles fetch errors gracefully.
- The code contains inline comments explaining each step.

## License

Licensed under the MIT License.