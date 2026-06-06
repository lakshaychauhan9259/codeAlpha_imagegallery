Lumière — Image Gallery
Overview
Lumière is a sophisticated and fully responsive image gallery built with HTML, CSS, and JavaScript. Inspired by editorial design and museum-style presentations, it provides an elegant platform for showcasing photography, artwork, portfolios, and curated image collections. The interface combines refined typography, smooth animations, and intuitive navigation to create an immersive viewing experience.
Features


Responsive Gallery Layout


Adaptive grid layout for desktop, tablet, and mobile devices.


Optional list view for alternative browsing.




Category Filtering


Filter images by:


Nature


Architecture


Portrait


Abstract


Travel






Image Tone Filters


Warm


Cool


Mono


Vivid


Fade




Interactive Image Cards


Hover animations


Smooth zoom effects


Category tags and metadata display




Advanced Lightbox Viewer


Full-screen image preview


Image title and description


Previous/Next navigation


Thumbnail navigation strip


Keyboard controls (Arrow Keys, ESC)


Touch swipe support for mobile devices




Accessibility Support


Keyboard navigation


ARIA labels


Focusable gallery elements




Modern Visual Design


Elegant serif and monospace typography


Museum-inspired color palette


Subtle grain texture effects


Smooth transitions and animations




Technologies Used


HTML5


CSS3


Vanilla JavaScript (ES6)


Google Fonts


Cormorant Garamond


DM Mono




Project Structure
imagegallery.html├── HTML Structure├── CSS Styling│   ├── Layout│   ├── Responsive Design│   ├── Animations│   └── Lightbox Styling└── JavaScript Functionality    ├── Gallery Rendering    ├── Category Filtering    ├── Tone Filters    ├── View Switching    ├── Lightbox Navigation    └── Touch & Keyboard Support
Usage


Open imagegallery.html in any modern web browser.


Browse images in grid or list view.


Filter images by category.


Apply visual tone effects.


Click any image to open the lightbox viewer.


Navigate using:


Mouse clicks


Arrow keys


Touch swipe gestures




Customization
Add New Images
Update the images array inside the JavaScript section:
{  id: 19,  title: "New Image",  category: "nature",  src: "image-url.jpg",  desc: "Image description"}
Add New Categories


Add a new filter button in the filter bar.


Assign the category to image objects.


The filtering system will automatically include it.


Modify Theme Colors
Edit the CSS variables under :root:
:root {  --accent: #c4855a;  --parchment: #f5f0e8;  --ink: #1a1714;}
Browser Compatibility


Google Chrome


Mozilla Firefox


Microsoft Edge


Safari


Opera


Use Cases


Photography Portfolios


Art Exhibitions


Creative Agencies


Travel Galleries


Digital Showcases


Personal Collections


License
This project is provided for educational and portfolio purposes. Feel free to customize and extend it according to your requirements.

Lumière delivers a visually rich and modern image gallery experience, combining elegant design principles with powerful browsing and viewing functionality.
