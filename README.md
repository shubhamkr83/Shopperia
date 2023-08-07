# Foodie-WebApp
<p>Created and deployed a fully functional & fully responsive E-Commerce web application using Reactjs for the front-end & Styled Components for styling. Integrated all the important features such as add to cart, search product, filter the product from the (category, company, price), login/logout, and a contact form that sends the data to the owner's email application. Executed all the API calls using Axios, and authenticate the user with Auth0.</p>

<h3>Live Project:- https://shopperia.netlify.app </h3>

# Features:-
<ol>
    <li>Login and Registration</li>   
    <li>Dynamic Routing</li>
    <li>Add to cart</li>
    <li>Cart Quantity Toggle</li>
    <li>Contact Form</li>
    <li>Filter the products by:-</li> 
        <ol>
          <li>Search Filter</li>
          <li>Change Layout</li>
          <li>Pricing:- </li>
          <ol>
            <li>Highest to Lowest</li>
             <li>Lowest to Highest</li>
          </ol>
          <li>Alphabetically Order:-</li>
          <ol>
            <li>A to Z</li>
            <li>Z to A</li>
          </ol>
             <li>Catagory Filter</li>
        <li>Company Filter</li>
        <li>Color Filter</li>
        <li>Price Range Filter</li>
        <li>Clear Filter</li>
        </ol>
    
</ol>


# Technology Used:-
<ul>
<li>React</li>
<li>React-icons</li>
<li>React-router-dom</li>
<li>Styled-components</li>
<li>Axios</li>
<li>Auth0</li>
</ul>


# Project Screenshot:- </h2>
<h3>Home Page</h3>

![Home Page](https://github.com/shubhamkr83/Shopperia/assets/72254047/ef32cdc5-e7ca-47b4-9da4-a4381940e714)


<h3>Product Page</h3>

![Product Page](https://github.com/shubhamkr83/Shopperia/assets/72254047/a8909e16-db1c-4754-8776-6020556f3c8f)


<h3>Contact Page</h3>

![Contact](https://github.com/shubhamkr83/Shopperia/assets/72254047/fd83c972-6106-40e5-96fc-984672f204da)


<h3>Add to cart Page</h3>

![Add to cart](https://github.com/shubhamkr83/Shopperia/assets/72254047/47b75441-1bbf-4262-a852-2fd869c276d1)


<h3>About Us Page</h3>

![About Us](https://github.com/shubhamkr83/Shopperia/assets/72254047/b9052cc0-5c7c-430d-b61c-bb6336f6d038)



<h2>Folder Structure:-</h2>
<pre>
.
├── app
│   ├── config
|       └── passport.js
│   ├── http
│       ├── controllers
│           ├── admin
│               ├── orderController.js
│               └── statusController.js
│           ├── customers
│               ├── cartController.js
│               └── orderController.js
│           ├── authController.js
│           └── homeController.js
│       └── middlewares 
│           ├── admin.js
│           ├── auth.js
│           └── guest.js
│   └── models
│       ├── menu.js
│       ├── order.js
│       └── user.js 
├── public     
│   ├── css
│       └── app.css
│   ├── img
│   └── js
│       ├── app.js
│       └── app.js.LICENCE.txt
├── resources 
│   ├── js
│       ├── CardWidget.js
│       ├── admin.js
│       ├── apiService.js
│       ├── app.js
│       └── stripe.js
│   ├── scss
│       ├── _varible.scss
│       └── app.scss
│   └── views
│       ├── admin.js
│           └── orders.ejs
│       ├── auth
│           ├── login.ejs
│           └── register.ejs
│       ├── customers
│           ├── cart.ejs
│           ├── orders.ejs
│           └── singleOrder.ejs
│       ├── errors
│           └── 404.ejs
│       ├── home.ejs
│       └── layout.ejs
├── routes
│   ├── api.js
│   └── web.js
├── .gitignore           
├── menus.json
├── mix-manifest.json                  
├── package-lock.json                   
├── package          
├── server.js
├── webpack.mix.js                
├── yarn-error.log                 
├── yarn.lock                 
└── README.md
</pre>

