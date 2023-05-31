# Recipe Search
This project is a recipe search web application built with React, Vite, and React Router. The application allows users to search for recipes by entering ingredients or recipe names into the search bar. It leverages the Font Awesome library for icons and integrates with the Edamam Recipe Search API to fetch recipe data.

## Project Structure
The project structure is as follows:

* index.html: The main HTML file that serves as the entry point for the application. It includes necessary dependencies and the root element where the React application is rendered.
* app.jsx: The main component that serves as the entry point for the React application. It wraps the application with the RouterProvider from React Router.
* main.jsx: The file responsible for rendering the React application using ReactDOM.createRoot. It also sets up the routing configuration using createBrowserRouter.
* routes/Home.jsx: The home page component where users can enter their search query. It includes a form with a search input and handles the submission of the form to fetch recipes.
* routes/RecipesPage.jsx: The recipes page component that displays the search results. It retrieves the recipes from the RecipesContext and renders them using the Recipe component.
* context/RecipesContext.jsx: The context provider component that holds the state of the recipes. It provides the recipes state and a function to update it to its child components.

## Dependencies
This project uses the following dependencies:

* React: JavaScript library for building user interfaces.
* Vite: Build tool for modern web development.
* React Router: Library for routing in React applications.
* Font Awesome: Icon library for adding icons to the application.

## License
This project is licensed under the MIT License. You are free to modify and distribute the code as per the terms of the license. Please note that while some rights are reserved, the project is released under an open-source license that allows for modification and distribution.
