# MERN AMAZONA

# Lessons

1.  Introduction
2.  Install Tools
3.  Create React App
4.  Create Git Repository

5.  List Products

    1. create products array
    2. add product images
    3. render products
    4. style products

6.  Add routing

    1. npm i react-router-dom
    2. create route for home screen
    3. create router for product screen

7.  Create Node.js Server

    1. run npm init in root folder
    2. update package.json set type: module
    3. add .js to imports
    4. npm install express
    5. create server.js
    6. add start command as node backend/server.js
    7. require express
    8. create route for / return backend/server.js
    9. move products.js from frontend to backend
    10. create route for /api/products
    11. return products
    12. run npm start

8.  Fetch products from backend

    1. set proxy in package.json
    2. npm install axios
    3. use state hook
    4. use effect hook
    5. use reducer hook

9.  Manage State By Reducer Hook

    1. define reducer
    2. update fetch
    3. get state from useReducer

10. Add bootstrap UI Framework

    1. npm install react-bootstrap bootstrap
    2. update App.js

11. Create Product and Rating Component

    1. create Rating component
    2. create product component
    3. use Rating component in product component

12. Create Product Details Screen

    1. fetch product from backend
    2. create 3 columns for image, info and action

13. create loading and message Component

    1. create loading component
    2. use spinner component
    3. create message component
    4. create utils.js to define getError function

14. Implement Add to card

    1. create react context
    2. define reducer
    3. create store provider
    4. implement add to cart button click handler

15. complete add to cart

    1. check exist item in the cart
    2. check count in stock in backend

16. create cart screen

    1. create 2 columns
    2. display items list
    3. create action column

17. complete cart screem

    1. click handler for inc/dec item
    2. click handler for remove item
    3. click handler for checkout

18. create signin screen

    1. create sign in form
    2. add email and password
    3. add signin button

19. connect to MongoDB Database

    1. create atlas mongodb
    2. install local mongodb database
    3. npm install mongodb
    4. connect to mongodb database

20. seed sample data

    1. create product model
    2. create user model
    3. create seed route
    4. use route in server.js
    5. seed sample product

21. seed sample users

    1. create user model
    2. seed sample users
    3. create user routes

22. create signin backend API

    1. create signin api
    2. npm install jsonwebtoken
    3. define generateToken

23. complete signin screen

    1. handle submit action
    2. save token in store and local storage
    3. show user name in handler

24. create shipping screen

    1. create form inputs
    2. handle save shipping address
    3. ad checkout wizard bar

25. create sign up screen

    1. create input forms
    2. handle submit
    3. create backend api

26. implement select payment method screen

    1. create input forms
    2. handle submit

27. create place order screen

    1. show cart items, payment and address
    2. handle placeorder action
    3. create order create api

28. implement place Order Action

    1. handle place order action
    2. create order create api

29. create order screen

    1. create backend api for order/:id
    2. fetch order api in frontend
    3. show order information in 2 columns

30. pay order by paypal

    1. generate paypall client id
    2. create api to return client
    3. install react-paypall-js
    4. use PayPalScriptProvider function
    5. use PayPalScriptReducer in order screen
    6. implement loadPaypalScript function
    7. render paypal button
    8. implement onApprove payment function
    9. create pay api in backend

31. Display Order History

    1. create order screen
    2. create order history
    3. use api in the frontend

32. create profile screen

    1. get user info from context
    2. show user information
    3. create user upi
    4. update user info

33. publish to heroku
    1. create and config node project
    2. serve build folder in frontend folder
    3. create heroku account
    4. connect to github
    5. create mongodb atlas database
    6. set database connection in heroku env virables
    7. commit and push
