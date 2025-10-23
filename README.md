# Password Manager

A simple and secure password manager built with Python and Tkinter that helps you generate and store passwords for different websites and services.

## Features

- **Password Generation**: Generate secure passwords with customizable length and character types
- **Password Storage**: Save passwords with associated website and email information
- **Auto-copy**: Generated passwords are automatically copied to clipboard
- **User-friendly Interface**: Clean and intuitive GUI built with Tkinter

## Requirements

- Python 3.x
- tkinter (usually comes with Python)
- pyperclip

## Installation

1. Clone this repository:
```bash
git clone https://github.com/GaurangHalder/password_manager.git
cd password_manager
```

2. Install required dependencies:
```bash
pip install pyperclip
```

## Usage

1. Run the application:
```bash
python main.py
```

2. Fill in the website, email/username, and password fields
3. Click "Generate Password" to create a secure password
4. Click "Add" to save the password to your local storage

## How it Works

- **Password Generation**: Creates passwords using a combination of letters (uppercase and lowercase), numbers, and symbols
- **Data Storage**: Passwords are stored in a local text file (`password_data.txt`) in the format: `website | email | password`
- **Security**: The application stores passwords locally on your machine

## File Structure

```
password_manager/
├── main.py          # Main application file
├── logo.png         # Application logo
├── README.md        # This file
└── .gitignore       # Git ignore file
```

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is open source and available under the MIT License.
