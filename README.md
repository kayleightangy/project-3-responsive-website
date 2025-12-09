# NYC Landmarks Virtual Tour

This is a static website showcasing various landmarks across New York City's five boroughs. The site features responsive design techniques including a dynamic image grid, responsive featured image using the `<picture>` element, and an embedded responsive video.

## Features

1. **Responsive Featured Image** - Uses the `<picture>` element to display different versions of the Wonder Wheel image based on screen size
2. **Image Grid Gallery** - Displays NYC landmarks in a responsive grid layout using CSS Grid
3. **Responsive Video** - Embedded YouTube video that maintains aspect ratio across all devices
4. **Proper Attribution** - All images include proper photographer credits

## Implementation Details

### HTML Elements Used
- `<picture>` element with `<source>` for responsive featured image
- `<figure>` and `<figcaption>` for image gallery with credits
- Responsive `<iframe>` for video embedding

### CSS Techniques
- CSS Grid for responsive image gallery
- Media queries for responsive design
- Aspect ratio control for images and videos
- Hover effects and transitions for interactive elements

## Project Structure
```
project-2/
├── index.html          # Main HTML file
├── style.css           # Stylesheet with responsive design
├── images/             # Directory containing all images
│   ├── pexels-kelsey-caroline-774981359-19122990.jpg              # Full size Wonder Wheel image
│   └── square/         # Directory containing square cropped images
│       ├── pexels-kelsey-caroline-774981359-19122990_sq_square.jpg
│       ├── pexels-loquellano-12404963_sq_square.jpg
│       ├── pexels-malcolmhill-12360516_sq_square.jpg
│       ├── pexels-mora-versio-2150673251-34091093_sq_square.jpg
│       ├── pexels-tracehudson-2424391_sq_square.jpg
│       └── praswin-prakashan-YOCN1a1m_dg-unsplash_sq_square.jpg
└── README.md           # This file
```

## Image Credits

All images used in this project are from free stock photo sites with proper attribution:

1. Wonder Wheel - Photo by Kelsey Caroline from Pexels
2. Statue of Liberty - Photo by Mora Versio from Pexels
3. Empire State Building - Photo by Trace Hudson from Pexels
4. Staten Island Ferry - Photo by Praswin Prakashan from Unsplash
5. Yankee Stadium - Photo by Malcolm Hill from Pexels
6. Roosevelt Island Tramway - Photo by Raphael Loquellano from Pexels

## Deployment

This site is deployed using GitHub Pages:

- Repository: https://github.com/kayleightangy/project-3-responsive-website
- Live Site: https://kayleightangy.github.io/project-3-responsive-website
