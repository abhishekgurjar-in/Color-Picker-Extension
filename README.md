# Color Picker Extension

### Introduction
Color is key in web design and development, and having an efficient way to select and manage colors can streamline your workflow. In this post, we'll explore how to create a Color Picker extension that lets you effortlessly pick colors from your screen, view a history of picked colors, and manage them easily. Using the EyeDropper API and modern web technologies, this extension offers a practical tool for designers and developers alike.
### Project Overview
The Color Picker extension provides a user-friendly interface to:
- Pick colors from the screen using the EyeDropper API.
- View a history of picked colors.
- Copy color codes to the clipboard.
- Clear all picked colors.

### Features
- **Color Picking**: Use the EyeDropper API to select colors from any part of your screen.
- **Color History**: Maintain a list of picked colors with easy access.
- **Clipboard Copy**: Quickly copy color codes to the clipboard.
- **Clear All**: Remove all colors from the history with a single click.

### Technologies Used
- **HTML**: Markup for the extension’s popup.
- **CSS**: Styling for the popup and its elements.
- **JavaScript**: Handles color picking, displaying color history, and managing clipboard operations.
- **EyeDropper API**: Allows picking colors from the screen.
- **localStorage**: Stores picked colors across sessions.

### Project Structure
1. **HTML (`index.html`)**: Contains the structure for the color picker interface.
2. **CSS (`style.css`)**: Styles the popup and its elements.
3. **JavaScript (`script.js`)**: Manages functionality such as picking colors, displaying them, and interacting with local storage.
4. **Manifest (`manifest.json`)**: Defines the extension’s metadata and configuration.

### Installation
To test the extension locally:
1. Save the files into a directory.
2. Open Chrome and navigate to `chrome://extensions/`.
3. Enable "Developer mode" (toggle in the top right).
4. Click "Load unpacked" and select your project directory.

### Usage
1. Click the “Pick Color” button in the extension popup to activate the color picker.
2. Select a color from anywhere on the screen.
3. View the picked colors in the popup and click on any color to copy its code to the clipboard.
4. Click "Clear All" to remove all colors from the history.



### Live Demo
You can test the extension locally by following the installation instructions above. Once installed, the extension’s popup will allow you to pick colors and manage your color history.

### Conclusion
This Color Picker extension demonstrates how to integrate the EyeDropper API into a browser extension, providing users with a handy tool for color selection and management. Whether you’re a designer or just someone who enjoys working with colors, this extension can enhance your workflow.

### Credits
- **EyeDropper API**: Provides the functionality to pick colors from the screen.
- **Poppins Font**: Used for styling the text in the popup.

### Author
**Abhishek Gurjar** is a dedicated web developer passionate about creating practical and functional web applications. Check out more of his projects on [GitHub](https://github.com/abhishekgurjarin).
