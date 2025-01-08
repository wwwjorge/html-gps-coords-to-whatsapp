# Share Your Location

This is a simple and user-friendly web application that allows users to share their current location (latitude and longitude) via WhatsApp or copy it to the clipboard. It is particularly useful for people who are not familiar with sharing coordinates manually.
## Features
- **Get Current Location**: The app uses the browser's Geolocation API to fetch the user's current coordinates (latitude and longitude).
    **Copy Coordinates**: Users can easily copy the coordinates to their clipboard with a single click.
    **Share on WhatsApp**: The app generates a WhatsApp link with the coordinates, allowing users to share their location instantly.
    **Customizable**: You can pass a phone number and a custom message via URL parameters to personalize the sharing experience.
    ## How It Works
1. **Access the App**: Open the HTML file in any modern web browser.
    **Get Location**: Click the "Obter Localização" (Get Location) button to fetch your current coordinates.
    **Copy or Share**:
    Use the "Copiar Coordenadas" (Copy Coordinates) button to copy the coordinates to your clipboard.
    Use the "Compartilhar no WhatsApp" (Share on WhatsApp) button to send the coordinates directly via WhatsApp.
    
## URL Parameters

You can customize the app by passing the following parameters in the URL:
- **`phone`**: The phone number to which the coordinates will be sent via WhatsApp (default: `+555185435919`).
    **`message`**: A custom message to include with the coordinates (default: `"Olá! Minhas coordenadas são:"`).
    
Example URL:
Copy
https://yourdomain.com/share-location.html?phone=+123456789&message=Hello! My coordinates are:
## Code Overview

### HTML Structure
- The app has a clean and responsive design with a centered container.
    It includes buttons for getting the location, copying coordinates, and sharing on WhatsApp.
    
### CSS Styling

- Modern and minimalistic design with hover effects for buttons.
    Responsive layout that works on both desktop and mobile devices.
    
### JavaScript Functionality

- **Geolocation API**: Fetches the user's current coordinates.
    **Clipboard API**: Copies the coordinates to the clipboard.
    **WhatsApp Integration**: Generates a WhatsApp link with the coordinates and a custom message.
    
### Key Functions

- `navigator.geolocation.getCurrentPosition`: Fetches the user's location.
    `copyToClipboard`: Copies the coordinates to the clipboard.
    `shareOnWhatsApp`: Opens WhatsApp with a pre-filled message containing the coordinates.
    
## License

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it as you see fit.

MIT License

Copyright (c) 2025 wwwjorge

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---
## How to Use

1. Clone or download this repository.
    Open the `index.html` file in your browser.
    Follow the on-screen instructions to get, copy, or share your location.

---

## Author

- Jorge Henrique Packeiser
    GitHub: [wwwjorge](https://github.com/wwwjorge)
