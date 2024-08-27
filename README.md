
# Caesar Message Encryptor

This is a simple web-based application that allows users to encrypt their messages using a basic character substitution method. The project uses JavaScript to perform the encryption in the browser, providing a quick and easy way to encrypt text for basic security purposes.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [How It Works](#how-it-works)

## Features

- Simple, intuitive interface for encrypting messages.
- Real-time encryption using JavaScript.
- Dark-themed UI for a modern look.
- Lightweight and easy to use.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You will need a web browser (such as Chrome, Firefox, or Edge) to run this application.

### Installation

1. Clone the repository to your local machine:

   \`\`\`bash
   git clone https://github.com/your-username/anonymous-message-encryptor.git
   \`\`\`

2. Navigate to the project directory:

   \`\`\`bash
   cd anonymous-message-encryptor
   \`\`\`

3. Open the `index.html` file in your web browser.

   You can do this by double-clicking the file or by dragging it into an open browser window.

## Usage

1. Enter the message you want to encrypt in the text input field.
2. Click the "Encrypt" button.
3. Your encrypted message will appear in the output box below.

## How It Works

This application uses a simple Caesar cipher-like encryption technique with a custom character ledger. Each character in the input text is replaced with another character that is a fixed number of positions away in a predefined ledger string.

### Encryption Key

The encryption key is set to 5, meaning each character is shifted by 5 positions in the ledger.

### Character Ledger

The ledger used for character substitution is:

\`\`\`
'qwertyuiopasdfghjklzxcvbnm 1234567890'
\`\`\`

Characters not found in this ledger are not encrypted and are added to the output as-is.


Feel free to reach out with any questions or suggestions!
