
## React Ecommerce Application

### Description
A full beauty ecommerce website application built from scratch.

<img src="./src/assets/images/oatts.png" alt="oatts home page" />

---

### Technologies

* React
* Redux
* SASS
* Bootstrap
* Firebase

---

### Live Link

The live link is unavailable because the project is still under development

---

### Data Flow

* A user can shop for makeup and beauty products via shop link or showcase links.
* On adding items to cart, the user can either login or create an account via email, google or continue shopping as a guest. This feature is enabled using firebase authentication.
<img src="./src/assets/images/createaccount.png" alt="oatts home page" />

<img src="./src/assets/images/login.png" alt="oatts home page" />

* Multiple users can access the site at thesame time a user can add and update items in the cart. This feature is enabled using firebase cloud firestore to store users information in the database. 
* User authentication, information and cart component state is managed using redux.
* User can proceed to checkout and make payment using a credit or debit card with the implementation of stripe.
<img src="./src/assets/images/shoppage.png" alt="oatts home page" />

---

### In Development

* Payment integration using Stripe

---

### Learning Process

Implementing redux to the project was the biggest challenge I faced and a learning process I took advantage of.
The project helped with understanding how to manage complex state, when to use state, hooks or redux and how to build reusable components like search, buttons and input fields.

---

### Credit
Images
* [Asos Face and Body- MakeUp](https://www.asos.com/women/face-body/makeup/cat/?cid=5020&nlid=ww|face+%2B+body|shop+by+product)
* [Asos Face and Body- Skin Care](https://www.asos.com/women/face-body/skin-care/cat/?cid=4540&nlid=ww|face+%2B+body|shop+by+product)
* [Unsplash- beauty products](https://unsplash.com)

---

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

### `npm test`

### `npm run build`

### `npm run eject`





