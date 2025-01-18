# Food-Recipie-Sharing-and-Rating-Platform

Overview
The Food Recipe Sharing and Rating System is a web-based application that allows users to share their favorite recipes, browse recipes shared by others, and rate them. This system aims to create a community of food enthusiasts who can exchange culinary ideas and experiences.


User Registration & Authentication: Users can create an account, log in, and manage their profiles.
Recipe Submission: Users can submit their own recipes with details such as ingredients, instructions, cooking time, and images.
Recipe Browsing: Users can browse through a collection of recipes submitted by others.
Rating System: Users can rate recipes on a scale of 1 to 5 stars.
Comments: Users can leave comments on recipes to provide feedback or ask questions.
Search Functionality: Users can search for recipes based on ingredients, cuisine, or recipe name.
Favorites: Users can save their favorite recipes for easy access later.
Technology Stack
Frontend: HTML, CSS, JavaScript (React or Vue.js)
Backend: Node.js with Express
Database: MongoDB or PostgreSQL
Authentication: JWT (JSON Web Tokens)

## Features

- **Add Recipe**: Users can add a new recipe with details such as name, description, ingredients, and instructions.
- **Search Recipe by Name**: Users can search for recipes by their name.
- **Filter Recipes by Ingredient**: Users can filter recipes based on ingredients present in the recipe.
- **View All Recipes**: Displays all the recipes added to the platform.
- **Service Layer**: Handles the core business logic of the platform.
- **DAO Layer**: Manages data access, simulating interaction with a database.
- **Unit Testing**: Comprehensive unit tests for both service and DAO layers using **JUnit** and **Mockito**.


How It Works
Add Recipe: When a user adds a recipe, 
the system prompts for the name, description, ingredients, and instructions. 
The recipe is stored in memory and can later be retrieved or searched.

Search by Name: The system allows users to search for recipes by their name. If the recipe exists in the system, its details are displayed.

Filter by Ingredient: Users can filter recipes by a specific ingredient. The system checks which recipes contain the ingredient and returns matching results.

Unit Testing: The project includes unit tests for both the DAO and Service layers:

DAO Tests: Verify the correctness of data retrieval and storage methods.
Service Tests: Mock the DAO and verify that the service methods behave correctly with different inputs and outputs.


Example Usage:
Adding a Recipe:

Enter recipe name: Pasta

Enter recipe description: Delicious pasta with tomato sauce.

Enter ingredients: Pasta, Tomato Sauce, Garlic

Enter instructions: Boil the pasta, sauté garlic, add sauce and mix.

Recipe added successfully!


Searching for a Recipe by Name:

Enter recipe name to search: Pasta

Recipe Found: 

Recipe Name: Pasta

Description: Delicious pasta with tomato sauce.

Ingredients: Pasta, Tomato Sauce, Garlic

Instructions: Boil the pasta, sauté garlic, add sauce and mix.



Filtering Recipes by Ingredient:

Enter ingredient to filter recipes by: Garlic

Filtered Recipes:

Recipe Name: Pasta

Description: Delicious pasta with tomato sauce.

Ingredients: Pasta, Tomato Sauce, Garlic

Instructions: Boil the pasta, sauté garlic, add sauce and mix.

