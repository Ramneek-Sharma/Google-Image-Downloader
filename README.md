# Google-Image-Downloader
## Overview
Google Image Downloader is a web application that allows users to search for and download images from Google based on a given keyword. The application uses Google's Custom Search API to fetch image URLs and downloads them. The downloaded images are then zipped and sent to the user's email address.

##Technologies Used
* Frontend: HTML, CSS (Tailwind CSS), JavaScript
* Backend: Python, Flask
* APIs: Google Custom Search API
* Additional Libraries: requests, google-api-python-client, zipfile

## Interface
<img width="376" alt="Screenshot 2024-10-14 at 6 49 15 AM" src="https://github.com/user-attachments/assets/ec7691fa-2a3a-4e88-be18-196d64242f04">

##File Structure
* app.py: Main Flask application file
* templates/index.html: HTML template for the web interface
* images/: Directory where downloaded images are temporarily stored
* downloaded_images.zip: Zip file containing downloaded images

##Running the Application

* Start the Flask development server:


python app.py

* Open a web browser and navigate to http://localhost:___

## Result
<img width="375" alt="Screenshot 2024-10-14 at 6 49 37 AM" src="https://github.com/user-attachments/assets/ac4851dd-1907-4c1e-912c-3f3636e50640">
<img width="602" alt="Screenshot 2024-10-14 at 6 51 03 AM" src="https://github.com/user-attachments/assets/8055cbc6-dd34-440e-9e88-ff95a43e72a1">

