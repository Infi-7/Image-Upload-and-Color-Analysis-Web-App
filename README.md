# Image Upload and Color Analysis Web App
This repository hosts a simple yet functional web application built using Flask. The app allows users to upload an image, displays the uploaded image, and analyzes its colors to identify the 10 most commonly used colors.

## Features
- Image Upload: Users can upload any image through the web interface.
- Dynamic Display: Uploaded images are displayed on the same page, centered with an appropriate header.
- Color Analysis: Analyzes the uploaded image and displays the 10 most frequent colors along with their counts.
- Responsive Design: The web interface adapts to different screen sizes for a user-friendly experience.

## Project Structure
```
Image-Upload-and-Color-Analysis-Web-App/
|-- static/
|   |-- styles.css      # CSS file for styling the web app
|   |-- upload/         # Directory where uploaded images are stored
|
|-- templates/
|   |-- index.html      # HTML template for the web app
|
|-- app.py              # Main Flask application script
|-- README.md           # Project README file
|-- requirements.txt    # Python dependencies
```

## Installation
1. Clone the repository:
```
  git clone https://github.com/Infi-7/Image-Upload-and-Color-Analysis-Web-App.git
  cd Image-Upload-and-Color-Analysis-Web-App
```
2. Set up a virtual environment (optional but recommended):
```
  python3 -m venv venv
  source venv/bin/activate  # On Windows: venv\Scripts\activate
```
3. Install dependencies:
```
  pip install -r requirements.txt
```
4. Run the application:
```
  python app.py
```
5. Open your browser and visit http://127.0.0.1:5010.

## Usage
1. Upload an image using the form provided on the home page.
2. The uploaded image will appear below the "Uploaded Image" header, centered in the view.
3. The 10 most common colors in the image will be displayed in a table below the image, showing each color's RGB value and count.

## Dependencies
- Flask
- Werkzeug
- Pillow (PIL)
- NumPy

## Example Output
When an image is uploaded, the page displays:
- The uploaded image, resized to half the browser window dimensions.
- A table listing the 10 most frequent colors, formatted as RGB tuples, along with their counts.

## Screenshots

Upload Form
![image](https://github.com/user-attachments/assets/5bd58b0f-72e9-44d4-9779-5e3bfba41074)

Uploaded Image and Color Analysis
![image](https://github.com/user-attachments/assets/39b31f21-badb-47e1-a100-a16727d4bde0)
![image](https://github.com/user-attachments/assets/97f2e1a1-2f86-4402-8460-ca8663d7e00c)

## Future Enhancements
- Add support for more image formats.
- Enhance the UI for a more modern look.
- Provide additional image analysis features (e.g., brightness, contrast).
- Optimize performance for larger image uploads.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
