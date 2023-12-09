# Flask Image Editor

This is a minimal Flask web app that allows users to upload an image, performs basic editing, and displays the edited image along with a short message. The purpose of this project is to showcase the ability to create a web application using Flask and handle file uploads.

## Project Structure

The project structure is kept simple to focus on the essential components.

/flask-image-editor
|-- static
| -- uploads |-- templates | -- index.html
`-- app.py

- **static/uploads**: Folder to store uploaded images.
- **templates/index.html**: HTML template for the web page.
- **app.py**: The main Flask application file.

## Usage
Click on the "Choose File" button to select an image file.
Click the "Upload" button to upload the selected image.
The app will perform basic editing on the image and display it along with a short message.
Dependencies
Flask
Pillow (PIL) for image processing
Install dependencies using:
pip install Flask Pillow

