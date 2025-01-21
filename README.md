# Email Scraper with Flask and WebSocket

This is a web application built using **Flask**, **Flask-SocketIO**, and **BeautifulSoup** that scrapes email addresses from websites, stores them in an SQLite database, and displays the results in real-time on a web interface. The application also includes functionality to handle errors and monitor the scraping process.

## Features

- Scrapes email addresses from websites
- Saves the scraped data (email, company name, URL, and user) into an SQLite database
- Displays scraped data and errors in real-time on a web interface
- Allows adding URLs to the scraping queue through a web interface
- Handles errors and logs them to a database for tracking
- WebSocket-based real-time updates for new leads and errors

## Requirements

- Python 3.x
- Flask
- Flask-SocketIO
- BeautifulSoup4
- Requests
- SQLite (built-in)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/adijain123/Leads_email_scraper.git
    cd Leads_email_scraper
    ```

2. Install the required dependencies from `requirements.txt`:

    ```bash
    pip install -r requirements.txt
    ```

3. Initialize the database by running the app once. This will create the necessary tables in an SQLite database (`scraped_data.db`):

    ```bash
    python app.py
    ```

## Running the Application

To run the Flask application, simply execute:

```bash
python app.py

