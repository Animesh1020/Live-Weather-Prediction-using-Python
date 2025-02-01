# U-Mail: A GUI-Based Email Client

## Overview
U-Mail is a feature-rich email client built with Tkinter, Firebase, and OpenAI API. It provides user authentication, email composition, inbox management, and AI-powered message formatting. Designed for ease of use, U-Mail allows users to securely send, receive, and organize emails with a modern, intuitive interface.

## Features
- **User Authentication**: Secure sign-up and login with Firebase.
- **Compose & Send Emails**: Draft and send emails using a simple GUI.
- **Inbox Management**: View received emails in an organized list.
- **AI-Powered Message Formatting**: Utilize OpenAI's API to enhance email content.
- **Password Strength Validation**: Ensures strong passwords during account creation.
- **Rich Text Formatting**: Options for bold, italic, underline, and bullet points.
- **Responsive & Animated UI**: Includes a sliding panel for enhanced user experience.

## Installation
### Prerequisites
Ensure you have Python installed along with the required dependencies.



### Install Dependencies
```sh
pip install -r requirements.txt
```

## Usage
Run the application with:
```sh
python u_mail.py
```
### Steps:
1. Sign up or log in using a valid email and password.
2. Navigate to the compose section to write an email.
3. Use AI assistance to improve message quality.
4. Send and manage emails seamlessly.

## Configuration
To enable Firebase authentication, replace the `firebaseConfig` in the script with your Firebase project credentials. Similarly, for AI-powered features, insert your OpenAI API key.

## Dependencies
- `tkinter`
- `customtkinter`
- `pyrebase`
- `requests`
- `openai`

To install manually:
```sh
pip install tkinter customtkinter pyrebase requests openai
```


## Author
Your Name - [GitHub Profile](https://github.com/yourusername)
