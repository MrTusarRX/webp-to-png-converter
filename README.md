# WEBP to PNG Converter

A simple, fast, and interactive web-based tool that allows users to easily convert WEBP images to PNG format directly in their browser without any server-side processing. The tool offers an engaging user experience with a cool neon glow interface.

## Features

- **Instant Conversion**: Upload a WEBP image and instantly convert it to PNG.
- **No Installation Required**: Simply open the `index.html` file in your browser to start converting.
- **Responsive Design**: The layout is optimized for both desktop and mobile devices.
- **Interactive UI**: Neon glowing effects, animations, and a modern interface to make the user experience exciting.
- **Client-Side Processing**: All processing is done directly in the browser using HTML5, CSS3, and JavaScript.

## Demo

You can try the tool directly by visiting the live demo [here](https://example.com) (replace with your actual live demo link).

## Screenshot

![WEBP to PNG Converter Screenshot](assets/screenshot.png)
*(Replace with an actual screenshot of your project)*

## How to Use

1. **Upload a WEBP Image**: Click the "Choose File" button to select a WEBP image from your device.
2. **Wait for Conversion**: Once the image is uploaded, it will automatically be converted to PNG format.
3. **Download the PNG**: After the conversion process is completed, a "Download PNG" button will appear. Click it to download your PNG file.

## Installation

There is no installation required. You can either clone the repository or simply open the `index.html` file in your browser to use the tool.

### To Clone the Repository:

Clone the repository to your local machine with the following commands:

```bash
git clone https://github.com/MrTusarRX/webp-to-png-converter.git
cd webp-to-png-converter
Then, open the index.html file in your web browser to start using the tool. Alternatively, you can also download the index.html file directly from this repository and open it in your browser.
Technologies Used

    HTML5: Provides the structure and layout of the page.
    CSS3: Used for styling the page, including animations, hover effects, and responsive layout.
    JavaScript: Handles the conversion process, loading the image, and generating the PNG download link.
    Canvas API: Renders the uploaded WEBP image and converts it to PNG format.
    FileReader API: Reads the uploaded image file directly in the browser without needing server-side processing.

How It Works

    Upload a WEBP Image: The user uploads a WEBP image using the file input field.
    Image Processing: The image is drawn onto a hidden HTML canvas element using JavaScript.
    Conversion to PNG: The canvas element is used to generate a PNG version of the image, which is then made available for download.
    Download the PNG: The converted PNG file is made available via a dynamic download link, which allows the user to save the file to their device.

Contributing

We welcome contributions to improve this tool! If you'd like to add new features, fix bugs, or improve the UI, feel free to fork the repository and create a pull request.
Steps to Contribute:

    Fork the repository to your own GitHub account.
    Create a new branch for your changes (git checkout -b feature-name).
    Make your changes and commit them (git commit -am 'Add new feature').
    Push the branch to your fork (git push origin feature-name).
    Create a pull request in the original repository.

License

This project is open-source and available under the MIT License.
Acknowledgments

    Thanks to MDN Web Docs for great documentation on web technologies.
    Inspired by simple web tools for everyday image conversions.

Feel free to explore, use, and improve this tool! If you run into any issues, please open an issue in the GitHub repository.

This `README.md` structure includes all the necessary sections: Features, Demo, How to Use, Installation, Technologies Used, and Contributing. You can replace the placeholders with actual details (like your demo link and screenshot).
