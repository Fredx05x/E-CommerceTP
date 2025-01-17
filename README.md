## About the project

A java web app with front and backend, a e-commerce site which allows user to sign up, sign in, view products by catalog, by category, add/delete/modify products in the cart, generate order and pay.
For pedagogical propose, the pay process is simulated by sending a mail to the user's email address.

##### Tech Stack
Java, Java web, JSP, JSTL, MySQL, JavaScript, JQuery, Responsive layout, and JDBC.

## Installation

- Open mysql workbench, create a database named `e_commercetp` with help of the `e_commercetp.sql` file in the `DB` folder of the project
- Open the project with [Netbeans](https://netbeans.org/)
- Build the project and run it in the browser of your preference
- Configure your database connection: you can change the default database connection username and password to your owns' by change the `login` or `pwd` variables in the `src/service/ConnectionDB` file

## Bonus points

- Mobile first and responsive design of 3 layers (Mobile, Tablets, and Desktop)
- JavaScript for userform validator (with Regex)
- jQuery framwork and animation and Addons (for styling the messagebox)
- Flexbox on CSS
- Change cart quantity in input box
- Backend prepared for adding admin functions

## How the app works

You can view the products and add products to the cart without sign up or sign in, however if you want to test making an order or checkout, you should signin with your registered email address and password.
