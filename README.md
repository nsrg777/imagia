# IMAGIA Image Gallery

## Overview

IMAGIA is a modern, responsive image gallery web application built using HTML, CSS, and JavaScript. It features a dark red and black theme and provides users with the ability to upload, view, filter, and download images directly in the browser.

The application is designed with a focus on clean UI, smooth interactions, and a professional photography-style layout.

---

## Features

### Image Gallery

* Responsive grid layout for displaying images
* Hover overlays with image title and category
* Smooth animations and transitions

### Lightbox Viewer

* Fullscreen image preview
* Next and previous navigation
* Keyboard support (arrow keys and escape)

### Image Upload

* Drag and drop upload support
* File picker option
* Upload progress indicator
* Stores uploaded images in localStorage
* Automatically adds uploaded images to the gallery

### Download Feature

* Download button available for each image
* Supports downloading from both gallery and lightbox view
* Preserves image quality and naming

### Filters

* Category-based filtering (Nature, Travel, Portrait, Abstract, Personal)
* Active filter state indicator

### Visual Effects

* Apply filters such as:

  * Grayscale
  * Sepia
  * Blur
  * Invert
  * Contrast

### User Experience

* Smooth animations
* Responsive design for all screen sizes
* Empty state handling when no images are available

---

## Project Structure

project-folder/
│
├── index.html
├── styles.css
└── script.js

---

## Technologies Used

* HTML5
* CSS3 (Flexbox, Grid, animations)
* Vanilla JavaScript (ES6)
* LocalStorage API

---

## How to Run

1. Download or clone the project.
2. Ensure all three files are in the same folder:

   * index.html
   * styles.css
   * script.js
3. Open index.html in your browser.

No additional setup or dependencies are required.

---

## Usage

* Click or drag images into the upload area to add them to the gallery.
* Use filter buttons to sort images by category.
* Click on any image to open it in the lightbox.
* Use arrow keys or navigation buttons to browse images.
* Click the download button to save images locally.

---

## Notes

* Uploaded images are stored in the browser using localStorage.
* Clearing browser data will remove uploaded images.
* Maximum file size for uploads is typically limited (e.g., 10MB per image).

---

## Future Improvements

* Backend integration for permanent image storage
* User authentication
* Image tagging and search functionality
* Cloud storage support
* Performance optimization for large galleries

---

## License

This project is open-source and free to use for educational and personal purposes.
