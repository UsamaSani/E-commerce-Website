# One Destination

One Destination is an e-commerce website built as a JavaScript assignment. The website offers features like user authentication, product display, search functionality, product categorization, user registration, and a persistent shopping cart, making it a fully functional e-commerce solution.

## Live Demo
Check out the live version of the website [here](https://comforting-cupcake-f85d2f.netlify.app/).

## Features

- **User Authentication**: Sign up and login functionality using a dummy JSON API. Users stay signed in unless they explicitly sign out, thanks to local storage persistence.
  
- **Product Display**: Products are displayed with the ability to filter them by categories.

- **Search Functionality**: Users can search for products by name using the search bar.

- **Add to Cart & Persistent Cart**: Products can be added to the cart. The cart persists even after the page is refreshed or reloaded unless the user signs out or manually removes items.

- **Stock Management**: When a user purchases a product, the product stock decreases. If the stock reaches zero, an "Out of Stock" message is displayed.

- **Purchase Success & Notifications**: When users successfully purchase a product, a message confirms the success of the transaction. If the same product is added to the cart more than once, a message is shown to indicate that the product is already in the cart.

- **Form Validation**: The login and registration forms include validation using regular expressions (regex) to ensure correct input.

- **User Dashboard**: Displays the logged-in user's information with a sign-out button.

## Technologies Used

- **HTML5**: For the structure of the website.
- **CSS3**: For styling and layout.
- **JavaScript (ES6)**: For dynamic functionality and user interactions.
- **Local Storage**: To persist cart items and user sessions.
- **Dummy JSON API**: For user registration and login.
  
## Getting Started

To clone and run this project locally,

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/UsamaSani/E-commerce-Website.git

## Usage

1. **Register/Login**: New users can register an account, while existing users can log in.
2. **Browse Products**: Users can browse products and filter them by category.
3. **Search Products**: Use the search bar to find specific products.
4. **Add to Cart**: Add products to the cart, and view cart items.
5. **Purchase Products**: Complete a purchase, with real-time stock updates.
6. **User Dashboard**: View user details and sign out from the dashboard.

## Folder Structure

```plaintext
├── index.html                # Main HTML file for the e-commerce platform
├── Ecommerece.js             # JavaScript file for handling main e-commerce logic
├── Ecommerece.css            # CSS file for styling the e-commerce pages
├── dashboard.html            # HTML file for the user dashboard
├── dashboard.js              # JavaScript file for managing dashboard functionality
├── dashboard.css             # CSS file for styling the dashboard
├── cart.html                 # HTML file for the shopping cart
├── cart.js                   # JavaScript file for handling cart functionality
├── cart.css                  # CSS file for styling the cart
├── login.html                # HTML file for login and registration pages
├── login.js                  # JavaScript file for managing login and registration functionality
├── login.css                 # CSS file for styling login and registration pages
└── README.md                 # Project documentation

## Contributing

Contributions are welcome! If you'd like to contribute to this project, feel free to submit a pull request. Please ensure your changes are well-documented and tested.

