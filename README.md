# End_Less_Scroll_Js
# Hosted_Link:-https://tulasidurga1.github.io/End_Less_Scroll_Js/
# HTML Structure:

- The HTML document is structured with a <head> section for metadata and resource links and a <body> section for the main content.
- The <meta> tags in the <head> section specify character encoding, compatibility settings, and viewport properties.
- The <title> tag sets the title of the webpage displayed in the browser.
- The <link> tag links an external CSS file to style the HTML content.
- The <script> tag links an external JavaScript file for adding interactivity to the webpage.
### CSS Styling:

- CSS (Cascading Style Sheets) is used to define the visual appearance of HTML elements.
- Styles are applied globally to elements with the * selector, setting margins, padding, and box-sizing.
- Specific styles are applied to the <body> element, adjusting font, background color, and margin settings.
- The <h1> heading is styled with text alignment, font size, and letter spacing.
- The .img-container class and its child <img> elements are styled to control margins and image width.
- A media query is used to adjust styles for screens with a maximum width of 600px, making the text smaller and changing margins.
### JavaScript Functionality:

- JavaScript adds dynamic behavior to the webpage.
- Variables and constants are defined to store data and settings.
- Functions are created to perform specific tasks:
- setAttribute(element, attributes): Sets attributes for HTML elements.
- imageLoaded(): Handles image loading events, updating counters.
- displayPhotos(): Displays photos by creating HTML elements and appending them to the image container.
- getPhotos(): Fetches photos from the Unsplash API using asynchronous fetch requests.
- An event listener is added to the window's scroll event to trigger the loading of more photos when the user reaches the bottom of the page.
- API Integration (Unsplash API):

- The code interacts with the Unsplash API to fetch random photos.
- An API key (apikey) is used for authentication.
- The fetch function is used to make an asynchronous HTTP request to the API.
- The fetched data is processed as JSON, and the resulting photos are displayed on the webpage.
## Endless Scroll:

- The webpage implements an endless scroll feature, where more photos are loaded as the user scrolls down.
- The window object's scroll event is used to detect when the user has reached the bottom of the page.
- When the user reaches the bottom and conditions are met (ready), more photos are fetched and displayed.
- In summary, this code creates a responsive webpage that uses HTML for structure, CSS for styling, and JavaScript for interactivity. It fetches and displays random photos from the Unsplash API and implements an endless scroll feature to provide a continuous stream of images as the user scrolls down the page.
