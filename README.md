# WhatsApp Bulk Messenger Documentation

## Introduction
WhatsApp Bulk Messenger is a Python script that uses the Selenium library to send bulk messages to multiple WhatsApp contacts from a text file. This documentation provides an overview of the script's functionalities and how to use it.

## Prerequisites
Before using WhatsApp Bulk Messenger, make sure you have the following:
- Python installed on your system.
- Microsoft Edge WebDriver installed and its path correctly specified in the script.
- A `message.txt` file containing the message to be sent.
- A `numbers.txt` file containing the phone numbers of the recipients.

## Installation
1. Clone the repository:
git clone https://github.com/your-username/WhatsApp-Bulk-Messenger.git


2. Install the required dependencies:
pip install selenium


3. Set the path to the Microsoft Edge WebDriver executable in the script.

## Usage
1. Open the terminal or command prompt and navigate to the cloned repository.

2. Execute the script:

3. The script will open the Microsoft Edge browser, prompting you to sign in to WhatsApp Web. Sign in to your WhatsApp account.

4. Once signed in, press ENTER in the terminal to start sending messages.

## Input Files
1. `message.txt`: This file should contain the message you want to send. The script will read the message from this file.

2. `numbers.txt`: This file should contain a list of phone numbers, one number per line, to which you want to send the message.

## Output
The script will display the status of each message sent, including success or any errors encountered.

## Notes
- If the script fails to send a message to a contact, it will retry up to three times before moving on to the next contact.
- Ensure both your phone and computer are connected to the internet during the process.
- Dismiss any alerts that may appear on the WhatsApp Web interface.

## Credits
This script was developed by Aayushman Ojha. You can find the original source code on GitHub at: [WhatsApp Bulk Messenger](https://github.com/your-username/WhatsApp-Bulk-Messenger)

## License
This project is licensed under the [MIT License](LICENSE).

