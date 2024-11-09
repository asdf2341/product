# 📄 Product Landing Page

This **Product Landing Page** is a modern, responsive webpage that showcases a product with an engaging design. The page includes a navigation bar, logo, embedded product video, and a contact form. The project is built using HTML, CSS, and includes features like responsive design using media queries and flexible layouts with CSS Flexbox.

## 📝 Table of Contents

- [Live Demo](#live-demo)
- [Features](#features)
- [User Stories](#user-stories)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)

## 🌐 Live Demo

Visit the live demo: [Product Landing Page](https://your-live-demo-link.com)

## ✨ Features

- **Sticky Navigation Bar**: The navigation bar remains at the top of the viewport as you scroll.
- **Responsive Design**: The page is fully responsive and looks great on both desktop and mobile devices.
- **Embedded Video**: The page includes an embedded product video to showcase the product in action.
- **Email Subscription Form**: Users can enter their email to subscribe for updates.
- **Modern Layout**: Utilizes CSS Flexbox for a clean and flexible design.

## ✅ User Stories

The project fulfills the following user stories:

1. The page includes a header element with an `id` of `header`.
2. There is an image inside the header element with an `id` of `header-img` (a logo image).
3. Inside the `#header` element, there is a navigation bar (`nav` element) with an `id` of `nav-bar`.
4. The navigation bar contains at least three clickable elements with the class `nav-link`.
5. Clicking on a `.nav-link` takes the user to the corresponding section of the landing page.
6. The page includes an embedded video with an `id` of `video`.
7. There is a form element with an `id` of `form` for email subscriptions.
8. The form contains an input field with an `id` of `email` and placeholder text.
9. The email input field uses HTML5 validation to check for a valid email address.
10. The form includes a submit button with an `id` of `submit`.
11. Submitting the form sends the email to a mock URL: `https://www.freecodecamp.com/email-submit`.
12. The navigation bar is always visible at the top of the page.
13. The page includes at least one media query for responsiveness.
14. The design uses CSS Flexbox for layout.

## 💻 Technologies Used

- **HTML5**: For structuring the webpage.
- **CSS3**: For styling, including Flexbox for layout and media queries for responsiveness.

## 🚀 Getting Started

To run the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/product-landing-page.git
   ```
2. Navigate to the project directory:
   ```bash
   cd product-landing-page
   ```
3. Open the `index.html` file in your browser.

## 📚 Usage

1. Explore the product landing page by scrolling and interacting with the elements.
2. Click the navigation links to jump to specific sections of the page.
3. Watch the embedded product video.
4. Enter your email in the subscription form and click **Submit** to send your email.

## 📁 Project Structure

```
product-landing-page/
├── index.html       # Main HTML file
├── styles.css       # CSS styles
├── img/             # Images folder
│   └── logo.png     # Logo image
└── README.md        # Project documentation
```

### `index.html`

Contains the structure of the landing page, including header, navigation, video, and form sections.

### `styles.css`

Defines the styles for the page, including Flexbox layout and media queries for responsive design.

### `img/`

Contains all images used on the page, including the logo.

## 🎨 CSS Features

- **Flexbox Layout**: Used for flexible and responsive design.
- **Sticky Navbar**: The navigation bar remains fixed at the top of the viewport.
- **Media Queries**: Adjusts the layout for different screen sizes.

### Example CSS:

```css
/* Sticky navigation bar */
#nav-bar {
  position: sticky;
  top: 0;
  background-color: #333;
  color: #fff;
}

/* Flexbox layout for main sections */
.features {
  display: flex;
  justify-content: space-around;
}

/* Responsive design */
@media (max-width: 600px) {
  .features {
    flex-direction: column;
    align-items: center;
  }
}
```

