# LinkedIn Auto Connect Bot

## Overview
This script automates the process of logging into LinkedIn and sending connection requests to users based on search criteria. It is developed using Selenium in Python.

## Features
- Logs into LinkedIn using provided credentials.
- Navigates to a specific search results page.
- Identifies and clicks "Connect" buttons on available profiles.
- Sends connection requests without an additional note.

## Prerequisites
Before running the script, ensure you have the following installed:
- Python (>=3.7)
- Google Chrome browser
- ChromeDriver (compatible with your Chrome version)
- Selenium library

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/linkedin-auto-connect.git
   cd linkedin-auto-connect
   ```
2. Install required Python packages:
   ```sh
   pip install selenium
   ```
3. Download the appropriate ChromeDriver for your Chrome version from [here](https://sites.google.com/chromium.org/driver/).
4. Place the ChromeDriver executable in your system's PATH or inside the project directory.

## Usage
1. Open the script (`linkedin_connect.py`) and update the following fields with your LinkedIn credentials:
   ```python
   name.send_keys("your-email@example.com")
   password.send_keys("your-password")
   ```
2. Run the script:
   ```sh
   python linkedin_connect.py
   ```
3. The script will:
   - Log into LinkedIn.
   - Navigate to a specific search results page.
   - Click "Connect" on available profiles.
   - Send connection requests without notes.




