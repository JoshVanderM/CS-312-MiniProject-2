# Web Application Mini-Project: CS-312-MiniProject-2

## Objective
The objective of this mini-project is to develop a web application using **Node.js**, **Express.js**, **Axios**, and a public API to retrieve and display data dynamically. The project focuses on **API integration**, **client-server communication**, and **user-friendly data presentation** using **EJS** templates.

## Instructions

### Step 1: API Choice
1. Browse the provided list of public APIs and choose one that fits your project idea.
2. Ensure the API is **CORS-enabled** and does not require authentication.
3. Understand the API structure and the type of data you can retrieve for your web application.

#### Example APIs:
- Use the **Joke API** to create a website that gives the user a joke based on their name.
- Use the **OpenWeatherMap API** to build a website that tells a user if it will rain tomorrow in their location of choice.
- Use the **Blockchain API** to check the price of a cryptocurrency for the user.
- Use the **CocktailDB API** to make a website that gives the user a random cocktail recipe with images of the cocktail.
- Use the **Open UV API** to make a website based on your home location that tells you if you need to apply sunscreen today.

### Step 2: Project Planning
- Gather content and design ideas, and (optional) create wireframes and mockups.
- Plan out how the application will work, including which routes might be necessary and which pages need to be made.
- Research your chosen API - identifying key features and the type of data it returns.
- Plan how the API data will be used in your web application.
- Identify potential user interactions, such as input forms or search filters, and how they’ll be implemented to fetch and display data from the API.

### Step 3: Setup
- Set up the project repository, initialize the Node.js application, and install necessary dependencies (**Express.js**, **EJS**, **Axios**, etc.).
- Create the application structure, including routes, views, and static files.
- Set up the **Express.js** server and configure routes for handling API requests.

### Step 4: API Integration
- Create a page with necessary input forms to collect the information from the user that is needed for the API (e.g., for **OpenWeatherMap API**, you may want the user to input their location).
- Define a route in your entry file (app.js/index.js) that leads the user to the page with the input forms.
- When the user submits the form, the external API should be invoked to fetch relevant data (hint: **Axios** can help!). Ensure the correct HTTP method and data format are used.
- Pass the API response to **EJS** for server-side rendering.
- Ensure proper error handling: display fetched data on success or show an error message on failure and prompt the user to try again.

### Step 5: Styling
- Style the application using **CSS** or a CSS framework like **Bootstrap**.
- Make sure the layout is responsive and looks good on both desktop and mobile devices.
- Style elements such as post lists, forms, buttons, and the overall layout.

### Step 6: Testing
- Test the application on different devices and browsers to ensure that the functionality works correctly.
