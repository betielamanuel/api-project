# Image Finder App

## Overview

The Image Finder App is a simple web application that allows users to search for images using the Unsplash API. The app features a search form where users can input keywords to find relevant images. It dynamically displays the results and provides links to the full-size images on Unsplash.

## Features

- **Image Search**: Users can search for images based on keywords.
- **Dynamic Image Display**: Displays search results dynamically as images are fetched from Unsplash.
- **Pagination**: Load more images by clicking the "Show more" button.
- **Responsive Design**: The app is designed to be responsive and user-friendly.

## Technologies Used

- **HTML**: Structure of the web pages.
- **CSS**: Styling of the web pages.
- **JavaScript**: For handling form submission, making API requests, and dynamically updating the DOM.
- **Unsplash API**: Provides the images and metadata.

## Setup

1. **Clone the Repository**:
    ```bash
    git clone <repository-url>
    ```

2. **Navigate to the Project Directory**:
    ```bash
    cd image-finder-app
    ```

3. **Install Dependencies**:
    No additional dependencies are needed for this project. Ensure you have an active internet connection to fetch images from the Unsplash API.

4. **Run the Application**:
    Open `index.html` in a web browser to view and interact with the application.

## File Structure

- **index.html**: Main HTML file containing the structure of the app, including the search form and image results.
- **assets/css/style.css**: Custom CSS file for styling the application.
- **assets/js/app.js**: JavaScript file handling the search functionality and image display logic.
- **README.md**: This file.

## JavaScript Functionality

- **Event Listeners**: Handles form submission and button clicks to fetch and display images.
- **Search Function**: Fetches images from the Unsplash API based on user input and displays them on the page.
- **Pagination**: Manages loading more images by updating the `page` variable and showing the "Show more" button.

## Usage

1. **Search for Images**: Enter keywords into the search input field and click "Search" or press Enter to find images.
2. **View Image Details**: Click on the image or the associated link to view the full-size image on Unsplash.
3. **Load More Images**: Click the "Show more" button to load additional images.

## Known Issues

- **API Rate Limiting**: The Unsplash API has rate limits; excessive requests may result in errors.
- **Browser Compatibility**: Ensure you use modern browsers for the best experience.

## Future Improvements

- **React Integration**: Refactor the app to use React for better state management and component-based architecture.
- **Enhanced Features**: Add user authentication, advanced search filters, and image categorization.

For any questions or feedback, please contact betiel.ab@gmail.com
