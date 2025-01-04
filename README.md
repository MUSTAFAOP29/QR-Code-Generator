# QR-Code-Generator
The QR Code Generator with Logo Integration is a Streamlit web app that allows users to create custom QR codes by inputting URLs or text. Users can overlay a logo, adjust error correction, and resize the logo for optimal display. The generated QR code can be downloaded with a custom file name, making it perfect for branding and marketing purposes.

Key Features:

QR Code Generation:

Users can input a URL or text, which is then encoded into a QR code.
The QR code can be customized with options for error correction, box size, and border size to ensure readability.
Logo Integration:

A user-defined logo image is placed in the center of the QR code.
The logo is resized while maintaining its aspect ratio, and it is overlaid on the QR code with transparency support.
Customizable File Name:

Users can provide a custom name for the generated QR code image (with .png extension), making it easier to organize and save files.
Download Option:

After generating the QR code with the logo, users can download the image directly from the app using the Download button.
Higher Error Correction:

The QR code is generated with high error correction (level H), which ensures better resilience to potential damage or distortion, maintaining readability.
Streamlit Interface:

The app uses Streamlit for an intuitive and interactive user interface. With simple input forms and real-time QR code generation, users can quickly customize and download their QR codes.
Technologies Used:

Streamlit: For creating the interactive web app interface.
Pillow (PIL): For image processing, resizing, and overlaying the logo on the QR code.
qrcode: A Python library to generate QR codes from user input.
Use Cases:

Business: Creating custom branded QR codes with logos for promotional materials, business cards, or marketing campaigns.
Education: Creating QR codes for educational materials, resources, or event tickets with an institution’s logo.
Personal: Generating personalized QR codes for personal websites, portfolios, or digital business cards.
This project combines simplicity and customization, offering an easy-to-use tool for generating functional and aesthetically appealing QR codes with logos
