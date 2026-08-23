# Message Encryption and Decryption

A simple client-side web application that demonstrates message encoding and decoding with an emoji-based substitution system. It is built with HTML, CSS, and JavaScript and runs directly in the browser.

## Features

- Enter a message and a password in the browser.
- Encrypt text into an emoji-based encoded message.
- Decrypt an encoded message using the same password.
- Simple password validation with a length between 5 and 25 characters.
- Responsive visual interface with image assets and optional text-to-speech controls.

## Project Structure

- `index.html` - main encryption page.
- `index1.html` - secondary page in the demo.
- `script.js` - encryption, decryption, validation, and interface logic.
- `style.css` - page styling and responsive layout.
- `settings.json` - project configuration.
- Image files - backgrounds, icons, and interface graphics.

## Getting Started

No build step is required. Clone the repository and open `index.html` in a modern web browser:

```bash
git clone https://github.com/udayn32/Message_encryption_decryption-.git
cd Message_encryption_decryption-
```

Then double-click `index.html`, or serve the folder with a local static server:

```bash
python -m http.server 8000
```

Open `http://localhost:8000` in your browser.

## How It Works

The application maps message characters to emoji sequences and uses a password as part of the transformation flow. Decryption requires the corresponding encoded message and password. The exact behavior is implemented in `script.js`.

## Security Notice

This is an educational demonstration, not a replacement for established cryptographic libraries or protocols. Do not use it to protect sensitive or production data.
