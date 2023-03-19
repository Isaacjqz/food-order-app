FOOD ORDERING APP

This is a food ordering app built with React. Users can browse and order meals from a selection of dishes, and view their cart at any time.

Components

Header

The header component contains the title of the app and a cart button, which displays the current number of items in the user's cart. Clicking on the cart button opens the cart modal.

Meals

The meals component displays a list of available meals. Users can click on individual meals to view more details about them and add them to their cart.

Cart

The cart component displays a list of items currently in the user's cart, along with the total cost. Users can adjust the quantity of each item or remove them entirely from the cart. The cart can be closed by clicking on the close button or clicking outside of the modal.

CartProvider

The CartProvider component serves as the store for the cart state. It uses the useReducer hook to manage cart state updates and provides the cart state and dispatch functions to its child components through the CartContext.

How to Run

To run the app, clone the repository and install the dependencies by running:

npm install

Then start the app with: 

npm start

The app will be available at http://localhost:3000/.

Dependencies

React
ReactDOM
React-dom
React-icons

Future Improvements

Implement user authentication and account management
Add payment processing functionality
Implement responsive design for mobile devices.