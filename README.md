# My-React-Store

A Store made with React.

* The Store has 2 user states: User and Admin
* The Admin can add New Products, Edit Existing Products and Delete Existing Products
* Every change an Admin makes reflects on the Products in every cart.
* Forms (Sign In, Sign Up, Add Product, Edit Product) don't have their own pages, but instead are opening in a Modal.
* The Website is responsive (Bootstrap is used to some extent, but there is a lot of use of custom CSS). 


Used in this Store:
1. React: useState, useEffect, useContext
2. Formik with Joi Validation
3. MockAPI used to store Products, Users and Carts
4. Pixabay Api is used to add images when creating and editing products to make it easier to find relevant images.
5. React Router is used to some extent and in order to make it possible to develop the store further.
6. Axios is used for requests handling.
7. Local Storage is used for saving the User Id (UUID created at MockAPI)

Enjoy :)
