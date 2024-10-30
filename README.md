# MyPass - Password Manager 🔒

![MyPass Logo](logo.png)

## Project Overview

MyPass is a secure, intuitive, and easy-to-use password manager built with Python and Tkinter. It provides functionalities to generate strong passwords, save them securely, and retrieve them easily when needed. This application ensures your credentials are stored locally and safely, making it an ideal choice for managing multiple passwords without relying on cloud storage.

---

## Features

- **Password Generation**: Automatically generates strong, random passwords with a mix of letters, numbers, and symbols.
- **Save and Retrieve**: Securely saves your credentials (website, email, password) in a JSON file for easy access.
- **Search Function**: Quickly retrieve saved passwords by entering the website name.
- **Clipboard Copying**: Instantly copies the generated password to your clipboard for immediate use.

---

## Project Structure

- **`main.py`**: Core Python script containing the application's functionality and UI setup.
- **`project.toml`**: Configuration file used by Poetry to manage dependencies.
- **`poetry.lock`**: Lock file for reproducible dependency management.
- **`logo.png`**: Logo displayed in the app’s GUI.

---

## Requirements

- **Python**: Version 3.8 or higher
- **Packages**: Listed in `project.toml` and managed by Poetry

To install the dependencies manually, use:

```bash
pip install pyperclip
