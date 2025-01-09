# **Food Recipe Sharing Platform**

This repository contains a **Next.js** project that allows users to share their favorite food recipes. The project explores the features and capabilities of the **Next.js** framework, leveraging **SQLite** as the database for storing recipe information.

---

## **Features**

### **Core Functionality**
- **Recipe Sharing**  
  Users can submit and share their favorite food recipes with others.  

- **Dynamic Routing**  
  Each recipe has a dedicated page generated dynamically using Next.js' powerful routing features.  

- **Server-Side Rendering (SSR)**  
  Recipes are rendered on the server for better SEO and performance.  

- **Static Site Generation (SSG)**  
  Frequently accessed pages (e.g., popular recipes) can be statically generated for faster loading.  

- **API Routes**  
  Built-in API routes are used to handle backend logic, such as adding, retrieving, and updating recipes.  

---

## **Tech Stack**

### **Frontend**
- **Next.js**  
  - Dynamic routing, SSR, and SSG for an optimal user experience.  

### **Database**
- **SQLite**  
  - A lightweight relational database for storing user-submitted recipes.  

### **Styling**
- **CSS Modules**  
  - Scoped and modular styling to keep the design clean and maintainable.  

---

## **Installation**

### **Step 1: Clone the Repository**

Step 2: Install Dependencies

Install all the required dependencies

Step 3: Run the Development Server

Start the Next.js development server:

npm run dev

The app will be accessible at http://localhost:3000.


---

Usage Guide

Home Page

View a list of all shared recipes.

Click on any recipe to view its details.


Share a Recipe

1. Navigate to the "Share Your Recipe" page.


2. Fill out the form with the recipe title, ingredients, and instructions.


3. Submit the recipe to share it with others.



Recipe Detail Page

View the full recipe, including ingredients, instructions, and the contributor's name.



---

Key Features in Detail

Dynamic Routing

Recipes are assigned unique URLs, e.g., /recipes/1, /recipes/2.

Pages are dynamically created based on the database entries.


API Routes

Custom API endpoints are used for interacting with the SQLite database:

GET /api/recipes - Fetch all recipes.

POST /api/recipes - Add a new recipe.

GET /api/recipes/:id - Fetch a single recipe by ID.

---

Future Enhancements

User Accounts
Add user authentication for personalized recipe sharing and management.

Search and Filters
Allow users to search recipes by title, ingredient, or category.

Likes and Comments
Add a feature for users to like and comment on recipes.



---

Contributing

We welcome contributions to improve this project!

1. Fork the repository.


2. Create a new branch for your feature or bugfix.


3. Submit a pull request with detailed information about your changes.




---

License

This project is licensed under the MIT License. See the LICENSE file for details.


---

Acknowledgments

Special thanks to:

The Next.js community for their detailed documentation and examples.

Open-source contributors for SQLite and related tools.




