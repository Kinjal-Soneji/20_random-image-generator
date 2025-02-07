# Random Image Generator

A simple web application that displays random images from Lorem Picsum and allows users to load more images on demand.

## Features

- Displays random images in a responsive grid layout
- "Load Next 5 Images" button to fetch additional random images
- Seamless integration with Lorem Picsum API
- Lightweight and easy to use
- Responsive design that works across different screen sizes

## Technologies Used

- HTML5
- JavaScript (Vanilla)
- [Lorem Picsum](https://picsum.photos/) for random images

## Getting Started

### Prerequisites

- A modern web browser
- A local web server (optional)

### Installation

1. Clone this repository or download the files:
```bash
git clone https://github.com/yourusername/random-image-generator.git
```

2. Navigate to the project directory:
```bash
cd random-image-generator
```

3. Open `index.html` in your web browser or serve the files using a local web server.

## Project Structure

```
random-image-generator/
│
├── index.html          # Main HTML file
├── style.css          # Stylesheet
├── main.js            # JavaScript functionality
└── README.md          # Project documentation
```

## How It Works

1. The application initially loads 5 random images from Lorem Picsum
2. Each image is 300px wide with a random height
3. Clicking the "Load Next 5 Images" button fetches 5 more unique random images
4. Images are appended to the existing gallery

## Usage

Simply open the application in a web browser. Click the "Load Next 5 Images" button whenever you want to see more random images.

## Customization

You can modify the following aspects of the application:

- Image size: Change the number in the URL within `main.js` (`https://picsum.photos/300`)
- Number of images loaded: Modify the loop count in the `fetchRandomImages` function
- Layout: Adjust the CSS in `style.css` to change the grid layout or image presentation

## API Reference

This project uses the Lorem Picsum API. The image URL format is:
```
https://picsum.photos/300?random=${number}
```
where `${number}` is a unique identifier to ensure different images are loaded.



