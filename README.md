# Gates Notes Reviews Automation

This Python project automates the extraction of book reviews from the [Gates Notes](https://www.gatesnotes.com/Books#AllReviews) website using Selenium and Pandas. The script retrieves information about book reviews, including title, description, and link, and then generates an HTML or Excel file with the collected data.

## Requirements

- **Python**
- Python Libraries: **pandas**, **selenium**

## Setup

1. **Install Required Libraries**:

   ```bash
   pip install pandas selenium

2. **ChromeDriver**:

Ensure that ChromeDriver is installed and provide the correct path in the script.

3. **Run the Script**:

Execute the script in a Python environment. You can adjust options as needed.

## Usage

The script performs the following actions:

Launches a Chrome browser controlled by Selenium.
Navigates to the Gates Notes website.
Extracts information about book reviews, including title, description, and link.
Creates a Pandas DataFrame with the collected data.
Saves the information to an HTML or Excel file in the application directory.

## Additional Notes

Headless Mode:

The script includes a version with the browser in "headless" mode, which does not open a visible window.

Output Files:

Output files are saved in the application directory with a name that includes the execution date.

Enjoy automating your data retrieval tasks with this project!
