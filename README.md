# Facebook Profile Scraper

This Python script uses Selenium to scrape basic public information from Facebook profiles. The script automates the login process and extracts details such as profile name, location, relationship status, contact information, website links, and basic info.

## Features
- **Automated Login**: Logs into Facebook using provided credentials.
- **Profile Data Extraction**: Scrapes data like name, location, relationship status, and more from public Facebook profiles.
- **Headless Mode**: Runs in the background without opening a browser window.
- **Logging**: Provides detailed logs for every action and potential errors.
- **JSON**: Saves In JSON File.

## Prerequisites
1. **Python 3.x** installed on your system.
2. Required Python libraries:
   - `selenium`
   - `webdriver-manager`
3. **Google Chrome** installed.
4. A **Facebook account** with valid login credentials.

## Installation
1. Clone the repository or download the script:
   ```bash
   git clone https://github.com/your-repository/facebook-profile-scraper.git
   cd facebook-profile-scraper
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the script:
   ```bash
   python facebook.py
   ```
2. Enter your Facebook credentials when prompted.
3. Provide the URL of the Facebook profile you want to scrape. Type `exit` to quit the program.

### Example Interaction
```plaintext
Enter your Facebook email/phone: user@example.com
Enter your Facebook password: ********
Enter Facebook profile URL to scrape (or type 'exit' to quit): https://www.facebook.com/profile_name
```

## Logging
All actions and errors are logged to the console. This includes:
- Login success or failure
- Profile data extraction progress
- Missing information or unavailable data

## Notes
- This script adheres to Facebook's public data scraping limits. Ensure you only scrape publicly available information to comply with legal and ethical guidelines.
- The script runs in headless mode by default to minimize system resource usage.

## Troubleshooting
- **WebDriver Errors**: Ensure that Chrome and `chromedriver` are up-to-date.
- **Login Issues**: Double-check your credentials and ensure 2FA is disabled for seamless automation.
- **Timeouts**: Increase the `WebDriverWait` durations in the script if pages take longer to load.

## Disclaimer
This tool is for educational purposes only. Use responsibly and adhere to Facebook's [terms of service](https://www.facebook.com/terms.php). The author is not liable for any misuse or potential account issues arising from this script.
```

You can adjust the repository link and any other details specific to your project. Let me know if you need further customization!
