# Google Images Scraper

This Python script utilizes Selenium and Requests modules to scrape and download images from Google Images based on a user-provided search query.

## Libraries
- `os`: Operating system operations.
- `time`: Time-related operations.
- `requests`: HTTP library for sending requests.
- `selenium`: Web automation tool for browser automation.
- `PIL`: Python Imaging Library for image processing.
- `io`: Core tools for working with streams.

## Functionality
- `get_images_from_google(driver, delay, max_images)`: Function to extract image URLs from Google Images.
- `scroll_down(driver)`: Function to scroll down the page.
- `download_image(download_path, url, file_name)`: Function to download images from URLs.

## Usage
1. Run the script.
2. Input your desired Google Images search query.
3. The script will create a directory named `imgs` to save downloaded images.
4. It will open a Chrome browser, search for the provided query on Google Images, and scrape image URLs.
5. Images will be downloaded to the `imgs` directory.

## Requirements
- Python 3.x
- Chrome web browser
- Chrome WebDriver
- Selenium (`pip install selenium`)

## Note
Ensure that you have installed the necessary dependencies and have proper permissions to download images to the specified directory.

## Disclaimer
This script is intended for educational purposes only. Scraping Google Images may be against Google's terms of service. Use it responsibly and at your own risk.