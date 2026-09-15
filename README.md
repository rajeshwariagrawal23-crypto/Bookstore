# BookStore — Online Bookstore Static Website

A static HTML/CSS/JavaScript bookstore created for the B.Tech 2nd-year Web Technology laboratory experiment.

## Pages / Features
- Home page with three-frame-style layout: top navigation, left category menu, right content area.
- Login page.
- Registration page with JavaScript validation.
- Catalogue page with book covers, author, publisher, Indian prices and Add to Cart buttons.
- Cart page with quantity, amount and total.
- CSS demonstration page covering fonts, background images/repetition and link pseudo-classes.
- Responsive fallback for small screens.

## Run
Open `index.html` in a browser.

For the most reliable experience, serve the folder with a local static server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Repository structure

```text
bookstore/
├── index.html
├── top.html
├── left.html
├── home.html
├── login.html
├── registration.html
├── catalogue.html
├── cart.html
├── css-demo.html
├── css/
│   └── style.css
├── js/
│   ├── validation.js
│   └── cart.js
├── assets/
│   ├── logo.svg
│   └── books/
└── README.md
```

> Note: The original lab sheet describes HTML frames. Since `<frameset>` is obsolete in modern HTML, this implementation uses `<iframe>` elements to preserve the requested three-frame appearance and navigation behavior.
