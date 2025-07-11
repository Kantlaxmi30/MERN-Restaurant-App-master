<<<<<<< HEAD
# **MERN stack Restaurant App**

#### Project link: https://swirly-food-delivery-app.vercel.app/

This is **Full stack** Restaurant app using **NextJS**(a production ready framework for ReactJS), **NodeJS**, **ExpressJS**, **MongoDB** and **TailwindCSS**.
I have created my own server using **NodeJS** and **ExpressJS** and **MongoDB**(noSQL database) as databse to store the information.

### Tools used to build this project
- **NextJS** (a production ready framework for **ReactJS**)
- **NodeJS**
- **ExpressJS**
- **MongoDB Atlas**
- **TailwindCSS**
- **Material UI**
- **Cloudinary** (to host images)

### Project Features
#### General features
- **Register/login** functionalites using **JWT** token.
- User information is stored in the **MongoDB** database.
- Navigating different pages using **File based Routing system** provided by **NextJS**
- **Admin Dashboard** to perform **CRUD** functionalities of Food item.
- All the **Images** and **Food details** are dynamically generated by **Admin** and fetched from the database.
- Filtering food based on categories.
- **Add/Remove** food from cart.
- **User** and **Cart** state management using **Redux Toolkit**
- Order details is stored in the databse


#### Customer perspective
-  **Beautiful** and **Modern** UI using modern tools like  **TailwindCSS** and **MaterialUI**
- Customer can navigate to multiple pages.(Authentication is not required) 
- Customer have an option to choose food from food categories
- Customer can **Register** new account and can **Sign in** to the application.
- Customer can **Add** and **Remove** food from cart.(Authentication is not required).
- Customer can order food only if he/she is signed in to the application.

#### Admin perspective
-  **Admin** account has the access to **Admin Dashboard**(protected route from customers)
- Admin can **add new food** item with **image**. The newly added food details is stored in the database with image url, whereas the actual image is hosted in the cloudinary using **Cloudinary API**
- Admin can **update**  and **delete** specific food.
- Admin has the access to  view all **user's** name and email(password is hashed using bcrypt) and delete user account.

#### Upcoming features
- Handling **Payment** using **stripe**
- Advanced **cart** functionalities.
- **Real time** food tracking using **socket.io**



=======
# MERN-Restaurant-App-master
>>>>>>> b414a0f04f93c577f8006b64f3faac5260d07edd
