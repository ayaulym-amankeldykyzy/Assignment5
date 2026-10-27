# PAWHAVEN — Frontend Assignments 4 & 5

Team: Miras Kamaladin, Dias Aibekuly, Ayaulym Amankeldykyzy
Group: SE-2504

## Run locally
Open `index.html` in a browser. The JavaScript is separated into `js/main.js`; styles are in `css/style.css`. Bootstrap is loaded from its CDN.

## Assignment 4 features
- Contact and signup form validation with custom English messages.
- FAQ accordion.
- Signup modal with close button, backdrop click, and Escape key.
- Day/Night theme switch saved in localStorage.
- Live date and time.

## Assignment 5 features
- DOM updates and accessible attributes.
- Read More toggle on About page.
- Product category filters using a `switch` statement.
- Load more products using an array of objects, `map`, and `forEach`.
- Interactive star ratings.
- Arrow-key navigation through the main menu.
- Synthesized sound feedback with an On/Off switch.
- Card/content animations with reduced-motion support.

Note: forms are front-end demonstrations only. They do not send messages to a server or create real accounts.

## DOM-generated components
- The FAQ questions and answers are created by `createFAQ()` in `js/main.js`; HTML contains only the mount container `#faq-container`.
- The signup popup and its form are created by `createSignupForm()` in `js/main.js`; the modal markup is not hard-coded into the HTML pages.
- Shop product cards are created by `createProductCard()` and `renderProducts()` from the `productCatalog` array; `shop.html` contains an empty `#product-grid` mount point.
